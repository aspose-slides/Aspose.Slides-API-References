---
title: Paragraph
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um parágrafo de texto.
type: docs
url: /pt/com.aspose.slides/paragraph/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Representa um parágrafo de texto.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [Paragraph()](#Paragraph--) | Inicializa uma nova instância da classe Paragraph com propriedades padrão. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Construtor de cópia que inicializa uma nova instância de uma classe Paragraph. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getPortions()](#getPortions--) | Retorna a coleção de porções de texto. |
| [getParagraphFormat()](#getParagraphFormat--) | Retorna o objeto de formatação para este parágrafo. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Mescla execuções com a mesma formatação. |
| [getText()](#getText--) | Obtém ou define o texto simples de um parágrafo. |
| [setText(String value)](#setText-java.lang.String-) | Obtém ou define o texto simples de um parágrafo. |
| [getRect()](#getRect--) | Obtém as coordenadas do retângulo que delimita o parágrafo. |
| [getLinesCount()](#getLinesCount--) | Obtém o número de linhas em um parágrafo. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Especifica as propriedades da porção que serão usadas se outra porção for inserida após a última. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Especifica as propriedades da porção que serão usadas se outra porção for inserida após a última. |
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

Construtor de cópia que inicializa uma nova instância de uma classe Paragraph.

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

Retorna o objeto de formatação para este parágrafo. Somente leitura [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

O objeto de formatação contém os parâmetros de formatação definidos apenas para o parágrafo atual; dados herdados não são aplicados.

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
public final RectF getRect()
```

Obtém as coordenadas do retângulo que delimita o parágrafo. O retângulo inclui todas as linhas de texto no parágrafo, incluindo as vazias.

**Retorna:**
android.graphics.RectF
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
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Especifica as propriedades da porção que serão usadas se outra porção for inserida após a última.

**Retorna:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Especifica as propriedades da porção que serão usadas se outra porção for inserida após a última.

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