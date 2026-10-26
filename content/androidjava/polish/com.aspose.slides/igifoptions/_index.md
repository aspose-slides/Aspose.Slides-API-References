---
title: IGifOptions
second_title: Aspose.Slides dla Androida przez Java API
description: Reprezentuje opcje eksportu GIF.
type: docs
url: /pl/com.aspose.slides/igifoptions/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Reprezentuje opcje eksportu GIF.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Pobiera lub ustawia rozmiar klatki. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Pobiera lub ustawia rozmiar klatki. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Określa, czy ukryte slajdy będą eksportowane. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Określa, czy ukryte slajdy będą eksportowane. |
| [getTransitionFps()](#getTransitionFps--) | Pobiera lub ustawia FPS przejścia [klatki/sek] Domyślna wartość to 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Pobiera lub ustawia FPS przejścia [klatki/sek] Domyślna wartość to 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Pobiera lub ustawia domyślny czas opóźnienia [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Pobiera lub ustawia domyślny czas opóźnienia [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```


Pobiera lub ustawia rozmiar klatki.

--------------------

Jeśli rozmiar jest pusty, wartość zostanie pobrana z [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Zwraca:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
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
public abstract boolean getExportHiddenSlides()
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
public abstract void setExportHiddenSlides(boolean value)
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
public abstract int getTransitionFps()
```


Pobiera lub ustawia FPS przejścia [klatki/sek] Domyślna wartość to 25.

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
public abstract void setTransitionFps(int value)
```


Pobiera lub ustawia FPS przejścia [klatki/sek] Domyślna wartość to 25.

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
public abstract int getDefaultDelay()
```


Pobiera lub ustawia domyślny czas opóźnienia [ms]. Ta wartość będzie używana, jeśli [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nie jest ustawiona. Domyślna wartość to 1000.

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
public abstract void setDefaultDelay(int value)
```


Pobiera lub ustawia domyślny czas opóźnienia [ms]. Ta wartość będzie używana, jeśli [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nie jest ustawiona. Domyślna wartość to 1000.

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