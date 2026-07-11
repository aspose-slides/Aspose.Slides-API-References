---
title: ISVGOptions
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά επιλογές SVG.
type: docs
url: /el/com.aspose.slides/isvgoptions/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Αντιπροσωπεύει τις επιλογές SVG.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Καθορίζει αν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Καθορίζει αν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Επιστρέφει ή ορίζει το κατώτερο όριο ανάλυσης για την απεικόνιση μετααρχείου. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Επιστρέφει ή ορίζει το κατώτερο όριο ανάλυσης για την απεικόνιση μετααρχείου. |
| [getDisable3DText()](#getDisable3DText--) | Καθορίζει αν το 3D κείμενο είναι απενεργοποιημένο στο SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Καθορίζει αν το 3D κείμενο είναι απενεργοποιημένο στο SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Απενεργοποιεί το διαχωρισμό των διαβαθμίσεων FromCornerX και FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Απενεργοποιεί το διαχωρισμό των διαβαθμίσεων FromCornerX και FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσωτερικών αποστάσεων για δείκτες. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσωτερικών αποστάσεων για δείκτες. |
| [getJpegQuality()](#getJpegQuality--) | Καθορίζει την ποιότητα κωδικοποίησης JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Καθορίζει την ποιότητα κωδικοποίησης JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Επιστρέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Επιστρέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. |
| [getPicturesCompression()](#getPicturesCompression--) | Αντιπροσωπεύει το επίπεδο συμπίεσης εικόνων Ανάγνωση/εγγραφή \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Αντιπροσωπεύει το επίπεδο συμπίεσης εικόνων Ανάγνωση/εγγραφή \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Μια ένδειξη boolean υποδεικνύει εάν τα περικομμένα τμήματα παραμένουν μέρος του εγγράφου. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Μια ένδειξη boolean υποδεικνύει εάν τα περικομμένα τμήματα παραμένουν μέρος του εγγράφου. |
| [getUseFrameSize()](#getUseFrameSize--) | Καθορίζει αν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Καθορίζει αν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Καθορίζει αν θα πραγματοποιηθεί η καθορισμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Καθορίζει αν θα πραγματοποιηθεί η καθορισμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Καθορίζει τρόπους διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Καθορίζει τρόπους διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. |
| [getInkOptions()](#getInkOptions--) | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγώμενο έγγραφο. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδέσμων (ligatures). |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδέσμων (ligatures). |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Καθορίζει αν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Καθορίζει αν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Επιστρέφει ή ορίζει το κατώτερο όριο ανάλυσης για την απεικόνιση μετααρχείου. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Επιστρέφει ή ορίζει το κατώτερο όριο ανάλυσης για την απεικόνιση μετααρχείου. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Καθορίζει αν το 3D κείμενο είναι απενεργοποιημένο στο SVG. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Καθορίζει αν το 3D κείμενο είναι απενεργοποιημένο στο SVG. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Απενεργοποιεί το διαχωρισμό των διαβαθμίσεων FromCornerX και FromCenter. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

Απενεργοποιεί το διαχωρισμό των διαβαθμίσεων FromCornerX και FromCenter. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσωτερικών αποστάσεων για δείκτες. Η μηχανή εγγραφής SVG του Aspose.Slides διαθέτει παρακάμπτιση για αυτό το πρόβλημα: περικόπτει το άκρο της γραμμής με το βέλος, έτσι ώστε η γραμμή να μην επικαλύπτει τους δείκτες. Αυτή η επιλογή απενεργοποιεί αυτή τη συμπεριφορά. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσωτερικών αποστάσεων για δείκτες. Η μηχανή εγγραφής SVG του Aspose.Slides διαθέτει παρακάμπτιση για αυτό το πρόβλημα: περικόπτει το άκρο της γραμμής με το βέλος, έτσι ώστε η γραμμή να μην επικαλύπτει τους δείκτες. Αυτή η επιλογή απενεργοποιεί αυτή τη συμπεριφορά. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Καθορίζει την ποιότητα κωδικοποίησης JPEG. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Καθορίζει την ποιότητα κωδικοποίησης JPEG. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Επιστρέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. Ανάγνωση/εγγραφή [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Επιστρέφει:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Επιστρέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. Ανάγνωση/εγγραφή [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Αντιπροσωπεύει το επίπεδο συμπίεσης εικόνων Ανάγνωση/εγγραφή \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Επιστρέφει:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Αντιπροσωπεύει το επίπεδο συμπίεσης εικόνων Ανάγνωση/εγγραφή \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Μια ένδειξη boolean υποδεικνύει εάν τα περικομμένα τμήματα παραμένουν μέρος του εγγράφου. Εάν είναι true, τα περικομμένα τμήματα θα αφαιρεθούν, εάν είναι false, θα σειριοποιηθούν στο έγγραφο (κάτι που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Μια ένδειξη boolean υποδεικνύει εάν τα περικομμένα τμήματα παραμένουν μέρος του εγγράφου. Εάν είναι true, τα περικομμένα τμήματα θα αφαιρεθούν, εάν είναι false, θα σειριοποιηθούν στο έγγραφο (κάτι που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Καθορίζει αν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. Ανάγνωση/εγγραφή boolean. Η προεπιλεγμένη τιμή είναι false.

**Επιστρέφει:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Καθορίζει αν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. Ανάγνωση/εγγραφή boolean. Η προεπιλεγμένη τιμή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Καθορίζει αν θα πραγματοποιηθεί η καθορισμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. Ανάγνωση/εγγραφή boolean. Η προεπιλεγμένη τιμή είναι true.

**Επιστρέφει:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Καθορίζει αν θα πραγματοποιηθεί η καθορισμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. Ανάγνωση/εγγραφή boolean. Η προεπιλεγμένη τιμή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Καθορίζει τρόπους διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. Ανάγνωση/εγγραφή [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Επιστρέφει:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Καθορίζει τρόπους διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. Ανάγνωση/εγγραφή [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγώμενο έγγραφο. Μόνο για ανάγνωση [IInkOptions](../../com.aspose.slides/iinkoptions)

**Επιστρέφει:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδέσμων (ligatures). Όταν οριστεί σε true, οι συνδέσεις θα απενεργοποιηθούν στην έξοδο. Από προεπιλογή, αυτή η ιδιότητα είναι false.

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
public abstract void setDisableFontLigatures(boolean value)
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδέσμων (ligatures). Όταν οριστεί σε true, οι συνδέσεις θα απενεργοποιηθούν στην έξοδο. Από προεπιλογή, αυτή η ιδιότητα είναι false.

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