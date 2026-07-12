---
title: MasterSlide
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um slide mestre em uma apresentação.
type: docs
url: /pt/com.aspose.slides/masterslide/
---
**Herança:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Representa um slide mestre em uma apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retorna o gerenciador HeaderFooter do slide mestre. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Cria um novo slide mestre baseado no atual, aplicando um tema externo a ele e aplica o slide mestre criado a todos os slides dependentes. |
| [getTitleStyle()](#getTitleStyle--) | Retorna o estilo de um texto de título. |
| [getBodyStyle()](#getBodyStyle--) | Retorna o estilo de um texto de corpo. |
| [getOtherStyle()](#getOtherStyle--) | Retorna o estilo de um outro texto. |
| [getLayoutSlides()](#getLayoutSlides--) | Retorna a coleção de slides de layout filho para este slide mestre. |
| [getPreserve()](#getPreserve--) | Determina se o mestre correspondente é excluído quando todos os slides que seguem esse mestre são excluídos. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Determina se o mestre correspondente é excluído quando todos os slides que seguem esse mestre são excluídos. |
| [getDependingSlides()](#getDependingSlides--) | Retorna um array com todos os slides que dependem deste slide mestre. |
| [hasDependingSlides()](#hasDependingSlides--) | Retorna true se existir ao menos um slide que depende deste slide mestre. |
| [getThemeManager()](#getThemeManager--) | Retorna o gerenciador de tema. |
| [getName()](#getName--) | Retorna ou define o nome de um slide mestre. |
| [setName(String value)](#setName-java.lang.String-) | Retorna ou define o nome de um slide mestre. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. |
| [getDrawingGuides()](#getDrawingGuides--) | Retorna uma coleção de guias de desenho para o slide mestre. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Retorna o gerenciador HeaderFooter do slide mestre. Somente leitura [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Retorna:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Cria um novo slide mestre baseado no atual, aplicando um tema externo a ele e aplica o slide mestre criado a todos os slides dependentes.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fname | java.lang.String | Caminho para o arquivo de tema externo (.thmx). |

**Retorna:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Novo MasterSlide com tema.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Retorna o estilo de um texto de título. Somente leitura [ITextStyle](../../com.aspose.slides/itextstyle).

**Retorna:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Retorna o estilo de um texto de corpo. Somente leitura [ITextStyle](../../com.aspose.slides/itextstyle).

**Retorna:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Retorna o estilo de um outro texto. Somente leitura [ITextStyle](../../com.aspose.slides/itextstyle).

**Retorna:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Retorna a coleção de slides de layout filho para este slide mestre. Somente leitura [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Você pode acessar a API alternativa para adicionar/inserir/remover/clonar slides de layout usando a propriedade ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Retorna:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Determina se o mestre correspondente é excluído quando todos os slides que seguem esse mestre são excluídos. Observação: Aspose.Slides nunca removerá nenhum mestre não utilizado por conta própria; para realmente remover mestres não utilizados, chame [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Leitura/Gravação  boolean .

**Retorna:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Determina se o mestre correspondente é excluído quando todos os slides que seguem esse mestre são excluídos. Observação: Aspose.Slides nunca removerá nenhum mestre não utilizado por conta própria; para realmente remover mestres não utilizados, chame [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Leitura/Gravação  boolean .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Retorna um array com todos os slides que dependem deste slide mestre.

**Retorna:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Retorna true se existir ao menos um slide que depende deste slide mestre. Somente leitura  boolean .

**Retorna:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Retorna o gerenciador de tema. Somente leitura [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Retorna:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

Retorna ou define o nome de um slide mestre. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Retorna ou define o nome de um slide mestre. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Especifica se as formas no slide mestre devem ser mostradas nos slides ou não. Para o próprio slide mestre, esta propriedade sempre retorna  false . Leitura/Gravação  boolean .

**Retorna:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Especifica se as formas no slide mestre devem ser mostradas nos slides ou não. Para o próprio slide mestre, esta propriedade sempre retorna  false . Leitura/Gravação  boolean .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Retorna uma coleção de guias de desenho para o slide mestre. Somente leitura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Adicionando o novo guia de desenho vertical à direita do centro do slide
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)