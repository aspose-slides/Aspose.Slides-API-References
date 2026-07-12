---
title: PortionFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: Esta classe contém as propriedades de formatação da porção de texto.
type: docs
url: /pt/com.aspose.slides/portionformat/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

Esta classe contém as propriedades de formatação de porção de texto. Ao contrário de [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), todas as propriedades desta classe são graváveis.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Instancia um objeto Presentation que representa um arquivo de apresentação
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides usa esses identificadores especiais (semelhantes aos usados no PowerPoint):
>      // +mn-lt - Fonte do Corpo Latin (Fonte Latin Menor)
>      // +mj-lt -Fonte de Cabeçalho Latin (Fonte Latin Maior)
>      // +mn-ea - Fonte do Corpo East Asian (Fonte East Asian Menor)
>      // +mj-ea - Fonte do Corpo East Asian (Fonte East Asian Menor)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Esta classe é usada para retornar e manipular as propriedades de formatação de porção de texto definidas para a porção específica. Isso significa que nenhuma herança é aplicada ao obter valores, portanto, na maioria dos casos você receberá valores que significam “undefined”.

Para obter os valores efetivos dos parâmetros de formatação, incluindo os herdados, você precisa usar o método [getEffective](../../com.aspose.slides/portionformat\#getEffective), que retorna uma instância de [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Inicializa uma nova instância da classe [PortionFormat](../../com.aspose.slides/portionformat). |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Retorna ou define o identificador do marcador. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Retorna ou define o identificador do marcador. |
| [getSmartTagClean()](#getSmartTagClean--) | Determina se a smart tag deve ser limpa. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Determina se a smart tag deve ser limpa. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Retorna ou define o hyperlink definido para clique do mouse. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Retorna ou define o hyperlink definido para clique do mouse. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Retorna ou define o hyperlink definido para passar o mouse. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Retorna ou define o hyperlink definido para passar o mouse. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Gerenciador de hyperlinks. |
| [getEffective()](#getEffective--) | Obtém os dados de formatação de porção efetivos com a herança aplicada. |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

Inicializa uma nova instância da classe [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

Retorna ou define o identificador do marcador. Leitura/Escrita String.

**Retorna:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

Retorna ou define o identificador do marcador. Leitura/Escrita String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

Determina se a smart tag deve ser limpa. Nenhuma herança aplicada. Leitura/Escrita boolean.

**Retorna:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

Determina se a smart tag deve ser limpa. Nenhuma herança aplicada. Leitura/Escrita boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Retorna ou define o hyperlink definido para clique do mouse. Leitura/Escrita [IHyperlink](../../com.aspose.slides/ihyperlink).

**Retorna:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Retorna ou define o hyperlink definido para clique do mouse. Leitura/Escrita [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Retorna ou define o hyperlink definido para passar o mouse. Leitura/Escrita [IHyperlink](../../com.aspose.slides/ihyperlink).

**Retorna:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Retorna ou define o hyperlink definido para passar o mouse. Leitura/Escrita [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Gerenciador de hyperlinks. Somente leitura [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Retorna:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

Obtém os dados de formatação de porção efetivos com a herança aplicada.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).