---
title: IHtml5Options
second_title: Aspose.Slides Androidhoz Java API referencia
description: HTML5 exportálási beállításokat képvisel.
type: docs
url: /hu/com.aspose.slides/ihtml5options/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtml5Options extends ISaveOptions
```

HTML5 exportálási beállításokat képvisel.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Módszerek

| Method | Leírás |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | Visszaadja vagy beállítja a tranzíciók animációs opcióját. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | Visszaadja vagy beállítja a tranzíciók animációs opcióját. |
| [getAnimateShapes()](#getAnimateShapes--) | Visszaadja vagy beállítja az alakzatok animációs opcióját. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | Visszaadja vagy beállítja az alakzatok animációs opcióját. |
| [getEmbedImages()](#getEmbedImages--) | Visszaadja vagy beállítja a képek beágyazási opcióját. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | Visszaadja vagy beállítja a képek beágyazási opcióját. |
| [getOutputPath()](#getOutputPath--) | Meghatározza, hogy hol kell tárolni a külső erőforrásokat. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | Meghatározza, hogy hol kell tárolni a külső erőforrásokat. |
| [getPicturesCompression()](#getPicturesCompression--) | A képek tömörítési szintjét reprezentálja Olvasás/írás PicturesCompression (#getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | A képek tömörítési szintjét reprezentálja Olvasás/írás PicturesCompression (#getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Azt az értéket adja meg vagy állítja be, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Azt az értéket adja meg vagy állítja be, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | A diák exportálásakor az oldalra helyezés módját adja meg vagy állítja be [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | A diák exportálásakor az oldalra helyezés módját adja meg vagy állítja be [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getAnimateTransitions() {#getAnimateTransitions--}
```
public abstract boolean getAnimateTransitions()
```

Visszaadja vagy beállítja a tranzíciók animációs opcióját. Olvasás/írás boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**  
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public abstract void setAnimateTransitions(boolean value)
```

Visszaadja vagy beállítja a tranzíciók animációs opcióját. Olvasás/írás boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public abstract boolean getAnimateShapes()
```

Visszaadja vagy beállítja az alakzatok animációs opcióját. Olvasás/írás boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**  
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public abstract void setAnimateShapes(boolean value)
```

Visszaadja vagy beállítja az alakzatok animációs opcióját. Olvasás/írás boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public abstract boolean getEmbedImages()
```

Visszaadja vagy beállítja a képek beágyazási opcióját. Olvasás/írás boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**  
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public abstract void setEmbedImages(boolean value)
```

Visszaadja vagy beállítja a képek beágyazási opcióját. Olvasás/írás boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public abstract String getOutputPath()
```

Meghatározza, hogy hol kell tárolni a külső erőforrásokat. Olvasás/írás String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**  
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public abstract void setOutputPath(String value)
```

Meghatározza, hogy hol kell tárolni a külső erőforrásokat. Olvasás/írás String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

A képek tömörítési szintjét reprezentálja Olvasás/írás PicturesCompression (#getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int)).

**Visszatér:**  
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

A képek tömörítési szintjét reprezentálja Olvasás/írás PicturesCompression (#getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int)).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Azt az értéket adja meg vagy állítja be, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. Ha igazra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság hamis.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Ligatúrák letiltása a szöveg megjelenítésében
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**  
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Azt az értéket adja meg vagy állítja be, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. Ha igazra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság hamis.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Ligatúrák letiltása a szöveg renderelésében
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

A diák exportálásakor az oldalra helyezés módját adja meg vagy állítja be [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**  
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

A diák exportálásakor az oldalra helyezés módját adja meg vagy állítja be [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |