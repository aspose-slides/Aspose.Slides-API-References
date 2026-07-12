---
title: IPortion
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma porção de texto dentro de um parágrafo de texto.
type: docs
url: /pt/com.aspose.slides/iportion/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Representa uma porção de texto dentro de um parágrafo de texto.
## Métodos

| Método | Descrição |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Retorna o objeto de formatação que contém propriedades de formatação definidas explicitamente da porção de texto sem herança aplicada. |
| [getText()](#getText--) | Obtém ou define o texto simples de uma porção. |
| [setText(String value)](#setText-java.lang.String-) | Obtém ou define o texto simples de uma porção. |
| [getField()](#getField--) | Retorna um campo desta porção. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Converte esta porção para o campo atualizado automaticamente. |
| [addField(String internalString)](#addField-java.lang.String-) | Converte esta porção para o campo atualizado automaticamente. |
| [removeField()](#removeField--) | Converte esta porção de campo para a porção simples. |
| [getRect()](#getRect--) | Obtém as coordenadas do retângulo que delimita a porção. |
| [getCoordinates()](#getCoordinates--) | Obtém as coordenadas do início da porção. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

Retorna o objeto de formatação que contém propriedades de formatação definidas explicitamente da porção de texto sem herança aplicada. Somente leitura [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

O objeto de formatação contém os parâmetros de formatação definidos apenas para a porção atual, dados herdados não são aplicados.

Para obter os valores efetivos incluindo os herdados, use o método [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective).

**Retorna:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

Obtém ou define o texto simples de uma porção. Leitura/Gravação String.

Valor: O texto.

**Retorna:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Obtém ou define o texto simples de uma porção. Leitura/Gravação String.

Valor: O texto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getField() {#getField--}
```
public abstract IField getField()
```

Retorna um campo desta porção. Somente leitura [IField](../../com.aspose.slides/ifield).

**Retorna:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

Converte esta porção para o campo atualizado automaticamente.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Tipo de campo [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

Converte esta porção para o campo atualizado automaticamente.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| internalString | java.lang.String | Nome interno da FieldTypeEx String |
### removeField() {#removeField--}
```
public abstract void removeField()
```

Converte esta porção de campo para a porção simples.
### getRect() {#getRect--}
```
public abstract RectF getRect()
```

Obtém as coordenadas do retângulo que delimita a porção. O retângulo inclui todas as linhas de texto na porção, incluindo linhas vazias.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
android.graphics.RectF - Retângulo que delimita a porção android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()
```

Obtém as coordenadas do início da porção. A coordenada X do ponto representa o início da porção a partir do primeiro caractere, incluindo o deslocamento lateral esquerdo. A coordenada Y inclui o deslocamento superior.

**Retorna:**
android.graphics.PointF - Coordenadas do início da porção android.graphics.PointF