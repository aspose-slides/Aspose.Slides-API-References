---
title: GifOptions
second_title: Aspose.Slides för Java API-referens
description: Representerar GIF-exportalternativ.
type: docs
url: /sv/com.aspose.slides/gifoptions/
---
**Arv:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

Representerar GIF-exportalternativ.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new Dimension(960, 720)); // storleken på den resulterande GIF-filen
>      gifOptions.setDefaultDelay(2000); // hur länge varje bild visas innan den byts till nästa
>      gifOptions.setTransitionFps(35); // öka FPS för bättre övergångsanimationskvalitet
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initierar en ny instans av GifOptions-klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Hämtar eller anger ramstorlek. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Hämtar eller anger ramstorlek. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Bestämmer om dolda bilder ska exporteras. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Bestämmer om dolda bilder ska exporteras. |
| [getTransitionFps()](#getTransitionFps--) | Hämtar eller anger övergångs-FPS [frames/sec] Standardvärdet är 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Hämtar eller anger övergångs-FPS [frames/sec] Standardvärdet är 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Hämtar eller anger standardfördröjningstid [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Hämtar eller anger standardfördröjningstid [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Initierar en ny instans av GifOptions-klassen.

### getFrameSize() {#getFrameSize--}
```
public final Dimension getFrameSize()
```


Hämtar eller anger ramstorlek.

--------------------

Om storleken är tomt tas värdet från [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Returnerar:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public final void setFrameSize(Dimension value)
```


Hämtar eller anger ramstorlek.

--------------------

Om storleken är tomt tas värdet från [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


Bestämmer om dolda bilder ska exporteras. Standardvärdet är false.

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
public final void setExportHiddenSlides(boolean value)
```


Bestämmer om dolda bilder ska exporteras. Standardvärdet är false.

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
public final int getTransitionFps()
```


Hämtar eller anger övergångs-FPS [frames/sec] Standardvärdet är 25.

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
public final void setTransitionFps(int value)
```


Hämtar eller anger övergångs-FPS [frames/sec] Standardvärdet är 25.

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
public final int getDefaultDelay()
```


Hämtar eller anger standardfördröjningstid [ms]. Detta värde används om [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) inte är angivet. Standardvärdet är 1000.

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
public final void setDefaultDelay(int value)
```


Hämtar eller anger standardfördröjningstid [ms]. Detta värde används om [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) inte är angivet. Standardvärdet är 1000.

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