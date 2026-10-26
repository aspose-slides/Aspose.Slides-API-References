---
title: IHyperlinkManager
second_title: Aspose.Slides för Java API Reference
description: Tillhandahåll hantering av hyperlänkar (lägg till, ta bort).
type: docs
url: /sv/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Tillhandahåll hantering av hyperlänkar (lägg till, ta bort).

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Ställ in extern hyperlänk vid klick. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Ställer in intern hyperlänk vid klick. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Tar bort hyperlänk vid klick. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Ställer in extern hyperlänk vid mus över. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Ställer in intern hyperlänk vid mus över. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Tar bort hyperlänk vid mus över. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Ställ in makrohyperlänk vid ett klick. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Ställ in extern hyperlänk vid klick.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | java.lang.String | Hyperlänk-URL. |

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlänk-objekt [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Ställer in intern hyperlänk vid klick.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Målsida. |

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlänk.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

Tar bort hyperlänk vid klick.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Ställer in extern hyperlänk vid mus över.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | java.lang.String | Hyperlänk-URL. |

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlänk.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Ställer in intern hyperlänk vid mus över.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Målsida. |

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlänk.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

Tar bort hyperlänk vid mus över.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

Ställ in makrohyperlänk vid ett klick.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| macroName | java.lang.String | Namnet på makrot |

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlänk-objekt [IHyperlink](../../com.aspose.slides/ihyperlink)