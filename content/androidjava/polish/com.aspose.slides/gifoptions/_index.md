---
title: GifOptions
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje opcje eksportu GIF.
type: docs
url: /pl/com.aspose.slides/gifoptions/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

Reprezentuje opcje eksportu GIF.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // rozmiar wynikowego GIFa
>      gifOptions.setDefaultDelay(2000); // jak długo każdy slajd będzie wyświetlany, zanim zostanie zmieniony na następny
>      gifOptions.setTransitionFps(35); // zwiększ FPS, aby poprawić jakość animacji przejścia
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [GifOptions()](#GifOptions--) | Inicjalizuje nową instancję klasy GifOptions. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Pobiera lub ustawia rozmiar klatki. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Pobiera lub ustawia rozmiar klatki. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Określa, czy ukryte slajdy będą eksportowane. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Określa, czy ukryte slajdy będą eksportowane. |
| [getTransitionFps()](#getTransitionFps--) | Pobiera lub ustawia liczbę FPS przejścia [frames/sec]. Domyślna wartość to 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Pobiera lub ustawia liczbę FPS przejścia [frames/sec]. Domyślna wartość to 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Pobiera lub ustawia domyślny czas opóźnienia [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Pobiera lub ustawia domyślny czas opóźnienia [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Inicjalizuje nową instancję klasy GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```


Pobiera lub ustawia rozmiar klatki.

--------------------

Jeśli rozmiar jest pusty, wartość zostanie pobrana z [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Zwraca:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```


Pobiera lub ustawia rozmiar klatki.

--------------------

Jeśli rozmiar jest pusty, wartość zostanie pobrana z [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


Określa, czy ukryte slajdy będą eksportowane. Domyślna wartość to false.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


Określa, czy ukryte slajdy będą eksportowane. Domyślna wartość to false.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```


Pobiera lub ustawia liczbę FPS przejścia [frames/sec]. Domyślna wartość to 25.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```


Pobiera lub ustawia liczbę FPS przejścia [frames/sec]. Domyślna wartość to 25.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```


Pobiera lub ustawia domyślny czas opóźnienia [ms]. Ta wartość zostanie użyta, jeśli [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nie jest ustawiona. Domyślna wartość to 1000.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```


Pobiera lub ustawia domyślny czas opóźnienia [ms]. Ta wartość zostanie użyta, jeśli [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nie jest ustawiona. Domyślna wartość to 1000.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |