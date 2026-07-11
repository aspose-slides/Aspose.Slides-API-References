---
title: GifOptions
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά τις επιλογές εξαγωγής GIF.
type: docs
url: /el/com.aspose.slides/gifoptions/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

Αναπαριστά τις επιλογές εξαγωγής GIF.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // το μέγεθος του παραγόμενου GIF
>      gifOptions.setDefaultDelay(2000); // πόσος χρόνος θα εμφανίζεται κάθε διαφάνεια μέχρι να μεταβεί στην επόμενη
>      gifOptions.setTransitionFps(35); // αυξήστε τα FPS για καλύτερη ποιότητα μετάβασης
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
| [getFrameSize()](#getFrameSize--) | Λαμβάνει ή ορίζει το μέγεθος του πλαισίου. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Λαμβάνει ή ορίζει το μέγεθος του πλαισίου. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν. |
| [getTransitionFps()](#getTransitionFps--) | Λαμβάνει ή ορίζει τα FPS μετάβασης [πλαισίων/δευτ.] Η προεπιλεγμένη τιμή είναι 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Λαμβάνει ή ορίζει τα FPS μετάβασης [πλαισίων/δευτ.] Η προεπιλεγμένη τιμή είναι 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Λαμβάνει ή ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Λαμβάνει ή ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```

Λαμβάνει ή ορίζει το μέγεθος του πλαισίου.

--------------------

Εάν το μέγεθος είναι κενό, τότε η τιμή θα ληφθεί από [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Επιστρέφει:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```

Λαμβάνει ή ορίζει το μέγεθος του πλαισίου.

--------------------

Εάν το μέγεθος είναι κενό, τότε η τιμή θα ληφθεί από [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
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
public final void setExportHiddenSlides(boolean value)
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
public final int getTransitionFps()
```

Λαμβάνει ή ορίζει τα FPS μετάβασης [πλαισίων/δευτ.] Η προεπιλεγμένη τιμή είναι 25.

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

Λαμβάνει ή ορίζει τα FPS μετάβασης [πλαισίων/δευτ.] Η προεπιλεγμένη τιμή είναι 25.

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

Λαμβάνει ή ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. Αυτή η τιμή θα χρησιμοποιηθεί εάν δεν έχει οριστεί [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-). Η προεπιλεγμένη τιμή είναι 1000.

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

Λαμβάνει ή ορίζει τον προεπιλεγμένο χρόνο καθυστέρησης [ms]. Αυτή η τιμή θα χρησιμοποιηθεί εάν δεν έχει οριστεί [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-). Η προεπιλεγμένη τιμή είναι 1000.

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