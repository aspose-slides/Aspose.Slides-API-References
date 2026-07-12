---
title: IGifOptions
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt GIF-Exportoptionen dar.
type: docs
url: /de/com.aspose.slides/igifoptions/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Stellt GIF-Exportoptionen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Liest oder setzt die Framegröße. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Liest oder setzt die Framegröße. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Bestimmt, ob versteckte Folien exportiert werden. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Bestimmt, ob versteckte Folien exportiert werden. |
| [getTransitionFps()](#getTransitionFps--) | Liest oder setzt die Übergangs-FPS [frames/sec]. Der Standardwert ist 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Liest oder setzt die Übergangs-FPS [frames/sec]. Der Standardwert ist 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Liest oder setzt die Standardverzögerungszeit [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Liest oder setzt die Standardverzögerungszeit [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```

Liest oder setzt die Framegröße.

--------------------

Wenn die Größe leer ist, wird der Wert von [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) übernommen.

**Rückgabewert:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```

Liest oder setzt die Framegröße.

--------------------

Wenn die Größe leer ist, wird der Wert von [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) übernommen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```

Bestimmt, ob versteckte Folien exportiert werden. Der Standardwert ist false.

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


**Rückgabewert:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```

Bestimmt, ob versteckte Folien exportiert werden. Der Standardwert ist false.

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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```

Liest oder setzt die Übergangs-FPS [frames/sec]. Der Standardwert ist 25.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```

Liest oder setzt die Übergangs-FPS [frames/sec]. Der Standardwert ist 25.

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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```

Liest oder setzt die Standardverzögerungszeit [ms]. Dieser Wert wird verwendet, wenn [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nicht festgelegt ist. Der Standardwert ist 1000.

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

**Rückgabewert:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)
```

Liest oder setzt die Standardverzögerungszeit [ms]. Dieser Wert wird verwendet, wenn [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nicht festgelegt ist. Der Standardwert ist 1000.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |