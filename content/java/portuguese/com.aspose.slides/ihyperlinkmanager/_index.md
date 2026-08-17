---
title: IHyperlinkManager
second_title: Aspose.Slides para Java Referência da API
description: Fornece gerenciamento de hyperlinks, adicionando e removendo.
type: docs
url: /pt/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Fornece gerenciamento de hyperlinks (adição, remoção).
## Métodos

| Method | Description |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Define hyperlink externo ao clicar. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Define hyperlink interno ao clicar. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Remove hyperlink ao clicar. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Define hyperlink externo ao passar o mouse. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Define hyperlink interno ao passar o mouse. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Remove hyperlink ao passar o mouse. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Define hyperlink de Macro ao clicar. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```


Define hyperlink externo ao clicar.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | java.lang.String | URL do Hyperlink. |

**Retorna:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - objeto Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


Define hyperlink interno ao clicar.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Slide de destino. |

**Retorna:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```


Remove hyperlink ao clicar.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```


Define hyperlink externo ao passar o mouse.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | java.lang.String | URL do Hyperlink. |

**Retorna:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - objeto Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


Define hyperlink interno ao passar o mouse.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Slide de destino. |

**Retorna:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - objeto Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```


Remove hyperlink ao passar o mouse.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```


Define hyperlink de Macro ao clicar.

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

**Retorna:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - objeto Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)