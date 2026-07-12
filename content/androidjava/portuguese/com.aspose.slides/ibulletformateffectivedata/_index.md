---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides para Android via Java API Reference
description: Objeto imutável que contém propriedades de formatação de marcadores de parágrafo efetivas.
type: docs
url: /pt/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

Objeto imutável que contém propriedades de formatação de marcadores de parágrafo efetivas.

--------------------

Esta interface é usada como parte de [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Métodos

| Método | Descrição |
| --- | --- |
| [getType()](#getType--) | Retorna o tipo de marcador de um parágrafo. |
| [getChar()](#getChar--) | Retorna o caractere de marcador de um parágrafo. |
| [getActualBulletValue()](#getActualBulletValue--) | Retorna o valor real do marcador para o parágrafo pai. |
| [getFont()](#getFont--) | Retorna a fonte do marcador de um parágrafo. |
| [getHeight()](#getHeight--) | Retorna a altura do marcador de um parágrafo. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Retorna o primeiro número usado para o grupo de marcadores numerados. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Retorna o estilo de um marcador numerado. |
| [isBulletHardColor()](#isBulletHardColor--) | Determina se o marcador tem cor própria ou a herda da primeira porção no parágrafo. |
| [isBulletHardFont()](#isBulletHardFont--) | Determina se o marcador tem fonte própria ou a herda da primeira porção no parágrafo. |
| [getPicture()](#getPicture--) | Retorna a imagem usada como marcador no parágrafo. |
| [getFillFormat()](#getFillFormat--) | Retorna o formato de preenchimento do marcador de um parágrafo. |
### getType() {#getType--}
```
public abstract byte getType()
```


Retorna o tipo de marcador de um parágrafo. Somente leitura [BulletType](../../com.aspose.slides/bullettype).

**Retorna:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


Retorna o caractere de marcador de um parágrafo. Somente leitura char.

**Retorna:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


Retorna o valor real do marcador para o parágrafo pai. Somente leitura String.

**Retorna:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


Retorna a fonte do marcador de um parágrafo. Somente leitura [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Retorna a altura do marcador de um parágrafo. Somente leitura float.

**Retorna:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


Retorna o primeiro número usado para o grupo de marcadores numerados. Somente leitura short.

**Retorna:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


Retorna o estilo de um marcador numerado. Somente leitura [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Retorna:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


Determina se o marcador tem cor própria ou a herda da primeira porção no parágrafo. Retorna **true** se o marcador tem cor própria e **false** se o marcador herda a cor da primeira porção no parágrafo. Somente leitura boolean.

**Retorna:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


Determina se o marcador tem fonte própria ou a herda da primeira porção no parágrafo. Retorna **true** se o marcador tem fonte própria e **true** se o marcador herda a fonte da primeira porção no parágrafo. Somente leitura boolean.

**Retorna:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Retorna a imagem usada como marcador no parágrafo. Somente leitura [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Retorna:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Retorna o formato de preenchimento do marcador de um parágrafo. Somente leitura [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Assuma que a primeira forma no primeiro slide é AutoShape com algum texto...
>      // Exiba informações sobre os marcadores dos parágrafos de texto
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


**Retorna:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)