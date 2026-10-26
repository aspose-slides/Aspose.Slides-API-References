---
title: GifOptions
second_title: Aspose.Slides for Java API Referencia
description: A GIF exportálási beállításokat képviseli.
type: docs
url: /hu/com.aspose.slides/gifoptions/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Minden megvalósított interfész:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

A GIF exportálási beállításokat képviseli.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new Dimension(960, 720)); // a létrehozott GIF mérete
>      gifOptions.setDefaultDelay(2000); // mennyi ideig jelenik meg minden dia, amíg a következőre vált
>      gifOptions.setTransitionFps(35); // növelje az FPS-t a jobb átmeneti animáció minőség érdekében
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktorok

| Constructor | Leírás |
| --- | --- |
| [GifOptions()](#GifOptions--) | Inicializál egy új példányt a GifOptions osztályból. |
## Módszerek

| Method | Leírás |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Lekéri vagy beállítja a keret méretét. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Lekéri vagy beállítja a keret méretét. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Meghatározza, hogy a rejtett diák exportálva lesznek-e. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Meghatározza, hogy a rejtett diák exportálva lesznek-e. |
| [getTransitionFps()](#getTransitionFps--) | Lekéri vagy beállítja az átmenet FPS-ét [frames/sec]. Az alapértelmezett érték 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Lekéri vagy beállítja az átmenet FPS-ét [frames/sec]. Az alapértelmezett érték 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Lekéri vagy beállítja az alapértelmezett késleltetési időt [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Lekéri vagy beállítja az alapértelmezett késleltetési időt [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

Inicializál egy új példányt a GifOptions osztályból.

### getFrameSize() {#getFrameSize--}
```
public final Dimension getFrameSize()
```

Lekéri vagy beállítja a keret méretét.

--------------------

Ha a méret üres, akkor az érték a [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)-ből kerül átadásra.

**Visszatérési érték:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public final void setFrameSize(Dimension value)
```

Lekéri vagy beállítja a keret méretét.

--------------------

Ha a méret üres, akkor az érték a [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)-ből kerül átadásra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

Meghatározza, hogy a rejtett diák exportálva lesznek-e. Az alapértelmezett érték false.

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


**Visszatérési érték:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

Meghatározza, hogy a rejtett diák exportálva lesznek-e. Az alapértelmezett érték false.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```

Lekéri vagy beállítja az átmenet FPS-ét [frames/sec]. Az alapértelmezett érték 25.

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

**Visszatérési érték:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```

Lekéri vagy beállítja az átmenet FPS-ét [frames/sec]. Az alapértelmezett érték 25.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

Lekéri vagy beállítja az alapértelmezett késleltetési időt [ms]. Ez az érték lesz használva, ha a [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nincs beállítva. Az alapértelmezett érték 1000.

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


**Visszatérési érték:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

Lekéri vagy beállítja az alapértelmezett késleltetési időt [ms]. Ez az érték lesz használva, ha a [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nincs beállítva. Az alapértelmezett érték 1000.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |