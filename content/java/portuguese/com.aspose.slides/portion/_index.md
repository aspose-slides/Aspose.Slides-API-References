---
title: Portion
second_title: Referência da API Aspose.Slides para Java
description: Representa uma porção de texto dentro de um parágrafo de texto.
type: docs
url: /pt/com.aspose.slides/portion/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Representa uma parte de texto dentro de um parágrafo de texto.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [Portion()](#Portion--) | Inicializa uma nova instância da classe Portion. |
| [Portion(String str)](#Portion-java.lang.String-) | Inicializa uma nova instância da classe Portion. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Inicializa uma nova instância da classe Portion. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Retorna o objeto de formatação que contém propriedades de formatação definidas explicitamente da porção de texto sem herança aplicada. |
| [getText()](#getText--) | Obtém ou define o texto simples de uma porção. |
| [setText(String value)](#setText-java.lang.String-) | Obtém ou define o texto simples de uma porção. |
| [getField()](#getField--) | Retorna um campo desta porção. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Converte esta porção no campo atualizado automaticamente. |
| [addField(String internalString)](#addField-java.lang.String-) | Converte esta porção no campo atualizado automaticamente. |
| [removeField()](#removeField--) | Converte esta porção de campo para a porção simples. |
| [getRect()](#getRect--) | Obtém as coordenadas do retângulo que delimita a porção. |
| [getCoordinates()](#getCoordinates--) | Obtém as coordenadas do início da porção. |
| [getSlide()](#getSlide--) | Retorna o slide pai de um texto. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um texto. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Inicializa uma nova instância da classe Portion.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Inicializa uma nova instância da classe Portion.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Inicializa uma nova instância da classe Portion.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Retorna o objeto de formatação que contém propriedades de formatação definidas explicitamente da porção de texto sem herança aplicada. Somente leitura [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

O objeto de formatação contém os parâmetros de formatação definidos apenas para a porção atual; dados herdados não são aplicados.

Para obter os valores efetivos incluindo os herdados, use o método [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective).

**Retorna:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Obtém ou define o texto simples de uma porção. Leitura/Gravação String.

Valor: O texto.

**Retorna:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Obtém ou define o texto simples de uma porção. Leitura/Gravação String.

Valor: O texto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Retorna um campo desta porção. Somente leitura [IField](../../com.aspose.slides/ifield).

**Retorna:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Converte esta porção no campo atualizado automaticamente.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Converte esta porção no campo atualizado automaticamente.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| internalString | java.lang.String | Nome interno do FieldType. |

### removeField() {#removeField--}
```
public final void removeField()
```

Converte esta porção de campo para a porção simples.

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

Obtém as coordenadas do retângulo que delimita a porção. O retângulo inclui todas as linhas de texto da porção, inclusive as vazias.

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
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```

Obtém as coordenadas do início da porção. A coordenada X do ponto representa o início da porção a partir do primeiro caractere, incluindo o espaçamento lateral esquerdo. A coordenada Y inclui o espaçamento superior.

**Retorna:**
java.awt.geom.Point2D.Float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retorna o slide pai de um texto. Somente leitura [BaseSlide](../../com.aspose.slides/baseslide).

**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retorna a apresentação pai de um texto. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject