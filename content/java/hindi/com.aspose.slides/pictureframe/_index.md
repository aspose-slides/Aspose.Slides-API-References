---
title: PictureFrame
second_title: Aspose.Slides जावा API संदर्भ
description: एक फ्रेम का प्रतिनिधित्व करता है जिसमें अंदर एक चित्र होता है।
type: docs
url: /hi/com.aspose.slides/pictureframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Represents a frame with a picture inside.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // एक निर्दिष्ट स्थिति और आकार के साथ स्लाइड में ऑडियो फ्रेम जोड़ता है।
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // प्रस्तुति संसाधनों में एक छवि जोड़ता है।
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // ऑडियो फ्रेम के लिए छवि सेट करता है।
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //संशोधित प्रस्तुति को डिस्क पर सहेजता है
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## मेथड्स

| Method | Description |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | shape के लॉक लौटाता है। |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | एक picture frame के लिए PictureFillFormat ऑब्जेक्ट लौटाता है। |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | picture frame की ऊँचाई का स्केल (मूल चित्र आकार के सापेक्ष) लौटाता है या सेट करता है। |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | picture frame की ऊँचाई का स्केल (मूल चित्र आकार के सापेक्ष) लौटाता है या सेट करता है। |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | picture frame की चौड़ाई का स्केल (मूल चित्र आकार के सापेक्ष) लौटाता है या सेट करता है। |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | picture frame की चौड़ाई का स्केल (मूल चित्र आकार के सापेक्ष) लौटाता है या सेट करता है। |
| [isCameo()](#isCameo--) | निर्धारित करता है कि PictureFrame एक Cameo ऑब्जेक्ट है या नहीं। |

### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

shape के लॉक लौटाता है। केवल-पढ़ने योग्य [IPictureFrameLock](../../com.aspose.slides/ipictureframelock)।

**वापसी:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

AutoShape प्रकार को PictureFrame के लिए लौटाता है या सेट करता है। सेट [ShapeType](../../com.aspose.slides/shapetype) के सभी आइटम अनुमति प्राप्त हैं, सिवाय सभी प्रकार की लाइनों के:

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

पढ़ने/लिखने योग्य [ShapeType](../../com.aspose.slides/shapetype)।

**वापसी:**
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

AutoShape प्रकार को PictureFrame के लिए लौटाता है या सेट करता है। सेट [ShapeType](../../com.aspose.slides/shapetype) के सभी आइटम अनुमति प्राप्त हैं, सिवाय सभी प्रकार की लाइनों के:

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

पढ़ने/लिखने योग्य [ShapeType](../../com.aspose.slides/shapetype)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

picture frame के लिए PictureFillFormat ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)।

**वापसी:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

picture frame की ऊँचाई का स्केल (मूल चित्र आकार के सापेक्ष) लौटाता है या सेट करता है। मान 1.0 100% के अनुरूप है। पढ़ने/लिखने योग्य  float .

**वापसी:**
float

### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

picture frame की ऊँचाई का स्केल (मूल चित्र आकार के सापेक्ष) लौटाता है या सेट करता है। मान 1.0 100% के अनुरूप है। पढ़ने/लिखने योग्य  float .

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

picture frame की चौड़ाई का स्केल (मूल चित्र आकार के सापेक्ष) लौटाता है या सेट करता है। मान 1.0 100% के अनुरूप है। पढ़ने/लिखने योग्य  float .

**वापसी:**
float

### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

picture frame की चौड़ाई का स्केल (मूल चित्र आकार के सापेक्ष) लौटाता है या सेट करता है। मान 1.0 100% के अनुरूप है। पढ़ने/लिखने योग्य  float .

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

निर्धारित करता है कि PictureFrame एक Cameo ऑब्जेक्ट है या नहीं। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean