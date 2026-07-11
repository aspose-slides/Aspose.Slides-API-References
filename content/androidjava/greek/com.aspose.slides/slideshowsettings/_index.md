---
title: SlideShowSettings
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αναπαριστά τις ρυθμίσεις προβολής διαφανειών για την παρουσίαση.
type: docs
url: /el/com.aspose.slides/slideshowsettings/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class SlideShowSettings
```

Αναπαριστά τις ρυθμίσεις προβολής διαφανειών για την παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Λαμβάνει ή ορίζει τον τύπο προβολής διαφανειών. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Λαμβάνει ή ορίζει τον τύπο προβολής διαφανειών. |
| [getLoop()](#getLoop--) | Βρόχος προβολής διαφανειών |
| [setLoop(boolean value)](#setLoop-boolean-) | Βρόχος προβολής διαφανειών |
| [getShowNarration()](#getShowNarration--) | Εμφάνιση αφήγησης στην προβολή διαφανειών |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Εμφάνιση αφήγησης στην προβολή διαφανειών |
| [getShowAnimation()](#getShowAnimation--) | Εμφάνιση κίνησης στην προβολή διαφανειών |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Εμφάνιση κίνησης στην προβολή διαφανειών |
| [getPenColor()](#getPenColor--) | Χρώμα πένας για την προβολή διαφανειών |
| [getSlides()](#getSlides--) | Εύρος διαφανειών |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Εύρος διαφανειών |
| [getUseTimings()](#getUseTimings--) | Χρήση χρονισμών στην προβολή διαφανειών |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Χρήση χρονισμών στην προβολή διαφανειών |
| [getShowMediaControls()](#getShowMediaControls--) | Εμφάνιση ελέγχων πολυμέσων |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Εμφάνιση ελέγχων πολυμέσων |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

Λαμβάνει ή ορίζει τον τύπο προβολής διαφανειών. Αναπαρίσταται από το ακόλουθο SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) πρόγονοι: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) and [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // για να ορίσετε τον τύπο "Browsed at a kiosk (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // για να ορίσετε τον τύπο "Browsed by individual (window)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // για να ορίσετε τον τύπο "Presented by a speaker (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

Λαμβάνει ή ορίζει τον τύπο προβολής διαφανειών. Αναπαρίσταται από το ακόλουθο SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) πρόγονοι: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) and [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // για να ορίσετε το "Browsed at a kiosk (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // για να ορίσετε το "Browsed by individual (window)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // για να ορίσετε το "Presented by a speaker (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

Βρόχος προβολής διαφανειών

**Επιστρέφει:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Βρόχος προβολής διαφανειών

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

Εμφάνιση αφήγησης στην προβολή διαφανειών

**Επιστρέφει:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

Εμφάνιση αφήγησης στην προβολή διαφανειών

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

Εμφάνιση κίνησης στην προβολή διαφανειών

**Επιστρέφει:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

Εμφάνιση κίνησης στην προβολή διαφανειών

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

Χρώμα πένας για την προβολή διαφανειών

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

Εύρος διαφανειών

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SlidesRange slidesRange = new SlidesRange();
>      slidesRange.setStart(1);
>      slidesRange.setEnd(3);
>      pres.getSlideShowSettings().setSlides(slidesRange);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

Εύρος διαφανειών

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SlidesRange slidesRange = new SlidesRange();
>      slidesRange.setStart(1);
>      slidesRange.setEnd(3);
>      pres.getSlideShowSettings().setSlides(slidesRange);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

Χρήση χρονισμών στην προβολή διαφανειών

**Επιστρέφει:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

Χρήση χρονισμών στην προβολή διαφανειών

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

Εμφάνιση ελέγχων πολυμέσων

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

Εμφάνιση ελέγχων πολυμέσων

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |