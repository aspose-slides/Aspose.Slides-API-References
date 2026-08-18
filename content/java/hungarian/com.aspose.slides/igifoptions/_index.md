---
title: IGifOptions
second_title: Aspose.Slides for Java API Referencia
description: A GIF exportálási beállításokat képviseli.
type: docs
url: /hu/com.aspose.slides/igifoptions/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

A GIF exportálási beállításokat képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Lekéri vagy beállítja a képkocka méretét. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Lekéri vagy beállítja a képkocka méretét. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Meghatározza, hogy a rejtett diák exportálva lesznek-e. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Meghatározza, hogy a rejtett diák exportálva lesznek-e. |
| [getTransitionFps()](#getTransitionFps--) | Lekéri vagy beállítja a transition FPS-t [frames/sec] Az alapértelmezett érték 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Lekéri vagy beállítja a transition FPS-t [frames/sec] Az alapértelmezett érték 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Lekéri vagy beállítja az alapértelmezett késleltetési időt [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Lekéri vagy beállítja az alapértelmezett késleltetési időt [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Dimension getFrameSize()
```


Lekéri vagy beállítja a képkocka méretét.

--------------------

Ha a méret üres, akkor az érték a [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)-ból kerül felhasználásra.

**Visszatérési érték:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public abstract void setFrameSize(Dimension value)
```


Lekéri vagy beállítja a képkocka méretét.

--------------------

Ha a méret üres, akkor az érték a [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)-ból kerül felhasználásra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
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
public abstract void setExportHiddenSlides(boolean value)
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
public abstract int getTransitionFps()
```


Lekéri vagy beállítja a transition FPS-t [frames/sec] Az alapértelmezett érték 25.

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


**Visszatérési érték:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```


Lekéri vagy beállítja a transition FPS-t [frames/sec] Az alapértelmezett érték 25.

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
public abstract int getDefaultDelay()
```


Lekéri vagy beállítja az alapértelmezett késleltetési időt [ms]. Ez az érték akkor lesz használva, ha a [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nincs beállítva. Az alapértelmezett érték 1000.

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
public abstract void setDefaultDelay(int value)
```


Lekéri vagy beállítja az alapértelmezett késleltetési időt [ms]. Ez az érték akkor lesz használva, ha a [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nincs beállítva. Az alapértelmezett érték 1000.

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