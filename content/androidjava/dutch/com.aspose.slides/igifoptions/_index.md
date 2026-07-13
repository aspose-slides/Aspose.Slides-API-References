---
title: IGifOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt GIF-exportopties voor.
type: docs
url: /nl/com.aspose.slides/igifoptions/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Stelt GIF-exportopties voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Haalt of stelt de framegrootte in. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Haalt of stelt de framegrootte in. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Bepaalt of verborgen dia’s worden geëxporteerd. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Bepaalt of verborgen dia’s worden geëxporteerd. |
| [getTransitionFps()](#getTransitionFps--) | Haalt of stelt overgang FPS [frames/sec] in. Standaardwaarde is 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Haalt of stelt overgang FPS [frames/sec] in. Standaardwaarde is 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Haalt of stelt de standaardvertragingstijd [ms] in. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Haalt of stelt de standaardvertragingstijd [ms] in. |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```


Haalt of stelt de framegrootte in.

--------------------

Als de grootte leeg is, wordt de waarde genomen van [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Retourwaarde:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```


Haalt of stelt de framegrootte in.

--------------------

Als de grootte leeg is, wordt de waarde genomen van [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


Bepaalt of verborgen dia’s worden geëxporteerd. Standaardwaarde is false.

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

**Retourwaarde:** boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


Bepaalt of verborgen dia’s worden geëxporteerd. Standaardwaarde is false.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```


Haalt of stelt overgang FPS [frames/sec] in. Standaardwaarde is 25.

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

**Retourwaarde:** int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```


Haalt of stelt overgang FPS [frames/sec] in. Standaardwaarde is 25.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```


Haalt of stelt de standaardvertragingstijd [ms] in. Deze waarde wordt gebruikt als [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) niet is ingesteld. Standaardwaarde is 1000.

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

**Retourwaarde:** int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)
```


Haalt of stelt de standaardvertragingstijd [ms] in. Deze waarde wordt gebruikt als [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) niet is ingesteld. Standaardwaarde is 1000.

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


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |