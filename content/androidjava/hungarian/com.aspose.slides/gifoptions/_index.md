---
title: GifOptions
second_title: Aspose.Slides Androidra a Java API hivatkozás alapján
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
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // a keletkezett GIF mérete
>      gifOptions.setDefaultDelay(2000); // mennyi ideig jelenik meg minden dia, amíg a következőre vált
>      gifOptions.setTransitionFps(35); // növelje az FPS-t a jobb átmeneti animáció minősége érdekében
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [GifOptions()](#GifOptions--) | Inicializál egy új példányt a GifOptions osztályból. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Lekérdezi vagy beállítja a keret méretét. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Lekérdezi vagy beállítja a keret méretét. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Megállapítja, hogy a rejtett diák exportálva lesznek-e. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Megállapítja, hogy a rejtett diák exportálva lesznek-e. |
| [getTransitionFps()](#getTransitionFps--) | Lekérdezi vagy beállítja az átmeneti FPS-t [frames/sec] Az alapértelmezett érték 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Lekérdezi vagy beállítja az átmeneti FPS-t [frames/sec] Az alapértelmezett érték 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Lekérdezi vagy beállítja az alapértelmezett késleltetési időt [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Lekérdezi vagy beállítja az alapértelmezett késleltetési időt [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

Inicializál egy új példányt a GifOptions osztályból.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```

Lekérdezi vagy beállítja a keret méretét.

--------------------

Ha a méret üres, akkor az érték a [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)-ből lesz felvéve.

**Visszatérési érték:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```

Lekérdezi vagy beállítja a keret méretét.

--------------------

Ha a méret üres, akkor az érték a [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)-ből lesz felvéve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

Megállapítja, hogy a rejtett diák exportálva lesznek-e. Az alapértelmezett érték false.

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

Megállapítja, hogy a rejtett diák exportálva lesznek-e. Az alapértelmezett érték false.

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

Lekérdezi vagy beállítja az átmeneti FPS-t [frames/sec] Az alapértelmezett érték 25.

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

Lekérdezi vagy beállítja az átmeneti FPS-t [frames/sec] Az alapértelmezett érték 25.

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

Lekérdezi vagy beállítja az alapértelmezett késleltetési időt [ms]. Ez az érték lesz használva, ha a [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nincs beállítva. Az alapértelmezett érték 1000.

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

Lekérdezi vagy beállítja az alapértelmezett késleltetési időt [ms]. Ez az érték lesz használva, ha a [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) nincs beállítva. Az alapértelmezett érték 1000.

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