---
title: Paragraph
second_title: Referência da API Aspose.Slides para Java
description: Representa um parágrafo de texto.
type: docs
url: /pt/com.aspose.slides/paragraph/
---
**Herança:**
java.lang.Object

**Todas as interfaces implementadas:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Representa um parágrafo de texto.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [Paragraph()](#Paragraph--) | Inicializa uma nova instância da classe Paragraph com propriedades padrão. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Construtor de cópia que inicializa uma nova instância da classe Paragraph. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getPortions()](#getPortions--) | Retorna a coleção de porções de texto. |
| [getParagraphFormat()](#getParagraphFormat--) | Retorna o objeto de formatação deste parágrafo. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Mescla execuções com a mesma formatação. |
| [getText()](#getText--) | Obtém ou define o texto simples de um parágrafo. |
| [setText(String value)](#setText-java.lang.String-) | Obtém ou define o texto simples de um parágrafo. |
| [getRect()](#getRect--) | Obtém as coordenadas do retângulo que delimita o parágrafo. |
| [getLinesCount()](#getLinesCount--) | Obtém o número de linhas em um parágrafo. |
| [getImage()](#getImage--) | Retorna uma imagem do parágrafo. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Retorna uma imagem do parágrafo com a escala especificada. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Especifica as propriedades da porção que devem ser usadas se outra porção for inserida após a última. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Especifica as propriedades da porção que devem ser usadas se outra porção for inserida após a última. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Retorna o slide pai de um parágrafo. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um parágrafo. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```


Inicializa uma nova instância da classe Paragraph com propriedades padrão.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```


Construtor de cópia que inicializa uma nova instância da classe Paragraph.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```


Retorna a coleção de porções de texto. Somente leitura [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Retorna:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```


Retorna o objeto de formatação deste parágrafo. Somente leitura [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

O objeto de formatação contém os parâmetros de formatação definidos apenas para o parágrafo atual, dados herdados não são aplicados.

Para obter os valores efetivos, incluindo os herdados, use o método [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Retorna:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Mescla execuções com a mesma formatação.

### getText() {#getText--}
```
public final String getText()
```


Obtém ou define o texto simples de um parágrafo. Leitura/gravação String.

Valor: O texto.

**Retorna:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Obtém ou define o texto simples de um parágrafo. Leitura/gravação String.

Valor: O texto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```


Obtém as coordenadas do retângulo que delimita o parágrafo. O retângulo inclui todas as linhas de texto no parágrafo, inclusive as vazias.

**Retorna:**
java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```


Obtém o número de linhas em um parágrafo.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
int - Contagem de linhas em um parágrafo
### getImage() {#getImage--}
```
public final IImage getImage()
```


Retorna uma imagem do parágrafo.

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Uma imagem contendo o parágrafo renderizado, ou null se o parágrafo não puder ser encontrado em sua coleção pai, não possuir limites de renderização válidos ou ocorrer um erro ao renderizar a imagem.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```


Retorna uma imagem do parágrafo com a escala especificada.

--------------------

> ```
> O exemplo a seguir mostra como renderizar cada parágrafo de caixa de texto em um slide como uma imagem com dimensionamento personalizado:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| scaleX | float | O fator de escala horizontal aplicado à imagem do parágrafo. |
| scaleY | float | O fator de escala vertical aplicado à imagem do parágrafo. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Uma imagem contendo o parágrafo renderizado, ou null se o parágrafo não puder ser encontrado em sua coleção pai, não possuir limites de renderização válidos ou ocorrer um erro ao renderizar a imagem.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```


Especifica as propriedades da porção que devem ser usadas se outra porção for inserida após a última.

**Retorna:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```


Especifica as propriedades da porção que devem ser usadas se outra porção for inserida após a última.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Retorna o slide pai de um parágrafo. Somente leitura [BaseSlide](../../com.aspose.slides/baseslide).

**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Retorna a apresentação pai de um parágrafo. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)