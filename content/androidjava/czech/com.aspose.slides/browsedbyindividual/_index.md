---
title: BrowsedByIndividual
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Okno prohlížené jednotlivcem
type: docs
url: /cs/com.aspose.slides/browsedbyindividual/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Prohlížené jednotlivcem (okno)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Inicializuje novou instanci třídy BrowsedByIndividual. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Zobrazit posuvník v okně |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Zobrazit posuvník v okně |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


Inicializuje novou instanci třídy BrowsedByIndividual.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


### getShowScrollbar() {#getShowScrollbar--}
```
public final boolean getShowScrollbar()
```


Zobrazit posuvník v okně

**Vrací:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


Zobrazit posuvník v okně

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |