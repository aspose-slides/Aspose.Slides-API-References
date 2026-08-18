---
title: HandoutLayoutingOptions
second_title: Aspose.Slides for Java API Referencia
description: A handout prezentáció elrendezési módját reprezentálja exportáláshoz.
type: docs
url: /hu/com.aspose.slides/handoutlayoutingoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class HandoutLayoutingOptions implements ISlidesLayoutOptions
```

A handout prezentáció elrendezési módját reprezentálja exportáláshoz.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [HandoutLayoutingOptions()](#HandoutLayoutingOptions--) | Inicializálja az alapértelmezett értékeket. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHandout()](#getHandout--) | Megadja, hány diát és milyen sorrendben helyeznek el az [HandoutType](../../com.aspose.slides/handouttype) oldalon. |
| [setHandout(int value)](#setHandout-int-) | Megadja, hány diát és milyen sorrendben helyeznek el az [HandoutType](../../com.aspose.slides/handouttype) oldalon. |
| [getPrintSlideNumbers()](#getPrintSlideNumbers--) | Megadja, hogy nyomtassa-e vagy sem a megjelenített dia számokat. |
| [setPrintSlideNumbers(boolean value)](#setPrintSlideNumbers-boolean-) | Megadja, hogy nyomtassa-e vagy sem a megjelenített dia számokat. |
| [getPrintFrameSlide()](#getPrintFrameSlide--) | Megadja, hogy kerüljenek-e keretek a megjelenített diák köré vagy sem. |
| [setPrintFrameSlide(boolean value)](#setPrintFrameSlide-boolean-) | Megadja, hogy kerüljenek-e keretek a megjelenített diák köré vagy sem. |
| [getPrintComments()](#getPrintComments--) | Megadja, hogy jelenjenek meg vagy sem a diákon megjegyzések. |
| [setPrintComments(boolean value)](#setPrintComments-boolean-) | Megadja, hogy jelenjenek meg vagy sem a diákon megjegyzések. |
### HandoutLayoutingOptions() {#HandoutLayoutingOptions--}
```
public HandoutLayoutingOptions()
```


Inicializálja az alapértelmezett értékeket.

### getHandout() {#getHandout--}
```
public final int getHandout()
```


Megadja, hány diát és milyen sorrendben helyeznek el az [HandoutType](../../com.aspose.slides/handouttype) oldalon.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Az alapértelmezett érték  **HandoutType.Handouts6Horizontal** .

**Visszatérési érték:**
int
### setHandout(int value) {#setHandout-int-}
```
public final void setHandout(int value)
```


Megadja, hány diát és milyen sorrendben helyeznek el az [HandoutType](../../com.aspose.slides/handouttype) oldalon.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Az alapértelmezett érték  **HandoutType.Handouts6Horizontal** .

**Paraméterek:**
| Parameter | Type | Leírás |
| --- | --- | --- |
| value | int |  |

### getPrintSlideNumbers() {#getPrintSlideNumbers--}
```
public final boolean getPrintSlideNumbers()
```


Megadja, hogy nyomtassa-e vagy sem a megjelenített dia számokat.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Az alapértelmezett érték  **true** .

**Visszatérési érték:**
boolean
### setPrintSlideNumbers(boolean value) {#setPrintSlideNumbers-boolean-}
```
public final void setPrintSlideNumbers(boolean value)
```


Megadja, hogy nyomtassa-e vagy sem a megjelenített dia számokat.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Az alapértelmezett érték  **true** .

**Paraméterek:**
| Parameter | Type | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getPrintFrameSlide() {#getPrintFrameSlide--}
```
public final boolean getPrintFrameSlide()
```


Megadja, hogy kerüljenek-e keretek a megjelenített diák köré vagy sem.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Az alapértelmezett érték  **true** .

**Visszatérési érték:**
boolean
### setPrintFrameSlide(boolean value) {#setPrintFrameSlide-boolean-}
```
public final void setPrintFrameSlide(boolean value)
```


Megadja, hogy kerüljenek-e keretek a megjelenített diák köré vagy sem.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Az alapértelmezett érték  **true** .

**Paraméterek:**
| Parameter | Type | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getPrintComments() {#getPrintComments--}
```
public final boolean getPrintComments()
```


Megadja, hogy jelenjenek meg vagy sem a diákon megjegyzések

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Az alapértelmezett érték  **false** .

**Visszatérési érték:**
boolean
### setPrintComments(boolean value) {#setPrintComments-boolean-}
```
public final void setPrintComments(boolean value)
```


Megadja, hogy jelenjenek meg vagy sem a diákon megjegyzések

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Az alapértelmezett érték  **false** .

**Paraméterek:**
| Parameter | Type | Leírás |
| --- | --- | --- |
| value | boolean |  |