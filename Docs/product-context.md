# product-context.md — Tu Mejor Versión / FWP Chile

> Archivo de contexto para Codex.  
> Proyecto: `tumejorversion.org`  
> Objetivo: usar este documento como fuente principal para mejorar copy, SEO, landings, estructura de venta por WhatsApp y consistencia de información de productos.  
> Última actualización sugerida: 2026-06-27

---

## 1. Contexto general del proyecto

Tu Mejor Versión es una web enfocada en productos FWP Chile de bienestar, energía, metabolismo, digestión, belleza y rutina activa.

La web funciona principalmente como:

- Página de autoridad y confianza.
- Catálogo/landing de productos.
- Sistema de conversión hacia WhatsApp.
- Base futura para SEO orgánico, contenidos educativos, packs, asesoría y remarketing.

La venta principal hoy debe dirigir a WhatsApp, no necesariamente a checkout directo.

Objetivo de mejora:

1. Mejorar la estructura visual y la experiencia móvil.
2. Mejorar SEO técnico y SEO de contenidos.
3. Aumentar confianza antes de la compra.
4. Diferenciar correctamente cada producto.
5. Separar 24BURN tradicional de 24BURN+.
6. Crear mejores CTAs hacia WhatsApp.
7. Usar copy persuasivo, pero seguro para suplementos alimenticios.
8. Evitar claims médicos, promesas garantizadas o lenguaje regulatoriamente riesgoso.

---

## 2. Ruta y estructura actual del proyecto

Ruta local del proyecto:

```txt
C:\Users\SEBASTIAN CORREA\OneDrive\Documentos\fwp\tumejorversion.org\SebaC0rrea
```

Carpetas actuales observadas:

```txt
24Burn/
Eboost/
Liv/
renovaplus/
images/
24B+/
docsproduct-sheets/
index.html
CNAME
.gitattributes
```

Recomendación de estructura limpia:

```txt
SebaC0rrea/
├─ index.html
├─ CNAME
├─ images/
├─ docs/
│  ├─ product-context.md
│  └─ product-sheets/
│     ├─ NEW PRODUCT SHEET 24BURN CHILE.pdf
│     ├─ NEW PRODUCT SHEET EBOOST CHILE.pdf
│     ├─ NEW PRODUCT SHEET LIV CHILE.pdf
│     ├─ PRODUCT SHEET 24B+ CHILE.pdf
│     └─ PRODUCT SHEET RVA+ DOYPACK CHILE.pdf
├─ 24Burn/
│  ├─ index.html
│  └─ images/
├─ 24burn-plus/
│  ├─ index.html
│  └─ images/
├─ Eboost/
│  ├─ index.html
│  └─ images/
├─ Liv/
│  ├─ index.html
│  └─ images/
└─ renovaplus/
   ├─ index.html
   └─ images/
```

Nota importante:

- La carpeta `24B+` puede servir como respaldo temporal, pero no es recomendable como URL final.
- Para SEO y estabilidad, usar `24burn-plus/` como ruta final.
- Nombre visible en la página: `24BURN+`.
- Si se mantiene la carpeta `docsproduct-sheets`, Codex debe leer los PDFs desde ahí. Idealmente renombrar a `docs/product-sheets`.

---

## 3. Principios de copy y compliance

Estos productos son suplementos alimenticios. La comunicación debe ser persuasiva, pero segura.

### Lenguaje recomendado

Usar palabras como:

- apoya
- acompaña
- contribuye
- complementa
- ayuda a mantener
- como parte de una alimentación equilibrada
- junto a hábitos saludables
- rutina diaria
- bienestar
- energía diaria
- sensación de ligereza
- rutina activa

### Lenguaje a evitar

Evitar o reemplazar:

- cura
- trata
- elimina enfermedades
- quema grasa garantizado
- baja de peso garantizado
- derrite grasa
- detox milagroso
- limpia toxinas de forma absoluta
- recupera tu salud
- elimina cansancio crónico
- trata fatiga crónica
- reemplaza comidas
- resultados asegurados
- antes/después extremos sin respaldo
- lenguaje médico agresivo

### Advertencia estándar para todas las landings

```txt
Suplemento alimenticio. No es medicamento. No reemplaza una alimentación balanceada. Consulta a un profesional de la salud si estás embarazada, en lactancia, tienes una condición médica, consumes medicamentos o tienes dudas sobre su consumo. Recomendado para adultos mayores de 18 años.
```

### Advertencia adicional para productos con cafeína o estimulantes

```txt
Este producto contiene ingredientes estimulantes como cafeína, guaraná, té, yerba mate o ginseng, según fórmula. Si eres sensible a la cafeína o tienes una condición médica, consulta con un profesional antes de consumirlo.
```

---

## 4. Estrategia de conversión estilo oferta de alto valor

No vender solo “un producto”. Vender una experiencia de compra guiada.

Cada landing debe comunicar que la persona recibe:

1. Producto original FWP.
2. Asesoría directa por WhatsApp.
3. Recomendación según objetivo personal.
4. Guía simple de preparación y uso.
5. Advertencias claras antes de comprar.
6. Seguimiento inicial post-compra.
7. Ayuda para recompra si el producto le acomoda.
8. Orientación honesta: si el producto no calza, se recomienda otra opción o no comprar.

Copy sugerido:

```txt
No se trata solo de comprar un suplemento. Se trata de elegir bien según tu objetivo, tu rutina y lo que realmente necesitas potenciar.
```

Oferta base reutilizable:

```txt
Compra asesorada por WhatsApp

Con Tu Mejor Versión recibes:
- Producto original FWP.
- Orientación antes de comprar.
- Recomendación según tu objetivo.
- Guía simple de uso.
- Información clara de ingredientes y advertencias.
- Seguimiento inicial para resolver dudas.

Si no sabemos si un producto calza contigo, te lo diremos antes de que compres.
```

---

## 5. WhatsApp y tracking

Usar variable para número de WhatsApp si el proyecto permite configuración:

```txt
WHATSAPP_NUMBER=
```

Si la web es estática, definir el número en un archivo central o constante.

### Mensajes prellenados por producto

Asesoría general:

```txt
Hola Seba, quiero que me ayudes a elegir el producto FWP más adecuado para mi objetivo.
```

E-BOOST:

```txt
Hola Seba, quiero información sobre E-BOOST. Busco más energía y enfoque para mi día a día. ¿Me puedes orientar?
```

24BURN:

```txt
Hola Seba, quiero información sobre 24BURN. Busco apoyar mi rutina de entrenamiento y activación diaria. ¿Me puedes orientar?
```

24BURN+:

```txt
Hola Seba, quiero información sobre 24BURN+. Busco apoyar mi metabolismo, energía y rutina activa. ¿Me puedes orientar?
```

LIV:

```txt
Hola Seba, quiero información sobre LIV. Busco apoyar mi digestión y sentirme más liviano/a. ¿Me puedes orientar?
```

RENÖVA+:

```txt
Hola Seba, quiero información sobre RENÖVA+. Busco apoyar piel, cabello, uñas, articulaciones y bienestar general. ¿Me puedes orientar?
```

### Eventos sugeridos

Implementar tracking sin romper si no existe GA4, Meta Pixel o dataLayer.

```txt
click_whatsapp_home
click_whatsapp_asesoria
click_whatsapp_eboost
click_whatsapp_24burn
click_whatsapp_24burn_plus
click_whatsapp_liv
click_whatsapp_renovaplus
view_product_eboost
view_product_24burn
view_product_24burn_plus
view_product_liv
view_product_renovaplus
quiz_started
quiz_completed
product_recommended
```

---

# 6. Productos

---

## 6.1 24BURN+

### Identificación

```txt
Nombre comercial: 24BURN+
Slug recomendado: 24burn-plus
Categoría: suplemento alimenticio en polvo
Sabor: té limón
Formato: doypack / sachets
Porción: 10 g
Porciones por envase: 28
Preparación: 1 sachet de 10 g en 200 ml de agua
Precio oficial informado: CLP $44.990
Precio promocional informado por lanzamiento: CLP $39.990
```

Nota:

- Usar precio promocional solo si sigue vigente.
- Si la promoción terminó, mostrar precio oficial o dejar texto dinámico tipo “consulta disponibilidad y precio actual”.

### Posicionamiento

24BURN+ debe posicionarse como una fórmula de activación completa y más equilibrada para rutina activa, metabolismo, rendimiento físico, recuperación y estado antioxidante.

No debe confundirse con el 24BURN tradicional.

### Hero sugerido

```txt
H1: 24BURN+: metabolismo, energía y rutina activa

Subheadline:
Una fórmula en polvo sabor té limón con fibras, vitaminas, tés, ginseng y magnesio, diseñada para acompañar tu metabolismo, rendimiento físico y bienestar diario.

CTA:
Quiero asesoría sobre 24BURN+
```

### Beneficios seguros

- Apoya la activación del metabolismo.
- Acompaña una rutina activa.
- Complementa el rendimiento físico.
- Apoya la recuperación muscular.
- Contribuye al estado antioxidante.
- Puede ser una opción para quienes buscan energía más equilibrada durante el día.

### Ingredientes destacados

- Harina de limón.
- Harina de alcachofa.
- Fibra de limón.
- Harina de espárrago.
- Polidextrosa.
- Mix vitamínico.
- Citrato de magnesio.
- Té verde.
- Té negro.
- Té rojo.
- Harina de manzana madura.
- Panax Ginseng.
- Harina de brócoli.
- Estevia.
- Curcumina.
- Según el informativo, el espárrago aparece como fuente natural de L-Carnitina. No comunicarlo como L-Carnitina agregada si no está explícito en la fórmula como ingrediente aislado.

### Datos nutricionales relevantes por porción

```txt
Porción: 10 g
Energía: 23 kcal
Carbohidratos disponibles: 5 g
Azúcares totales: 0 g
Fibra dietética: 3 g
Cafeína: 4,5 mg por porción
Ginseng: 36 mg por porción
Yodo: 31,1 ug por porción
Zinc: 3,9 mg por porción
Biotina: 31,1 ug por porción
```

### Alérgenos / puede contener

```txt
Puede contener: trigo, soya, leche y huevos.
```

### Preparación

```txt
Agrega 1 sachet de 24BURN+ (10 g) en un vaso con 200 ml de agua y remueve por unos segundos.
```

### Para quién es

- Personas que quieren apoyar su rutina activa.
- Personas que buscan una opción para metabolismo y energía diaria.
- Personas que entrenan y quieren complementar su rendimiento.
- Personas que prefieren una activación más equilibrada.
- Adultos mayores de 18 años.

### Para quién no es / precauciones

- No recomendado para menores de 18 años.
- Embarazadas o lactantes deben consultar a su médico.
- Personas con afecciones médicas o que toman medicamentos deben consultar a un profesional.
- Personas sensibles a estimulantes deben revisar su tolerancia, aunque la cafeína informada por porción es baja.
- Personas con condiciones tiroideas deben consultar a su médico, ya que contiene yodo.

### Diferencia con 24BURN tradicional

24BURN+ tiene una fórmula más amplia con fibras, vitaminas, tés, ginseng, magnesio, harina de limón, alcachofa, espárrago, manzana y brócoli. Su comunicación debe ser más equilibrada: metabolismo, actividad diaria, rendimiento, recuperación y antioxidantes.

### SEO

```txt
Title:
24BURN+ en Chile | Metabolismo, Energía y Rutina Activa

Meta description:
24BURN+ de FWP, suplemento en polvo sabor té limón con fibras, vitaminas, tés, ginseng y magnesio. Compra con asesoría por WhatsApp en Chile.
```

### FAQ sugeridas

#### ¿24BURN+ es lo mismo que 24BURN?

No. 24BURN+ es una versión distinta, con una fórmula más amplia basada en fibras, vitaminas, tés, ginseng, magnesio y otros ingredientes. 24BURN tradicional tiene otro formato, porción e ingredientes.

#### ¿Cómo se prepara 24BURN+?

Agrega 1 sachet de 10 g en 200 ml de agua y remueve por unos segundos.

#### ¿Cuántas porciones trae?

Trae 28 porciones por envase.

#### ¿Tiene cafeína?

Sí. Contiene 4,5 mg de cafeína por porción.

#### ¿Tiene yodo?

Sí. La información nutricional indica yodo por porción. Personas con condiciones tiroideas deben consultar a su médico antes de consumirlo.

#### ¿Es medicamento?

No. Es un suplemento alimenticio y no reemplaza una alimentación balanceada.

---

## 6.2 24BURN tradicional

### Identificación

```txt
Nombre comercial: 24BURN
Slug actual: 24Burn
Slug recomendado futuro: 24burn
Categoría: suplemento alimenticio en polvo
Sabor: té limón
Formato: pote
Porción: 15 g
Porciones por envase: 33
Preparación: 1 scoop de 15 g en 200 ml de agua
Precio sugerido informado: CLP $35.990
```

### Posicionamiento

24BURN tradicional debe posicionarse como una opción de activación física y mental, energía y acompañamiento para entrenamiento/rutina fitness.

Tiene un enfoque más intenso y deportivo que 24BURN+.

### Hero sugerido

```txt
H1: Activa tu rutina fitness con 24BURN

Subheadline:
Una fórmula en polvo sabor té limón con L-Carnitina, guaraná, té verde y Panax Ginseng para acompañar tu metabolismo, entrenamiento y activación diaria.

CTA:
Quiero asesoría sobre 24BURN
```

### Beneficios seguros

- Apoya el metabolismo.
- Acompaña el rendimiento deportivo.
- Complementa la activación física y mental.
- Puede acompañar una rutina fitness.
- Gracias a su contenido de fibra, contribuye al bienestar digestivo.

### Ingredientes destacados

- Maltodextrina.
- Polidextrosa.
- L-Carnitina.
- Extracto de guaraná.
- Concentrado de kelp.
- Extracto de té verde.
- Cafeína.
- Panax Ginseng.
- Vitamina B3.
- Vitamina A.
- Vitamina B2.
- Sucralosa.

### Datos nutricionales relevantes por porción

```txt
Porción: 15 g
Energía: 6,9 kcal
Carbohidratos disponibles: 3,5 g
Azúcares: 0,2 g
Fibra dietaria: 3,3 g
L-Carnitina / Té: 150 mg por porción
Extracto de Panax Ginseng: 23 mg por porción
Extracto de Té Verde 95% Polifenoles: 60 mg por porción
Sucralosa: 36 mg por porción
```

### Preparación

```txt
Agrega 1 scoop de 24BURN (15 g) en un vaso con 200 ml de agua y remueve por unos segundos.
```

### Para quién es

- Personas con rutina fitness.
- Personas que buscan activación diaria.
- Personas que quieren complementar entrenamiento.
- Personas que buscan apoyo para metabolismo y energía.
- Adultos mayores de 18 años.

### Para quién no es / precauciones

- No recomendado para menores de 18 años.
- Embarazadas o lactantes deben consultar a su médico.
- Personas con afecciones médicas o que toman medicamentos deben consultar a un profesional.
- Personas sensibles a cafeína/estimulantes deben tener precaución.

### SEO

```txt
Title:
24BURN en Chile | Activación, Energía y Rutina Fitness

Meta description:
24BURN de FWP, suplemento en polvo sabor té limón con L-Carnitina, guaraná, té verde y Panax Ginseng. Compra con asesoría por WhatsApp en Chile.
```

### FAQ sugeridas

#### ¿24BURN sirve para entrenar?

Puede acompañar una rutina de entrenamiento y activación diaria, siempre como complemento de hábitos saludables.

#### ¿Cómo se prepara?

Agrega 1 scoop de 15 g en 200 ml de agua y remueve por unos segundos.

#### ¿Cuántas porciones trae?

Trae 33 porciones por envase.

#### ¿Contiene L-Carnitina?

Sí. La información del producto indica L-Carnitina dentro de sus ingredientes y 150 mg por porción en la tabla nutricional.

#### ¿Es igual a 24BURN+?

No. Son productos distintos, con formato, porción, ingredientes y enfoque diferentes.

---

## 6.3 E-BOOST

### Identificación

```txt
Nombre comercial: E-BOOST
Slug actual: Eboost
Slug recomendado futuro: eboost
Categoría: suplemento alimenticio en polvo
Sabor: mandarina
Formato: caja / sachets
Porción: 7 g
Porciones por envase: 28
Preparación: 1 sachet de 7 g en 200 ml de agua
Precio sugerido informado: CLP $39.990
```

### Posicionamiento

E-BOOST debe posicionarse como energía, enfoque y activación para días largos, estudio, trabajo, entrenamiento o momentos de alta exigencia.

No comunicar como tratamiento de fatiga crónica o burnout clínico.

### Hero sugerido

```txt
H1: Energía y enfoque para días que exigen más de ti

Subheadline:
E-BOOST combina guaraná, yerba mate, té negro, BCAA, vitaminas y magnesio para acompañar tu energía diaria, concentración y rendimiento.

CTA:
Quiero asesoría sobre E-BOOST
```

### Beneficios seguros

- Apoya la energía diaria.
- Acompaña el enfoque y la concentración.
- Complementa rutinas de trabajo, estudio o entrenamiento.
- Ayuda a reducir la sensación de cansancio ocasional.
- Puede apoyar una actitud más activa durante el día.

### Ingredientes destacados

- Harina de mandarina.
- Fibra de bamboo.
- Blend NRG:
  - Vitamina D.
  - Vitamina E.
  - Malatocitrato de magnesio.
  - Valina.
  - Leucina.
  - Isoleucina.
- Mix vitamínico.
- Guaraná.
- Té negro.
- Yerba mate.
- Harina de algarrobo.
- Stevia.
- Curcumina.

### Datos nutricionales relevantes por porción

```txt
Porción: 7 g
Energía: 2 kcal
Fibra dietética: 1 g
Vitamina A: 216 ug
Vitamina D3: 2,9 ug
Vitamina E: 23 mg
Vitamina C: 63 mg
Vitamina B9: 104,8 ug
Vitamina B1: 0,8 mg
Vitamina B2: 0,9 mg
Vitamina B6: 1,1 mg
Vitamina B3: 4,8 mg
Vitamina B12: 1,9 ug
Hierro: 3,8 mg
Yodo: 31,5 ug
Zinc: 4 mg
Magnesio: 265,7 mg
Biotina: 31,5 ug
Vitamina B5: 5,3 mg
Valina: 63,5 mg
Leucina: 196,4 mg
Isoleucina: 63,5 mg
```

### Alérgenos / puede contener

```txt
Puede contener: trigo, soya, leche y huevos.
```

### Preparación

```txt
Agrega 1 sachet de E-BOOST (7 g) en un vaso con 200 ml de agua y remueve por unos segundos.
```

### Para quién es

- Personas que trabajan o estudian muchas horas.
- Personas que necesitan energía y foco durante el día.
- Personas con rutina activa.
- Personas que entrenan y buscan complementar su energía.
- Adultos mayores de 18 años.

### Para quién no es / precauciones

- No recomendado para menores de 18 años.
- Embarazadas o lactantes deben consultar a su médico.
- Personas con afecciones médicas o que toman medicamentos deben consultar a un profesional.
- Personas sensibles a estimulantes deben tener precaución por guaraná, té negro y yerba mate.
- Personas con condiciones tiroideas deben consultar a su médico, ya que contiene yodo.

### SEO

```txt
Title:
E-BOOST en Chile | Energía y Enfoque Diario

Meta description:
E-BOOST de FWP, suplemento en polvo sabor mandarina con guaraná, yerba mate, té negro, BCAA, vitaminas y magnesio. Compra con asesoría por WhatsApp en Chile.
```

### FAQ sugeridas

#### ¿Para qué sirve E-BOOST?

E-BOOST está pensado para acompañar energía, enfoque y concentración en rutinas de trabajo, estudio o entrenamiento.

#### ¿Cómo se prepara?

Agrega 1 sachet de 7 g en 200 ml de agua y remueve por unos segundos.

#### ¿Cuántas porciones trae?

Trae 28 porciones.

#### ¿Tiene azúcar?

La información del producto indica 0 g de azúcares totales por porción.

#### ¿Tiene yodo?

Sí. La tabla nutricional informa yodo por porción. Personas con condiciones tiroideas deben consultar a su médico.

---

## 6.4 LIV

### Identificación

```txt
Nombre comercial: LIV
Slug actual: Liv
Slug recomendado futuro: liv
Categoría: suplemento alimenticio en polvo
Sabor: manzana verde
Formato: pote o doypack, según disponibilidad
Porción: 10 g
Porciones por envase: 28
Preparación: 1 scoop de 10 g en 200 ml de agua
Precio sugerido informado: CLP $49.990
```

### Posicionamiento

LIV debe posicionarse como fibra, probióticos, bienestar digestivo y sensación de ligereza.

Evitar prometer detox milagroso, limpieza absoluta, tratamiento digestivo o pérdida de peso garantizada.

### Hero sugerido

```txt
H1: Fibra, probióticos y ligereza para tu rutina diaria

Subheadline:
LIV combina fibra, fructooligosacáridos y probióticos para apoyar tu bienestar digestivo y ayudarte a sentirte más liviano/a como parte de una alimentación equilibrada.

CTA:
Quiero asesoría sobre LIV
```

### Beneficios seguros

- Apoya el bienestar digestivo.
- Contribuye al consumo diario de fibra.
- Ayuda a prolongar la saciedad como parte de una alimentación equilibrada.
- Acompaña una rutina de alimentación más consciente.
- Puede ayudar a sentir mayor ligereza dentro de una rutina saludable.

### Ingredientes destacados

- Harina de manzana.
- Fructooligosacáridos.
- Fibra de bamboo.
- Sabor manzana verde.
- Harina de pitahaya.
- Harina de papaya.
- Harina de linaza.
- Harina de ciruela.
- Cultivos probióticos:
  - Bifidobacterium animalis ssp. lactis (BLC1).
  - Lactobacillus acidophilus (LA3).
  - Streptococcus thermophilus.
- Estevia.

### Datos nutricionales relevantes por porción

```txt
Porción: 10 g
Energía: 4 kcal
Fibra dietética: 6 g
Azúcares totales: 0 g
Bifidobacterium animalis ssp. lactis (BLC1): 1x10^10 UFC por porción
Lactobacillus acidophilus (LA3): 2x10^9 UFC por porción
Streptococcus thermophilus: 1x10^8 UFC por porción
```

### Alérgenos / contiene

```txt
Contiene derivados lácteos por cultivos probióticos.
```

### Preparación

```txt
Agrega 1 scoop de LIV (10 g) en un vaso con 200 ml de agua y remueve por unos segundos.
```

### Para quién es

- Personas que quieren aumentar su consumo de fibra.
- Personas que buscan apoyar su bienestar digestivo.
- Personas que quieren sentirse más livianas como parte de hábitos saludables.
- Personas que buscan una rutina de alimentación más consciente.
- Adultos mayores de 18 años.

### Para quién no es / precauciones

- No recomendado para menores de 18 años.
- Embarazadas o lactantes deben consultar a su médico.
- Personas con afecciones médicas o que toman medicamentos deben consultar a un profesional.
- Personas con alergia o sensibilidad a derivados lácteos deben revisar antes de consumir.
- Si hay molestias digestivas persistentes, derivar a profesional de salud.

### SEO

```txt
Title:
LIV en Chile | Fibra, Probióticos y Bienestar Digestivo

Meta description:
LIV de FWP, suplemento en polvo sabor manzana verde con fibra, fructooligosacáridos y probióticos. Compra con asesoría por WhatsApp en Chile.
```

### FAQ sugeridas

#### ¿Para qué sirve LIV?

LIV está pensado para apoyar el bienestar digestivo, el consumo de fibra y la sensación de ligereza como parte de una alimentación equilibrada.

#### ¿Cómo se prepara?

Agrega 1 scoop de 10 g en 200 ml de agua y remueve por unos segundos.

#### ¿Cuántas porciones trae?

Trae 28 porciones por envase.

#### ¿Tiene probióticos?

Sí. Contiene cultivos probióticos según la información del producto.

#### ¿Contiene leche?

Contiene derivados lácteos por los cultivos probióticos.

#### ¿Es un producto detox?

Se debe evitar comunicarlo como detox milagroso. Mejor decir que apoya el bienestar digestivo y una rutina más consciente.

---

## 6.5 RENÖVA+

### Identificación

```txt
Nombre comercial: RENÖVA+
Slug actual: renovaplus
Slug recomendado futuro: renovaplus o renova-plus
Categoría: suplemento alimenticio en polvo
Sabor: berries
Formato: doypack / sachets
Porción: 15 g
Porciones por envase: 21
Preparación: 1 sachet de 15 g en 250 ml de agua
Precio oficial informado: CLP $49.990
```

### Posicionamiento

RENÖVA+ debe posicionarse como colágeno, belleza, vitalidad, piel, cabello, uñas, articulaciones, músculos y bienestar general.

Evitar prometer “rejuvenecimiento garantizado” o “anti-edad absoluto”.

### Hero sugerido

```txt
H1: Colágeno, belleza y vitalidad en tu rutina diaria

Subheadline:
RENÖVA+ combina colágeno hidrolizado Peptan®, resveratrol, Q10, zinc, magnesio y vitaminas para apoyar piel, cabello, uñas, articulaciones y bienestar general.

CTA:
Quiero asesoría sobre RENÖVA+
```

### Beneficios seguros

- Apoya el cuidado de piel, uñas y cabello.
- Complementa la nutrición diaria con colágeno hidrolizado.
- Apoya articulaciones y músculos.
- Contribuye al bienestar general.
- Aporta antioxidantes como resveratrol y Q10.
- Aporta proteínas por porción.

### Ingredientes destacados

- Colágeno hidrolizado Peptan®.
- Harina de arándanos.
- Fibra de avena Sanacel Oat®.
- Inulina.
- Harina de uva.
- Mix de vitaminas y minerales.
- Coenzima Q10.
- Resveratrol.
- Vitamina C.
- Zinc.
- Magnesio.
- Estevia.

### Datos nutricionales relevantes por porción

```txt
Porción: 15 g
Energía: 46 kcal
Proteínas: 11,4 g
Fibra dietética: 1 g
Vitamina C: 63 mg
Coenzima Q10: 15 mg
Yodo: 150 ug
Zinc: 15 mg
Biotina: 31,2 ug
Magnesio: 302 mg
Selenio: 17,6 ug
```

### Alérgenos / puede contener

```txt
Puede contener: sésamo, gluten, soya, leche y huevo.
```

### Preparación

```txt
Agrega 1 sachet de RENÖVA+ (15 g) en un vaso con 250 ml de agua y remueve por unos segundos.
```

### Para quién es

- Personas que quieren apoyar piel, cabello y uñas.
- Personas que buscan complementar colágeno en su rutina.
- Personas que buscan apoyo para articulaciones y músculos.
- Personas que quieren una rutina de belleza y bienestar desde la nutrición.
- Adultos mayores de 18 años.

### Para quién no es / precauciones

- No recomendado para menores de 18 años.
- Embarazadas o lactantes deben consultar a su médico.
- Personas con afecciones médicas o que toman medicamentos deben consultar a un profesional.
- Personas con condiciones tiroideas deben consultar a su médico, ya que contiene yodo.
- Personas con alergias a sésamo, gluten, soya, leche o huevo deben revisar antes de consumir.

### SEO

```txt
Title:
RENÖVA+ en Chile | Colágeno, Belleza y Bienestar

Meta description:
RENÖVA+ de FWP, suplemento en polvo sabor berries con colágeno Peptan®, resveratrol, Q10, zinc, magnesio y vitaminas. Compra con asesoría por WhatsApp en Chile.
```

### FAQ sugeridas

#### ¿Para qué sirve RENÖVA+?

RENÖVA+ está pensado para complementar la nutrición diaria con colágeno, proteínas, antioxidantes, vitaminas y minerales que apoyan piel, cabello, uñas, articulaciones y bienestar general.

#### ¿Cómo se prepara?

Agrega 1 sachet de 15 g en 250 ml de agua y remueve por unos segundos.

#### ¿Cuántas porciones trae?

Trae 21 porciones por envase.

#### ¿Contiene colágeno?

Sí. Contiene colágeno hidrolizado Peptan®.

#### ¿Tiene yodo?

Sí. La tabla nutricional informa yodo por porción. Personas con condiciones tiroideas deben consultar a su médico antes de consumirlo.

#### ¿Es medicamento?

No. Es un suplemento alimenticio y no reemplaza una alimentación balanceada.

---

# 7. Comparador de productos

Usar en home y/o página `/productos`.

| Objetivo del usuario | Producto recomendado | Enfoque principal |
|---|---|---|
| Más energía y enfoque | E-BOOST | Energía diaria, concentración, estudio, trabajo y rutina activa |
| Metabolismo y rutina activa equilibrada | 24BURN+ | Metabolismo, rendimiento, recuperación y antioxidantes |
| Activación física y entrenamiento | 24BURN | Activación, energía, fitness, L-Carnitina y té verde |
| Digestión y ligereza | LIV | Fibra, probióticos, bienestar digestivo y saciedad |
| Piel, cabello, uñas y articulaciones | RENÖVA+ | Colágeno, proteínas, antioxidantes, belleza y vitalidad |

Copy sugerido:

```txt
¿No sabes cuál elegir?

Cada producto tiene una misión distinta. Escríbeme por WhatsApp y te ayudo a elegir según tu objetivo, rutina y condiciones personales.
```

---

# 8. Quiz recomendado

Crear sección:

```txt
Encuentra tu producto ideal en 30 segundos
```

Preguntas:

1. ¿Qué quieres potenciar?
   - Energía y enfoque.
   - Metabolismo y entrenamiento.
   - Digestión y ligereza.
   - Piel, cabello, uñas y articulaciones.
   - No estoy seguro/a.

2. Tu rutina actual es más de:
   - Trabajo o estudio.
   - Entrenamiento.
   - Rutina sedentaria.
   - Bienestar general.
   - Estoy retomando hábitos.

3. ¿Tienes sensibilidad a la cafeína o estimulantes?
   - Sí.
   - No.
   - No lo sé.

4. ¿Prefieres asesoría antes de comprar?
   - Sí, quiero que me orienten.
   - Quiero ver el producto recomendado.

Lógica sugerida:

- Energía y enfoque → E-BOOST.
- Metabolismo y entrenamiento intenso → 24BURN.
- Metabolismo y rutina activa equilibrada → 24BURN+.
- Digestión y ligereza → LIV.
- Belleza/articulaciones/vitalidad → RENÖVA+.
- Duda/sensibilidad/condición médica → asesoría por WhatsApp.

---

# 9. Páginas recomendadas

## Home `/`

Objetivo:
Ayudar a elegir producto, generar confianza y derivar a WhatsApp.

Secciones:

1. Hero principal.
2. Selector por objetivo.
3. Comparador de productos.
4. Bloque de confianza.
5. Oferta asesorada.
6. Productos destacados.
7. Testimonios reales si existen.
8. Preguntas frecuentes.
9. CTA final.

Hero sugerido:

```txt
H1: Encuentra tu mejor versión con productos FWP en Chile

Subheadline:
Energía, metabolismo, digestión, belleza y bienestar en una rutina simple, práctica y acompañada.

CTA principal:
Quiero asesoría por WhatsApp

CTA secundario:
Ver productos
```

## `/24burn-plus/`

Landing nueva para 24BURN+.

## `/24Burn/` o `/24burn/`

Landing de 24BURN tradicional.

## `/Eboost/` o `/eboost/`

Landing de E-BOOST.

## `/Liv/` o `/liv/`

Landing de LIV.

## `/renovaplus/`

Landing de RENÖVA+.

## `/sobre-nosotros/`

Objetivo:
Construir confianza.

Contenido:

- Quién está detrás de Tu Mejor Versión.
- Por qué nace la marca.
- Qué significa “Tu Mejor Versión”.
- Por qué trabajar con FWP.
- Cómo se asesora antes de comprar.
- Cómo contactar por WhatsApp.

## `/como-comprar/`

Objetivo:
Reducir fricción.

Contenido:

1. Elige producto o pide asesoría.
2. Confirma disponibilidad.
3. Recibe datos de pago.
4. Coordina despacho.
5. Recibe seguimiento y recomendaciones.

## `/preguntas-frecuentes/`

Preguntas:

- ¿Hacen envíos a todo Chile?
- ¿Cómo se paga?
- ¿Los productos son originales?
- ¿Puedo pedir asesoría antes de comprar?
- ¿Son medicamentos?
- ¿Puedo consumirlos si tengo una condición médica?
- ¿Cuánto dura cada producto?
- ¿Cuál me conviene según mi objetivo?
- ¿Cuál es la diferencia entre 24BURN y 24BURN+?

## `/packs/`

Objetivo:
Aumentar ticket promedio.

Packs sugeridos:

- Pack Energía y Enfoque: E-BOOST.
- Pack Rutina Activa: 24BURN+ o 24BURN.
- Pack Ligereza: LIV.
- Pack Belleza y Vitalidad: RENÖVA+.
- Pack Bienestar Integral: RENÖVA+ + LIV.
- Pack Activación Diaria: E-BOOST + 24BURN+.

Nota:
No inventar descuentos si no existen.

## `/asesoria/`

Objetivo:
Capturar indecisos.

Hero sugerido:

```txt
H1: ¿No sabes cuál producto elegir?

Subheadline:
Cuéntame tu objetivo y te ayudo a elegir el producto FWP que más calza con tu rutina.

CTA:
Pedir asesoría por WhatsApp
```

## Páginas SEO por intención

Crear:

```txt
/energia-y-enfoque/
/metabolismo-y-entrenamiento/
/digestion-y-ligereza/
/colageno-piel-cabello-articulaciones/
```

Estas páginas deben educar primero y vender después.

---

# 10. SEO técnico

Implementar en todas las páginas:

- Un solo H1 por página.
- H2/H3 ordenados.
- Title único.
- Meta description única.
- Canonical.
- Open Graph.
- Twitter Card.
- Alt text descriptivo en imágenes.
- Sitemap.xml.
- Robots.txt.
- JSON-LD Organization.
- JSON-LD Product por landing.
- JSON-LD FAQPage si hay FAQs.
- JSON-LD BreadcrumbList.

No usar `aggregateRating` ni `review` si no hay reseñas reales verificables.

---

# 11. Metadatos sugeridos

## Home

```txt
Title:
Tu Mejor Versión | Productos FWP en Chile

Description:
Encuentra productos FWP en Chile para energía, metabolismo, digestión, belleza y bienestar. Compra con asesoría directa por WhatsApp.
```

## E-BOOST

```txt
Title:
E-BOOST en Chile | Energía y Enfoque Diario

Description:
E-BOOST de FWP, suplemento en polvo sabor mandarina con guaraná, yerba mate, té negro, BCAA, vitaminas y magnesio. Compra con asesoría por WhatsApp.
```

## 24BURN

```txt
Title:
24BURN en Chile | Activación, Energía y Rutina Fitness

Description:
24BURN de FWP, suplemento en polvo sabor té limón con L-Carnitina, guaraná, té verde y Panax Ginseng. Compra con asesoría por WhatsApp.
```

## 24BURN+

```txt
Title:
24BURN+ en Chile | Metabolismo, Energía y Rutina Activa

Description:
24BURN+ de FWP, suplemento en polvo sabor té limón con fibras, vitaminas, tés, ginseng y magnesio. Compra con asesoría por WhatsApp.
```

## LIV

```txt
Title:
LIV en Chile | Fibra, Probióticos y Bienestar Digestivo

Description:
LIV de FWP, suplemento en polvo sabor manzana verde con fibra, fructooligosacáridos y probióticos. Compra con asesoría por WhatsApp.
```

## RENÖVA+

```txt
Title:
RENÖVA+ en Chile | Colágeno, Belleza y Bienestar

Description:
RENÖVA+ de FWP, suplemento en polvo sabor berries con colágeno Peptan®, resveratrol, Q10, zinc, magnesio y vitaminas. Compra con asesoría por WhatsApp.
```

---

# 12. Componentes reutilizables sugeridos

Si el proyecto evoluciona a componentes o se reorganiza el HTML, crear bloques reutilizables para:

- Header.
- Footer.
- SEOHead.
- ProductHero.
- TrustSection.
- OfferStack.
- WhatsAppCTA.
- ProductBenefits.
- ProductIngredients.
- ProductHowToUse.
- ProductWarnings.
- ProductFAQ.
- ProductComparison.
- ProductQuiz.
- TestimonialSection.
- BlogCard.
- StickyMobileCTA.

---

# 13. Lista de assets recomendados por producto

## 24BURN+

Usar:

- Mockup doypack negro de 24B+.
- Informativo oficial 24BURN+.
- Color principal: verde lima.
- Fondo: blanco/premium con contraste negro.

Alt text sugerido:

```txt
Doypack 24BURN+ sabor té limón de FWP Chile
```

## 24BURN

Usar:

- Mockup pote blanco de 24BURN.
- Color principal: verde lima.
- Fondo: blanco/premium.

Alt text sugerido:

```txt
Pote 24BURN sabor té limón de FWP Chile
```

## E-BOOST

Usar:

- Caja E-BOOST.
- Sachet E-BOOST.
- Color principal: naranjo.
- Fondo: blanco con acentos energéticos.

Alt text sugerido:

```txt
E-BOOST sabor mandarina de FWP Chile en caja y sachet
```

## LIV

Usar:

- Pote o doypack LIV según disponibilidad.
- Color principal: celeste/verde agua.
- Fondo: claro, fresco, digestivo.

Alt text sugerido:

```txt
LIV sabor manzana verde de FWP Chile con fibra y probióticos
```

## RENÖVA+

Usar:

- Doypack blanco RENÖVA+.
- Color principal: magenta/rosa.
- Fondo: blanco, piel, belleza, vitalidad.

Alt text sugerido:

```txt
RENÖVA+ sabor berries de FWP Chile con colágeno Peptan
```

---

# 14. Prioridad de implementación para Codex

## Fase 1 — Orden y corrección

1. Revisar estructura actual.
2. Crear backup antes de modificar.
3. Crear `24burn-plus/index.html`.
4. Separar 24BURN y 24BURN+.
5. Corregir cualquier mezcla de ingredientes o precios.
6. Agregar CTAs WhatsApp personalizados.
7. Agregar advertencia estándar en todas las landings.
8. Agregar bloque de confianza.

## Fase 2 — Home y conversión

1. Mejorar hero de home.
2. Agregar selector por objetivo.
3. Agregar comparador de productos.
4. Agregar oferta asesorada.
5. Agregar CTA final fuerte.
6. Agregar botón sticky de WhatsApp en mobile.

## Fase 3 — SEO técnico

1. Titles.
2. Meta descriptions.
3. Canonical.
4. Open Graph.
5. Twitter cards.
6. Sitemap.
7. Robots.
8. Alt text.
9. Schema Product, FAQ, Organization, Breadcrumb.

## Fase 4 — Páginas nuevas

1. `/sobre-nosotros/`
2. `/como-comprar/`
3. `/preguntas-frecuentes/`
4. `/asesoria/`
5. `/packs/`

## Fase 5 — SEO de contenidos

1. `/energia-y-enfoque/`
2. `/metabolismo-y-entrenamiento/`
3. `/digestion-y-ligereza/`
4. `/colageno-piel-cabello-articulaciones/`
5. Estructura inicial de blog.

---

# 15. Checklist antes de publicar

Antes de subir cambios:

- Verificar que todas las rutas funcionen.
- Verificar que las imágenes carguen.
- Revisar versión móvil.
- Revisar botones de WhatsApp.
- Revisar que no haya claims médicos riesgosos.
- Revisar precios.
- Revisar que 24BURN y 24BURN+ no estén mezclados.
- Probar metadatos.
- Generar sitemap.
- Revisar enlaces internos.
- Comprobar que no haya errores de consola.
- Validar visualmente en Chrome y móvil.
- Confirmar que las páginas principales tengan H1 único.

---

# 16. Instrucción final para Codex

Antes de modificar código:

1. Lee este archivo completo.
2. Revisa la estructura actual del proyecto.
3. Identifica si la web es HTML estática o usa algún framework.
4. No hagas cambios masivos sin plan.
5. Trabaja por fases.
6. Entrega resumen de archivos modificados.
7. Indica próximos pasos sugeridos.
8. No inventes datos de producto, testimonios, descuentos, stock ni reseñas.
9. Si falta un dato, déjalo como pendiente o usa texto genérico seguro.
