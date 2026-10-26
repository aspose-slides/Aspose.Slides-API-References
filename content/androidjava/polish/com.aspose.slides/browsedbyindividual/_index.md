---
title: BrowsedByIndividual
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Przeglądane indywidualnie w oknie
type: docs
url: /pl/com.aspose.slides/browsedbyindividual/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Przeglądane indywidualnie (okno)

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

| Konstruktor | Opis |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Inicjalizuje nową instancję klasy BrowsedByIndividual. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Pokaż pasek przewijania w oknie |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Pokaż pasek przewijania w oknie |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


Inicjalizuje nową instancję klasy BrowsedByIndividual.

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


Pokaż pasek przewijania w oknie

**Zwraca:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


Pokaż pasek przewijania w oknie

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |