---
title: IParagraph
second_title: Referência da API Aspose.Slides para Java
description: Representa um parágrafo de um texto.
type: docs
url: /pt/com.aspose.slides/iparagraph/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Representa um parágrafo de um texto.
## Métodos

| Método | Descrição |
| --- | --- |
| [getPortions()](#getPortions--) | Retorna a coleção de porções de texto. |
| [getParagraphFormat()](#getParagraphFormat--) | Retorna o objeto de formatação para este parágrafo. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Une execuções com a mesma formatação. |
| [getText()](#getText--) | Obtém ou define o texto simples de um parágrafo. |
| [setText(String value)](#setText-java.lang.String-) | Obtém ou define o texto simples de um parágrafo. |
| [getRect()](#getRect--) | Obtém as coordenadas do retângulo que delimita o parágrafo. |
| [getLinesCount()](#getLinesCount--) | Obtém o número de linhas em um parágrafo. |
| [getImage()](#getImage--) | Retorna uma imagem do parágrafo. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Retorna uma imagem do parágrafo com a escala especificada. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Especifica as propriedades da porção que serão usadas se outra porção for inserida após a última. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Especifica as propriedades da porção que serão usadas se outra porção for inserida após a última. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

Retorna a coleção de porções de texto. Somente leitura [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Retorna:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

Retorna o objeto de formatação para este parágrafo. Somente leitura [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Retorna:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Une execuções com a mesma formatação.

### getText() {#getText--}
```
public abstract String getText()
```

Obtém ou define o texto simples de um parágrafo. Leitura/gravação String.

Valor: O texto.

**Retorna:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Obtém ou define o texto simples de um parágrafo. Leitura/gravação String.

Valor: O texto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Obtém as coordenadas do retângulo que delimita o parágrafo. O retângulo inclui todas as linhas de texto no parágrafo, inclusive as vazias.

**Retorna:**
java.awt.geom.Rectangle2D.Float - Retângulo que delimita o parágrafo java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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
public abstract IImage getImage()
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
[IImage](../../com.aspose.slides/iimage) - Uma imagem contendo o parágrafo renderizado, ou null se o parágrafo não for encontrado na coleção pai, não possuir limites de renderização válidos ou ocorrer um erro ao renderizar a imagem.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Retorna uma imagem do parágrafo com a escala especificada.

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
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
[IImage](../../com.aspose.slides/iimage) - Uma imagem contendo o parágrafo renderizado, ou null se o parágrafo não for encontrado na coleção pai, não possuir limites de renderização válidos ou ocorrer um erro ao renderizar a imagem.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

Especifica as propriedades da porção que serão usadas se outra porção for inserida após a última.

**Retorna:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

Especifica as propriedades da porção que serão usadas se outra porção for inserida após a última.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |