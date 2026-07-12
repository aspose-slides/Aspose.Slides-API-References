---
title: IMasterSlide
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um slide mestre em uma apresentação.
type: docs
url: /pt/com.aspose.slides/imasterslide/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Representa um slide mestre em uma apresentação.
## Métodos

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retorna o gerenciador HeaderFooter do slide mestre. |
| [getTitleStyle()](#getTitleStyle--) | Retorna o estilo de um texto de título. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Cria um novo slide mestre com base no atual, aplica um tema externo a ele e aplica o slide mestre criado a todos os slides dependentes. |
| [getBodyStyle()](#getBodyStyle--) | Retorna o estilo de um texto de corpo. |
| [getOtherStyle()](#getOtherStyle--) | Retorna o estilo de um outro texto. |
| [getLayoutSlides()](#getLayoutSlides--) | Retorna a coleção de slides de layout filho deste slide mestre. |
| [getPreserve()](#getPreserve--) | Determina se o mestre correspondente é excluído quando todos os slides que seguem esse mestre são excluídos. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Determina se o mestre correspondente é excluído quando todos os slides que seguem esse mestre são excluídos. |
| [hasDependingSlides()](#hasDependingSlides--) | Retorna true se existir ao menos um slide que dependa deste slide mestre. |
| [getDependingSlides()](#getDependingSlides--) | Retorna um array com todos os slides que dependem deste slide mestre. |
| [getDrawingGuides()](#getDrawingGuides--) | Retorna uma coleção de guias de desenho para o slide mestre. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Retorna o gerenciador HeaderFooter do slide mestre. Somente leitura [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Retorna:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

Retorna o estilo de um texto de título. Somente leitura [ITextStyle](../../com.aspose.slides/itextstyle).

**Retorna:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Cria um novo slide mestre com base no atual, aplica um tema externo a ele e aplica o slide mestre criado a todos os slides dependentes.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Caminho para o arquivo de tema externo (.thmx). |

**Retorna:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Novo MasterSlide com tema.

### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

Retorna o estilo de um texto de corpo. Somente leitura [ITextStyle](../../com.aspose.slides/itextstyle).

**Retorna:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

Retorna o estilo de um outro texto. Somente leitura [ITextStyle](../../com.aspose.slides/itextstyle).

**Retorna:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

Retorna a coleção de slides de layout filho deste slide mestre. Somente leitura [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Você pode acessar a API alternativa para adicionar/inserir/remover/clonar slides de layout usando a propriedade ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Retorna:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

Determina se o mestre correspondente é excluído quando todos os slides que seguem esse mestre são excluídos. Nota: Aspose.Slides nunca removerá nenhum mestre não usado por conta própria; para realmente remover mestres não usados chame [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Leitura/gravação boolean.

**Retorna:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

Determina se o mestre correspondente é excluído quando todos os slides que seguem esse mestre são excluídos. Nota: Aspose.Slides nunca removerá nenhum mestre não usado por conta própria; para realmente remover mestres não usados chame [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Leitura/gravação boolean.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Retorna true se existir ao menos um slide que dependa deste slide mestre. Somente leitura boolean.

**Retorna:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Retorna um array com todos os slides que dependem deste slide mestre.

**Retorna:**
com.aspose.slides.ISlide[] - Array de [ISlide](../../com.aspose.slides/islide), que dependem deste slide mestre
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
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