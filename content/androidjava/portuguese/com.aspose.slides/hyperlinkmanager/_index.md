---
title: HyperlinkManager
second_title: Aspose.Slides para Android via Referência da API Java
description: Fornece gerenciamento de hyperlinks, adicionando e removendo.
type: docs
url: /pt/com.aspose.slides/hyperlinkmanager/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Fornece gerenciamento de hyperlinks (adição, remoção).
## Métodos

| Método | Descrição |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Define hyperlink externo ao clicar. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Define hyperlink interno ao clicar. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Remove hyperlink ao clicar. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Define hyperlink externo ao passar o mouse. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Define hyperlink interno ao passar o mouse. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Remove hyperlink ao passar o mouse. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Define hyperlink de macro ao clicar. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

Define hyperlink externo ao clicar.

--------------------

> ```
> O código de exemplo a seguir mostra como adicionar uma Caixa de Texto com Hyperlink.
>  
>  // Instancia uma classe Presentation que representa um PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Obtém o primeiro slide da apresentação
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Adiciona um objeto AutoShape com o tipo definido como Retângulo
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Converte a forma para AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Acessa a propriedade ITextFrame associada ao AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Adiciona algum texto ao frame
>      portion.setText("Aspose.Slides");
>      // Define o Hyperlink para o texto da porção
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Salva a apresentação PPTX
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | java.lang.String | URL do hyperlink. |

**Retorno:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Define hyperlink interno ao clicar.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Slide de destino. |

**Retorno:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

Remove hyperlink ao clicar.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

Define hyperlink externo ao passar o mouse.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | java.lang.String | URL do hyperlink. |

**Retorno:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Define hyperlink interno ao passar o mouse.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Slide de destino. |

**Retorno:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

Remove hyperlink ao passar o mouse.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

Define hyperlink de macro ao clicar.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
>      shape.getHyperlinkManager().setMacroHyperlinkClick("MacroName");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| macroName | java.lang.String | Nome da macro |

**Retorno:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - objeto Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorno:**
com.aspose.slides.IDOMObject