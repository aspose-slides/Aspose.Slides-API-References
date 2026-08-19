---
title: GifOptions
second_title: Aspose.Slides voor Java API-referentie
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
>      gifOptions.setFrameSize(new Dimension(960, 720)); // de grootte van de resulterende GIF
>      gifOptions.setDefaultDelay(2000); // hoe lang elke dia wordt weergegeven totdat deze naar de volgende wordt veranderd
>      gifOptions.setTransitionFps(35); // verhoog FPS voor betere overgangsanimeerkwaliteit
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initialiseert een nieuwe instantie van de GifOptions-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Haal of stel de framegrootte in. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Haal of stel de framegrootte in. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Bepaalt of verborgen dia's zullen worden geëxporteerd. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Bepaalt of verborgen dia's zullen worden geëxporteerd. |
| [getTransitionFps()](#getTransitionFps--) | Haal of stel overgang FPS [frames/sec] in. De standaardwaarde is 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Haal of stel overgang FPS [frames/sec] in. De standaardwaarde is 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Haal of stel de standaardvertragingstijd [ms] in. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Haal of stel de standaardvertragingstijd [ms] in. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

Initialiseert een nieuwe instantie van de GifOptions-klasse.

### getFrameSize() {#getFrameSize--}
```
public final Dimension getFrameSize()
```

Haal of stel de framegrootte in.

--------------------

Als de grootte leeg is, wordt de waarde genomen van [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Geeft terug:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public final void setFrameSize(Dimension value)
```

Haal of stel de framegrootte in.

--------------------

Als de grootte leeg is, wordt de waarde genomen van [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

Bepaalt of verborgen dia's zullen worden geëxporteerd. De standaardwaarde is false.

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


**Geeft terug:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

Bepaalt of verborgen dia's zullen worden geëxporteerd. De standaardwaarde is false.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```

Haal of stel overgang FPS [frames/sec] in. De standaardwaarde is 25.

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

**Geeft terug:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```

Haal of stel overgang FPS [frames/sec] in. De standaardwaarde is 25.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

Haal of stel de standaardvertragingstijd [ms] in. Deze waarde wordt gebruikt als [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) niet is ingesteld. De standaardwaarde is 1000.

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

**Geeft terug:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

Haal of stel de standaardvertragingstijd [ms] in. Deze waarde wordt gebruikt als [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) niet is ingesteld. De standaardwaarde is 1000.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |