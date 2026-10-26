---
title: ThreeDFormat
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά 3-D ιδιότητες.
type: docs
url: /el/com.aspose.slides/threedformat/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IThreeDFormat](../../com.aspose.slides/ithreedformat), [com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public final class ThreeDFormat extends PVIObject implements IThreeDFormat, IThreeDParamSource
```

Αναπαριστά 3-D ιδιότητες.

--------------------

> ```
> The following example shows how to add 3D shape in PowerPoint Presentation.
>  
>  // Δημιουργεί ένα αντικείμενο της κλάσης Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Προσθέτει ένα σχήμα χρησιμοποιώντας τη μέθοδο AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
>      // Ορίζει το TextFrame και τις ιδιότητές του.
>      shape.getTextFrame().setText("3D");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Ορίζει τις ιδιότητες ThreeDFormat.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Αποθηκεύει το αρχείο Presentation.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply Gradient affect to 3D shape in PowerPoint Presentation.
>  
>  // Δημιουργεί ένα αντικείμενο της κλάσης Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Προσθέτει ένα σχήμα χρησιμοποιώντας τη μέθοδο AddAutoShape.
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Ορίζει το TextFrame και τις ιδιότητές του.
>      shape.getTextFrame().setText("3D Gradient");
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(64);
>      // Ρυθμίζει το FillFormat.FillType σε FillType.Gradient και ορίζει τις ιδιότητες gradient.
>      shape.getFillFormat().setFillType(FillType.Gradient);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(0, Color.BLUE);
>      shape.getFillFormat().getGradientFormat().getGradientStops().add(100, Color.ORANGE);
>      // Ορίζει τις ιδιότητες ThreeDFormat.
>      shape.getThreeDFormat().getCamera().setCameraType(CameraPresetType.OrthographicFront);
>      shape.getThreeDFormat().getCamera().setRotation(20, 30, 40);
>      shape.getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Flat);
>      shape.getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      shape.getThreeDFormat().setMaterial(MaterialPresetType.Flat);
>      shape.getThreeDFormat().setExtrusionHeight(100);
>      shape.getThreeDFormat().getExtrusionColor().setColor(Color.BLUE);
>      // Αποθηκεύει το αρχείο Presentation.
>      pres.save("sandbox_3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to apply 3D effect on text. For creating a 3D text its possible to use WordArt transform effect.
>  
>  // Δημιουργεί ένα αντικείμενο της κλάσης Presentation.
>  Presentation pres = new Presentation();
>  try {
>      // Προσθέτει ένα σχήμα χρησιμοποιώντας τη μέθοδο AddAutoShape.
>       IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
>      // Ορίζει το TextFrame και τις ιδιότητές του.
>      shape.getTextFrame().setText("3D Text");
>      // Ρυθμίζει το FillFormat.FillType σε FillType.NoFill
>      shape.getFillFormat().setFillType(FillType.NoFill);
>      shape.getLineFormat().getFillFormat().setFillType(FillType.NoFill);
>      // Ρυθμίζει το Portion του TextFrame και τις ιδιότητες του PortionFormat
>      Portion portion = (Portion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Pattern);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getForeColor().setColor(Color.ORANGE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().getBackColor().setColor(Color.WHITE);
>      portion.getPortionFormat().getFillFormat().getPatternFormat().setPatternStyle(PatternStyle.LargeGrid);
>      shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getDefaultPortionFormat().setFontHeight(128);
>      ITextFrame textFrame = shape.getTextFrame();
>      // Ρύθμιση του μετασχηματισμού WordArt "Arch Up".
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUp);
>      // Ορίζει τις ιδιότητες ThreeDFormat του ITextFrame.
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(3.5f);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>      // Αποθηκεύει το αρχείο Presentation.
>      pres.save("text3d.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getContourWidth()](#getContourWidth--) | Επιστρέφει ή ορίζει το πλάτος ενός 3D περιγράμματος. |
| [setContourWidth(double value)](#setContourWidth-double-) | Επιστρέφει ή ορίζει το πλάτος ενός 3D περιγράμματος. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Επιστρέφει ή ορίζει το ύψος ενός εφέ εξώθησης. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Επιστρέφει ή ορίζει το ύψος ενός εφέ εξώθησης. |
| [getDepth()](#getDepth--) | Επιστρέφει ή ορίζει το βάθος ενός 3D σχήματος. |
| [setDepth(double value)](#setDepth-double-) | Επιστρέφει ή ορίζει το βάθος ενός 3D σχήματος. |
| [getBevelTop()](#getBevelTop--) | Επιστρέφει ή ορίζει τον τύπο ενός άνω 3D κοψιού. |
| [getBevelBottom()](#getBevelBottom--) | Επιστρέφει ή ορίζει τον τύπο ενός κάτω 3D κοψιού. |
| [getContourColor()](#getContourColor--) | Επιστρέφει ή ορίζει το χρώμα ενός περιγράμματος. |
| [getExtrusionColor()](#getExtrusionColor--) | Επιστρέφει ή ορίζει το χρώμα μιας εξώθησης. |
| [getCamera()](#getCamera--) | Επιστρέφει ή ορίζει τις ρυθμίσεις μιας κάμερας. |
| [getLightRig()](#getLightRig--) | Επιστρέφει ή ορίζει τον τύπο ενός φωτός. |
| [getMaterial()](#getMaterial--) | Επιστρέφει ή ορίζει τον τύπο ενός υλικού. |
| [setMaterial(int value)](#setMaterial-int-) | Επιστρέφει ή ορίζει τον τύπο ενός υλικού. |
| [getEffective()](#getEffective--) | Λαμβάνει αποτελεσματικά δεδομένα μορφοποίησης 3-D με την κληρονομικότητα εφαρμοσμένη. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο ανάγνωση long.

**Επιστρέφει:**
long
### getContourWidth() {#getContourWidth--}
```
public final double getContourWidth()
```

Επιστρέφει ή ορίζει το πλάτος ενός 3D περιγράμματος. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public final void setContourWidth(double value)
```

Επιστρέφει ή ορίζει το πλάτος ενός 3D περιγράμματος. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public final double getExtrusionHeight()
```

Επιστρέφει ή ορίζει το ύψος ενός εφέ εξώθησης. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public final void setExtrusionHeight(double value)
```

Επιστρέφει ή ορίζει το ύψος ενός εφέ εξώθησης. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public final double getDepth()
```

Επιστρέφει ή ορίζει το βάθος ενός 3D σχήματος. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setDepth(double value) {#setDepth-double-}
```
public final void setDepth(double value)
```

Επιστρέφει ή ορίζει το βάθος ενός 3D σχήματος. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public final IShapeBevel getBevelTop()
```

Επιστρέφει ή ορίζει τον τύπο ενός άνω 3D κοψιού. Μόνο ανάγνωση [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Επιστρέφει:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public final IShapeBevel getBevelBottom()
```

Επιστρέφει ή ορίζει τον τύπο ενός κάτω 3D κοψιού. Μόνο ανάγνωση [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Επιστρέφει:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public final IColorFormat getContourColor()
```

Επιστρέφει ή ορίζει το χρώμα ενός περιγράμματος. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public final IColorFormat getExtrusionColor()
```

Επιστρέφει ή ορίζει το χρώμα μιας εξώθησης. Μόνο ανάγνωση [IColorFormat](../../com.aspose.slides/icolorformat).

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public final ICamera getCamera()
```

Επιστρέφει ή ορίζει τις ρυθμίσεις μιας κάμερας. Μόνο ανάγνωση [ICamera](../../com.aspose.slides/icamera).

**Επιστρέφει:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public final ILightRig getLightRig()
```

Επιστρέφει ή ορίζει τον τύπο ενός φωτός. Μόνο ανάγνωση [ILightRig](../../com.aspose.slides/ilightrig).

**Επιστρέφει:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public final int getMaterial()
```

Επιστρέφει ή ορίζει τον τύπο ενός υλικού. Ανάγνωση/εγγραφή [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Επιστρέφει:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public final void setMaterial(int value)
```

Επιστρέφει ή ορίζει τον τύπο ενός υλικού. Ανάγνωση/εγγραφή [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IThreeDFormatEffectiveData getEffective()
```

Λαμβάνει αποτελεσματικά δεδομένα μορφοποίησης 3-D με την κληρονομικότητα εφαρμοσμένη.

--------------------

> ```
> This example demonstrates how to get effective properties for camera, light rig and shape's top bevel.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try 
>  {
>      IThreeDFormatEffectiveData threeDEffectiveData = pres.getSlides().get_Item(0).getShapes().get_Item(0).getThreeDFormat().getEffective();
>      System.out.println("= Effective camera properties =");
>      System.out.println("Type: " + threeDEffectiveData.getCamera().getCameraType());
>      System.out.println("Field of view: " + threeDEffectiveData.getCamera().getFieldOfViewAngle());
>      System.out.println("Zoom: " + threeDEffectiveData.getCamera().getZoom());
>      System.out.println("= Effective light rig properties =");
>      System.out.println("Type: " + threeDEffectiveData.getLightRig().getLightType());
>      System.out.println("Direction: " + threeDEffectiveData.getLightRig().getDirection());
>      System.out.println("= Effective shape's top face relief properties =");
>      System.out.println("Type: " + threeDEffectiveData.getBevelTop().getBevelType());
>      System.out.println("Width: " + threeDEffectiveData.getBevelTop().getWidth());
>      System.out.println("Height: " + threeDEffectiveData.getBevelTop().getHeight());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - Ένα [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).