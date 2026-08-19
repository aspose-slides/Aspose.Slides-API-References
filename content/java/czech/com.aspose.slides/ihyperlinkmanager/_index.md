---
title: IHyperlinkManager
second_title: Aspose.Slides for Java API Reference
description: Poskytuje správu hypertextových odkazů (přidávání, odstraňování).
type: docs
url: /cs/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Poskytuje správu hypertextových odkazů (přidávání, odstraňování).
## Metody

| Metoda | Popis |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Nastaví externí hypertextový odkaz po kliknutí. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Nastaví interní hypertextový odkaz po kliknutí. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Odstraní hypertextový odkaz po kliknutí. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Nastaví externí hypertextový odkaz při přejetí myší. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Nastaví interní hypertextový odkaz při přejetí myší. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Odstraní hypertextový odkaz při přejetí myší. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Nastaví hypertextový odkaz na makro po kliknutí. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```


Nastaví externí hypertextový odkaz po kliknutí.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| url | java.lang.String | URL hypertextového odkazu. |

**Návratová hodnota:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink objekt [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


Nastaví interní hypertextový odkaz po kliknutí.

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


Odstraní hypertextový odkaz po kliknutí.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```


Nastaví externí hypertextový odkaz při přejetí myší.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| url | java.lang.String | URL hypertextového odkazu. |

**Návratová hodnota:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


Nastaví interní hypertextový odkaz při přejetí myší.

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


Odstraní hypertextový odkaz při přejetí myší.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```


Nastaví hypertextový odkaz na makro po kliknutí.

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
| macroName | java.lang.String | Název makra |

**Návratová hodnota:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink objekt [IHyperlink](../../com.aspose.slides/ihyperlink)