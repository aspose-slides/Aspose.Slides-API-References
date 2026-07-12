---
title: HandoutLayoutingOptions
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt den Handzettel-Präsentationslayoutmodus für den Export dar.
type: docs
url: /de/com.aspose.slides/handoutlayoutingoptions/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class HandoutLayoutingOptions implements ISlidesLayoutOptions
```

Stellt den Handzettel-Präsentationslayoutmodus für den Export dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HandoutLayoutingOptions()](#HandoutLayoutingOptions--) | Initialisiert die Standardwerte. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHandout()](#getHandout--) | Gibt an, wie viele Folien und in welcher Reihenfolge auf der Seite [HandoutType](../../com.aspose.slides/handouttype) platziert werden. |
| [setHandout(int value)](#setHandout-int-) | Gibt an, wie viele Folien und in welcher Reihenfolge auf der Seite [HandoutType](../../com.aspose.slides/handouttype) platziert werden. |
| [getPrintSlideNumbers()](#getPrintSlideNumbers--) | Gibt an, ob die angezeigten Folienzahlen gedruckt werden sollen oder nicht. |
| [setPrintSlideNumbers(boolean value)](#setPrintSlideNumbers-boolean-) | Gibt an, ob die angezeigten Folienzahlen gedruckt werden sollen oder nicht. |
| [getPrintFrameSlide()](#getPrintFrameSlide--) | Gibt an, ob Rahmen um die angezeigten Folien gezeichnet werden sollen oder nicht. |
| [setPrintFrameSlide(boolean value)](#setPrintFrameSlide-boolean-) | Gibt an, ob Rahmen um die angezeigten Folien gezeichnet werden sollen oder nicht. |
| [getPrintComments()](#getPrintComments--) | Gibt an, ob Kommentare auf den Folien angezeigt werden sollen oder nicht. |
| [setPrintComments(boolean value)](#setPrintComments-boolean-) | Gibt an, ob Kommentare auf den Folien angezeigt werden sollen oder nicht. |
### HandoutLayoutingOptions() {#HandoutLayoutingOptions--}
```
public HandoutLayoutingOptions()
```

Initialisiert die Standardwerte.

### getHandout() {#getHandout--}
```
public final int getHandout()
```

Gibt an, wie viele Folien und in welcher Reihenfolge auf der Seite [HandoutType](../../com.aspose.slides/handouttype) platziert werden.

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
--------------------

Standardwert ist **HandoutType.Handouts6Horizontal** .

**Rückgabe:**
int
### setHandout(int value) {#setHandout-int-}
```
public final void setHandout(int value)
```

Gibt an, wie viele Folien und in welcher Reihenfolge auf der Seite [HandoutType](../../com.aspose.slides/handouttype) platziert werden.

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
--------------------

Standardwert ist **HandoutType.Handouts6Horizontal** .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getPrintSlideNumbers() {#getPrintSlideNumbers--}
```
public final boolean getPrintSlideNumbers()
```

Gibt an, ob die angezeigten Folienzahlen gedruckt werden sollen oder nicht.

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
--------------------

Standardwert ist **true** .

**Rückgabe:**
boolean
### setPrintSlideNumbers(boolean value) {#setPrintSlideNumbers-boolean-}
```
public final void setPrintSlideNumbers(boolean value)
```

Gibt an, ob die angezeigten Folienzahlen gedruckt werden sollen oder nicht.

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
--------------------

Standardwert ist **true** .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getPrintFrameSlide() {#getPrintFrameSlide--}
```
public final boolean getPrintFrameSlide()
```

Gibt an, ob Rahmen um die angezeigten Folien gezeichnet werden sollen oder nicht.

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
--------------------

Standardwert ist **true** .

**Rückgabe:**
boolean
### setPrintFrameSlide(boolean value) {#setPrintFrameSlide-boolean-}
```
public final void setPrintFrameSlide(boolean value)
```

Gibt an, ob Rahmen um die angezeigten Folien gezeichnet werden sollen oder nicht.

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
--------------------

Standardwert ist **true** .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getPrintComments() {#getPrintComments--}
```
public final boolean getPrintComments()
```

Gibt an, ob Kommentare auf den Folien angezeigt werden sollen oder nicht.

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
--------------------

Standardwert ist **false** .

**Rückgabe:**
boolean
### setPrintComments(boolean value) {#setPrintComments-boolean-}
```
public final void setPrintComments(boolean value)
```

Gibt an, ob Kommentare auf den Folien angezeigt werden sollen oder nicht.

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
--------------------

Standardwert ist **false** .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |