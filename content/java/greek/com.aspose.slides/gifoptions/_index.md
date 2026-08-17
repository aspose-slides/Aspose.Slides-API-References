---
title: GifOptions
second_title: Aspose.Slides για Java Αναφορά API
description: Αντιπροσωπεύει τις επιλογές εξαγωγής GIF.
type: docs
url: /el/com.aspose.slides/gifoptions/
---
**Κληρονομικότητα:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Όλες οι Υλοποιημένες Διεπαφές:**  
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)  
```
public class GifOptions extends SaveOptions implements IGifOptions
```

Αντιπροσωπεύει τις επιλογές εξαγωγής GIF.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new Dimension(960, 720)); // το μέγεθος του παραγόμενου GIF
>      gifOptions.setDefaultDelay(2000); // πόσο χρόνο θα εμφανίζεται κάθε διαφάνεια μέχρι να αλλάξει στην επόμενη
>      gifOptions.setTransitionFps(35); // αυξήστε το FPS για καλύτερη ποιότητα κινούμενης μετάβασης
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [GifOptions()](#GifOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης GifOptions. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Λαμβάνει ή ορίζει το μέγεθος του καρέ. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Λαμβάνει ή ορίζει το μέγεθος του καρέ. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Καθορίζει αν οι κρυφές διαφάνειες θα εξαχθούν. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Καθορίζει αν οι κρυφές διαφάνειες θα εξαχθούν. |
| [getTransitionFps()](#getTransitionFps--) | Λαμβάνει ή ορίζει το FPS μετάβασης [καρέ/δευτ.]. Η προεπιλεγμένη τιμή είναι 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Λαμβάνει ή ορίζει το FPS μετάβασης [καρέ/δευτ.]. Η προεπιλεγμένη τιμή είναι 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Λαμβάνει ή ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Λαμβάνει ή ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Dimension getFrameSize()
```

Λαμβάνει ή ορίζει το μέγεθος του καρέ.

--------------------

Εάν το μέγεθος είναι κενό, τότε η τιμή θα ληφθεί από [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Επιστρέφει:**  
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public final void setFrameSize(Dimension value)
```

Λαμβάνει ή ορίζει το μέγεθος του καρέ.

--------------------

Εάν το μέγεθος είναι κενό, τότε η τιμή θα ληφθεί από [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

Καθορίζει αν οι κρυφές διαφάνειες θα εξαχθούν. Η προεπιλεγμένη τιμή είναι false.

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
public final void setExportHiddenSlides(boolean value)
```

Καθορίζει αν οι κρυφές διαφάνειες θα εξαχθούν. Η προεπιλεγμένη τιμή είναι false.

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
public final int getTransitionFps()
```

Λαμβάνει ή ορίζει το FPS μετάβασης [καρέ/δευτ.]. Η προεπιλεγμένη τιμή είναι 25.

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
public final void setTransitionFps(int value)
```

Λαμβάνει ή ορίζει το FPS μετάβασης [καρέ/δευτ.]. Η προεπιλεγμένη τιμή είναι 25.

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
public final int getDefaultDelay()
```

Λαμβάνει ή ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. Αυτή η τιμή θα χρησιμοποιηθεί εάν [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) δεν έχει οριστεί. Η προεπιλεγμένη τιμή είναι 1000.

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
public final void setDefaultDelay(int value)
```

Λαμβάνει ή ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. Αυτή η τιμή θα χρησιμοποιηθεί εάν [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) δεν έχει οριστεί. Η προεπιλεγμένη τιμή είναι 1000.

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