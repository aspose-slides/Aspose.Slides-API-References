---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents paragraph bullet formatting properties.
type: docs
url: /es/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Representa las propiedades de formato de viñetas de párrafo.
## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | Devuelve o establece el tipo de viñeta de un párrafo sin herencia. |
| [setType(byte value)](#setType-byte-) | Devuelve o establece el tipo de viñeta de un párrafo sin herencia. |
| [getChar()](#getChar--) | Devuelve o establece el carácter de viñeta de un párrafo sin herencia. |
| [setChar(char value)](#setChar-char-) | Devuelve o establece el carácter de viñeta de un párrafo sin herencia. |
| [getFont()](#getFont--) | Devuelve o establece la fuente de viñeta de un párrafo sin herencia. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Devuelve o establece la fuente de viñeta de un párrafo sin herencia. |
| [getHeight()](#getHeight--) | Devuelve o establece la altura de viñeta de un párrafo sin herencia. |
| [setHeight(float value)](#setHeight-float-) | Devuelve o establece la altura de viñeta de un párrafo sin herencia. |
| [getColor()](#getColor--) | Devuelve el formato de color de una viñeta de un párrafo sin herencia. |
| [getPicture()](#getPicture--) | Devuelve la imagen utilizada como viñeta en un párrafo sin herencia. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Devuelve o establece el primer número que se usa para el grupo de viñetas numeradas sin herencia. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Devuelve o establece el primer número que se usa para el grupo de viñetas numeradas sin herencia. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Devuelve o establece el estilo de una viñeta numerada sin herencia. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Devuelve o establece el estilo de una viñeta numerada sin herencia. |
| [isBulletHardColor()](#isBulletHardColor--) | Determina si la viñeta tiene color propio o lo hereda de la primera porción del párrafo. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Determina si la viñeta tiene color propio o lo hereda de la primera porción del párrafo. |
| [isBulletHardFont()](#isBulletHardFont--) | Determina si la viñeta tiene fuente propia o la hereda de la primera porción del párrafo. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Determina si la viñeta tiene fuente propia o la hereda de la primera porción del párrafo. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Establece desplazamientos predeterminados distintos de cero para el sangrado y MarginLeft efectivos del párrafo cuando las viñetas están habilitadas (como PowerPoint hace al habilitar viñetas/numeración en él). |
| [getEffective()](#getEffective--) | Obtiene los datos de formato de viñeta efectivos con la herencia aplicada. |
### getType() {#getType--}
```
public abstract byte getType()
```

Devuelve o establece el tipo de viñeta de un párrafo sin herencia. Lectura/escritura [BulletType](../../com.aspose.slides/bullettype).

**Devuelve:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Devuelve o establece el tipo de viñeta de un párrafo sin herencia. Lectura/escritura [BulletType](../../com.aspose.slides/bullettype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```

Devuelve o establece el carácter de viñeta de un párrafo sin herencia. Lectura/escritura char.

**Devuelve:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

Devuelve o establece el carácter de viñeta de un párrafo sin herencia. Lectura/escritura char.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Devuelve o establece la fuente de viñeta de un párrafo sin herencia. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

Devuelve o establece la fuente de viñeta de un párrafo sin herencia. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Devuelve o establece la altura de viñeta de un párrafo sin herencia. El valor Float.NaN determina que la viñeta hereda la altura de la primera porción del párrafo. Lectura/escritura float.

**Devuelve:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Devuelve o establece la altura de viñeta de un párrafo sin herencia. El valor Float.NaN determina que la viñeta hereda la altura de la primera porción del párrafo. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Devuelve el formato de color de una viñeta de un párrafo sin herencia. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Devuelve la imagen utilizada como viñeta en un párrafo sin herencia. Solo lectura [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Devuelve:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Devuelve o establece el primer número que se usa para el grupo de viñetas numeradas sin herencia. Lectura/escritura short.

**Devuelve:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

Devuelve o establece el primer número que se usa para el grupo de viñetas numeradas sin herencia. Lectura/escritura short.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Devuelve o establece el estilo de una viñeta numerada sin herencia. Lectura/escritura [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Devuelve:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

Devuelve o establece el estilo de una viñeta numerada sin herencia. Lectura/escritura [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

Determina si la viñeta tiene color propio o lo hereda de la primera porción del párrafo. **NullableBool\#True** si la viñeta tiene color propio y **NullableBool\#False** si la viñeta hereda el color de la primera porción del párrafo. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

Determina si la viñeta tiene color propio o lo hereda de la primera porción del párrafo. **NullableBool\#True** si la viñeta tiene color propio y **NullableBool\#False** si la viñeta hereda el color de la primera porción del párrafo. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

Determina si la viñeta tiene fuente propia o la hereda de la primera porción del párrafo. **NullableBool\#True** si la viñeta tiene fuente propia y **NullableBool\#False** si la viñeta hereda la fuente de la primera porción del párrafo. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

Determina si la viñeta tiene fuente propia o la hereda de la primera porción del párrafo. **NullableBool\#True** si la viñeta tiene fuente propia y **NullableBool\#False** si la viñeta hereda la fuente de la primera porción del párrafo. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

Establece desplazamientos predeterminados distintos de cero para el sangrado y MarginLeft efectivos del párrafo cuando las viñetas están habilitadas (como PowerPoint hace al habilitar viñetas/numeración en él). Si las viñetas están deshabilitadas, simplemente restablece el sangrado y MarginLeft del párrafo (como PowerPoint hace al deshabilitar viñetas/numeración). Los desplazamientos de sangrado se aplican respecto al contexto actual de la viñeta — IBulletFormat.Type, .NumberedBulletStyle y FontHeight de la primera porción. Los desplazamientos distintos de cero se aplican al sangrado y MarginLeft efectivos del párrafo actual (haciendo que los valores resultantes sean locales).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

Obtiene los datos de formato de viñeta efectivos con la herencia aplicada.

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).