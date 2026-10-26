---
title: IHyperlinkManager
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller hantering av hyperlänkar för att lägga till och ta bort.
type: docs
url: /sv/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Tillhandahåller hantering av hyperlänkar (lägg till, ta bort).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Ställer in extern hyperlänk vid klick. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Ställer in intern hyperlänk vid klick. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Tar bort hyperlänk vid klick. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Ställer in extern hyperlänk när musen hålls över. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Ställer in intern hyperlänk när musen hålls över. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Tar bort hyperlänk när musen hålls över. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Ställer in makrohyperlänk vid klick. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Ställer in extern hyperlänk vid klick.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | java.lang.String | Hyperlänk URL. |

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
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
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

Tar bort hyperlänk vid klick.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Ställer in extern hyperlänk när musen hålls över.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | java.lang.String | Hyperlänk URL. |

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Ställer in intern hyperlänk när musen hålls över.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Målsida. |

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

Tar bort hyperlänk när musen hålls över.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

Ställer in makrohyperlänk vid klick.

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
| macroName | java.lang.String | Namn på makrot |

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)