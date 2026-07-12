---
title: IHyperlinkManager
second_title: Aspose.Slides für Android über Java API-Referenz
description: Bereitstellen der Verwaltung von Hyperlinks, Hinzufügen und Entfernen.
type: docs
url: /de/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Provide hyperlinks management (adding, removing).

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Setzt externen Hyperlink beim Klick. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Setzt internen Hyperlink beim Klick. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Entfernt Hyperlink beim Klick. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Setzt externen Hyperlink bei Mausüberfahrt. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Setzt internen Hyperlink bei Mausüberfahrt. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Entfernt Hyperlink bei Mausüberfahrt. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Setzt Makro-Hyperlink bei einem Klick. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Setzt externen Hyperlink beim Klick.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.lang.String | Hyperlink-URL. |

**Rückgabe:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink-Objekt [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Setzt internen Hyperlink beim Klick.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Zielfolie. |

**Rückgabe:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

Entfernt Hyperlink beim Klick.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Setzt externen Hyperlink bei Mausüberfahrt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.lang.String | Hyperlink-URL. |

**Rückgabe:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Setzt internen Hyperlink bei Mausüberfahrt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Zielfolie. |

**Rückgabe:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

Entfernt Hyperlink bei Mausüberfahrt.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

Setzt Makro-Hyperlink bei einem Klick.

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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| macroName | java.lang.String | Name des Makros |

**Rückgabe:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink-Objekt [IHyperlink](../../com.aspose.slides/ihyperlink)