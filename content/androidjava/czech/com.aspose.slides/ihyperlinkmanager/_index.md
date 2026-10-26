---
title: IHyperlinkManager
second_title: Aspose.Slides for Android via Java API Reference
description: Provide hyperlinks management adding removing.
type: docs
url: /cs/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Poskytuje správu hyperlinks (přidávání, odstraňování).
## Metody

| Metoda | Popis |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Set external hyperlink on click. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Sets internal hyperlink on click. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Removes hyperlink on click. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Sets external hyperlink mouse over. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Sets internal hyperlink mouse over. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Removes hyperlink mouse over. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Set Macro hyperlink on a click. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```


Nastaví externí hyperlink při kliknutí.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| url | java.lang.String | Hyperlink URL. |

**Návratová hodnota:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink objekt [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


Nastaví interní hyperlink při kliknutí.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Cílový snímek. |

**Návratová hodnota:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```


Odstraní hyperlink při kliknutí.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```


Nastaví externí hyperlink při najetí myší.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| url | java.lang.String | Hyperlink URL. |

**Návratová hodnota:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


Nastaví interní hyperlink při najetí myší.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Cílový snímek. |

**Návratová hodnota:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```


Odstraní hyperlink při najetí myší.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```


Nastaví Macro hyperlink při kliknutí.

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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| macroName | java.lang.String | Name of the macro |

**Návratová hodnota:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink objekt [IHyperlink](../../com.aspose.slides/ihyperlink)