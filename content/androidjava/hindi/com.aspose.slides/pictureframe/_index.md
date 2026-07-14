---
title: PictureFrame
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: चित्र के भीतर एक फ्रेम का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/pictureframe/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)  
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

एक फ्रेम को चित्र के भीतर दर्शाता है।

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
>      // प्रेजेंटेशन संसाधनों में एक छवि जोड़ता है।
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // ऑडियो फ्रेम के लिए छवि सेट करता है।
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //परिवर्तित प्रेजेंटेशन को डिस्क पर सहेजता है।
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | शेप के लॉक लौटाता है। |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | चित्र फ्रेम के लिए PictureFillFormat ऑब्जेक्ट लौटाता है। |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | चित्र फ्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | चित्र फ्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | चित्र फ्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | चित्र फ्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। |
| [isCameo()](#isCameo--) | निर्धारित करता है कि PictureFrame Cameo ऑब्जेक्ट है या नहीं। |

### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

शेप के लॉक लौटाता है। केवल-पठन [IPictureFrameLock](../../com.aspose.slides/ipictureframelock)।

**वापसी:**  
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

PictureFrame के लिए AutoShape प्रकार को लौटाता है या सेट करता है। सेट [ShapeType](../../com.aspose.slides/shapetype) के सभी आइटम अनुमत हैं, सिवाय सभी प्रकार की लाइनों के:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5।

पढ़ें/लिखें [ShapeType](../../com.aspose.slides/shapetype)।

**वापसी:**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

PictureFrame के लिए AutoShape प्रकार को लौटाता है या सेट करता है। सेट [ShapeType](../../com.aspose.slides/shapetype) के सभी आइटम अनुमत हैं, सिवाय सभी प्रकार की लाइनों के:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5।

पढ़ें/लिखें [ShapeType](../../com.aspose.slides/shapetype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

चित्र फ्रेम के लिए PictureFillFormat ऑब्जेक्ट लौटाता है। केवल-पठन [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)।

**वापसी:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

चित्र फ्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। मान 1.0 100% के बराबर है। पढ़ें/लिखें float ।

**वापसी:**  
float

### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

चित्र फ्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। मान 1.0 100% के बराबर है। पढ़ें/लिखें float ।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

चित्र फ्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। मान 1.0 100% के बराबर है। पढ़ें/लिखें float ।

**वापसी:**  
float

### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

चित्र फ्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है या सेट करता है। मान 1.0 100% के बराबर है। पढ़ें/लिखें float ।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

निर्धारित करता है कि PictureFrame Cameo ऑब्जेक्ट है या नहीं। केवल-पठन boolean।

**वापसी:**  
boolean