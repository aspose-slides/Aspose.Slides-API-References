---
title: PictureFrame
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά ένα πλαίσιο με μια εικόνα μέσα.
type: docs
url: /el/com.aspose.slides/pictureframe/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Αναπαριστά ένα πλαίσιο με μια εικόνα μέσα.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Προσθέτει ένα πλαίσιο ήχου στη διαφάνεια με καθορισμένη θέση και μέγεθος.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Προσθέτει μια εικόνα στους πόρους της παρουσίασης.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Ορίζει την εικόνα για το πλαίσιο ήχου.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Αποθηκεύει την τροποποιημένη παρουσίαση στο δίσκο
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## Methods

| Method | Description |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Επιστρέφει τις κλειδώσεις του σχήματος. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Επιστρέφει το αντικείμενο PictureFillFormat για ένα πλαίσιο εικόνας. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Επιστρέφει ή ορίζει την κλίμακα του ύψους (σχετικά με το αρχικό μέγεθος εικόνας) του πλαισίου εικόνας. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Επιστρέφει ή ορίζει την κλίμακα του ύψους (σχετικά με το αρχικό μέγεθος εικόνας) του πλαισίου εικόνας. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Επιστρέφει ή ορίζει την κλίμακα του πλάτους (σχετικά με το αρχικό μέγεθος εικόνας) του πλαισίου εικόνας. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Επιστρέφει ή ορίζει την κλίμακα του πλάτους (σχετικά με το αρχικό μέγεθος εικόνας) του πλαισίου εικόνας. |
| [isCameo()](#isCameo--) | Καθορίζει εάν το PictureFrame είναι αντικείμενο Cameo ή όχι. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```


Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο για ανάγνωση [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Returns:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Επιστρέφει ή ορίζει τον τύπο AutoShape για ένα PictureFrame. Επιτρέπονται όλα τα στοιχεία του συνόλου [ShapeType](../../com.aspose.slides/shapetype), εκτός από όλους τους τύπους γραμμών:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

Ανάγνωση/εγγραφή [ShapeType](../../com.aspose.slides/shapetype).

**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Επιστρέφει ή ορίζει τον τύπο AutoShape για ένα PictureFrame. Επιτρέπονται όλα τα στοιχεία του συνόλου [ShapeType](../../com.aspose.slides/shapetype), εκτός από όλους τους τύπους γραμμών:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

Ανάγνωση/εγγραφή [ShapeType](../../com.aspose.slides/shapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```


Επιστρέφει το αντικείμενο PictureFillFormat για ένα πλαίσιο εικόνας. Μόνο για ανάγνωση [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returns:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```


Επιστρέφει ή ορίζει την κλίμακα του ύψους (σχετικά με το αρχικό μέγεθος εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή  float .

**Returns:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```


Επιστρέφει ή ορίζει την κλίμακα του ύψους (σχετικά με το αρχικό μέγεθος εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```


Επιστρέφει ή ορίζει την κλίμακα του πλάτους (σχετικά με το αρχικό μέγεθος εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή  float .

**Returns:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```


Επιστρέφει ή ορίζει την κλίμακα του πλάτους (σχετικά με το αρχικό μέγεθος εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```


Καθορίζει εάν το PictureFrame είναι αντικείμενο Cameo ή όχι. Μόνο για ανάγνωση boolean.

**Returns:**
boolean