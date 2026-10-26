---
title: GifOptions
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt GIF-Exportoptionen dar.
type: docs
url: /de/com.aspose.slides/gifoptions/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

Stellt GIF-Exportoptionen dar.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // die Größe des resultierenden GIFs
>      gifOptions.setDefaultDelay(2000); // wie lange jede Folie angezeigt wird, bis sie zur nächsten wechselt
>      gifOptions.setTransitionFps(35); // FPS erhöhen für bessere Übergangsanimationsqualität
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initialisiert eine neue Instanz der GifOptions-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Liest oder setzt die Rahmengröße. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Liest oder setzt die Rahmengröße. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Bestimmt, ob versteckte Folien exportiert werden. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Bestimmt, ob versteckte Folien exportiert werden. |
| [getTransitionFps()](#getTransitionFps--) | Liest oder setzt die Übergangs-FPS [frames/sec]. Der Standardwert ist 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Liest oder setzt die Übergangs-FPS [frames/sec]. Der Standardwert ist 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Liest oder setzt die Standardverzögerungszeit [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Liest oder setzt die Standardverzögerungszeit [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

Initialisiert eine neue Instanz der GifOptions-Klasse.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```

Liest oder setzt die Rahmengröße.

--------------------

Wenn die Größe leer ist, wird der Wert von [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) übernommen.

**Rückgabe:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```

Liest oder setzt die Rahmengröße.

--------------------

Wenn die Größe leer ist, wird der Wert von [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) übernommen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
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


**Rückgabe:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
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
public final int getTransitionFps()
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

**Rückgabe:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
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
public final int getDefaultDelay()
```

Liest oder setzt die Standardverzögerungszeit [ms]. Dieser Wert wird verwendet, wenn [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nicht gesetzt ist. Der Standardwert ist 1000.

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

**Rückgabe:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

Liest oder setzt die Standardverzögerungszeit [ms]. Dieser Wert wird verwendet, wenn [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nicht gesetzt ist. Der Standardwert ist 1000.

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