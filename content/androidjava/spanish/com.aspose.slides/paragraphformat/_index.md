---
title: ParagraphFormat
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Esta clase contiene las propiedades de formato de párrafo.
type: docs
url: /es/com.aspose.slides/paragraphformat/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las Interfaces Implementadas:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Esta clase contiene las propiedades de formato de párrafo. A diferencia de [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), todas las propiedades de esta clase son modificables.

--------------------

Esta clase se utiliza para obtener y manipular las propiedades de formato de párrafo definidas para un párrafo determinado. Esto significa que no se aplica herencia al obtener los valores, por lo que en la mayoría de los casos obtendrá valores que significan "undefined".

Para obtener los valores efectivos de los parámetros de formato, incluida la herencia, necesita usar el método [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) que devuelve una instancia de [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Inicializa una nueva instancia de la clase [ParagraphFormat](../../com.aspose.slides/paragraphformat). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBullet()](#getBullet--) | Devuelve el formato de viñeta del párrafo. |
| [getDepth()](#getDepth--) | Devuelve o establece la profundidad del párrafo. |
| [setDepth(short value)](#setDepth-short-) | Devuelve o establece la profundidad del párrafo. |
| [getAlignment()](#getAlignment--) | Devuelve o establece la alineación del texto en un párrafo sin herencia. |
| [setAlignment(int value)](#setAlignment-int-) | Devuelve o establece la alineación del texto en un párrafo sin herencia. |
| [getSpaceWithin()](#getSpaceWithin--) | Devuelve o establece la cantidad de espacio entre líneas base en un párrafo. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Devuelve o establece la cantidad de espacio entre líneas base en un párrafo. |
| [getSpaceBefore()](#getSpaceBefore--) | Devuelve o establece la cantidad de espacio antes de la primera línea en un párrafo sin herencia. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Devuelve o establece la cantidad de espacio antes de la primera línea en un párrafo sin herencia. |
| [getSpaceAfter()](#getSpaceAfter--) | Devuelve o establece la cantidad de espacio después de la última línea en un párrafo sin herencia. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Devuelve o establece la cantidad de espacio después de la última línea en un párrafo sin herencia. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Determina si se utiliza el salto de línea asiático oriental en un párrafo. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Determina si se utiliza el salto de línea asiático oriental en un párrafo. |
| [getRightToLeft()](#getRightToLeft--) | Determina si se utiliza la escritura de derecha a izquierda en un párrafo. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Determina si se utiliza la escritura de derecha a izquierda en un párrafo. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Determina si se utiliza el salto de línea latino en un párrafo. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Determina si se utiliza el salto de línea latino en un párrafo. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Determina si se utiliza la puntuación colgante en un párrafo. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Determina si se utiliza la puntuación colgante en un párrafo. |
| [getMarginLeft()](#getMarginLeft--) | Devuelve o establece el margen izquierdo en un párrafo sin herencia. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Devuelve o establece el margen izquierdo en un párrafo sin herencia. |
| [getMarginRight()](#getMarginRight--) | Devuelve o establece el margen derecho en un párrafo sin herencia. |
| [setMarginRight(float value)](#setMarginRight-float-) | Devuelve o establece el margen derecho en un párrafo sin herencia. |
| [getIndent()](#getIndent--) | Devuelve o establece la sangría de primera línea/sangría colgante del párrafo sin herencia. |
| [setIndent(float value)](#setIndent-float-) | Devuelve o establece la sangría de primera línea/sangría colgante del párrafo sin herencia. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Devuelve o establece el tamaño de tabulación predeterminado sin herencia. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Devuelve o establece el tamaño de tabulación predeterminado sin herencia. |
| [getTabs()](#getTabs--) | Devuelve las tabulaciones de un párrafo. |
| [getFontAlignment()](#getFontAlignment--) | Devuelve o establece la alineación de fuente en un párrafo sin herencia. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Devuelve o establece la alineación de fuente en un párrafo sin herencia. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Devuelve el formato de porción predeterminado de un párrafo. |
| [getEffective()](#getEffective--) | Obtiene los datos de formato de párrafo efectivos con la herencia aplicada. |
| [getVersion()](#getVersion--) |  |
### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

Inicializa una nueva instancia de la clase [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

Devuelve el formato de viñeta del párrafo. Solo lectura [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Devuelve:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```

Devuelve o establece la profundidad del párrafo. El valor 0 significa valor indefinido. Lectura/escritura  short .

**Devuelve:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Devuelve o establece la profundidad del párrafo. El valor 0 significa valor indefinido. Lectura/escritura  short .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Devuelve o establece la alineación del texto en un párrafo sin herencia. Lectura/escritura [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instanciar un objeto Presentation que representa un archivo PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Acceder a la primera diapositiva
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Acceder al primer y segundo marcador de posición en la diapositiva y convertirlo a AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Cambiar el texto en ambos marcadores de posición
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Obtener el primer párrafo de los marcadores de posición
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Alinear el párrafo de texto al centro
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Escribir la presentación como un archivo PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Devuelve o establece la alineación del texto en un párrafo sin herencia. Lectura/escritura [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instanciar un objeto Presentation que representa un archivo PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Acceder a la primera diapositiva
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Acceder al primer y segundo marcador de posición en la diapositiva y convertirlo a AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Cambiar el texto en ambos marcadores de posición
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Obtener el primer párrafo de los marcadores de posición
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Alinear el párrafo de texto al centro
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Escribir la presentación como un archivo PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

Devuelve o establece la cantidad de espacio entre líneas base en un párrafo. Un valor positivo significa porcentaje, negativo - tamaño en puntos. No se aplica herencia. Lectura/escritura  float .

**Devuelve:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Devuelve o establece la cantidad de espacio entre líneas base en un párrafo. Un valor positivo significa porcentaje, negativo - tamaño en puntos. No se aplica herencia. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Devuelve o establece la cantidad de espacio antes de la primera línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de la fuente que debe ocupar el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en puntos. Lectura/escritura  float .

**Devuelve:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Devuelve o establece la cantidad de espacio antes de la primera línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de la fuente que debe ocupar el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en puntos. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Devuelve o establece la cantidad de espacio después de la última línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de la fuente que debe ocupar el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en puntos. Lectura/escritura  float .

**Devuelve:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Devuelve o establece la cantidad de espacio después de la última línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de la fuente que debe ocupar el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en puntos. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Determina si se utiliza el salto de línea asiático oriental en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Determina si se utiliza el salto de línea asiático oriental en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Determina si se utiliza la escritura de derecha a izquierda en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Determina si se utiliza la escritura de derecha a izquierda en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Determina si se utiliza el salto de línea latino en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Determina si se utiliza el salto de línea latino en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Determina si se utiliza la puntuación colgante en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Determina si se utiliza la puntuación colgante en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Devuelve o establece el margen izquierdo en un párrafo sin herencia. Lectura/escritura  float .

**Devuelve:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Devuelve o establece el margen izquierdo en un párrafo sin herencia. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Devuelve o establece el margen derecho en un párrafo sin herencia. Lectura/escritura  float .

**Devuelve:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Devuelve o establece el margen derecho en un párrafo sin herencia. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

Devuelve o establece la sangría de primera línea/sangría colgante del párrafo sin herencia. La sangría colgante puede definirse con valores negativos. Lectura/escritura  float .

**Devuelve:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Devuelve o establece la sangría de primera línea/sangría colgante del párrafo sin herencia. La sangría colgante puede definirse con valores negativos. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Devuelve o establece el tamaño de tabulación predeterminado sin herencia. Lectura/escritura  float .

**Devuelve:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Devuelve o establece el tamaño de tabulación predeterminado sin herencia. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

Devuelve las tabulaciones de un párrafo. No se aplica herencia. Solo lectura [ITabCollection](../../com.aspose.slides/itabcollection).

**Devuelve:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

Devuelve o establece la alineación de fuente en un párrafo sin herencia. Lectura/escritura [FontAlignment](../../com.aspose.slides/fontalignment).

**Devuelve:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

Devuelve o establece la alineación de fuente en un párrafo sin herencia. Lectura/escritura [FontAlignment](../../com.aspose.slides/fontalignment).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

Devuelve el formato de porción predeterminado de un párrafo. No se aplica herencia. Solo lectura [IPortionFormat](../../com.aspose.slides/iportionformat).

**Devuelve:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

Obtiene los datos de formato de párrafo efectivos con la herencia aplicada.

--------------------

> ```
> This example demonstrates getting some effective paragraph format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long