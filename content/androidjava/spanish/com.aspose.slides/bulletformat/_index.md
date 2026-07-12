---
title: BulletFormat
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa las propiedades de formato de viñetas de párrafo.
type: docs
url: /es/com.aspose.slides/bulletformat/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
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
| [getHeight()](#getHeight--) | Devuelve o establece la altura de la viñeta de un párrafo sin herencia. |
| [setHeight(float value)](#setHeight-float-) | Devuelve o establece la altura de la viñeta de un párrafo sin herencia. |
| [getColor()](#getColor--) | Devuelve el formato de color de una viñeta de un párrafo sin herencia. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Devuelve o establece el primer número que se usa para el grupo de viñetas numeradas sin herencia. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Devuelve o establece el primer número que se usa para el grupo de viñetas numeradas sin herencia. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Devuelve o establece el estilo de una viñeta numerada sin herencia. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Devuelve o establece el estilo de una viñeta numerada sin herencia. |
| [isBulletHardColor()](#isBulletHardColor--) | Determina si la viñeta tiene color propio o lo hereda de la primera porción del párrafo. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Determina si la viñeta tiene color propio o lo hereda de la primera porción del párrafo. |
| [isBulletHardFont()](#isBulletHardFont--) | Determina si la viñeta tiene fuente propia o la hereda de la primera porción del párrafo. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Determina si la viñeta tiene fuente propia o la hereda de la primera porción del párrafo. |
| [getPicture()](#getPicture--) | Devuelve la imagen usada como viñeta en un párrafo sin herencia. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Establece desplazamientos predeterminados distintos de cero para el sangrado efectivo del párrafo y MarginLeft cuando las viñetas están habilitadas (como PowerPoint hace si habilita viñetas/numeración). |
| [getEffective()](#getEffective--) | Obtiene los datos de formato de viñeta efectivos con la herencia aplicada. |
| [getVersion()](#getVersion--) |  |
### getType() {#getType--}
```
public final byte getType()
```

Devuelve o establece el tipo de viñeta de un párrafo sin herencia. Lectura/escritura [BulletType](../../com.aspose.slides/bullettype).

**Devuelve:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Devuelve o establece el tipo de viñeta de un párrafo sin herencia. Lectura/escritura [BulletType](../../com.aspose.slides/bullettype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public final char getChar()
```

Devuelve o establece el carácter de viñeta de un párrafo sin herencia. Lectura/escritura char.

**Devuelve:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

Devuelve o establece el carácter de viñeta de un párrafo sin herencia. Lectura/escritura char.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public final IFontData getFont()
```

Devuelve o establece la fuente de viñeta de un párrafo sin herencia. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

Devuelve o establece la fuente de viñeta de un párrafo sin herencia. Lectura/escritura [IFontData](../../com.aspose.slides/ifontdata).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Devuelve o establece la altura de la viñeta de un párrafo sin herencia. El valor Float.NaN determina que la viñeta hereda la altura de la primera porción del párrafo. Lectura/escritura float.

--------------------

Un valor de altura negativo indica que la altura se da en puntos y un valor positivo indica que la altura es un porcentaje del texto circundante.

**Devuelve:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Devuelve o establece la altura de la viñeta de un párrafo sin herencia. El valor Float.NaN determina que la viñeta hereda la altura de la primera porción del párrafo. Lectura/escritura float.

--------------------

Un valor de altura negativo indica que la altura se da en puntos y un valor positivo indica que la altura es un porcentaje del texto circundante.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Devuelve el formato de color de una viñeta de un párrafo sin herencia. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

Devuelve o establece el primer número que se usa para el grupo de viñetas numeradas sin herencia. Lectura/escritura short.

**Devuelve:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

Devuelve o establece el primer número que se usa para el grupo de viñetas numeradas sin herencia. Lectura/escritura short.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

Devuelve o establece el estilo de una viñeta numerada sin herencia. Lectura/escritura [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Devuelve:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

Devuelve o establece el estilo de una viñeta numerada sin herencia. Lectura/escritura [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

Determina si la viñeta tiene color propio o lo hereda de la primera porción del párrafo. **NullableBool.True** si la viñeta tiene color propio y **NullableBool.False** si la viñeta hereda el color de la primera porción del párrafo. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

Determina si la viñeta tiene color propio o lo hereda de la primera porción del párrafo. **NullableBool.True** si la viñeta tiene color propio y **NullableBool.False** si la viñeta hereda el color de la primera porción del párrafo. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

Determina si la viñeta tiene fuente propia o la hereda de la primera porción del párrafo. **NullableBool.True** si la viñeta tiene fuente propia y **NullableBool.False** si la viñeta hereda la fuente de la primera porción del párrafo. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

Determina si la viñeta tiene fuente propia o la hereda de la primera porción del párrafo. **NullableBool.True** si la viñeta tiene fuente propia y **NullableBool.False** si la viñeta hereda la fuente de la primera porción del párrafo. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Devuelve la imagen usada como viñeta en un párrafo sin herencia. Solo lectura [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Devuelve:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

Establece desplazamientos predeterminados distintos de cero para el sangrado efectivo del párrafo y MarginLeft cuando las viñetas están habilitadas (como PowerPoint hace si habilita viñetas/numeración). Si las viñetas están deshabilitadas, simplemente restablece el sangrado del párrafo y MarginLeft (como PowerPoint hace si deshabilita viñetas/numeración). Los desplazamientos de sangrado se aplican respecto al contexto actual de la viñeta - IBulletFormat.Type, .NumberedBulletStyle y FontHeight de la primera porción. Los desplazamientos de sangrado distintos de cero se aplican al sangrado efectivo y MarginLeft del párrafo actual (hacen que los valores resultantes sean locales).
### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
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
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long