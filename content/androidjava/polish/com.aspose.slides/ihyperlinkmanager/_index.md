---
title: IHyperlinkManager
second_title: Aspose.Slides for Android via Java API Reference
description: Provide hyperlinks management adding removing.
type: docs
url: /pl/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Zarządzaj hiperłączami (dodawanie, usuwanie).

## Metody

| Metoda | Opis |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Ustaw zewnętrzne hiperłącze po kliknięciu. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Ustaw wewnętrzne hiperłącze po kliknięciu. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Usuń hiperłącze po kliknięciu. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Ustaw zewnętrzne hiperłącze po najechaniu myszą. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Ustaw wewnętrzne hiperłącze po najechaniu myszą. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Usuń hiperłącze po najechaniu myszą. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Ustaw hiperłącze makra po kliknięciu. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Ustaw zewnętrzne hiperłącze po kliknięciu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| url | java.lang.String | URL hiperłącza. |

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - obiekt Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Ustaw wewnętrzne hiperłącze po kliknięciu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Docelowy slajd. |

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

Usuń hiperłącze po kliknięciu.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Ustaw zewnętrzne hiperłącze po najechaniu myszą.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| url | java.lang.String | URL hiperłącza. |

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Ustaw wewnętrzne hiperłącze po najechaniu myszą.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Docelowy slajd. |

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

Usuń hiperłącze po najechaniu myszą.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

Ustaw hiperłącze makra po kliknięciu.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| macroName | java.lang.String | Nazwa makra |

**Zwraca:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - obiekt Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)