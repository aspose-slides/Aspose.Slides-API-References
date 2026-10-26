---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides para Android mediante la API Java
description: Objeto inmutable que contiene las propiedades de formato de viñeta de párrafo efectivas.
type: docs
url: /es/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Objeto inmutable que contiene las propiedades de formato de viñeta de párrafo efectivas.

--------------------

Esta interfaz se usa como parte de [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | Devuelve el tipo de viñeta de un párrafo. |
| [getChar()](#getChar--) | Devuelve el carácter de viñeta de un párrafo. |
| [getActualBulletValue()](#getActualBulletValue--) | Devuelve el valor real de la viñeta para el párrafo principal. |
| [getFont()](#getFont--) | Devuelve la fuente de la viñeta de un párrafo. |
| [getHeight()](#getHeight--) | Devuelve la altura de la viñeta de un párrafo. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Devuelve el primer número que se usa para el grupo de viñetas numeradas. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Devuelve el estilo de una viñeta numerada. |
| [isBulletHardColor()](#isBulletHardColor--) | Determina si la viñeta tiene su propio color o lo hereda de la primera porción del párrafo. |
| [isBulletHardFont()](#isBulletHardFont--) | Determina si la viñeta tiene su propia fuente o la hereda de la primera porción del párrafo. |
| [getPicture()](#getPicture--) | Devuelve la imagen utilizada como viñeta en el párrafo. |
| [getFillFormat()](#getFillFormat--) | Devuelve el formato de relleno de la viñeta de un párrafo. |
### getType() {#getType--}
```
public abstract byte getType()
```

Devuelve el tipo de viñeta de un párrafo. Solo lectura [BulletType](../../com.aspose.slides/bullettype).

**Devuelve:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```

Devuelve el carácter de viñeta de un párrafo. Solo lectura char.

**Devuelve:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

Devuelve el valor real de la viñeta para el párrafo principal. Solo lectura String.

**Devuelve:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Devuelve la fuente de la viñeta de un párrafo. Solo lectura [IFontData](../../com.aspose.slides/ifontdata).

**Devuelve:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Devuelve la altura de la viñeta de un párrafo. Solo lectura float.

**Devuelve:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Devuelve el primer número que se usa para el grupo de viñetas numeradas. Solo lectura short.

**Devuelve:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Devuelve el estilo de una viñeta numerada. Solo lectura [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Devuelve:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

Determina si la viñeta tiene su propio color o lo hereda de la primera porción del párrafo. Devuelve **true** si la viñeta tiene su propio color y **false** si la viñeta hereda el color de la primera porción del párrafo. Solo lectura boolean.

**Devuelve:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

Determina si la viñeta tiene su propia fuente o la hereda de la primera porción del párrafo. Devuelve **true** si la viñeta tiene su propia fuente y **true** si la viñeta hereda la fuente de la primera porción del párrafo. Solo lectura boolean.

**Devuelve:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

Devuelve la imagen utilizada como viñeta en el párrafo. Solo lectura [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Devuelve:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Devuelve el formato de relleno de la viñeta de un párrafo. Solo lectura [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Assume that the first shape on the first slide is AutoShape with some text...
>      // Output information about text paragraphs' bullets
>      AutoShape autoShape = (AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for (IParagraph para : autoShape.getTextFrame().getParagraphs())
>      {
>          IBulletFormatEffectiveData bulletFormatEffective = para.getParagraphFormat().getBullet().getEffective();
>          System.out.println("Bullet type: " + bulletFormatEffective.getType());
>          if (bulletFormatEffective.getType() != BulletType.None)
>          {
>              System.out.println("Bullet fill type: " + bulletFormatEffective.getFillFormat().getFillType());
>              switch (bulletFormatEffective.getFillFormat().getFillType())
>              {
>                  case FillType.Solid:
>                      System.out.println("Solid fill color: " + bulletFormatEffective.getFillFormat().getSolidFillColor());
>                      break;
>                  case FillType.Gradient:
>                      System.out.println("Gradient stops count: " + bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops().size());
>                      for (IGradientStopEffectiveData gradStop : bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops())
>                          System.out.println(gradStop.getPosition() + ": " + gradStop.getColor());
>                      break;
>                  case FillType.Pattern:
>                      System.out.println("Pattern style: " + bulletFormatEffective.getFillFormat().getPatternFormat().getPatternStyle());
>                      System.out.println("Fore color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getForeColor());
>                      System.out.println("Back color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getBackColor());
>                      break;
>              }
>          }
>          System.out.println();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)