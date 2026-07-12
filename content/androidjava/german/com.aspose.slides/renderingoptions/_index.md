---
title: RenderingOptions
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt Optionen bereit, die steuern, wie eine Präsentation/Folie gerendert wird.
type: docs
url: /de/com.aspose.slides/renderingoptions/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IRenderingOptions](../../com.aspose.slides/irenderingoptions)
```
public class RenderingOptions extends SaveOptions implements IRenderingOptions
```

Stellt Optionen bereit, die steuern, wie eine Präsentation/Folie gerendert wird.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      IRenderingOptions renderingOpts = new RenderingOptions();
>      renderingOpts.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomTruncated);
>      FileOutputStream out = new FileOutputStream("pres-Original.png");
>      pres.getSlides().get_Item(0).getThumbnail(renderingOpts).compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, out);
>      out.flush();
>      out.close();
>      renderingOpts.setDefaultRegularFont("Arial Black");
>      FileOutputStream out = new FileOutputStream("pres-ArialBlackDefault.png");
>      pres.getSlides().get_Item(0).getThumbnail(renderingOpts).compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, out);
>      out.flush();
>      out.close();
>      renderingOpts.setDefaultRegularFont("Arial Narrow");
>      FileOutputStream out = new FileOutputStream("pres-ArialNarrowDefault.png");
>      pres.getSlides().get_Item(0).getThumbnail(renderingOpts).compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, out);
>      out.flush();
>      out.close();
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RenderingOptions()](#RenderingOptions--) | Standardkonstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Liest oder legt den Modus fest, in dem Folien beim Export einer Präsentation auf der Seite angeordnet werden [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Liest oder legt den Modus fest, in dem Folien beim Export einer Präsentation auf der Seite angeordnet werden [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Liest oder legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Liest oder legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. |
### RenderingOptions() {#RenderingOptions--}
```
public RenderingOptions()
```


Standardkonstruktor.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Liest oder legt den Modus fest, in dem Folien beim Export einer Präsentation auf der Seite angeordnet werden [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
> 
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      android.graphics.Bitmap[] handoutSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoutSlides.length; index++)
>      {
>          FileOutputStream out = new FileOutputStream("handout-" + index + ".png");
>          handoutSlides[index].compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Liest oder legt den Modus fest, in dem Folien beim Export einer Präsentation auf der Seite angeordnet werden [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
> 
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      android.graphics.Bitmap[] handoutSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoutSlides.length; index++)
>      {
>          FileOutputStream out = new FileOutputStream("handout-" + index + ".png");
>          handoutSlides[index].compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur-Lesen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Rückgabe:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


Liest oder legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf true gesetzt, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      options.setDisableFontLigatures(true);
> 
>      IImage[] renderedSlides = pres.getImages(options);
>      for (int index = 0; index < renderedSlides.length; index++)
>      {
>          IImage slideImage = renderedSlides[index];
>          slideImage.save("slide-" + index + ".png");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```


Liest oder legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf true gesetzt, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      options.setDisableFontLigatures(true);
> 
>      IImage[] renderedSlides = pres.getImages(options);
>      for (int index = 0; index < renderedSlides.length; index++)
>      {
>          IImage slideImage = renderedSlides[index];
>          slideImage.save("slide-" + index + ".png");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |