---
title: TextFrameFormat
second_title: Aspose.Slides για την αναφορά API Java
description: Περιέχει τις ιδιότητες formatTextFrameFormatting των TextFrames.
type: docs
url: /el/com.aspose.slides/textframeformat/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

Περιέχει τις ιδιότητες formatTextFrameFormatting του TextFrame.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Αρχικοποιεί ένα νέο αντίτυπο της κλάσης [TextFrameFormat](../../com.aspose.slides/textframeformat). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Επιστρέφει το στυλ του κειμένου. |
| [getThreeDFormat()](#getThreeDFormat--) | Επιστρέφει το αντικείμενο ThreeDFormat που αντιπροσωπεύει τις ιδιότητες 3δ εφέ για ένα κείμενο. |
| [getMarginLeft()](#getMarginLeft--) | Επιστρέφει ή ορίζει το αριστερό περιθώριο (points) σε ένα TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Επιστρέφει ή ορίζει το αριστερό περιθώριο (points) σε ένα TextFrame. |
| [getMarginRight()](#getMarginRight--) | Επιστρέφει ή ορίζει το δεξί περιθώριο (points) σε ένα TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Επιστρέφει ή ορίζει το δεξί περιθώριο (points) σε ένα TextFrame. |
| [getMarginTop()](#getMarginTop--) | Επιστρέφει ή ορίζει το άνω περιθώριο (points) σε ένα TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Επιστρέφει ή ορίζει το άνω περιθώριο (points) σε ένα TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Επιστρέφει ή ορίζει το κάτω περιθώριο (points) σε ένα TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Επιστρέφει ή ορίζει το κάτω περιθώριο (points) σε ένα TextFrame. |
| [getWrapText()](#getWrapText--) | True αν το κείμενο είναι αναδιπλωμένο στα περιθώρια του TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | True αν το κείμενο είναι αναδιπλωμένο στα περιθώρια του TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Επιστρέφει ή ορίζει το κάθετο άγκυρο κειμένου σε ένα TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Επιστρέφει ή ορίζει το κάθετο άγκυρο κειμένου σε ένα TextFrame. |
| [getCenterText()](#getCenterText--) | Αν NullableBool.True τότε το κείμενο πρέπει να κεντραριστεί οριζόντια στο κουτί. |
| [setCenterText(byte value)](#setCenterText-byte-) | Αν NullableBool.True τότε το κείμενο πρέπει να κεντραριστεί οριζόντια στο κουτί. |
| [getTextVerticalType()](#getTextVerticalType--) | Καθορίζει τον προσανατολισμό του κειμένου. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Καθορίζει τον προσανατολισμό του κειμένου. |
| [getAutofitType()](#getAutofitType--) | Επιστρέφει ή ορίζει τη λειτουργία autofit του κειμένου. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Επιστρέφει ή ορίζει τη λειτουργία autofit του κειμένου. |
| [getColumnCount()](#getColumnCount--) | Επιστρέφει ή ορίζει τον αριθμό των στηλών στην περιοχή κειμένου. |
| [setColumnCount(int value)](#setColumnCount-int-) | Επιστρέφει ή ορίζει τον αριθμό των στηλών στην περιοχή κειμένου. |
| [getColumnSpacing()](#getColumnSpacing--) | Επιστρέφει ή ορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε points). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Επιστρέφει ή ορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε points). |
| [getRotationAngle()](#getRotationAngle--) | Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο εντός του πλαισίου. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο εντός του πλαισίου. |
| [getTransform()](#getTransform--) | Λαμβάνει ή ορίζει το σχήμα αναδίπλωσης κειμένου. |
| [setTransform(byte value)](#setTransform-byte-) | Λαμβάνει ή ορίζει το σχήμα αναδίπλωσης κειμένου. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Λαμβάνει ή ορίζει τη διατήρηση του κειμένου επίπεδης ακόμη και αν εφαρμοστεί εφέ 3-Δ Περιστροφής. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Λαμβάνει ή ορίζει τη διατήρηση του κειμένου επίπεδης ακόμη και αν εφαρμοστεί εφέ 3-Δ Περιστροφής. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης πλαισίου κειμένου με την κληρονομικότητα εφαρμόστηκε. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

Αρχικοποιεί ένα νέο αντίτυπο της κλάσης [TextFrameFormat](../../com.aspose.slides/textframeformat).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

Επιστρέφει το στυλ του κειμένου. Μόνο για ανάγνωση [ITextStyle](../../com.aspose.slides/itextstyle).

**Επιστρέφει:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

Επιστρέφει το αντικείμενο ThreeDFormat που αντιπροσωπεύει τις ιδιότητες 3δ εφέ για ένα κείμενο. Μόνο για ανάγνωση [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Ορισμός μετασχηματισμού κειμένου
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Ορισμός εξώθησης
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Ορισμός περιγράμματος
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Ορισμός βάθους
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Ορισμός υλικού
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Ορισμός φωτισμού
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Ορισμός τύπου κάμερας
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Επιστρέφει ή ορίζει το αριστερό περιθώριο (points) σε ένα TextFrame. Αναγνώγωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Επιστρέφει ή ορίζει το αριστερό περιθώριο (points) σε ένα TextFrame. Αναγνώγωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Επιστρέφει ή ορίζει το δεξί περιθώριο (points) σε ένα TextFrame. Αναγνώγωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Επιστρέφει ή ορίζει το δεξί περιθώριο (points) σε ένα TextFrame. Αναγνώγωση/εγγραφή double.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Επιστρέφει ή ορίζει το άνω περιθώριο (points) σε ένα TextFrame. Αναγνώγωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Επιστρέφει ή ορίζει το άνω περιθώριο (points) σε ένα TextFrame. Αναγνώγωση/εγγραφή double.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Επιστρέφει ή ορίζει το κάτω περιθώριο (points) σε ένα TextFrame. Αναγνώγωση/εγγραφή double.

**Επιστρέφει:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Επιστρέφει ή ορίζει το κάτω περιθώριο (points) σε ένα TextFrame. Αναγνώγωση/εγγραφή double.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

True αν το κείμενο είναι αναδιπλωμένο στα περιθώρια του TextFrame. Αναγνώγωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

True αν το κείμενο είναι αναδιπλωμένο στα περιθώρια του TextFrame. Αναγνώγωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

Επιστρέφει ή ορίζει το κάθετο άγκυρο κειμένου σε ένα TextFrame. Αναγνώγωση/εγγραφή [TextAnchorType](../../com.aspose.slides/textanchortype).

**Επιστρέφει:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

Επιστρέφει ή ορίζει το κάθετο άγκυρο κειμένου σε ένα TextFrame. Αναγνώγωση/εγγραφή [TextAnchorType](../../com.aspose.slides/textanchortype).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

Αν NullableBool.True τότε το κείμενο πρέπει να κεντραριστεί οριζόντια στο κουτί. Αναγνώγωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

Αν NullableBool.True τότε το κείμενο πρέπει να κεντραριστεί οριζόντια στο κουτί. Αναγνώγωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Καθορίζει τον προσανατολισμό του κειμένου. Η προκύπτουσα τιμή της οπτικής περιστροφής του κειμένου συνοψίζεται από αυτή την ιδιότητα και την προσαρμοσμένη γωνία στην ιδιότητα RotationAngle. Αναγνώγωση/εγγραφή [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Επιστρέφει:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Καθορίζει τον προσανατολισμό του κειμένου. Η προκύπτουσα τιμή της οπτικής περιστροφής του κειμένου συνοψίζεται από αυτή την ιδιότητα και την προσαρμοσμένη γωνία στην ιδιότητα RotationAngle. Αναγνώγωση/εγγραφή [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

Επιστρέφει ή ορίζει τη λειτουργία autofit του κειμένου. Αναγνώγωση/εγγραφή [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

Επιστρέφει ή ορίζει τη λειτουργία autofit του κειμένου. Αναγνώγωση/εγγραφή [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Επιστρέφει ή ορίζει τον αριθμό των στηλών στην περιοχή κειμένου. Αυτή η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί στο μηδέν. Η τιμή 0 σημαίνει ακαθόριστη τιμή. Αναγνώγωση/εγγραφή int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

Επιστρέφει ή ορίζει τον αριθμό των στηλών στην περιοχή κειμένου. Αυτή η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί στο μηδέν. Η τιμή 0 σημαίνει ακαθόριστη τιμή. Αναγνώγωση/εγγραφή int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

Επιστρέφει ή ορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε points). Αυτό πρέπει να ισχύει μόνο όταν υπάρχει περισσότερη από 1 στήλη. Η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί στο μηδέν. Αναγνώγωση/εγγραφή double.

**Επιστρέφει:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

Επιστρέφει ή ορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε points). Αυτό πρέπει να ισχύει μόνο όταν υπάρχει περισσότερη από 1 στήλη. Η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί στο μηδέν. Αναγνώγωση/εγγραφή double.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο εντός του πλαισίου. Αν δεν καθοριστεί, χρησιμοποιείται η περιστροφή του συνοδευτικού σχήματος. Αν καθοριστεί, τότε αυτή εφαρμόζεται ανεξάρτητα από το σχήμα. Δηλαδή το σχήμα μπορεί να έχει περιστροφή επιπλέον της περιστροφής που εφαρμόζεται στο ίδιο το κείμενο. Η προκύπτουσα τιμή της οπτικής περιστροφής του κειμένου συνοψίζεται από αυτή την ιδιότητα και τον προδιαγεγραμμένο κάθετο τύπο στην ιδιότητα TextVerticalType. Αναγνώγωση/εγγραφή float.

--------------------

> ```
> Θεωρήστε την περίπτωση όπου ένα σχήμα έχει εφαρμοσμένη περιστροφή 90 μοιρών δεξιόστροφα. 
>  Επιπλέον, το ίδιο το σώμα κειμένου έχει περιστροφή -90 μοιρών 
>  αριστερόστροφα εφαρμοσμένη σε αυτό. Στη συνέχεια το προκύπτον σχήμα θα φαίνεται να
>  είναι περιστραμμένο, αλλά το κείμενο μέσα σε αυτό θα φαίνεται σαν να δεν είχε περιστραφεί καθόλου.
```

**Επιστρέφει:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο εντός του πλαισίου. Αν δεν καθοριστεί, χρησιμοποιείται η περιστροφή του συνοδευτικού σχήματος. Αν καθοριστεί, τότε αυτή εφαρμόζεται ανεξάρτητα από το σχήμα. Δηλαδή το σχήμα μπορεί να έχει περιστροφή επιπλέον της περιστροφής που εφαρμόζεται στο ίδιο το κείμενο. Η προκύπτουσα τιμή της οπτικής περιστροφής του κειμένου συνοψίζεται από αυτή την ιδιότητα και τον προδιαγεγραμμένο κάθετο τύπο στην ιδιότητα TextVerticalType. Αναγνώγωση/εγγραφή float.

--------------------

> ```
> Θεωρήστε την περίπτωση όπου ένα σχήμα έχει εφαρμοσμένη περιστροφή 90 μοιρών δεξιόστροφα. 
>  Επιπλέον, το ίδιο το σώμα κειμένου έχει περιστροφή -90 μοιρών 
>  αριστερόστροφα εφαρμοσμένη σε αυτό. Τότε το προκύπτον σχήμα θα φαίνεται να είναι περιστραμμένο, αλλά το κείμενο μέσα σε αυτό θα φαίνεται σαν να δεν είχε περιστραφεί καθόλου.
```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public final byte getTransform()
```

Λαμβάνει ή ορίζει το σχήμα αναδίπλωσης κειμένου. Αναγνώγωση/εγγραφή [TextShapeType](../../com.aspose.slides/textshapetype).

**Επιστρέφει:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

Λαμβάνει ή ορίζει το σχήμα αναδίπλωσης κειμένου. Αναγνώγωση/εγγραφή [TextShapeType](../../com.aspose.slides/textshapetype).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

Λαμβάνει ή ορίζει τη διατήρηση του κειμένου επίπεδης ακόμη και αν εφαρμοστεί εφέ 3-Δ Περιστροφής. Αναγνώγωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

Λαμβάνει ή ορίζει τη διατήρηση του κειμένου επίπεδης ακόμη και αν εφαρμοστεί εφέ 3-Δ Περιστροφής. Αναγνώγωση/εγγραφή boolean.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης πλαισίου κειμένου με την κληρονομικότητα εφαρμοσμένη.

--------------------

> ```
> This example demonstrates getting some of effective text frame formatting properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.getTextFrame().getTextFrameFormat().getEffective();
>     
>      System.out.println("Anchoring type: " + effectiveTextFrameFormat.getAnchoringType());
>      System.out.println("Autofit type: " + effectiveTextFrameFormat.getAutofitType());
>      System.out.println("Text vertical type: " + effectiveTextFrameFormat.getTextVerticalType());
>      System.out.println("Margins");
>      System.out.println("   Left: " + effectiveTextFrameFormat.getMarginLeft());
>      System.out.println("   Top: " + effectiveTextFrameFormat.getMarginTop());
>      System.out.println("   Right: " + effectiveTextFrameFormat.getMarginRight());
>      System.out.println("   Bottom: " + effectiveTextFrameFormat.getMarginBottom());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).