---
title: IParagraph
second_title: Aspose.Slides para Android via Referência da API Java
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

| Method | Description |
| --- | --- |
| [getPortions()](#getPortions--) | Retorna a coleção de trechos de texto. |
| [getParagraphFormat()](#getParagraphFormat--) | Retorna o objeto de formatação para este parágrafo. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Mescla execuções com a mesma formatação. |
| [getText()](#getText--) | Obtém ou define o texto simples de um parágrafo. |
| [setText(String value)](#setText-java.lang.String-) | Obtém ou define o texto simples de um parágrafo. |
| [getRect()](#getRect--) | Obtém as coordenadas do retângulo que delimita o parágrafo. |
| [getLinesCount()](#getLinesCount--) | Obtém o número de linhas em um parágrafo. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Especifica as propriedades da porção que devem ser usadas se outra porção for inserida após a última. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Especifica as propriedades da porção que devem ser usadas se outra porção for inserida após a última. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```


Retorna a coleção de trechos de texto. Somente leitura [IPortionCollection](../../com.aspose.slides/iportioncollection).

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


Mescla execuções com a mesma formatação.

### getText() {#getText--}
```
public abstract String getText()
```


Obtém ou define o texto simples de um parágrafo. Leitura/Gravação String.

Valor: O texto.

**Retorna:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Obtém ou define o texto simples de um parágrafo. Leitura/Gravação String.

Valor: O texto.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```


Obtém as coordenadas do retângulo que delimita o parágrafo. O retângulo inclui todas as linhas de texto no parágrafo, incluindo as vazias.

**Retorna:**
android.graphics.RectF - Retângulo que delimita o parágrafo android.graphics.RectF
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
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


Especifica as propriedades da porção que devem ser usadas se outra porção for inserida após a última.

**Retorna:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


Especifica as propriedades da porção que devem ser usadas se outra porção for inserida após a última.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |