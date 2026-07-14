---
title: IShape
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: एक स्लाइड पर आकार का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ishape/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

एक स्लाइड पर आकार का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | निर्धारित करता है कि आकार TextHolder है या नहीं। |
| [getPlaceholder()](#getPlaceholder--) | एक आकार के लिए प्लेसहोल्डर लौटाता है। |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले पर सेट करता है। |
| [removePlaceholder()](#removePlaceholder--) | निर्धारित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [getCustomData()](#getCustomData--) | आकार के कस्टम डेटा को लौटाता है। |
| [getRawFrame()](#getRawFrame--) | कच्चे आकार फ्रेम के गुणों को लौटाता या सेट करता है। |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | कच्चे आकार फ्रेम के गुणों को लौटाता या सेट करता है। |
| [getFrame()](#getFrame--) | आकार फ्रेम के गुणों को लौटाता या सेट करता है। |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | आकार फ्रेम के गुणों को लौटाता या सेट करता है। |
| [getLineFormat()](#getLineFormat--) | एक आकार के लिए लाइन फॉर्मेटिंग गुणों को सम्मिलित करने वाले LineFormat ऑब्जेक्ट को लौटाता है। |
| [getThreeDFormat()](#getThreeDFormat--) | एक आकार के लिए लाइन फॉर्मेटिंग गुणों को सम्मिलित करने वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। |
| [getEffectFormat()](#getEffectFormat--) | एक आकार पर लागू पिक्सेल इफ़ेक्ट्स को सम्मिलित करने वाले EffectFormat ऑब्जेक्ट को लौटाता है। |
| [getFillFormat()](#getFillFormat--) | एक आकार के लिए फ़िल फॉर्मेटिंग गुणों को सम्मिलित करने वाले FillFormat ऑब्जेक्ट को लौटाता है। |
| [getImage()](#getImage--) | आकार थंबनेल लौटाता है। |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | आकार थंबनेल लौटाता है। |
| [getHidden()](#getHidden--) | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। |
| [setHidden(boolean value)](#setHidden-boolean-) | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। |
| [getZOrderPosition()](#getZOrderPosition--) | z-क्रम में एक आकार की स्थिति लौटाता है। |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | आकार पर कनेक्शन साइटों की संख्या लौटाता है। |
| [getRotation()](#getRotation--) | निर्दिष्ट आकार के z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या को लौटाता या सेट करता है। |
| [setRotation(float value)](#setRotation-float-) | निर्दिष्ट आकार के z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या को लौटाता या सेट करता है। |
| [getX()](#getX--) | बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के x-निर्देशांक को प्राप्त या सेट करता है। |
| [setX(float value)](#setX-float-) | बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के x-निर्देशांक को प्राप्त या सेट करता है। |
| [getY()](#getY--) | बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के y-निर्देशांक को प्राप्त या सेट करता है। |
| [setY(float value)](#setY-float-) | बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के y-निर्देशांक को प्राप्त या सेट करता है। |
| [getWidth()](#getWidth--) | बिंदुओं में मापी गई आकार की चौड़ाई को प्राप्त या सेट करता है। |
| [setWidth(float value)](#setWidth-float-) | बिंदुओं में मापी गई आकार की चौड़ाई को प्राप्त या सेट करता है। |
| [getHeight()](#getHeight--) | बिंदुओं में मापी गई आकार की ऊँचाई को प्राप्त या सेट करता है। |
| [setHeight(float value)](#setHeight-float-) | बिंदुओं में मापी हुई आकार की ऊँचाई को प्राप्त या सेट करता है। |
| [getAlternativeText()](#getAlternativeText--) | आकार से जुड़ी वैकल्पिक पाठ को लौटाता या सेट करता है। |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | आकार से जुड़ी वैकल्पिक पाठ को लौटाता या सेट करता है। |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | आकार से जुड़ी वैकल्पिक पाठ का शीर्षक लौटाता या सेट करता है। |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | आकार से जुड़ी वैकल्पिक पाठ का शीर्षक लौटाता या सेट करता है। |
| [getName()](#getName--) | एक आकार का नाम लौटाता या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | एक आकार का नाम लौटाता या सेट करता है। |
| [isDecorative()](#isDecorative--) | ‘Mark as decorative’ विकल्प को पढ़ें/लिखें बूलियन के रूप में प्राप्त या सेट करता है। |
| [setDecorative(boolean value)](#setDecorative-boolean-) | ‘Mark as decorative’ विकल्प को पढ़ें/लिखें बूलियन के रूप में प्राप्त या सेट करता है। |
| [getShapeLock()](#getShapeLock--) | आकार के लॉक लौटाता है। |
| [getUniqueId()](#getUniqueId--) | ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए एक आंतरिक, प्रस्तुति-परिधि पहचानकर्ता लौटाता है। |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | एक स्लाइड-परिधि अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने देता है। |
| [isGrouped()](#isGrouped--) | निर्धारित करता है कि आकार समूहित है या नहीं। |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | प्रॉपर्टी निर्धारित करती है कि आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | प्रॉपर्टी निर्धारित करती है कि आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। |
| [getParentGroup()](#getParentGroup--) | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [getBasePlaceholder()](#getBasePlaceholder--) | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से आकार जो वर्तमान आकार से विरासत में मिला है)। |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

निर्धारित करता है कि आकार TextHolder है या नहीं। केवल-पढ़ने योग्य बूलियन।

**रिटर्न:**
boolean
### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

एक आकार के लिए प्लेसहोल्डर लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../../com.aspose.slides/iplaceholder)।

**रिटर्न:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)
### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

यदि कोई नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले पर सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | प्लेसहोल्डर से सामग्री कॉपी करने के लिए। |

**रिटर्न:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - नया [IPlaceholder](../../com.aspose.slides/iplaceholder).
### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

निर्धारित करता है कि यह आकार प्लेसहोल्डर नहीं है।

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

आकार के कस्टम डेटा को लौटाता है। केवल-पढ़ने योग्य [ICustomData](../../com.aspose.slides/icustomdata)।

**रिटर्न:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

कच्चे आकार फ्रेम के गुणों को लौटाता या सेट करता है। पढ़ें/लिखें [IShapeFrame](../../com.aspose.slides/ishapeframe)।

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //या
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //ऐसा कोड अस्पष्ट स्थितियों का कारण बन सकता है। इसलिए IShape.getFrame() के लिए अपरिभाषित मानों के उपयोग पर प्रतिबंध जोड़ दिया गया है। x, y, width, height, flipH, flipV और rotationAngle के मान परिभाषित होने चाहिए (Float.NaN या NullableBool.NotDefined नहीं)। ऊपर दिया गया उदाहरण कोड अब ArgumentException अपवाद फेंकता है।
>  //यह इन उपयोग मामलों पर लागू होता है:
>  IShape shape = ...;
>  shape.setFrame(...); // अपरिभाषित नहीं हो सकता
>  IShapeCollection shapes = ...;
>  // x, y, width, height पैरामीटर Float.NaN नहीं हो सकते:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape प्लेसहोल्डर से जुड़ा हुआ है
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // अब shape प्लेसहोल्डर से x, y, height, flipH, flipV मान विरासत में लेता है और width=100 तथा rotationAngle=0 को ओवरराइड करता है।
```

**रिटर्न:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

कच्चे आकार फ्रेम के गुणों को लौटाता या सेट करता है। पढ़ें/लिखें [IShapeFrame](../../com.aspose.slides/ishapeframe)।

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //या
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //ऐसी कोड अस्पष्ट स्थितियों का कारण बन सकता है। इसलिए IShape.getFrame() के लिए अपरिभाषित मानों के उपयोग पर प्रतिबंध जोड़ा गया है। x, y, width, height, flipH, flipV और rotationAngle के मान परिभाषित होने चाहिए (not Float.NaN or NullableBool.NotDefined). Example code above now throws ArgumentException exception.
>  //यह इन उपयोग मामलों पर लागू होता है:
>  IShape shape = ...;
>  shape.setFrame(...); // अपरिभाषित नहीं हो सकता
>  IShapeCollection shapes = ...;
>  // x, y, width, height पैरामीटर Float.NaN नहीं हो सकते:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape प्लेसहोल्डर से जुड़ा हुआ है
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // अब shape प्लेसहोल्डर से x, y, height, flipH, flipV मान विरासत में लेता है और width=100 तथा rotationAngle=0 को ओवरराइड करता है।
```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

आकार फ्रेम के गुणों को लौटाता या सेट करता है। पढ़ें/लिखें [IShapeFrame](../../com.aspose.slides/ishapeframe)।

--------------------

वापसी वाले IShapeFrame इंस्टेंस की प्रत्येक प्रॉपर्टी अपरिभाषित नहीं है (NaN या NotDefined नहीं)। असाइन किए गए IShapeFrame इंस्टेंस की प्रत्येक प्रॉपर्टी अपरिभाषित नहीं होनी चाहिए (NaN या NotDefined नहीं)। आप RawFrame इंस्टेंस की प्रॉपर्टीज़ के लिए अपरिभाषित मान सेट कर सकते हैं।

**रिटर्न:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

आकार फ्रेम के गुणों को लौटाता या सेट करता है। पढ़ें/लिखें [IShapeFrame](../../com.aspose.slides/ishapeframe)।

--------------------

वापसी वाले IShapeFrame इंस्टेंस की प्रत्येक प्रॉपर्टी अपरिभाषित नहीं है (NaN या NotDefined नहीं)। असाइन किए गए IShapeFrame इंस्टेंस की प्रत्येक प्रॉपर्टी अपरिभाषित नहीं होनी चाहिए (NaN या NotDefined नहीं)। आप RawFrame इंस्टेंस की प्रॉपर्टीज़ के लिए अपरिभाषित मान सेट कर सकते हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

LineFormat ऑब्जेक्ट को लौटाता है जिसमें आकार के लिए लाइन फॉर्मेटिंग गुण शामिल होते हैं। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

ThreeDFormat ऑब्जेक्ट को लौटाता है जिसमें आकार के लिए लाइन फॉर्मेटिंग गुण शामिल होते हैं। केवल-पढ़ने योग्य [IThreeDFormat](../../com.aspose.slides/ithreedformat)।

**रिटर्न:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

EffectFormat ऑब्जेक्ट को लौटाता है जिसमें आकार पर लागू पिक्सेल इफ़ेक्ट्स शामिल होते हैं। केवल-पढ़ने योग्य [IEffectFormat](../../com.aspose.slides/ieffectformat)।

**रिटर्न:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

FillFormat ऑब्जेक्ट को लौटाता है जिसमें आकार के लिए फ़िल फॉर्मेटिंग गुण शामिल होते हैं। केवल-पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**रिटर्न:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

आकार थंबनेल लौटाता है। ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार डिफ़ॉल्ट रूप से प्रयोग किया जाता है।

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - आकार थंबनेल।
### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

आकार थंबनेल लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bounds | int | आकार थंबनेल बाउंड्स प्रकार। |
| scaleX | float | X स्केल |
| scaleY | float | Y स्केल |

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - आकार थंबनेल या null यदि ShapeThumbnailBounds.Appearance प्रयोग किया गया हो और आकार के दृश्य तत्व न हों।
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

निर्धारित करता है कि आकार छिपा हुआ है या नहीं। पढ़ें/लिखें बूलियन।

**रिटर्न:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

निर्धारित करता है कि आकार छिपा हुआ है या नहीं। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

z-क्रम में एक आकार की स्थिति लौटाता है। Shapes[0] वापस z-क्रम के पीछे का आकार देता है, और Shapes[Shapes.Count - 1] सामने का आकार देता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int
### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

निर्दिष्ट आकार के z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या को लौटाता या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान घड़ी-विपरीत घुमाव दर्शाता है। पढ़ें/लिखें float।

--------------------

वापसी मान हमेशा परिभाषित रहता है (Float.NaN नहीं)। असाइन किया गया मान परिभाषित होना चाहिए (Float.NaN नहीं)। आप RawFrame इंस्टेंस की प्रॉपर्टीज़ के लिए अपरिभाषित मान सेट कर सकते हैं।

**रिटर्न:**
float
### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

निर्दिष्ट आकार के z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या को लौटाता या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान घड़ी-विपरीत घुमाव दर्शाता है। पढ़ें/लिखें float।

--------------------

वापसी मान हमेशा परिभाषित रहता है (Float.NaN नहीं)। असाइन किया गया मान परिभाषित होना चाहिए (Float.NaN नहीं)। आप RawFrame इंस्टेंस की प्रॉपर्टीज़ के लिए अपरिभाषित मान सेट कर सकते हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के x-निर्देशांक को प्राप्त या सेट करता है। पढ़ें/लिखें float।

--------------------

वापसी मान हमेशा परिभाषित रहता है और कभी Float.NaN नहीं होता। असाइन किया गया मान भी परिभाषित होना चाहिए; केवल RawFrame इंस्टेंस की प्रॉपर्टीज़ पर Float.NaN सेट करें।

**रिटर्न:**
float
### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के x-निर्देशांक को प्राप्त या सेट करता है। पढ़ें/लिखें float।

--------------------

वापसी मान हमेशा परिभाषित रहता है और कभी Float.NaN नहीं होता। असाइन किया गया मान भी परिभाषित होना चाहिए; केवल RawFrame इंस्टेंस की प्रॉपर्टीज़ पर Float.NaN सेट करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के y-निर्देशांक को प्राप्त या सेट करता है। पढ़ें/लिखें float।

--------------------

वापसी मान हमेशा परिभाषित रहता है और कभी Float.NaN नहीं होता। असाइन किया गया मान भी परिभाषित होना चाहिए; केवल RawFrame इंस्टेंस की प्रॉपर्टीज़ पर Float.NaN सेट करें।

**रिटर्न:**
float
### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के y-निर्देशांक को प्राप्त या सेट करता है। पढ़ें/लिखें float।

--------------------

वापसी मान हमेशा परिभाषित रहता है और कभी Float.NaN नहीं होता। असाइन किया गया मान भी परिभाषित होना चाहिए; केवल RawFrame इंस्टेंस की प्रॉपर्टीज़ पर Float.NaN सेट करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

बिंदुओं में मापी गई आकार की चौड़ाई को प्राप्त या सेट करता है। पढ़ें/लिखें float।

--------------------

वापसी मान हमेशा परिभाषित रहता है और कभी Float.NaN नहीं होता। असाइन किया गया मान भी परिभाषित होना चाहिए; केवल RawFrame इंस्टेंस की प्रॉपर्टीज़ पर Float.NaN सेट करें।

**रिटर्न:**
float
### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

बिंदुओं में मापी गई आकार की चौड़ाई को प्राप्त या सेट करता है। पढ़ें/लिखें float।

--------------------

वापसी मान हमेशा परिभाषित रहता है और कभी Float.NaN नहीं होता। असाइन किया गया मान भी परिभाषित होना चाहिए; केवल RawFrame इंस्टेंस की प्रॉपर्टीज़ पर Float.NaN सेट करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

बिंदुओं में मापी गई आकार की ऊँचाई को प्राप्त या सेट करता है। पढ़ें/लिखें float।

--------------------

वापसी मान हमेशा परिभाषित रहता है और कभी Float.NaN नहीं होता। असाइन किया गया मान भी परिभाषित होना चाहिए; केवल RawFrame इंस्टेंस की प्रॉपर्टीज़ पर Float.NaN सेट करें।

**रिटर्न:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

बिंदुओं में मापी गई आकार की ऊँचाई को प्राप्त या सेट करता है। पढ़ें/लिखें float।

--------------------

वापसी मान हमेशा परिभाषित रहता है और कभी Float.NaN नहीं होता। असाइन किया गया मान भी परिभाषित होना चाहिए; केवल RawFrame इंस्टेंस की प्रॉपर्टीज़ पर Float.NaN सेट करें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

आकार से जुड़ी वैकल्पिक पाठ को लौटाता या सेट करता है। पढ़ें/लिखें String।

**रिटर्न:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

आकार से जुड़ी वैकल्पिक पाठ को लौटाता या सेट करता है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

आकार से जुड़ी वैकल्पिक पाठ का शीर्षक लौटाता या सेट करता है। पढ़ें/लिखें String।

**रिटर्न:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

आकार से जुड़ी वैकल्पिक पाठ का शीर्षक लौटाता या सेट करता है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

एक आकार का नाम लौटाता या सेट करता है। पढ़ें/लिखें String।

**रिटर्न:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

एक आकार का नाम लौटाता या सेट करता है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

‘Mark as decorative’ विकल्प को पढ़ें/लिखें बूलियन के रूप में प्राप्त करता है।

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```

‘Mark as decorative’ विकल्प को पढ़ें/लिखें बूलियन के रूप में सेट करता है।

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)।

**रिटर्न:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

आंतरिक, प्रस्तुति-परिधि पहचानकर्ता लौटाता है जो ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए अभिप्रेत है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी नहीं माना जाना चाहिए। केवल-पढ़ने योग्य long। देखें \#getOfficeInteropShapeId.getOfficeInteropShapeId।

**रिटर्न:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

एक स्लाइड-परिधि अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पढ़ने योग्य long। देखें \#getUniqueId.getUniqueId।

**रिटर्न:**
long
### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य बूलियन।

--------------------

प्रॉपर्टी \#getParentGroup.getParentGroup पैरेंट GroupShape ऑब्जेक्ट लौटाता है यदि आकार समूहित है।

**रिटर्न:**
boolean
### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

प्रॉपर्टी निर्धारित करती है कि आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें/लिखें [BlackWhiteMode](../../com.aspose.slides/blackwhitemode)।

**रिटर्न:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

प्रॉपर्टी निर्धारित करती है कि आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें/लिखें [BlackWhiteMode](../../com.aspose.slides/blackwhitemode)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../../com.aspose.slides/igroupshape)।

--------------------

प्रॉपर्टी \#isGrouped.isGrouped निर्धारित करती है कि आकार समूहित है या नहीं।

**रिटर्न:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG जनरेशन विकल्प |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से आकार जो वर्तमान आकार से विरासत में मिला है)।

--------------------

> ```
> // प्लेसहोल्डर आकार के सभी (master/layout/slide) एनिमेटेड इफ़ेक्ट्स प्राप्त करें
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape = slide.getShapes().get_Item(0);
>      IEffect[] shapeEffects = slide.getTimeline().getMainSequence().getEffectsByShape(shape);
>      IShape layoutShape = shape.getBasePlaceholder();
>      IEffect[] layoutShapeEffects = slide.getLayoutSlide().getTimeline().getMainSequence().getEffectsByShape(layoutShape);
>      IShape masterShape = layoutShape.getBasePlaceholder();
>      IEffect[] masterShapeEffects = slide.getLayoutSlide().getMasterSlide().getTimeline().getMainSequence().getEffectsByShape(masterShape);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

यदि वर्तमान आकार विरासत में नहीं मिला है तो null लौटाया जाता है।

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape)