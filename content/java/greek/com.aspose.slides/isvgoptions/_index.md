---
title: ISVGOptions
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά τις επιλογές SVG.
type: docs
url: /el/com.aspose.slides/isvgoptions/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Αναπαριστά τις επιλογές SVG.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Καθορίζει αν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Καθορίζει αν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Επιστρέφει ή ορίζει το κατώτερο όριο ανάλυσης για τη ραστεροποίηση μετααρχείου. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Επιστρέφει ή ορίζει το κατώτερο όριο ανάλυσης για τη ραστεροποίηση μετααρχείου. |
| [getDisable3DText()](#getDisable3DText--) | Καθορίζει αν το 3Δ κείμενο είναι απενεργοποιημένο σε SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Καθορίζει αν το 3Δ κείμενο είναι απενεργοποιημένο σε SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Απενεργοποιεί το διαχωρισμό των gradient FromCornerX και FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Απενεργοποιεί το διαχωρισμό των gradient FromCornerX και FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | Η SVG 1.1 δεν διαθέτει δυνατότητα ορισμού περιθωρίων για δείκτες. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | Η SVG 1.1 δεν διαθέτει δυνατότητα ορισμού περιθωρίων για δείκτες. |
| [getJpegQuality()](#getJpegQuality--) | Καθορίζει την ποιότητα κωδικοποίησης JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Καθορίζει την ποιότητα κωδικοποίησης JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Επιστέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Επιστέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. |
| [getPicturesCompression()](#getPicturesCompression--) | Αναπαριστά το επίπεδο συμπίεσης εικόνων Ανάγνωση/εγγραφή \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Αναπαριστά το επίπεδο συμπίεσης εικόνων Ανάγνωση/εγγραφή \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Μια λογική σημαία υποδεικνύει αν τα περικυκολογημένα τμήματα παραμένουν μέρος του εγγράφου. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Μια λογική σημαία υποδεικνύει αν τα περικυκολογημένα τμήματα παραμένουν μέρος του εγγράφου. |
| [getUseFrameSize()](#getUseFrameSize--) | Καθορίζει αν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Καθορίζει αν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Καθορίζει αν θα γίνει η καθορισμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Καθορίζει αν θα γίνει η καθορισμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Καθορίζει έναν τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Καθορίζει έναν τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. |
| [getInkOptions()](#getInkOptions--) | Παρέχει επιλογές που ελέγχουν την εμφάνιση αντικειμένων Ink στο εξαγόμενο έγγραφο. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς τη χρήση συνδέσεων. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς τη χρήση συνδέσεων. |
### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Καθορίζει αν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. Ανάγνωση/εγγραφή boolean.

**Τιμή επιστροφής:**
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

Επιστρέφει ή ορίζει το κατώτερο όριο ανάλυσης για τη ραστεροποίηση μετααρχείου. Ανάγνωση/εγγραφή int.

**Τιμή επιστροφής:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Επιστρέφει ή ορίζει το κατώτερο όριο ανάλυσης για τη ραστεροποίηση μετααρχείου. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Καθορίζει αν το 3Δ κείμενο είναι απενεργοποιημένο σε SVG. Ανάγνωση/εγγραφή boolean.

**Τιμή επιστροφής:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Καθορίζει αν το 3Δ κείμενο είναι απενεργοποιημένο σε SVG. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Απενεργοποιεί το διαχωρισμό των gradient FromCornerX και FromCenter. Ανάγνωση/εγγραφή boolean.

**Τιμή επιστροφής:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

Απενεργοποιεί το διαχωρισμό των gradient FromCornerX και FromCenter. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

Η SVG 1.1 δεν διαθέτει δυνατότητα ορισμού περιθωρίων για δείκτες. Η μηχανή εγγραφής Aspose.Slides SVG έχει εναλλακτική λύση για αυτό το πρόβλημα: κόβει το άκρο της γραμμής με το βέλος, ώστε η γραμμή να μην επικαλύπτει τους δείκτες. Αυτή η επιλογή απενεργοποιεί αυτή τη συμπεριφορά. Ανάγνωση/εγγραφή boolean.

**Τιμή επιστροφής:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

Η SVG 1.1 δεν διαθέτει δυνατότητα ορισμού περιθωρίων για δείκτες. Η μηχανή εγγραφής Aspose.Slides SVG έχει εναλλακτική λύση για αυτό το πρόβλημα: κόβει το άκρο της γραμμής με το βέλος, ώστε η γραμμή να μην επικαλύπτει τους δείκτες. Αυτή η επιλογή απενεργοποιεί αυτή τη συμπεριφορά. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Καθορίζει την ποιότητα κωδικοποίησης JPEG. Ανάγνωση/εγγραφή int.

**Τιμή επιστροφής:**
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

**Τιμή επιστροφής:**
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

Αντανακλά το επίπεδο συμπίεσης εικόνων Ανάγνωση/εγγραφή \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Τιμή επιστροφής:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Αντανακλά το επίπεδο συμπίεσης εικόνων Ανάγνωση/εγγραφή \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Μια λογική σημαία υποδεικνύει αν τα περικυκολογημένα τμήματα παραμένουν μέρος του εγγράφου. Αν αληθής, τα περικομμένα μέρη θα αφαιρεθούν· αν ψευδής, θα σειριοποιηθούν στο έγγραφο (πράγμα που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). Ανάγνωση/εγγραφή boolean.

**Τιμή επιστροφής:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Μια λογική σημαία υποδεικνύει αν τα περικυκολογημένα τμήματα παραμένουν μέρος του εγγράφου. Αν αληθής, τα περικομμένα μέρη θα αφαιρεθούν· αν ψευδής, θα σειριοποιηθούν στο έγγραφο (πράγμα που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Καθορίζει αν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. Ανάγνωση/εγγραφή boolean. Η προεπιλεγμένη τιμή είναι false.

**Τιμή επιστροφής:**
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

Καθορίζει αν θα γίνει η καθορισμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. Ανάγνωση/εγγραφή boolean. Η προεπιλεγμένη τιμή είναι true.

**Τιμή επιστροφής:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Καθορίζει αν θα γίνει η καθορισμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. Ανάγνωση/εγγραφή boolean. Η προεπιλεγμένη τιμή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Καθορίζει έναν τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. Ανάγνωση/εγγραφή [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Τιμή επιστροφής:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Καθορίζει έναν τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. Ανάγνωση/εγγραφή [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Παρέχει επιλογές που ελέγχουν την εμφάνιση αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο ανάγνωση [IInkOptions](../../com.aspose.slides/iinkoptions)

**Τιμή επιστροφής:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς τη χρήση συνδέσεων. Όταν οριστεί σε true, οι συνδέσεις θα απενεργοποιηθούν στην απόδοση. Από προεπιλογή, η ιδιότητα είναι false.

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

**Τιμή επιστροφής:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Ανακτά ή ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς τη χρήση συνδέσεων. Όταν οριστεί σε true, οι συνδέσεις θα απενεργοποιηθούν στην απόδοση. Από προεπιλογή, η ιδιότητα είναι false.

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