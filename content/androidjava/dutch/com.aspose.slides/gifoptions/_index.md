---
title: GifOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt GIF-exportopties voor.
type: docs
url: /nl/com.aspose.slides/gifoptions/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

Stelt GIF-exportopties voor.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // de grootte van de resulterende GIF
>      gifOptions.setDefaultDelay(2000); // hoe lang elke dia wordt weergegeven totdat deze naar de volgende wordt gewijzigd
>      gifOptions.setTransitionFps(35); // verhoog FPS voor betere overgangsanimatiekwaliteit
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initialiseert een nieuwe instantie van de GifOptions-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Haalt de framegrootte op of stelt deze in. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Haalt de framegrootte op of stelt deze in. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Bepaalt of verborgen dia's worden geëxporteerd. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Bepaalt of verborgen dia's worden geëxporteerd. |
| [getTransitionFps()](#getTransitionFps--) | Haalt de overgangs-FPS op of stelt deze in [frames/sec]. De standaardwaarde is 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Haalt de overgangs-FPS op of stelt deze in [frames/sec]. De standaardwaarde is 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Haalt de standaardvertragingstijd op of stelt deze in [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Haalt de standaardvertragingstijd op of stelt deze in [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

Initialiseert een nieuwe instantie van de GifOptions-klasse.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```

Haalt de framegrootte op of stelt deze in.

--------------------

Als de grootte leeg is, wordt de waarde gehaald van [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Retour:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```

Haalt de framegrootte op of stelt deze in.

--------------------

Als de grootte leeg is, wordt de waarde gehaald van [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

Bepaalt of verborgen dia's worden geëxporteerd. De standaardwaarde is false.

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

**Retour:** boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

Bepaalt of verborgen dia's worden geëxporteerd. De standaardwaarde is false.

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
public final int getTransitionFps()
```

Haalt de overgangs-FPS op of stelt deze in [frames/sec]. De standaardwaarde is 25.

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

**Retour:** int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```

Haalt de overgangs-FPS op of stelt deze in [frames/sec]. De standaardwaarde is 25.

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
public final int getDefaultDelay()
```

Haalt de standaardvertragingstijd op of stelt deze in [ms]. Deze waarde wordt gebruikt als [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) niet is ingesteld. De standaardwaarde is 1000.

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

**Retour:** int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

Haalt de standaardvertragingstijd op of stelt deze in [ms]. Deze waarde wordt gebruikt als [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) niet is ingesteld. De standaardwaarde is 1000.

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