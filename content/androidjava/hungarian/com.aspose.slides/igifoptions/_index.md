---
title: IGifOptions
second_title: Aspose.Slides for Android Java API hivatkozás
description: A GIF exportálási beállításokat reprezentálja.
type: docs
url: /hu/com.aspose.slides/igifoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Represents GIF exporting options.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Lekéri vagy beállítja a keret méretét. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Lekéri vagy beállítja a keret méretét. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Megállapítja, hogy a rejtett diák exportálásra kerülnek-e. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Megállapítja, hogy a rejtett diák exportálásra kerülnek-e. |
| [getTransitionFps()](#getTransitionFps--) | Lekéri vagy beállítja a transition FPS [frames/sec] Az alapértelmezett érték 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Lekéri vagy beállítja a transition FPS [frames/sec] Az alapértelmezett érték 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Lekéri vagy beállítja az alapértelmezett késleltetési időt [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Lekéri vagy beállítja az alapértelmezett késleltetési időt [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```


Lekéri vagy beállítja a keret méretét.

--------------------

Ha a méret üres, akkor az érték a [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)-ból lesz beszerezve

**Visszatér:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```


Lekéri vagy beállítja a keret méretét.

--------------------

Ha a méret üres, akkor az érték a [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)-ból lesz beszerezve

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


Megállapítja, hogy a rejtett diák exportálásra kerülnek-e. Az alapértelmezett érték hamis.

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


**Visszatér:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


Megállapítja, hogy a rejtett diák exportálásra kerülnek-e. Az alapértelmezett érték hamis.

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


Lekéri vagy beállítja a transition FPS [frames/sec] Az alapértelmezett érték 25.

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


**Visszatér:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```


Lekéri vagy beállítja a transition FPS [frames/sec] Az alapértelmezett érték 25.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```


Lekéri vagy beállítja az alapértelmezett késleltetési időt [ms]. Ez az érték lesz használva, ha [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nincs beállítva. Az alapértelmezett érték 1000.

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

**Visszatér:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)
```


Lekéri vagy beállítja az alapértelmezett késleltetési időt [ms]. Ez az érték lesz használva, ha [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nincs beállítva. Az alapértelmezett érték 1000.

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