---
title: IGifOptions
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αναπαριστά τις επιλογές εξαγωγής GIF.
type: docs
url: /el/com.aspose.slides/igifoptions/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Αναπαριστά τις επιλογές εξαγωγής GIF.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Λαμβάνει ή ορίζει το μέγεθος του πλαισίου. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Λαμβάνει ή ορίζει το μέγεθος του πλαισίου. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν. |
| [getTransitionFps()](#getTransitionFps--) | Λαμβάνει ή ορίζει το FPS μετάβασης [frames/sec] Η προεπιλεγμένη τιμή είναι 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Λαμβάνει ή ορίζει το FPS μετάβασης [frames/sec] Η προεπιλεγμένη τιμή είναι 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Λαμβάνει ή ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Λαμβάνει ή ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Dimension getFrameSize()
```

Λαμβάνει ή ορίζει το μέγεθος του πλαισίου.

--------------------

Εάν το μέγεθος είναι κενό, η τιμή θα ληφθεί από [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Επιστρέφει:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public abstract void setFrameSize(Dimension value)
```

Λαμβάνει ή ορίζει το μέγεθος του πλαισίου.

--------------------

Εάν το μέγεθος είναι κενό, η τιμή θα ληφθεί από [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.awt.Dimension |  |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```

Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν. Η προεπιλεγμένη τιμή είναι false.

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

**Επιστρέφει:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```

Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν. Η προεπιλεγμένη τιμή είναι false.

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

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```

Λαμβάνει ή ορίζει το FPS μετάβασης [frames/sec] Η προεπιλεγμένη τιμή είναι 25.

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


**Επιστρέφει:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```

Λαμβάνει ή ορίζει το FPS μετάβασης [frames/sec] Η προεπιλεγμένη τιμή είναι 25.

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

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```

Λαμβάνει ή ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. Αυτή η τιμή θα χρησιμοποιηθεί εάν τα [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) δεν έχουν οριστεί. Η προεπιλεγμένη τιμή είναι 1000.

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

**Επιστρέφει:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)
```

Λαμβάνει ή ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. Αυτή η τιμή θα χρησιμοποιηθεί εάν τα [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) δεν έχουν οριστεί. Η προεπιλεγμένη τιμή είναι 1000.

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

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |