---
title: SVGOptions
second_title: Αναφορά API Java του Aspose.Slides
description: Αναπαριστά επιλογές SVG.
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
| [SVGOptions()](#SVGOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Αρχικοποιεί μια νέα παρουσία της κλάσης SVGOptions προσδιορίζοντας το αντικείμενο ελεγκτή ενσωμάτωσης συνδέσμου. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. |
| [getUseFrameSize()](#getUseFrameSize--) | Καθορίζει εάν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Καθορίζει εάν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Καθορίζει εάν θα εκτελεστεί η συγκεκριμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Καθορίζει εάν θα εκτελεστεί η συγκεκριμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. |
| [getVectorizeText()](#getVectorizeText--) | Καθορίζει εάν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Καθορίζει εάν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Επιστρέφει ή ορίζει το κάτω όριο ανάλυσης για τη ραστεροποίηση μετααρχείων. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Επιστρέφει ή ορίζει το κάτω όριο ανάλυσης για τη ραστεροποίηση μετααρχείων. |
| [getDisable3DText()](#getDisable3DText--) | Καθορίζει εάν το 3D κείμενο είναι απενεργοποιημένο στο SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Καθορίζει εάν το 3D κείμενο είναι απενεργοποιημένο στο SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Απενεργοποιεί τον διαχωρισμό των διαβαθμίων FromCornerX και FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Απενεργοποιεί τον διαχωρισμό των διαβαθμίων FromCornerX και FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσοχών για δείκτες. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσοχών για δείκτες. |
| [getDefault()](#getDefault--) | Επιστρέφει τις προεπιλεγμένες ρυθμίσεις. |
| [getSimple()](#getSimple--) | Επιστρέφει ρυθμίσεις για την πιο απλή και μικρότερη δημιουργία αρχείου SVG. |
| [getWYSIWYG()](#getWYSIWYG--) | Επιστρέφει ρυθμίσεις για τη πιο ακριβή δημιουργία αρχείου SVG. |
| [getJpegQuality()](#getJpegQuality--) | Καθορίζει την ποιότητα κωδικοποίησης JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Καθορίζει την ποιότητα κωδικοποίησης JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Επιστρέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Επιστρέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. |
| [getPicturesCompression()](#getPicturesCompression--) | Αναπαριστά το επίπεδο συμπίεσης των εικόνων |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Αναπαριστά το επίπεδο συμπίεσης των εικόνων |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Μια λογική σημαία που υποδεικνύει αν τα περικομμένα μέρη παραμένουν ως μέρος του εγγράφου. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Μια λογική σημαία που υποδεικνύει αν τα περικομμένα μέρη παραμένουν ως μέρος του εγγράφου. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Καθορίζει έναν τρόπο διαχείρισης των εξωτερικά φορτωμένων γραμματοσειρών. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Καθορίζει έναν τρόπο διαχείρισης των εξωτερικά φορτωμένων γραμματοσειρών. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Παίρνει ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση ligatures. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Παίρνει ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση ligatures. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Αρχικοποιεί μια νέα παρουσία της κλάσης SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Αρχικοποιεί μια νέα παρουσία της κλάσης SVGOptions προσδιορίζοντας το αντικείμενο ελεγκτή ενσωμάτωσης συνδέσμου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Η αναφορά του ελεγκτή ενσωμάτωσης συνδέσμου. |

--------------------

Ο ελεγκτής ενσωμάτωσης συνδέσμου είναι ένα αντικείμενο εκχωρητή (delegate) που είναι υπεύθυνο για τη λήψη αποφάσεων εάν οι πόροι (όπως εικόνες) πρέπει να ενσωματωθούν ή να αναφερθούν ως εξωτερικοί πόροι. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο για ανάγνωση [IInkOptions](../../com.aspose.slides/iinkoptions)

**Επιστρέφει:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Καθορίζει εάν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. Ανάγνωση/εγγραφή boolean . Προεπιλεγμένη τιμή είναι false.

**Επιστρέφει:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Καθορίζει εάν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. Ανάγνωση/εγγραφή boolean . Προεπιλεγμένη τιμή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Καθορίζει εάν θα εκτελεστεί η συγκεκριμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. Ανάγνωση/εγγραφή boolean . Προεπιλεγμένη τιμή είναι true.

**Επιστρέφει:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Καθορίζει εάν θα εκτελεστεί η συγκεκριμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. Ανάγνωση/εγγραφή boolean . Προεπιλεγμένη τιμή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Καθορίζει εάν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Καθορίζει εάν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Επιστρέφει ή ορίζει το κάτω όριο ανάλυσης για τη ραστεροποίηση μετααρχείων. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Επιστρέφει ή ορίζει το κάτω όριο ανάλυσης για τη ραστεροποίηση μετααρχείων. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Καθορίζει εάν το 3D κείμενο είναι απενεργοποιημένο στο SVG. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Καθορίζει εάν το 3D κείμενο είναι απενεργοποιημένο στο SVG. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Απενεργοποιεί τον διαχωρισμό των διαβαθμίων FromCornerX και FromCenter. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Απενεργοποιεί τον διαχωρισμό των διαβαθμίων FromCornerX και FromCenter. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσοχών για δείκτες. Η μηχανή γραφής SVG του Aspose.Slides έχει εναλλακτική λύση για αυτό το πρόβλημα: περικόπτει το άκρο της γραμμής με βέλος, ώστε η γραμμή να μην επικαλύπτει τους δείκτες. Αυτή η επιλογή απενεργοποιεί τη συμπεριφορά αυτή. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσοχών για δείκτες. Η μηχανή γραφής SVG του Aspose.Slides έχει εναλλακτική λύση για αυτό το πρόβλημα: περικόπτει το άκρο της γραμμής με βέλος, ώστε η γραμμή να μην επικαλύπτει τους δείκτες. Αυτή η επιλογή απενεργοποιεί τη συμπεριφορά αυτή. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Επιστρέφει τις προεπιλεγμένες ρυθμίσεις. Μόνο για ανάγνωση [SVGOptions](../../com.aspose.slides/svgoptions).

**Επιστρέφει:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Επιστρέφει ρυθμίσεις για την πιο απλή και μικρότερη δημιουργία αρχείου SVG. Μόνο για ανάγνωση [SVGOptions](../../com.aspose.slides/svgoptions).

**Επιστρέφει:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Επιστρέφει ρυθμίσεις για τη πιο ακριβή δημιουργία αρχείου SVG. Μόνο για ανάγνωση [SVGOptions](../../com.aspose.slides/svgoptions).

**Επιστρέφει:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Καθορίζει την ποιότητα κωδικοποίησης JPEG. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Καθορίζει την ποιότητα κωδικοποίησης JPEG. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Επιστρέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. Ανάγνωση/εγγραφή [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Επιστρέφει:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Επιστρέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. Ανάγνωση/εγγραφή [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

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

Μια λογική σημαία που υποδεικνύει αν τα περικομμένα μέρη παραμένουν ως μέρος του εγγράφου. Εάν είναι true, τα περικομμένα μέρη θα αφαιρεθούν· εάν είναι false, θα διατηρηθούν στο έγγραφο (που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο).

**Επιστρέφει:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Μια λογική σημαία που υποδεικνύει αν τα περικομμένα μέρη παραμένουν ως μέρος του εγγράφου. Εάν είναι true, τα περικομμένα μέρη θα αφαιρεθούν· εάν είναι false, θα διατηρηθούν στο έγγραφο (που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Καθορίζει έναν τρόπο διαχείρισης των εξωτερικά φορτωμένων γραμματοσειρών. Ανάγνωση/εγγραφή [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Επιστρέφει:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Καθορίζει έναν τρόπο διαχείρισης των εξωτερικά φορτωμένων γραμματοσειρών. Ανάγνωση/εγγραφή [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Παίρνει ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση ligatures. Όταν οριστεί σε true, οι συνδέσεις θα απενεργοποιηθούν στην παραχθείσα έξοδο. Από προεπιλογή, αυτή η ιδιότητα είναι false.

--------------------

> ```
> Παράδειγμα:
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

Παίρνει ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση ligatures. Όταν οριστεί σε true, οι συνδέσεις θα απενεργοποιηθούν στην παραχθείσα έξοδο. Από προεπιλογή, αυτή η ιδιότητα είναι false.

--------------------

> ```
> Παράδειγμα:
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