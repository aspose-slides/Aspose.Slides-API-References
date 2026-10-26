---
title: ParagraphFormat
second_title: Referência da API Aspose.Slides para Java
description: Esta classe contém as propriedades de formatação de parágrafo.
type: docs
url: /pt/com.aspose.slides/paragraphformat/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Esta classe contém as propriedades de formatação de parágrafo. Ao contrário de [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), todas as propriedades desta classe são graváveis.

--------------------

Esta classe é usada para retornar e manipular as propriedades de formatação de parágrafo definidas para o parágrafo específico. Isso significa que nenhuma herança é aplicada ao obter valores, portanto, na maioria dos casos você receberá valores que significam "undefined".

Para obter os valores de parâmetro de formatação efetiva, incluindo herdados, você precisa usar o método [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) que retorna uma instância [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Inicializa uma nova instância da classe [ParagraphFormat](../../com.aspose.slides/paragraphformat). |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBullet()](#getBullet--) | Retorna o formato de marcador do parágrafo. |
| [getDepth()](#getDepth--) | Retorna ou define a profundidade do parágrafo. |
| [setDepth(short value)](#setDepth-short-) | Retorna ou define a profundidade do parágrafo. |
| [getAlignment()](#getAlignment--) | Retorna ou define o alinhamento de texto em um parágrafo sem herança. |
| [setAlignment(int value)](#setAlignment-int-) | Retorna ou define o alinhamento de texto em um parágrafo sem herança. |
| [getSpaceWithin()](#getSpaceWithin--) | Retorna ou define a quantidade de espaço entre linhas de base em um parágrafo. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Retorna ou define a quantidade de espaço entre linhas de base em um parágrafo. |
| [getSpaceBefore()](#getSpaceBefore--) | Retorna ou define a quantidade de espaço antes da primeira linha em um parágrafo sem herança. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Retorna ou define a quantidade de espaço antes da primeira linha em um parágrafo sem herança. |
| [getSpaceAfter()](#getSpaceAfter--) | Retorna ou define a quantidade de espaço após a última linha em um parágrafo sem herança. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Retorna ou define a quantidade de espaço após a última linha em um parágrafo sem herança. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Determina se a quebra de linha do Leste Asiático é usada em um parágrafo. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Determina se a quebra de linha do Leste Asiático é usada em um parágrafo. |
| [getRightToLeft()](#getRightToLeft--) | Determina se a escrita da direita para a esquerda é usada em um parágrafo. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Determina se a escrita da direita para a esquerda é usada em um parágrafo. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Determina se a quebra de linha latina é usada em um parágrafo. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Determina se a quebra de linha latina é usada em um parágrafo. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Determina se a pontuação suspensa é usada em um parágrafo. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Determina se a pontuação suspensa é usada em um parágrafo. |
| [getMarginLeft()](#getMarginLeft--) | Retorna ou define a margem esquerda em um parágrafo sem herança. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Retorna ou define a margem esquerda em um parágrafo sem herança. |
| [getMarginRight()](#getMarginRight--) | Retorna ou define a margem direita em um parágrafo sem herança. |
| [setMarginRight(float value)](#setMarginRight-float-) | Retorna ou define a margem direita em um parágrafo sem herança. |
| [getIndent()](#getIndent--) | Retorna ou define o recuo da primeira linha/recuo suspenso do parágrafo sem herança. |
| [setIndent(float value)](#setIndent-float-) | Retorna ou define o recuo da primeira linha/recuo suspenso do parágrafo sem herança. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Retorna ou define o tamanho de tabulação padrão sem herança. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Retorna ou define o tamanho de tabulação padrão sem herança. |
| [getTabs()](#getTabs--) | Retorna as tabulações de um parágrafo. |
| [getFontAlignment()](#getFontAlignment--) | Retorna ou define o alinhamento da fonte em um parágrafo sem herança. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Retorna ou define o alinhamento da fonte em um parágrafo sem herança. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Retorna o formato padrão de porção de um parágrafo. |
| [getEffective()](#getEffective--) | Obtém os dados de formatação efetiva do parágrafo com a herança aplicada. |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```


Inicializa uma nova instância da classe [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```


Retorna o formato de marcador do parágrafo. Somente leitura [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Retorna:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```


Retorna ou define a profundidade do parágrafo. Valor 0 significa valor indefinido. Leitura/gravação short .

**Retorna:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```


Retorna ou define a profundidade do parágrafo. Valor 0 significa valor indefinido. Leitura/gravação short .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Retorna ou define o alinhamento de texto em um parágrafo sem herança. Leitura/gravação [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instanciar um objeto Presentation que representa um arquivo PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Acessando o primeiro slide
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Acessando o primeiro e o segundo placeholder no slide e convertendo-o para AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Alterar o texto em ambos os placeholders
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Obtendo o primeiro parágrafo dos placeholders
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Alinhando o parágrafo de texto ao centro
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Escrevendo a apresentação como um arquivo PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Retorna ou define o alinhamento de texto em um parágrafo sem herança. Leitura/gravação [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instanciar um objeto Presentation que representa um arquivo PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Acessando o primeiro slide
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Acessando o primeiro e o segundo placeholder no slide e convertendo-o para AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Alterar o texto em ambos os placeholders
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Obtendo o primeiro parágrafo dos placeholders
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Alinhando o parágrafo de texto ao centro
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Escrevendo a apresentação como um arquivo PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```


Retorna ou define a quantidade de espaço entre linhas de base em um parágrafo. Valor positivo significa porcentagem, negativo – tamanho em pontos. Nenhuma herança aplicada. Leitura/gravação float .

**Retorna:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```


Retorna ou define a quantidade de espaço entre linhas de base em um parágrafo. Valor positivo significa porcentagem, negativo – tamanho em pontos. Nenhuma herança aplicada. Leitura/gravação float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```


Retorna ou define a quantidade de espaço antes da primeira linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ocupar. Um valor negativo especifica o tamanho do espaço em branco em pontos. Leitura/gravação float .

**Retorna:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```


Retorna ou define a quantidade de espaço antes da primeira linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ocupar. Um valor negativo especifica o tamanho do espaço em branco em pontos. Leitura/gravação float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```


Retorna ou define a quantidade de espaço após a última linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ocupar. Um valor negativo especifica o tamanho do espaço em branco em pontos. Leitura/gravação float .

**Retorna:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```


Retorna ou define a quantidade de espaço após a última linha em um parágrafo sem herança. Um valor positivo especifica a porcentagem do tamanho da fonte que o espaço em branco deve ocupar. Um valor negativo especifica o tamanho do espaço em branco em pontos. Leitura/gravação float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```


Determina se a quebra de linha do Leste Asiático é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```


Determina se a quebra de linha do Leste Asiático é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```


Determina se a escrita da direita para a esquerda é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```


Determina se a escrita da direita para a esquerda é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```


Determina se a quebra de linha latina é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```


Determina se a quebra de linha latina é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```


Determina se a pontuação suspensa é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```


Determina se a pontuação suspensa é usada em um parágrafo. Nenhuma herança aplicada. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


Retorna ou define a margem esquerda em um parágrafo sem herança. Leitura/gravação float .

**Retorna:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


Retorna ou define a margem esquerda em um parágrafo sem herança. Leitura/gravação float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


Retorna ou define a margem direita em um parágrafo sem herança. Leitura/gravação float .

**Retorna:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


Retorna ou define a margem direita em um parágrafo sem herança. Leitura/gravação float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```


Retorna ou define o recuo da primeira linha/recuo suspenso do parágrafo sem herança. O recuo suspenso pode ser definido com valores negativos. Leitura/gravação float .

**Retorna:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```


Retorna ou define o recuo da primeira linha/recuo suspenso do parágrafo sem herança. O recuo suspenso pode ser definido com valores negativos. Leitura/gravação float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```


Retorna ou define o tamanho de tabulação padrão sem herança. Leitura/gravação float .

**Retorna:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```


Retorna ou define o tamanho de tabulação padrão sem herança. Leitura/gravação float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```


Retorna as tabulações de um parágrafo. Nenhuma herança aplicada. Somente leitura [ITabCollection](../../com.aspose.slides/itabcollection).

**Retorna:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```


Retorna ou define o alinhamento da fonte em um parágrafo sem herança. Leitura/gravação [FontAlignment](../../com.aspose.slides/fontalignment).

**Retorna:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```


Retorna ou define o alinhamento da fonte em um parágrafo sem herança. Leitura/gravação [FontAlignment](../../com.aspose.slides/fontalignment).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```


Retorna o formato padrão de porção de um parágrafo. Nenhuma herança aplicada. Somente leitura [IPortionFormat](../../com.aspose.slides/iportionformat).

**Retorna:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```


Obtém os dados de formatação efetiva do parágrafo com a herança aplicada.

--------------------

> ```
> Este exemplo demonstra como obter algumas propriedades efetivas de formatação de parágrafo.
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


**Retorna:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versão. Somente leitura long.

**Retorna:**
long