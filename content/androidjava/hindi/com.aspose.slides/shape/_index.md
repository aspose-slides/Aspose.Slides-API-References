---
title: Shape
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: स्लाइड पर एक आकार का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/shape/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject  
```
public class Shape implements IShape, IDOMObject
```

एक स्लाइड पर आकार का प्रतिनिधित्व करता है।  
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। |
| [getPlaceholder()](#getPlaceholder--) | एक आकार के लिए प्लेसहोल्डर लौटाता है। |
| [removePlaceholder()](#removePlaceholder--) | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट वाले के लिए प्लेसहोल्डर गुण सेट करता है। |
| [getBasePlaceholder()](#getBasePlaceholder--) | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से आकार जिससे वर्तमान आकार विरासत में मिला है)। |
| [getCustomData()](#getCustomData--) | आकार का कस्टम डेटा लौटाता है। |
| [getRawFrame()](#getRawFrame--) | रॉ आकार फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | रॉ आकार फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। |
| [getFrame()](#getFrame--) | आकार फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | आकार फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। |
| [getLineFormat()](#getLineFormat--) | एक LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। |
| [getThreeDFormat()](#getThreeDFormat--) | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए 3D प्रभाव प्रॉपर्टीज़ हैं। |
| [getEffectFormat()](#getEffectFormat--) | एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल प्रभाव होते हैं। |
| [getFillFormat()](#getFillFormat--) | एक FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए फिल फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। |
| [getImage()](#getImage--) | आकार की थंबनेल लौटाता है। |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | आकार की थंबनेल लौटाता है। |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [getHyperlinkClick()](#getHyperlinkClick--) | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है या सेट करता है। |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है या सेट करता है। |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है या सेट करता है। |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है या सेट करता है। |
| [getHyperlinkManager()](#getHyperlinkManager--) | हाइपरलिंक प्रबंधक लौटाता है। |
| [getHidden()](#getHidden--) | निर्धारित करता है कि आकार छुपा है या नहीं। |
| [setHidden(boolean value)](#setHidden-boolean-) | निर्धारित करता है कि आकार छुपा है या नहीं। |
| [getZOrderPosition()](#getZOrderPosition--) | z-क्रम में आकार की स्थिति लौटाता है। |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | आकार पर कनेक्शन साइटों की संख्या लौटाता है। |
| [getRotation()](#getRotation--) | निर्धारित आकार के z-अक्ष के चारों ओर घुमाए जाने वाले डिग्री की संख्या लौटाता है या सेट करता है। |
| [setRotation(float value)](#setRotation-float-) | निर्धारित आकार के z-अक्ष के चारों ओर घुमाए जाने वाले डिग्री की संख्या लौटाता है या सेट करता है। |
| [getX()](#getX--) | बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है। |
| [setX(float value)](#setX-float-) | बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है। |
| [getY()](#getY--) | बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है। |
| [setY(float value)](#setY-float-) | बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है। |
| [getWidth()](#getWidth--) | बिंदुओं में मापी गई आकार की चौड़ाई को प्राप्त करता है या सेट करता है। |
| [setWidth(float value)](#setWidth-float-) | बिंदुओं में मापी गई आकार की चौड़ाई को प्राप्त करता है या सेट करता है। |
| [getHeight()](#getHeight--) | बिंदुओं में मापी गई आकार की ऊंचाई को प्राप्त करता है या सेट करता है। |
| [setHeight(float value)](#setHeight-float-) | बिंदुओं में मापी गई आकार की ऊंचाई को प्राप्त करता है या सेट करता है। |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | प्रॉपर्टी निर्दिष्ट करती है कि आकार काले-से-बैे रंग प्रदर्शन मोड में कैसे रेंडर होगा। |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | प्रॉपर्टी निर्दिष्ट करती है कि आकार काले-से-बैे रंग प्रदर्शन मोड में कैसे रेंडर होगा। |
| [getUniqueId()](#getUniqueId--) | ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए अभिप्रेत आंतरिक, प्रस्तुति-स्कोप पहचानकर्ता लौटाता है। |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | एक स्लाइड-स्कोप अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल तक स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है। |
| [getAlternativeText()](#getAlternativeText--) | आकार से संबंधित वैकल्पिक पाठ को प्राप्त करता है या सेट करता है। |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | आकार से संबंधित वैकल्पिक पाठ को प्राप्त करता है या सेट करता है। |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | आकार से संबंधित वैकल्पिक पाठ के शीर्षक को प्राप्त करता है या सेट करता है। |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | आकार से संबंधित वैकल्पिक पाठ के शीर्षक को प्राप्त करता है या सेट करता है। |
| [getName()](#getName--) | एक आकार का नाम प्राप्त करता है या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | एक आकार का नाम प्राप्त करता है या सेट करता है। |
| [isDecorative()](#isDecorative--) | 'Mark as decorative' विकल्प प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean। |
| [setDecorative(boolean value)](#setDecorative-boolean-) | 'Mark as decorative' विकल्प प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean। |
| [getShapeLock()](#getShapeLock--) | आकार के लॉक लौटाता है। |
| [isGrouped()](#isGrouped--) | निर्धारित करता है कि आकार समूहित है या नहीं। |
| [getParentGroup()](#getParentGroup--) | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | रेंडर की गई सामग्री से गणना किए गए आकार की दृश्य सीमाएँ प्राप्त करता है। |
| [getSlide()](#getSlide--) | एक आकार की पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | एक स्लाइड की पैरेंट प्रस्तुति लौटाता है। |
### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean
### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार के पास कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../../com.aspose.slides/iplaceholder)।

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Presentation क्लास का उदाहरण बनाता है
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // पहली स्लाइड तक पहुंचता है
>      ISlide sld = pres.getSlides().get_Item(0);
>      // प्लेसहोल्डर खोजने के लिए शेप्स पर पुनरावृति करता है
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // प्रत्येक प्लेसहोल्डर में टेक्स्ट बदलता है
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // प्रस्तुति को डिस्क पर सहेजता है
>      pres.save("output_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set Prompt Text in Placeholder.
>  
>  Presentation pres = new Presentation("Presentation2.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      for (IShape shape : slide.getSlide().getShapes()) // स्लाइड पर पुनरावृति करता है
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint प्रदर्शित करता है "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // उपशीर्षक जोड़ता है
>              {
>                  text = "Add Subtitle";
>              }
>              ((IAutoShape)shape).getTextFrame().setText(text);
>              System.out.println("Placeholder with text: " + text);
>          }
>      }
>      pres.save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)
### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है।

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट वाले के लिए प्लेसहोल्डर गुण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | सामग्री को कॉपी करने के लिए प्लेसहोल्डर। |

**वापसी:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - नया #getPlaceholder.getPlaceholder।
### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से आकार जिससे वर्तमान आकार विरासत में मिला है)।

--------------------

> ```
> // सभी (master/layout/slide) एनीमेटेड इफ़ेक्ट्स को प्लेसहोल्डर आकार से प्राप्त करें
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

**वापसी:**
[IShape](../../com.aspose.slides/ishape)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

आकार का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../../com.aspose.slides/icustomdata)।

**वापसी:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

रॉ आकार फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ें/लिखें [IShapeFrame](../../com.aspose.slides/ishapeframe)।

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //या
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //ऐसा कोड अस्पष्ट स्थितियों का कारण बन सकता है। इसलिए IShape.getFrame() के लिए अपरिभाषित मानों के उपयोग पर प्रतिबंध जोड़े गए हैं। x, y, width, height, flipH, flipV और rotationAngle के मान परिभाषित होने चाहिए (Float.NaN या NullableBool.NotDefined नहीं)। ऊपर का उदाहरण अब ArgumentException अपवाद उत्पन्न करता है।
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
>  //लेकिन IShape.RawFrame फ्रेम प्रॉपर्टीज़ को अपरिभाषित किया जा सकता है। यह अर्थपूर्ण है जब आकार प्लेसहोल्डर से जुड़ा हो। तब अपरिभाषित आकार फ्रेम मान पैरेंट प्लेसहोल्डर आकार से अधिलेखित होते हैं। यदि उस आकार के लिए कोई पैरेंट प्लेसहोल्डर नहीं है तो आकार अपने IShape.RawFrame के आधार पर प्रभावी फ्रेम का मूल्यांकन करते समय डिफ़ॉल्ट मानों का उपयोग करता है। x, y, width, height, flipH, flipV और rotationAngle के लिए डिफ़ॉल्ट मान क्रमशः 0 और NullableBool.False हैं। उदाहरण:
>  IShape shape = ...; // आकार प्लेसहोल्डर से जुड़ा है
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // अब आकार x, y, height, flipH, flipV मान प्लेसहोल्डर से विरासत में लेता है और width=100 तथा rotationAngle=0 को अधिलेखित करता है।{code}
> ```


**वापसी:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

रॉ आकार फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ें/लिखें [IShapeFrame](../../com.aspose.slides/ishapeframe)।

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //या
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //ऐसा कोड अस्पष्ट स्थितियों का कारण बन सकता है। इसलिए IShape.getFrame() के लिए अपरिभाषित मानों के उपयोग पर प्रतिबंध लगाए गए हैं। x, y, width, height, flipH, flipV और rotationAngle के मान परिभाषित होने चाहिए (Float.NaN या NullableBool.NotDefined नहीं)। ऊपर का उदाहरण अब ArgumentException अपवाद फेंकता है।
>  //यह निम्न उपयोग मामलों पर लागू होता है:
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
>  //लेकिन IShape.RawFrame फ्रेम प्रॉपर्टीज़ को अपरिभाषित किया जा सकता है। यह तब सार्थक है जब आकार प्लेसहोल्डर से जुड़ा हो। तब अपरिभाषित आकार फ्रेम मान पैरेंट प्लेसहोल्डर आकार से अधिलेखित होते हैं। यदि उस आकार के लिए कोई पैरेंट प्लेसहोल्डर नहीं है तो वह आकार अपने IShape.RawFrame के आधार पर प्रभावी फ्रेम का मूल्यांकन करते समय डिफ़ॉल्ट मानों का उपयोग करता है। डिफ़ॉल्ट मान x, y, width, height, flipH, flipV और rotationAngle के लिए क्रमशः 0 और NullableBool.False होते हैं। उदाहरण के लिए:
>  IShape shape = ...; // आकार प्लेसहोल्डर से जुड़ा है
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // अब आकार x, y, height, flipH, flipV मान प्लेसहोल्डर से विरासत में लेता है और width=100 तथा rotationAngle=0 को अधिलेखित करता है।{code}
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

आकार फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ें/लिखें [IShapeFrame](../../com.aspose.slides/ishapeframe)।

--------------------

Returned value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Assigned value must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**वापसी:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

आकार फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ें/लिखें [IShapeFrame](../../com.aspose.slides/ishapeframe)।

--------------------

Returned value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Assigned value must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

एक LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। नोट: कुछ प्रकार के आकार जिनमें लाइन प्रॉपर्टीज़ नहीं होती हैं, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [ILineFormat](../../com.aspose.slides/ilineformat)।

**वापसी:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए 3D प्रभाव प्रॉपर्टीज़ हैं। नोट: कुछ प्रकार के आकार जिनमें 3D प्रॉपर्टीज़ नहीं होती हैं, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [IThreeDFormat](../../com.aspose.slides/ithreedformat)।

**वापसी:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल प्रभाव होते हैं। नोट: कुछ प्रकार के आकार जिनमें इफ़ेक्ट प्रॉपर्टीज़ नहीं होती हैं, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [IEffectFormat](../../com.aspose.slides/ieffectformat)।

**वापसी:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

एक FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए फिल फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। नोट: कुछ प्रकार के आकार जिनमें फिल प्रॉपर्टीज़ नहीं होती हैं, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

--------------------

> ```
> The following example shows how to change the accent color for a theme of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      shape.getFillFormat().setFillType(FillType.Solid);
>      shape.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example demonstrates how to obtain palette colors from the main theme color and then used in shapes.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accent 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Accent 4, Lighter 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, Lighter 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, Lighter 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, Darker 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, Darker 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getImage() {#getImage--}
```
public final IImage getImage()
```

आकार की थंबनेल लौटाता है। ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार डिफ़ॉल्ट रूप से उपयोग किया जाता है।

**वापसी:**
[IImage](../../com.aspose.slides/iimage) - आकार थंबनेल।
### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

आकार की थंबनेल लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bounds | int | Shape thumbnail bounds type. |
| scaleX | float | X scale |
| scaleY | float | Y scale |

**वापसी:**
[IImage](../../com.aspose.slides/iimage) - आकार थंबनेल या null यदि ShapeThumbnailBounds.Appearance उपयोग किया गया हो और आकार में दृश्य तत्व न हों।
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |
### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है या सेट करता है। पढ़ें/लिखें [IHyperlink](../../com.aspose.slides/ihyperlink)।

**वापसी:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है या सेट करता है। पढ़ें/लिखें [IHyperlink](../../com.aspose.slides/ihyperlink)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है या सेट करता है। पढ़ें/लिखें [IHyperlink](../../com.aspose.slides/ihyperlink)।

**वापसी:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(I??????? ?????????)
```

माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है या सेट करता है। पढ़ें/लिखें [IHyperlink](../../com.aspose.slides/ihyperlink)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |
### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

हाइपरलिंक प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)।

**वापसी:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

निर्धारित करता है कि आकार छुपा है या नहीं। पढ़ें/लिखें boolean।

**वापसी:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

निर्धारित करता है कि आकार छुपा है या नहीं। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

z-क्रम में आकार की स्थिति लौटाता है। Shapes[0] पीछे की स्थिति लौटाता है, और Shapes[Shapes.Count - 1] सामने की स्थिति लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**
int
### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**
int
### getRotation() {#getRotation--}
```
public final float getRotation()
```

निर्दिष्ट आकार के z-अक्ष के चारों ओर घुमाए जाने वाले डिग्री की संख्या लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में। पढ़ें/लिखें float।

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**वापसी:**
float
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

निर्दिष्ट आकार के z-अक्ष के चारों ओर घुमाए जाने वाले डिग्री की संख्या लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में। पढ़ें/लिखें float।

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getX() {#getX--}
```
public final float getX()
```

बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें float।

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**वापसी:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें float।

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें float।

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**वापसी:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें float।

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

बिंदुओं में मापी गई आकार की चौड़ाई को प्राप्त करता है या सेट करता है। पढ़ें/लिखें float।

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**वापसी:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

बिंदुओं में मापी गई आकार की चौड़ाई को प्राप्त करता है या सेट करता है। पढ़ें/लिखें float।

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

बिंदुओं में मापी गई आकार की ऊंचाई को प्राप्त करता है या सेट करता है। पढ़ें/लिखें float।

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**वापसी:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

बिंदुओं में मापी गई आकार की ऊंचाई को प्राप्त करता है या सेट करता है। पढ़ें/लिखें float।

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

प्रॉपर्टी निर्दिष्ट करती है कि आकार काले-से-बैे रंग प्रदर्शन मोड में कैसे रेंडर होगा। पढ़ें/लिखें [BlackWhiteMode](../../com.aspose.slides/blackwhitemode)।

**वापसी:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

प्रॉपर्टी निर्दिष्ट करती है कि आकार काले-से-बैे रंग प्रदर्शन मोड में कैसे रेंडर होगा। पढ़ें/लिखें [BlackWhiteMode](../../com.aspose.slides/blackwhitemode)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

आंतरिक, प्रस्तुति-स्कोप पहचानकर्ता लौटाता है जो ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए अभिप्रेत है। क्योंकि यह मान उपयोगकर्ता या प्रोग्रामेटिक रूप से पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य long। देखें \#getOfficeInteropShapeId.getOfficeInteropShapeId।

**वापसी:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

स्लाइड-स्कोप अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल तक स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है। केवल-पढ़ने योग्य long। देखें \#getUniqueId.getUniqueId।

**वापसी:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

आकार से संबंधित वैकल्पिक पाठ को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String।

**वापसी:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

आकार से संबंधित वैकल्पिक पाठ को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

आकार से संबंधित वैकल्पिक पाठ के शीर्षक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String।

**वापसी:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

आकार से संबंधित वैकल्पिक पाठ के शीर्षक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getName() {#getName--}
```
public final String getName()
```

एक आकार का नाम प्राप्त करता है या सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग का उपयोग करें। पढ़ें/लिखें String।

**वापसी:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

एक आकार का नाम प्राप्त करता है या सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग का उपयोग करें। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

'Mark as decorative' विकल्प प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean।

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

'Mark as decorative' विकल्प प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean।

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
public IBaseShapeLock getShapeLock()
```

आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)।

**वापसी:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य boolean।

--------------------

Property \#getParentGroup.getParentGroup returns parent GroupShape object if shape is grouped.

**वापसी:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../../com.aspose.slides/igroupshape)।

--------------------

Property \#isGrouped.isGrouped determines whether the shape is grouped.

**वापसी:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

रेंडर की गई सामग्री से गणना किए गए आकार की दृश्य सीमाएँ प्राप्त करता है।

**वापसी:**
android.graphics.RectF - एक android.graphics.RectF जो स्लाइड निर्देशांक में आकार की दृश्य सीमाएँ दर्शाता है।

--------------------

The returned rectangle represents the axis-aligned bounds of all content produced by the shape during rendering in slide coordinate space. These bounds may differ from the shape's model bounds \#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float) and may contain negative coordinates if the rendered content extends beyond the slide origin. The visual bounds take into account rendering-related aspects such as transformations (for example, rotation), stroke width and joins, text layout and overflow, SmartArt geometry, and other layout effects that influence the final rendered appearance of the shape. The returned bounds are not clipped to the slide rectangle.
### getSlide() {#getSlide--}
```
public final RectF getVisualBounds()
```

एक आकार की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide)।

**वापसी:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

एक स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)