---
title: SVGOptions
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει τις επιλογές SVG.
type: docs
url: /el/com.aspose.slides/svgoptions/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Αναπαριστά επιλογές SVG.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Δημιουργεί μια νέα παρουσία της κλάσης SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Δημιουργεί μια νέα παρουσία της κλάσης SVGOptions, προσδιορίζοντας το αντικείμενο ελεγκτή ενσωμάτωσης συνδέσμου. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink σε εξαγόμενο έγγραφο. |
| [getUseFrameSize()](#getUseFrameSize--) | Καθορίζει εάν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Καθορίζει εάν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Καθορίζει εάν θα εκτελεστεί η καθορισμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Καθορίζει εάν θα εκτελεστεί η καθορισμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. |
| [getVectorizeText()](#getVectorizeText--) | Καθορίζει εάν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Καθορίζει εάν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Επιστρέφει ή ορίζει το κατώτατο όριο ανάλυσης για την rasterization των metafile. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Επιστρέφει ή ορίζει το κατώτατο όριο ανάλυσης για την rasterization των metafile. |
| [getDisable3DText()](#getDisable3DText--) | Καθορίζει εάν το 3D κείμενο είναι απενεργοποιημένο σε SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Καθορίζει εάν το 3D κείμενο είναι απενεργοποιημένο σε SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Απενεργοποιεί το διαχωρισμό των gradient FromCornerX και FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Απενεργοποιεί το διαχωρισμό των gradient FromCornerX και FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσοχών για markers. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσοχών για markers. |
| [getDefault()](#getDefault--) | Επιστρέφει τις προεπιλεγμένες ρυθμίσεις. |
| [getSimple()](#getSimple--) | Επιστρέφει τις ρυθμίσεις για την πιο απλή και μικρότερη δημιουργία αρχείου SVG. |
| [getWYSIWYG()](#getWYSIWYG--) | Επιστρέφει τις ρυθμίσεις για τη πιο ακριβή δημιουργία αρχείου SVG. |
| [getJpegQuality()](#getJpegQuality--) | Καθορίζει την ποιότητα κωδικοποίησης JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Καθορίζει την ποιότητα κωδικοποίησης JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Επιστρέφει και ορίζει μια διεπαφή επανάκλησης που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Επιστρέφει και ορίζει μια διεπαφή επανάκλησης που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. |
| [getPicturesCompression()](#getPicturesCompression--) | Αναπαριστά το επίπεδο συμπίεσης των εικόνων |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Αναπαριστά το επίπεδο συμπίεσης των εικόνων |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Μία λογική σημαία υποδεικνύει αν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Μία λογική σημαία υποδεικνύει αν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Καθορίζει έναν τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Καθορίζει έναν τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδετικών χαρακτήρων. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδετικών χαρακτήρων. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Δημιουργεί μια νέα παρουσία της κλάσης SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Δημιουργεί μια νέα παρουσία της κλάσης SVGOptions, προσδιορίζοντας το αντικείμενο ελεγκτή ενσωμάτωσης συνδέσμου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Η αναφορά ελεγκτή ενσωμάτωσης συνδέσμου. |

--------------------

Ο ελεγκτής ενσωμάτωσης συνδέσμου είναι ένα αντικείμενο εκχωρητή που είναι υπεύθυνο για τη λήψη αποφάσεων εάν οι πόροι (όπως εικόνες) πρέπει να ενσωματωθούν ή να αναφέρονται ως εξωτερικοί πόροι. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink σε εξαγόμενο έγγραφο. Μόνο-ανάγνωση [IInkOptions](../../com.aspose.slides/iinkoptions)

**Επιστρέφει:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Καθορίζει εάν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. Ανάγνωση/Εγγραφή  boolean . Η προεπιλεγμένη τιμή είναι false.

**Επιστρέφει:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Καθορίζει εάν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. Ανάγνωση/Εγγραφή  boolean . Η προεπιλεγμένη τιμή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Καθορίζει εάν θα εκτελεστεί η καθορισμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. Ανάγνωση/Εγγραφή  boolean . Η προεπιλεγμένη τιμή είναι true.

**Επιστρέφει:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Καθορίζει εάν θα εκτελεστεί η καθορισμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. Ανάγνωση/Εγγραφή  boolean . Η προεπιλεγμένη τιμή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Καθορίζει εάν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Καθορίζει εάν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Επιστρέφει ή ορίζει το κατώτατο όριο ανάλυσης για την rasterization των metafile. Ανάγνωση/Εγγραφή int.

**Επιστρέφει:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Επιστρέφει ή ορίζει το κατώτατο όριο ανάλυσης για την rasterization των metafile. Ανάγνωση/Εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Καθορίζει εάν το 3D κείμενο είναι απενεργοποιημένο σε SVG. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Καθορίζει εάν το 3D κείμενο είναι απενεργοποιημένο σε SVG. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Απενεργοποιεί το διαχωρισμό των gradient FromCornerX και FromCenter. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Απενεργοποιεί το διαχωρισμό των gradient FromCornerX και FromCenter. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσοχών για markers. Η μηχανή εγγραφής SVG του Aspose.Slides έχει τρόπο αντιμετώπισης: κόβει το άκρο της γραμμής με το βέλος, ώστε η γραμμή να μην επικαλύπτει τα markers. Αυτή η επιλογή απενεργοποιεί αυτή τη συμπεριφορά. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσοχών για markers. Η μηχανή εγγραφής SVG του Aspose.Slides έχει τρόπο αντιμετώπισης: κόβει το άκρο της γραμμής με το βέλος, ώστε η γραμμή να μην επικαλύπτει τα markers. Αυτή η επιλογή απενεργοποιεί αυτή τη συμπεριφορά. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Επιστρέφει τις προεπιλεγμένες ρυθμίσεις. Μόνο-ανάγνωση [SVGOptions](../../com.aspose.slides/svgoptions).

**Επιστρέφει:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Επιστρέφει τις ρυθμίσεις για την πιο απλή και μικρότερη δημιουργία αρχείου SVG. Μόνο-ανάγνωση [SVGOptions](../../com.aspose.slides/svgoptions).

**Επιστρέφει:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Επιστρέφει τις ρυθμίσεις για τη πιο ακριβή δημιουργία αρχείου SVG. Μόνο-ανάγνωση [SVGOptions](../../com.aspose.slides/svgoptions).

**Επιστρέφει:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Καθορίζει την ποιότητα κωδικοποίησης JPEG. Ανάγνωση/Εγγραφή int.

**Επιστρέφει:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Καθορίζει την ποιότητα κωδικοποίησης JPEG. Ανάγνωση/Εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Επιστρέφει και ορίζει μια διεπαφή επανάκλησης που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. Ανάγνωση/Εγγραφή [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Επιστρέφει:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Επιστρέφει και ορίζει μια διεπαφή επανάκλησης που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. Ανάγνωση/Εγγραφή [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Αναπαριστά το επίπεδο συμπίεσης των εικόνων

**Επιστρέφει:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Αναπαριστά το επίπεδο συμπίεσης των εικόνων

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Μία λογική σημαία υποδεικνύει αν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. Εάν είναι true, τα περικομμένα τμήματα θα αφαιρεθούν· εάν είναι false, θα διατηρηθούν στο έγγραφο (που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο)

**Επιστρέφει:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Μία λογική σημαία υποδεικνύει αν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. Εάν είναι true, τα περικομμένα τμήματα θα αφαιρεθούν· εάν είναι false, θα διατηρηθούν στο έγγραφο (που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο)

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Καθορίζει έναν τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. Ανάγνωση/Εγγραφή [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Επιστρέφει:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Καθορίζει έναν τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. Ανάγνωση/Εγγραφή [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδετικών χαρακτήρων. Όταν οριστεί σε true, οι συνδετικοί χαρακτήρες θα απενεργοποιηθούν στην απόδοση. Από προεπιλογή, αυτή η ιδιότητα είναι false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδετικών χαρακτήρων. Όταν οριστεί σε true, οι συνδετικοί χαρακτήρες θα απενεργοποιηθούν στην απόδοση. Από προεπιλογή, αυτή η ιδιότητα είναι false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |