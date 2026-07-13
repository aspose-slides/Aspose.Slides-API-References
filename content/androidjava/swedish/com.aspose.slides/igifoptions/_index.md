---
title: IGifOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar GIF-exportalternativ.
type: docs
url: /sv/com.aspose.slides/igifoptions/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Representerar GIF-exportalternativ.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Hämtar eller anger ramstorlek. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Hämtar eller anger ramstorlek. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Avgör om dolda bilder ska exporteras. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Avgör om dolda bilder ska exporteras. |
| [getTransitionFps()](#getTransitionFps--) | Hämtar eller anger övergångs-FPS [bilder/s] Standardvärdet är 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Hämtar eller anger övergångs-FPS [bilder/s] Standardvärdet är 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Hämtar eller anger standardfördröjningstid [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Hämtar eller anger standardfördröjningstid [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```

Hämtar eller anger ramstorlek.

--------------------

Om storleken är tom tas värdet från [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Returnerar:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```

Hämtar eller anger ramstorlek.

--------------------

Om storleken är tom tas värdet från [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```

Avgör om dolda bilder ska exporteras. Standardvärdet är falskt.

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

**Returnerar:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```

Avgör om dolda bilder ska exporteras. Standardvärdet är falskt.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```

Hämtar eller anger övergångs-FPS [bilder/s] Standardvärdet är 25.

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

**Returnerar:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```

Hämtar eller anger övergångs-FPS [bilder/s] Standardvärdet är 25.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```

Hämtar eller anger standardfördröjningstid [ms]. Detta värde kommer att användas om [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) inte är satt. Standardvärdet är 1000.

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

**Returnerar:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)
```

Hämtar eller anger standardfördröjningstid [ms]. Detta värde kommer att användas om [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) inte är satt. Standardvärdet är 1000.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |