---
title: ITextFrameFormat
second_title: Aspose.Slides for Java API Reference
description: Περιέχει τις ιδιότητες μορφοποίησης των TextFrames.
type: docs
url: /el/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Περιέχει τις ιδιότητες μορφοποίησης του TextFrame.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Επιστρέφει το στυλ του κειμένου. |
| [getMarginLeft()](#getMarginLeft--) | Επιστρέφει ή ορίζει το αριστερό περιθώριο (σε σημεία) σε ένα TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Επιστρέφει ή ορίζει το αριστερό περιθώριο (σε σημεία) σε ένα TextFrame. |
| [getMarginRight()](#getMarginRight--) | Επιστρέφει ή ορίζει το δεξιό περιθώριο (σε σημεία) σε ένα TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Επιστρέφει ή ορίζει το δεξιό περιθώριο (σε σημεία) σε ένα TextFrame. |
| [getMarginTop()](#getMarginTop--) | Επιστρέφει ή ορίζει το επάνω περιθώριο (σε σημεία) σε ένα TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Επιστρέφει ή ορίζει το επάνω περιθώριο (σε σημεία) σε ένα TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Επιστρέφει ή ορίζει το κάτω περιθώριο (σε σημεία) σε ένα TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Επιστρέφει ή ορίζει το κάτω περιθώριο (σε σημεία) σε ένα TextFrame. |
| [getWrapText()](#getWrapText--) | Αληθές αν το κείμενο είναι τυλιγμένο στα περιθώρια του TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Αληθές αν το κείμενο είναι τυλιγμένο στα περιθώρια του TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Επιστρέφει ή ορίζει το κάθετο αγκρόσυνομο κείμενο σε ένα TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Επιστρέφει ή ορίζει το κάθετο αγκρόσυνομο κείμενο σε ένα TextFrame. |
| [getCenterText()](#getCenterText--) | Εάν NullableBool.True τότε το κείμενο πρέπει να κεντράρεται οριζόντια στο πλαίσιο. |
| [setCenterText(byte value)](#setCenterText-byte-) | Εάν NullableBool.True τότε το κείμενο πρέπει να κεντράρεται οριζόντια στο πλαίσιο. |
| [getTextVerticalType()](#getTextVerticalType--) | Καθορίζει τον προσανατολισμό του κειμένου. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Καθορίζει τον προσανατολισμό του κειμένου. |
| [getAutofitType()](#getAutofitType--) | Επιστρέφει ή ορίζει τη λειτουργία autofit του κειμένου. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Επιστρέφει ή ορίζει τη λειτουργία autofit του κειμένου. |
| [getColumnCount()](#getColumnCount--) | Επιστρέφει ή ορίζει τον αριθμό των στηλών στην περιοχή κειμένου. |
| [setColumnCount(int value)](#setColumnCount-int-) | Επιστρέφει ή ορίζει τον αριθμό των στηλών στην περιοχή κειμένου. |
| [getColumnSpacing()](#getColumnSpacing--) | Επιστρέφει ή ορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε σημεία). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Επιστρέφει ή ορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε σημεία). |
| [getThreeDFormat()](#getThreeDFormat--) | Επιστρέφει το αντικείμενο ThreeDFormat που αντιπροσωπεύει τις ιδιότητες 3d εφέ για κείμενο. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Επιστρέφει ή ορίζει τη διατήρηση του κειμένου εκτός της 3D σκηνής εντελώς. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Επιστρέφει ή ορίζει τη διατήρηση του κειμένου εκτός της 3D σκηνής εντελώς. |
| [getRotationAngle()](#getRotationAngle--) | Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο μέσα στο περιθώριο. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο μέσα στο περιθώριο. |
| [getTransform()](#getTransform--) | Αποκτά ή ορίζει το σχήμα περιτύλιξης κειμένου. |
| [setTransform(byte value)](#setTransform-byte-) | Αποκτά ή ορίζει το σχήμα περιτύλιξης κειμένου. |
| [getEffective()](#getEffective--) | Αποκτά τα αποτελεσματικά δεδομένα μορφοποίησης του πλαισίου κειμένου με την κληρονομική εφαρμογή. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```


Επιστρέφει το στυλ του κειμένου. Μόνο για ανάγνωση [ITextStyle](../../com.aspose.slides/itextstyle).

**Επιστρέφει:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Επιστρέφει ή ορίζει το αριστερό περιθώριο (σε σημεία) σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


Επιστρέφει ή ορίζει το αριστερό περιθώριο (σε σημεία) σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Επιστρέφει ή ορίζει το δεξιό περιθώριο (σε σημεία) σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


Επιστρέφει ή ορίζει το δεξιό περιθώριο (σε σημεία) σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Επιστρέφει ή ορίζει το επάνω περιθώριο (σε σημεία) σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


Επιστρέφει ή ορίζει το επάνω περιθώριο (σε σημεία) σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Επιστρέφει ή ορίζει το κάτω περιθώριο (σε σημεία) σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


Επιστρέφει ή ορίζει το κάτω περιθώριο (σε σημεία) σε ένα TextFrame. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```


Αληθές αν το κείμενο είναι τυλιγμένο στα περιθώρια του TextFrame. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```


Αληθές αν το κείμενο είναι τυλιγμένο στα περιθώρια του TextFrame. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Επιστρέφει ή ορίζει το κάθετο αγκρόσυνομο κείμενο σε ένα TextFrame. Ανάγνωση/εγγραφή [TextAnchorType](../../com.aspose.slides/textanchortype).

**Επιστρέφει:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```


Επιστρέφει ή ορίζει το κάθετο αγκρόσυνομο κείμενο σε ένα TextFrame. Ανάγνωση/εγγραφή [TextAnchorType](../../com.aspose.slides/textanchortype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```


Εάν NullableBool.True τότε το κείμενο πρέπει να κεντράρεται οριζόντια στο πλαίσιο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```


Εάν NullableBool.True τότε το κείμενο πρέπει να κεντράρεται οριζόντια στο πλαίσιο. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Καθορίζει τον προσανατολισμό του κειμένου. Η προκύπτουσα τιμή της οπτικής περιστροφής του κειμένου συνοψίζεται από αυτήν την ιδιότητα και την προσαρμοσμένη γωνία στην ιδιότητα RotationAngle. Ανάγνωση/εγγραφή [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Επιστρέφει:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


Καθορίζει τον προσανατολισμό του κειμένου. Η προκύπτουσα τιμή της οπτικής περιστροφής του κειμένου συνοψίζεται από αυτήν την ιδιότητα και την προσαρμοσμένη γωνία στην ιδιότητα RotationAngle. Ανάγνωση/εγγραφή [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Επιστρέφει ή ορίζει τη λειτουργία autofit του κειμένου. Ανάγνωση/εγγραφή [TextAutofitType](../../com.aspose.slides/textautofittype).

**Επιστρέφει:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```


Επιστρέφει ή ορίζει τη λειτουργία autofit του κειμένου. Ανάγνωση/εγγραφή [TextAutofitType](../../com.aspose.slides/textautofittype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Επιστρέφει ή ορίζει τον αριθμό των στηλών στην περιοχή κειμένου. Η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα τεθεί σε μηδέν. Η τιμή 0 σημαίνει αόριστη τιμή. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```


Επιστρέφει ή ορίζει τον αριθμό των στηλών στην περιοχή κειμένου. Η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα τεθεί σε μηδέν. Η τιμή 0 σημαίνει αόριστη τιμή. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```


Επιστρέφει ή ορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε σημεία). Αυτό ισχύει μόνο όταν υπάρχει περισσότερη από 1 στήλη. Η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα τεθεί σε μηδέν. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```


Επιστρέφει ή ορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε σημεία). Αυτό ισχύει μόνο όταν υπάρχει περισσότερη από 1 στήλη. Η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα τεθεί σε μηδέν. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```


Επιστρέφει το αντικείμενο ThreeDFormat που αντιπροσωπεύει τις ιδιότητες 3d εφέ για κείμενο. Μόνο για ανάγνωση [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Ορίστε τη μετατροπή κειμένου
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Ορίστε την εξώθηση
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Ορίστε το περίγραμμα
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Ορίστε το βάθος
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Ορίστε το υλικό
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Ορίστε τον φωτισμό
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Ορίστε τον τύπο κάμερας
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```


Επιστρέφει ή ορίζει τη διατήρηση του κειμένου εκτός της 3D σκηνής εντελώς. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```


Επιστρέφει ή ορίζει τη διατήρηση του κειμένου εκτός της 3D σκηνής εντελώς. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```


Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο μέσα στο περιθώριο. Εάν δεν έχει καθοριστεί, χρησιμοποιείται η περιστροφή του συνοδευτικού σχήματος. Εάν καθοριστεί, εφαρμόζεται ανεξάρτητα από το σχήμα. Δηλαδή, το σχήμα μπορεί να έχει περιστροφή επιπλέον της περιστροφής του κειμένου. Η προκύπτουσα τιμή της οπτικής περιστροφής του κειμένου συνοψίζεται από αυτήν την ιδιότητα και τον προκαθορισμένο κάθετο τύπο στην ιδιότητα TextVerticalType. Ανάγνωση/εγγραφή float.

--------------------

> ```
> Σκεφτείτε την περίπτωση όπου ένα σχήμα έχει εφαρμοσμένη περιστροφή 90 μοιρών προς τα δεξιά. 
>  Επιπλέον, το ίδιο το κείμενο έχει περιστροφή -90 μοιρών 
>  αριστερόστροφα εφαρμόζεται σε αυτό. Τότε το προκύπτοντας σχήμα θα φαίνεται να
>  είναι περιστραμμένο, αλλά το κείμενο μέσα σε αυτό θα φαίνεται σαν να μην είχε περιστραφεί καθόλου.
> ```

**Επιστρέφει:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```


Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο μέσα στο περιθώριο. Εάν δεν έχει καθοριστεί, χρησιμοποιείται η περιστροφή του συνοδευτικού σχήματος. Εάν καθοριστεί, εφαρμόζεται ανεξάρτητα από το σχήμα. Δηλαδή, το σχήμα μπορεί να έχει περιστροφή επιπλέον της περιστροφής του κειμένου. Η προκύπτουσα τιμή της οπτικής περιστροφής του κειμένου συνοψίζεται από αυτήν την ιδιότητα και τον προκαθορισμένο κάθετο τύπο στην ιδιότητα TextVerticalType. Ανάγνωση/εγγραφή float.

--------------------

> ```
> Σκεφτείτε την περίπτωση όπου ένα σχήμα έχει εφαρμοσμένη περιστροφή 90 μοιρών δεξιόστροφα. 
>  Επιπλέον, το ίδιο το κείμενο έχει περιστροφή -90 μοιρών 
>  αριστερόστροφα εφαρμόζεται σε αυτό. Τότε το προκύπτον σχήμα θα φαίνεται να
>  είναι περιστραμμένο, αλλά το κείμενο μέσα σε αυτό θα φαίνεται σαν να μην είχε περιστραφεί καθόλου.
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```


Αποκτά ή ορίζει το σχήμα περιτύλιξης κειμένου. Ανάγνωση/εγγραφή [TextShapeType](../../com.aspose.slides/textshapetype).

**Επιστρέφει:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```


Αποκτά ή ορίζει το σχήμα περιτύλιξης κειμένου. Ανάγνωση/εγγραφή [TextShapeType](../../com.aspose.slides/textshapetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```


Αποκτά τα αποτελεσματικά δεδομένα μορφοποίησης του πλαισίου κειμένου με την κληρονομική εφαρμογή.

**Επιστρέφει:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - Ένα [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).