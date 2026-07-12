---
title: BulletFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa as propriedades de formatação de marcadores de parágrafo.
type: docs
url: /pt/com.aspose.slides/bulletformat/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

Representa as propriedades de formatação de marcadores de parágrafo.
## Métodos

| Método | Descrição |
| --- | --- |
| [getType()](#getType--) | Retorna ou define o tipo de marcador de um parágrafo sem herança. |
| [setType(byte value)](#setType-byte-) | Retorna ou define o tipo de marcador de um parágrafo sem herança. |
| [getChar()](#getChar--) | Retorna ou define o caractere de marcador de um parágrafo sem herança. |
| [setChar(char value)](#setChar-char-) | Retorna ou define o caractere de marcador de um parágrafo sem herança. |
| [getFont()](#getFont--) | Retorna ou define a fonte do marcador de um parágrafo sem herança. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Retorna ou define a fonte do marcador de um parágrafo sem herança. |
| [getHeight()](#getHeight--) | Retorna ou define a altura do marcador de um parágrafo sem herança. |
| [setHeight(float value)](#setHeight-float-) | Retorna ou define a altura do marcador de um parágrafo sem herança. |
| [getColor()](#getColor--) | Retorna o formato de cor de um marcador de um parágrafo sem herança. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Retorna ou define o primeiro número usado para o grupo de marcadores numerados sem herança. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Retorna ou define o primeiro número usado para o grupo de marcadores numerados sem herança. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Retorna ou define o estilo de um marcador numerado sem herança. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Retorna ou define o estilo de um marcador numerado sem herança. |
| [isBulletHardColor()](#isBulletHardColor--) | Determina se o marcador tem cor própria ou a herda da primeira porção do parágrafo. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Determina se o marcador tem cor própria ou a herda da primeira porção do parágrafo. |
| [isBulletHardFont()](#isBulletHardFont--) | Determina se o marcador tem fonte própria ou a herda da primeira porção do parágrafo. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Determina se o marcador tem fonte própria ou a herda da primeira porção do parágrafo. |
| [getPicture()](#getPicture--) | Retorna a imagem usada como marcador em um parágrafo sem herança. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Define deslocamentos padrão diferentes de zero para Indent e MarginLeft efetivos do parágrafo quando marcadores estão habilitados (como o PowerPoint faz ao habilitar marcadores/numeração de parágrafo). |
| [getEffective()](#getEffective--) | Obtém dados de formatação de marcador efetivos com a herança aplicada. |
| [getVersion()](#getVersion--) |  |
### getType() {#getType--}
```
public final byte getType()
```


Retorna ou define o tipo de marcador de um parágrafo sem herança. Leitura/gravação [BulletType](../../com.aspose.slides/bullettype).

**Retorna:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


Retorna ou define o tipo de marcador de um parágrafo sem herança. Leitura/gravação [BulletType](../../com.aspose.slides/bullettype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```


Retorna ou define o caractere de marcador de um parágrafo sem herança. Leitura/gravação char .

**Retorna:**
char
### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```


Retorna ou define o caractere de marcador de um parágrafo sem herança. Leitura/gravação char .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```


Retorna ou define a fonte do marcador de um parágrafo sem herança. Leitura/gravação [IFontData](../../com.aspose.slides/ifontdata).

**Retorna:**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```


Retorna ou define a fonte do marcador de um parágrafo sem herança. Leitura/gravação [IFontData](../../com.aspose.slides/ifontdata).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Retorna ou define a altura do marcador de um parágrafo sem herança. O valor Float.NaN determina que o marcador herda a altura da primeira porção do parágrafo. Leitura/gravação float .

--------------------

Um valor de altura negativo indica que a altura é fornecida em pontos e um valor positivo indica que a altura é uma porcentagem do texto ao redor.

**Retorna:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Retorna ou define a altura do marcador de um parágrafo sem herança. O valor Float.NaN determina que o marcador herda a altura da primeira porção do parágrafo. Leitura/gravação float .

--------------------

Um valor de altura negativo indica que a altura é fornecida em pontos e um valor positivo indica que a altura é uma porcentagem do texto ao redor.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Retorna o formato de cor de um marcador de um parágrafo sem herança. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```


Retorna ou define o primeiro número usado para o grupo de marcadores numerados sem herança. Leitura/gravação short .

**Retorna:**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```


Retorna ou define o primeiro número usado para o grupo de marcadores numerados sem herança. Leitura/gravação short .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```


Retorna ou define o estilo de um marcador numerado sem herança. Leitura/gravação [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Retorna:**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```


Retorna ou define o estilo de um marcador numerado sem herança. Leitura/gravação [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```


Determina se o marcador tem cor própria ou a herda da primeira porção do parágrafo. **NullableBool.True** se o marcador tem cor própria e **NullableBool.False** se o marcador herda a cor da primeira porção do parágrafo. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```


Determina se o marcador tem cor própria ou a herda da primeira porção do parágrafo. **NullableBool.True** se o marcador tem cor própria e **NullableBool.False** se o marcador herda a cor da primeira porção do parágrafo. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```


Determina se o marcador tem fonte própria ou a herda da primeira porção do parágrafo. **NullableBool.True** se o marcador tem fonte própria e **NullableBool.False** se o marcador herda a fonte da primeira porção do parágrafo. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```


Determina se o marcador tem fonte própria ou a herda da primeira porção do parágrafo. **NullableBool.True** se o marcador tem fonte própria e **NullableBool.False** se o marcador herda a fonte da primeira porção do parágrafo. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```


Retorna a imagem usada como marcador em um parágrafo sem herança. Somente leitura [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Retorna:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```


Define deslocamentos padrão diferentes de zero para Indent e MarginLeft efetivos do parágrafo quando marcadores estão habilitados (como o PowerPoint faz ao habilitar marcadores/numeração de parágrafo). Se os marcadores estiverem desabilitados, apenas redefine Indent e MarginLeft do parágrafo (como o PowerPoint faz ao desabilitar marcadores/numeração de parágrafo). Os deslocamentos de recuo são aplicados em relação ao contexto atual do marcador — IBulletFormat.Type, .NumberedBulletStyle e FontHeight da primeira porção. Deslocamentos de recuo diferentes de zero são aplicados ao Indent e MarginLeft efetivos do parágrafo atual (fazendo com que os valores resultantes sejam locais).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```


Obtém dados de formatação de marcador efetivos com a herança aplicada.

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

**Retorna:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - Um [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versão. Somente leitura long.

**Retorna:**
long