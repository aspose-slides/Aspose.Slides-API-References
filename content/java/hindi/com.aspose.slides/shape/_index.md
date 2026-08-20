---
title: Shape
second_title: Aspose.Slides for Java API संदर्भ
description: स्लाइड पर एक आकार को दर्शाता है।
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

एक स्लाइड पर एक आकार का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। |
| [getPlaceholder()](#getPlaceholder--) | एक आकार के लिए प्लेसहोल्डर लौटाता है। |
| [removePlaceholder()](#removePlaceholder--) | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट एक में सेट करता है। |
| [getBasePlaceholder()](#getBasePlaceholder--) | एक मूलभूत प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से आकार जो वर्तमान आकार से विरासत में मिला है)। |
| [getCustomData()](#getCustomData--) | आकार का कस्टम डेटा लौटाता है। |
| [getRawFrame()](#getRawFrame--) | रॉ आकार फ्रेम के गुण लौटाता या सेट करता है। |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | रॉ आकार फ्रेम के गुण लौटाता या सेट करता है। |
| [getFrame()](#getFrame--) | रॉ आकार फ्रेम के गुण लौटाता या सेट करता है। |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | रॉ आकार फ्रेम के गुण लौटाता या सेट करता है। |
| [getLineFormat()](#getLineFormat--) | एक LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए लाइन फॉर्मेटिंग गुण होते हैं। |
| [getThreeDFormat()](#getThreeDFormat--) | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के 3D प्रभाव गुण होते हैं। |
| [getEffectFormat()](#getEffectFormat--) | एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल इफ़ेक्ट होते हैं। |
| [getFillFormat()](#getFillFormat--) | एक FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के भरने के फॉर्मेटिंग गुण होते हैं। |
| [getImage()](#getImage--) | आकार थंबनेल लौटाता है। |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | आकार थंबनेल लौटाता है। |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [getHyperlinkClick()](#getHyperlinkClick--) | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। |
| [getHyperlinkManager()](#getHyperlinkManager--) | हाइपरलिंक प्रबंधक लौटाता है। |
| [getHidden()](#getHidden--) | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। |
| [setHidden(boolean value)](#setHidden-boolean-) | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। |
| [getZOrderPosition()](#getZOrderPosition--) | z-क्रम में आकार की स्थिति लौटाता है। |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | आकार पर कनेक्शन साइटों की संख्या लौटाता है। |
| [getRotation()](#getRotation--) | निर्दिष्ट आकार को z-अक्ष के आसपास घुमाए जाने वाले डिग्री की संख्या को लौटाता या सेट करता है। |
| [setRotation(float value)](#setRotation-float-) | निर्दिष्ट आकार को z-अक्ष के आसपास घुमाए जाने वाले डिग्री की संख्या को लौटाता या सेट करता है। |
| [getX()](#getX--) | आकार के ऊपर-बाएँ कोने के x-निर्देशांक को पॉइंट्स में प्राप्त या सेट करता है। |
| [setX(float value)](#setX-float-) | आकार के ऊपर-बाएँ कोने के x-निर्देशांक को पॉइंट्स में प्राप्त या सेट करता है। |
| [getY()](#getY--) | आकार के ऊपर-बाएँ कोने के y-निर्देशांक को पॉइंट्स में प्राप्त या सेट करता है। |
| [setY(float value)](#setY-float-) | आकार के ऊपर-बाएँ कोने के y-निर्देशांक को पॉइंट्स में प्राप्त या सेट करता है। |
| [getWidth()](#getWidth--) | आकार की चौड़ाई को पॉइंट्स में प्राप्त या सेट करता है। |
| [setWidth(float value)](#setWidth-float-) | आकार की चौड़ाई को पॉइंट्स में प्राप्त या सेट करता है। |
| [getHeight()](#getHeight--) | आकार की ऊँचाई को पॉइंट्स में प्राप्त या सेट करता है। |
| [setHeight(float value)](#setHeight-float-) | आकार की ऊँचाई को पॉइंट्स में प्राप्त या सेट करता है। |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | प्रॉपर्टी यह निर्दिष्ट करती है कि आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | प्रॉपर्टी यह निर्दिष्ट करती है कि आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। |
| [getUniqueId()](#getUniqueId--) | ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है। |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है। |
| [getAlternativeText()](#getAlternativeText--) | एक आकार से जुड़ा वैकल्पिक पाठ लौटाता या सेट करता है। |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | एक आकार से जुड़ा वैकल्पिक पाठ लौटाता या सेट करता है। |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | एक आकार से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता या सेट करता है। |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | एक आकार से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता या सेट करता है। |
| [getName()](#getName--) | आकार का नाम लौटाता या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | आकार का नाम लौटाता या सेट करता है। |
| [isDecorative()](#isDecorative--) | ‘Mark as decorative’ विकल्प को पढ़ने/लिखने वाले बूलियन के रूप में प्राप्त या सेट करता है। |
| [setDecorative(boolean value)](#setDecorative-boolean-) | ‘Mark as decorative’ विकल्प को पढ़ने/लिखने वाले बूलियन के रूप में प्राप्त या सेट करता है। |
| [getShapeLock()](#getShapeLock--) | आकार के लॉक लौटाता है। |
| [isGrouped()](#isGrouped--) | निर्धारित करता है कि आकार समूहित है या नहीं। |
| [getParentGroup()](#getParentGroup--) | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | रेंडर किए गए सामग्री से गणना किए गए आकार की दृश्य सीमाएँ प्राप्त करता है। |
| [getSlide()](#getSlide--) | आकार की पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | स्लाइड की पैरेंट प्रस्तुति लौटाता है। |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पठन boolean .

**रिटर्न:**
boolean
### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार में कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पठन [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Instantiates a Presentation class
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Accesses the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Iterates through shapes to find the placeholder
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Changes the text in each placeholder
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Saves the presentation to disk
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
>      for (IShape shape : slide.getSlide().getShapes()) // Iterates through the slide
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint displays "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Adds subtitle
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

**रिटर्न:**
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

यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट एक में सेट करता है।

**परामितर:**
| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | जिस प्लेसहोल्डर से सामग्री कॉपी करनी है। |

**रिटर्न:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New #getPlaceholder.getPlaceholder.
### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

एक मूलभूत प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से आकार जो वर्तमान आकार से विरासत में मिला है)।

--------------------

> ```
> // सभी (मास्टर/लेआउट/स्लाइड) एनीमेटेड इफ़ेक्ट्स को प्लेसहोल्डर शेप से प्राप्त करें
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
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

आकार का कस्टम डेटा लौटाता है। केवल-पठन [ICustomData](../../com.aspose.slides/icustomdata).

**रिटर्न:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

रॉ आकार फ्रेम के गुण लौटाता या सेट करता है। पढ़ें/लिखें [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  // या
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  // ऐसे कोड से अस्पष्ट स्थितियों का निर्माण हो सकता है। इसलिए IShape.getFrame() के लिए अपरिभाषित मानों के उपयोग पर प्रतिबंध लगाए गए हैं। x, y, width, height, flipH, flipV और rotationAngle के मान परिभाषित होने चाहिए (Float.NaN या NullableBool.NotDefined नहीं)। ऊपर दिया गया उदाहरण अब ArgumentException अपवाद फेंकता है।
>  // यह उपयोग मामलों पर लागू होता है:
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
>  // लेकिन IShape.RawFrame फ्रेम गुण अपरिभाषित हो सकते हैं। यह तभी समझ में आता है जब shape placeholder से जुड़ी हो। तब अपरिभाषित shape फ्रेम मान पैरेंट placeholder shape से अधिलेखित हो जाते हैं। यदि उस shape के लिए कोई पैरेंट placeholder नहीं है तो shape अपने IShape.RawFrame के आधार पर प्रभावी फ्रेम का मूल्यांकन करते समय डिफ़ॉल्ट मानों का उपयोग करता है। डिफ़ॉल्ट मान x, y, width, height, flipH, flipV और rotationAngle के लिए 0 और NullableBool.False हैं। उदाहरण के लिए:
>  IShape shape = ...; // shape placeholder से जुड़ी है
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // अब shape placeholder से x, y, height, flipH, flipV मान प्राप्त करता है और width=100 तथा rotationAngle=0 को ओवरराइड करता है.{code}
> ```


**रिटर्न:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

रॉ आकार फ्रेम के गुण लौटाता या सेट करता है। पढ़ें/लिखें [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //या
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //ऐसे कोड से अस्पष्ट स्थितियां उत्पन्न हो सकती हैं। इसलिए IShape.getFrame() के लिए अपरिभाषित मानों के उपयोग पर प्रतिबंध लगाए गए हैं। x, y, width, height, flipH, flipV और rotationAngle के मान परिभाषित होने चाहिए (Float.NaN या NullableBool.NotDefined नहीं)। उपरोक्त उदाहरण अब ArgumentException अपवाद फेंकता है।
>  //यह निम्नलिखित उपयोग मामलों पर लागू होता है:
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
>  //लेकिन IShape.RawFrame के फ्रेम गुण अपरिभाषित हो सकते हैं। यह तब समझ में आता है जब shape placeholder से जुड़ी हो। तब अपरिभाषित shape फ्रेम मान पैरेंट placeholder shape से अधिलेखित हो जाते हैं। यदि उस shape के लिए कोई पैरेंट placeholder नहीं है तो shape अपने IShape.RawFrame के आधार पर प्रभावी फ्रेम का मूल्यांकन करते समय डिफ़ॉल्ट मानों का उपयोग करता है। डिफ़ॉल्ट मान x, y, width, height, flipH, flipV और rotationAngle के लिए 0 और NullableBool.False होते हैं। उदाहरण के लिए:
>  IShape shape = ...; // shape placeholder से जुड़ी है
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // अब shape placeholder से x, y, height, flipH, flipV मान प्राप्त करता है और width=100 तथा rotationAngle=0 को ओवरराइड करता है.{code}
> ```


**परामितर:**
| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

आकार फ्रेम के गुण लौटाता या सेट करता है। पढ़ें/लिखें [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Returned value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**रिटर्न:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

आकार फ्रेम के गुण लौटाता या सेट करता है। पढ़ें/लिखें [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Returned value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**परामितर:**
| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

एक LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए लाइन फॉर्मेटिंग गुण होते हैं। नोट: कुछ प्रकार के आकार जिनमें लाइन गुण नहीं होते हैं, उनके लिए null लौटाया जा सकता है। केवल-पठन [ILineFormat](../../com.aspose.slides/ilineformat).

**रिटर्न:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के 3D प्रभाव गुण होते हैं। नोट: कुछ प्रकार के आकार जिनमें 3D गुण नहीं होते हैं, उनके लिए null लौटाया जा सकता है। केवल-पठन [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**रिटर्न:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल इफ़ेक्ट होते हैं। नोट: कुछ प्रकार के आकार जिनमें इफ़ेक्ट गुण नहीं होते हैं, उनके लिए null लौटाया जा सकता है। केवल-पठन [IEffectFormat](../../com.aspose.slides/ieffectformat).

**रिटर्न:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

एक FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के भरने के फॉर्मेटिंग गुण होते हैं। नोट: कुछ प्रकार के आकार जिनमें भरने के गुण नहीं होते हैं, उनके लिए null लौटाया जा सकता है। केवल-पठन [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // एक्सेंट 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // एक्सेंट 4, हल्का 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // एक्सेंट 4, हल्का 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // एक्सेंट 4, हल्का 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // एक्सेंट 4, गहरा 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // एक्सेंट 4, गहरा 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getImage() {#getImage--}
```
public final IImage getImage()
```

आकार थंबनेल लौटाता है। ShapeThumbnailBounds.Shape आकार थंबनेल बॉउंड्स टाइप डिफ़ॉल्ट रूप से उपयोग किया जाता है।

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - Shape थंबनेल।
### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

आकार थंबनेल लौटाता है।

**परामितर:**
| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| bounds | int | Shape थंबनेल बॉउंड्स टाइप। |
| scaleX | float | X स्केल |
| scaleY | float | Y स्केल |

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - Shape थंबनेल या null यदि ShapeThumbnailBounds.Appearance उपयोग किया गया हो और आकार में दृश्य तत्व न हों।
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है।

**परामितर:**
| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है।

**परामितर:**
| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG जनरेशन विकल्प |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ें/लिखें [IHyperlink](../../com.aspose.slides/ihyperlink).

**रिटर्न:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ें/लिखें [IHyperlink](../../com.aspose.slides/ihyperlink).

**परामितर:**
| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ें/लिखें [IHyperlink](../../com.aspose.slides/ihyperlink).

**रिटर्न:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ें/लिखें [IHyperlink](../../com.aspose.slides/ihyperlink).

**परामितर:**
| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

हाइपरलिंक प्रबंधक लौटाता है। केवल-पठन [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**रिटर्न:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

निर्धारित करता है कि आकार छिपा हुआ है या नहीं। पढ़ें/लिखें boolean .

**रिटर्न:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

निर्धारित करता है कि आकार छिपा हुआ है या नहीं। पढ़ें/लिखें boolean .

**परामितर:**
| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

एक आकार की z-क्रम में स्थिति लौटाता है। Shapes[0] z-क्रम के पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] सामने वाला आकार लौटाता है। केवल-पठन int .

**रिटर्न:**
int
### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पठन int .

**रिटर्न:**
int
### getRotation() {#getRotation--}
```
public final float getRotation()
```

निर्दिष्ट आकार को z-अक्ष के आसपास घुमाए जाने वाले डिग्री की संख्या को लौटाता या सेट करता है। धनात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; ऋणात्मक मान प्रतिवादी घुमाव दर्शाता है। पढ़ें/लिखें float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**रिटर्न:**
float
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```
Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. पढ़ें/लिखें float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

आकार के ऊपर-बाएँ कोने के x-कोऑर्डिनेट को प्राप्त करता है या सेट करता है, जिसे बिंदुओं में मापा जाता है। पढ़ें/लिखें float.

--------------------

वापसी मान हमेशा परिभाषित होता है और कभी Float.NaN नहीं होता। नियुक्त मान भी परिभाषित होना चाहिए; Float.NaN केवल RawFrame उदाहरण के गुणों को ही असाइन करें।

**रिटर्न:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

आकार के ऊपर-बाएँ कोने के x-कोऑर्डिनेट को प्राप्त करता है या सेट करता है, जिसे बिंदुओं में मापा जाता है। पढ़ें/लिखें float.

--------------------

वापसी मान हमेशा परिभाषित होता है और कभी Float.NaN नहीं होता। नियुक्त मान भी परिभाषित होना चाहिए; Float.NaN केवल RawFrame उदाहरण के गुणों को ही असाइन करें।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

आकार के ऊपर-बाएँ कोने के y-कोऑर्डिनेट को प्राप्त करता है या सेट करता है, जिसे बिंदुओं में मापा जाता है। पढ़ें/लिखें float.

--------------------

वापसी मान हमेशा परिभाषित होता है और कभी Float.NaN नहीं होता। नियुक्त मान भी परिभाषित होना चाहिए; Float.NaN केवल RawFrame उदाहरण के गुणों को ही असाइन करें।

**रिटर्न:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

आकार के ऊपर-बाएँ कोने के y-कोऑर्डिनेट को प्राप्त करता है या सेट करता है, जिसे बिंदुओं में मापा जाता है। पढ़ें/लिखें float.

--------------------

वापसी मान हमेशा परिभाषित होता है और कभी Float.NaN नहीं होता। नियुक्त मान भी परिभाषित होना चाहिए; Float.NaN केवल RawFrame उदाहरण के गुणों को ही असाइन करें।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

आकार की चौड़ाई को प्राप्त करता है या सेट करता है, जिसे बिंदुओं में मापा जाता है। पढ़ें/लिखें float.

--------------------

वापसी मान हमेशा परिभाषित होता है और कभी Float.NaN नहीं होता। नियुक्त मान भी परिभाषित होना चाहिए; Float.NaN केवल RawFrame उदाहरण के गुणों को ही असाइन करें।

**रिटर्न:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

आकार की चौड़ाई को प्राप्त करता है या सेट करता है, जिसे बिंदुओं में मापा जाता है। पढ़ें/लिखें float.

--------------------

वापसी मान हमेशा परिभाषित होता है और कभी Float.NaN नहीं होता। नियुक्त मान भी परिभाषित होना चाहिए; Float.NaN केवल RawFrame उदाहरण के गुणों को ही असाइन करें।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

आकार की ऊँचाई को प्राप्त करता है या सेट करता है, जिसे बिंदुओं में मापा जाता है। पढ़ें/लिखें float.

--------------------

वापसी मान हमेशा परिभाषित होता है और कभी Float.NaN नहीं होता। नियुक्त मान भी परिभाषित होना चाहिए; Float.NaN केवल RawFrame उदाहरण के गुणों को ही असाइन करें।

**रिटर्न:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

आकार की ऊँचाई को प्राप्त करता है या सेट करता है, जिसे बिंदुओं में मापा जाता है। पढ़ें/लिखें float.

--------------------

वापसी मान हमेशा परिभाषित होता है और कभी Float.NaN नहीं होता। नियुक्त मान भी परिभाषित होना चाहिए; Float.NaN केवल RawFrame उदाहरण के गुणों को ही असाइन करें।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

गुण निर्दिष्ट करता है कि आकार काली-श्वेत प्रदर्शन मोड में कैसे रेंडर होगा। पढ़ें/लिखें [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**रिटर्न:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

गुण निर्दिष्ट करता है कि आकार काली-श्वेत प्रदर्शन मोड में कैसे रेंडर होगा। पढ़ें/लिखें [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

आंतरिक, प्रेजेंटेशन-स्तरीय पहचानकर्ता लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग किया जाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्रामेटिकली पुनः असाइन किया जा सकता है, इसे एक स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य long। देखें \#getOfficeInteropShapeId.getOfficeInteropShapeId।

**रिटर्न:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

स्लाइड-स्तरीय अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल तक स्थिर रहता है और PowerPoint या इंटरॉप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पढ़ने योग्य long। देखें \#getUniqueId.getUniqueId।

**रिटर्न:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

आकार से जुड़ा वैकल्पिक पाठ लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

आकार से जुड़ा वैकल्पिक पाठ लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

आकार से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

आकार से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

आकार का नाम लौटाता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान उपयोग करें। पढ़ें/लिखें String.

**रिटर्न:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

आकार का नाम लौटाता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान उपयोग करें। पढ़ें/लिखें String.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

‘Mark as decorative’ विकल्प को प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean.

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
public final void setDecorative(boolean value)
```

‘Mark as decorative’ विकल्प को प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)।

**रिटर्न:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

निर्धारित करता है कि क्या आकार समूहित है। केवल-पढ़ने योग्य boolean.

--------------------

गुण \#getParentGroup.getParentGroup पैरेंट GroupShape ऑब्जेक्ट लौटाता है यदि आकार समूहित है।

**रिटर्न:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

पैरेंट GroupShape ऑब्जेक्ट लौटाता है यदि आकार समूहित है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../../com.aspose.slides/igroupshape)।

--------------------

गुण \#isGrouped.isGrouped निर्धारित करता है कि क्या आकार समूहित है।

**रिटर्न:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final Rectangle2D.Float getVisualBounds()
```

आकार की दृश्य सीमाओं को प्राप्त करता है जो उसके रेंडर किए गए कंटेंट से गणना की गई हैं।

**रिटर्न:**
java.awt.geom.Rectangle2D.Float - एक java.awt.geom.Rectangle2D.Float जो स्लाइड निर्देशांक में आकार की दृश्य सीमाओं को दर्शाता है।

--------------------

वापसी आयत सभी कंटेंट के अक्ष-संकल्पित सीमाओं को दर्शाती है जो shape के rendering के दौरान स्लाइड कोऑर्डिनेट स्पेस में उत्पन्न होता है। ये सीमाएँ shape के मॉडल सीमाओं \#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float) से भिन्न हो सकती हैं और नकारात्मक निर्देशांक भी रख सकती हैं यदि रेंडर किया गया कंटेंट स्लाइड मूल बिंदु से बाहर तक विस्तारित हो। दृश्य सीमाएँ परिवर्तनों (उदाहरण के लिए, rotation), स्ट्रोक चौड़ाई और जॉइन्स, पाठ लेआउट और ओवरफ़्लो, SmartArt ज्यामिति, और अन्य लेआउट प्रभावों को सम्मिलित करती हैं जो shape के अंतिम प्रदर्शित रूप को प्रभावित करते हैं। लौटाई गई सीमाएँ स्लाइड आयत में क्लिप नहीं की गई हैं।
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

आकार की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide)।

**रिटर्न:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

स्लाइड की पैरेंट प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation)