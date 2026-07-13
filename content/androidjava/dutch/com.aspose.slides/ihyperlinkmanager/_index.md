---
title: IHyperlinkManager
second_title: Aspose.Slides for Android via Java API Reference
description: Biedt beheer van hyperlinks (toevoegen, verwijderen).
type: docs
url: /nl/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Biedt beheer van hyperlinks (toevoegen, verwijderen).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Stel een externe hyperlink in bij klikken. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Stelt interne hyperlink in bij klikken. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Verwijdert hyperlink bij klikken. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Stelt externe hyperlink in bij muisover. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Stelt interne hyperlink in bij muisover. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Verwijdert hyperlink bij muisover. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Stel macrohyperlink in bij klikken. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Stel een externe hyperlink in bij klikken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | java.lang.String | URL van de hyperlink. |

**Retourwaarde:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Stelt interne hyperlink in bij klikken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Doelslide. |

**Retourwaarde:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

Verwijdert hyperlink bij klikken.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Stelt externe hyperlink in bij muisover.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | java.lang.String | URL van de hyperlink. |

**Retourwaarde:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Stelt interne hyperlink in bij muisover.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Doelslide. |

**Retourwaarde:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

Verwijdert hyperlink bij muisover.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

Stel macrohyperlink in bij klikken.

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


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| macroName | java.lang.String | Naam van de macro |

**Retourwaarde:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)