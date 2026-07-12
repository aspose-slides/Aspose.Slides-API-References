---
title: IBulletFormat
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa as propriedades de formatação de marcadores de parágrafo.
type: docs
url: /pt/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Representa as propriedades de formatação de marcadores de parágrafo.
## Métodos

| Método | Descrição |
| --- | --- |
| [getType()](#getType--) | Retorna ou define o tipo de marcador de um parágrafo sem herança. |
| [setType(byte value)](#setType-byte-) | Retorna ou define o tipo de marcador de um parágrafo sem herança. |
| [getChar()](#getChar--) | Retorna ou define o caractere de marcador de um parágrafo sem herança. |
| [setChar(char value)](#setChar-char-) | Retorna ou define o caractere de marcador de um parágrafo sem herança. |
| [getFont()](#getFont--) | Retorna ou define a fonte de marcador de um parágrafo sem herança. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Retorna ou define a fonte de marcador de um parágrafo sem herança. |
| [getHeight()](#getHeight--) | Retorna ou define a altura do marcador de um parágrafo sem herança. |
| [setHeight(float value)](#setHeight-float-) | Retorna ou define a altura do marcador de um parágrafo sem herança. |
| [getColor()](#getColor--) | Retorna o formato de cor de um marcador de um parágrafo sem herança. |
| [getPicture()](#getPicture--) | Retorna a imagem usada como marcador em um parágrafo sem herança. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Retorna ou define o primeiro número usado para um grupo de marcadores numerados sem herança. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Retorna ou define o primeiro número usado para um grupo de marcadores numerados sem herança. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Retorna ou define o estilo de um marcador numerado sem herança. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Retorna ou define o estilo de um marcador numerado sem herança. |
| [isBulletHardColor()](#isBulletHardColor--) | Determina se o marcador tem cor própria ou a herda da primeira porção do parágrafo. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Determina se o marcador tem cor própria ou a herda da primeira porção do parágrafo. |
| [isBulletHardFont()](#isBulletHardFont--) | Determina se o marcador tem fonte própria ou a herda da primeira porção do parágrafo. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Determina se o marcador tem fonte própria ou a herda da primeira porção do parágrafo. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Define deslocamentos padrão não-zero para Indent e MarginLeft efetivos do parágrafo quando marcadores estão habilitados (como o PowerPoint faz ao habilitar marcadores/numerção). |
| [getEffective()](#getEffective--) | Obtém os dados efetivos de formatação de marcador com a herança aplicada. |
### getType() {#getType--}
```
public abstract byte getType()
```

Retorna ou define o tipo de marcador de um parágrafo sem herança. Leitura/Gravação [BulletType](../../com.aspose.slides/bullettype).

**Retorna:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Retorna ou define o tipo de marcador de um parágrafo sem herança. Leitura/Gravação [BulletType](../../com.aspose.slides/bullettype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

Retorna ou define o caractere de marcador de um parágrafo sem herança. Leitura/Gravação char.

**Retorna:**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

Retorna ou define o caractere de marcador de um parágrafo sem herança. Leitura/Gravação char.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Retorna ou define a fonte de marcador de um parágrafo sem herança. Leitura/Gravação [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

Retorna ou define a fonte de marcador de um parágrafo sem herança. Leitura/Gravação [IFontData](../../com.aspose.slides/ifontdata).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Retorna ou define a altura do marcador de um parágrafo sem herança. O valor Float.NaN determina que o marcador herda a altura da primeira porção do parágrafo. Leitura/Gravação float.

**Retorna:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Retorna ou define a altura do marcador de um parágrafo sem herança. O valor Float.NaN determina que o marcador herda a altura da primeira porção do parágrafo. Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Retorna o formato de cor de um marcador de um parágrafo sem herança. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Retorna a imagem usada como marcador em um parágrafo sem herança. Somente leitura [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Retorna:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Retorna ou define o primeiro número usado para um grupo de marcadores numerados sem herança. Leitura/Gravação short.

**Retorna:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

Retorna ou define o primeiro número usado para um grupo de marcadores numerados sem herança. Leitura/Gravação short.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Retorna ou define o estilo de um marcador numerado sem herança. Leitura/Gravação [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Retorna:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

Retorna ou define o estilo de um marcador numerado sem herança. Leitura/Gravação [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

Determina se o marcador tem cor própria ou a herda da primeira porção do parágrafo. **NullableBool#True** se o marcador tem cor própria e **NullableBool#False** se herda a cor da primeira porção do parágrafo. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

Determina se o marcador tem cor própria ou a herda da primeira porção do parágrafo. **NullableBool#True** se o marcador tem cor própria e **NullableBool#False** se herda a cor da primeira porção do parágrafo. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

Determina se o marcador tem fonte própria ou a herda da primeira porção do parágrafo. **NullableBool#True** se o marcador tem fonte própria e **NullableBool#False** se herda a fonte da primeira porção do parágrafo. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

Determina se o marcador tem fonte própria ou a herda da primeira porção do parágrafo. **NullableBool#True** se o marcador tem fonte própria e **NullableBool#False** se herda a fonte da primeira porção do parágrafo. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

Define deslocamentos padrão não-zero para Indent e MarginLeft efetivos do parágrafo quando marcadores estão habilitados (como o PowerPoint faz ao habilitar marcadores/numerção). Se os marcadores estiverem desabilitados, apenas reinicia Indent e MarginLeft (como o PowerPoint faz ao desabilitar marcadores/numerção). Os deslocamentos de recuo são aplicados em relação ao contexto atual do marcador – IBulletFormat.Type, .NumberedBulletStyle e FontHeight da primeira porção. Deslocamentos de recuo não-zero são aplicados ao Indent e MarginLeft efetivos do parágrafo atual (fazendo com que os valores resultantes sejam locais).
### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

Obtém os dados efetivos de formatação de marcador com a herança aplicada.

--------------------

> ```
> Este exemplo demonstra como obter algumas propriedades efetivas de formatação de marcadores.
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


**Retorna:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).