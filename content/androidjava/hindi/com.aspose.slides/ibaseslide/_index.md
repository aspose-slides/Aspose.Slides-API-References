---
title: IBaseSlide
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: सभी स्लाइड प्रकारों के लिए सामान्य डेटा का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ibaseslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

सभी स्लाइड प्रकारों के लिए सामान्य डेटा का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getShapes()](#getShapes--) | एक स्लाइड के आकार लौटाता है। |
| [getControls()](#getControls--) | एक स्लाइड पर ActiveX नियंत्रणों का संग्रह लौटाता है। |
| [getName()](#getName--) | स्लाइड का नाम लौटाता है या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | स्लाइड का नाम लौटाता है या सेट करता है। |
| [getSlideId()](#getSlideId--) | स्लाइड की ID लौटाता है। |
| [getCustomData()](#getCustomData--) | स्लाइड का कस्टम डेटा लौटाता है। |
| [getTimeline()](#getTimeline--) | एनीमेशन टाइमलाइन ऑब्जेक्ट लौटाता है। |
| [getSlideShowTransition()](#getSlideShowTransition--) | TransitionEx ऑब्जेक्ट लौटाता है जिसमें यह जानकारी होती है कि निर्दिष्ट स्लाइड स्लाइड शो के दौरान कैसे आगे बढ़ती है। |
| [getBackground()](#getBackground--) | स्लाइड की पृष्ठभूमि लौटाता है। |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | सम्मिलित हाइपरलिंक तक आसान पहुँच प्रदान करता है। |
| [getShowMasterShapes()](#getShowMasterShapes--) | निर्धारित करता है कि मास्टर स्लाइड पर आकार स्लाइडों पर दिखाए जाने चाहिए या नहीं। |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | निर्धारित करता है कि मास्टर स्लाइड पर आकार स्लाइडों पर दिखाए जाने चाहिए या नहीं। |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | निर्दिष्ट वैकल्पिक पाठ वाले आकार की पहली उपस्थिति खोजता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | सभी स्वीकार्य आकारों में सभी पैराग्राफ़ में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | निर्धारित करता है कि दो IBaseSlide उदाहरण समान हैं या नहीं। |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```


एक स्लाइड के आकार लौटाता है। केवल-पढ़ने योग्य [IShapeCollection](../../com.aspose.slides/ishapecollection)।

**वापसी:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```


एक स्लाइड पर ActiveX नियंत्रणों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IControlCollection](../../com.aspose.slides/icontrolcollection)।

**वापसी:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```


स्लाइड का नाम लौटाता है या सेट करता है। पढ़ने-और-लेखन योग्य String।

**वापसी:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


स्लाइड का नाम लौटाता है या सेट करता है। पढ़ने-और-लेखन योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```


स्लाइड की ID लौटाता है। केवल-पढ़ने योग्य long।

**वापसी:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


स्लाइड का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../../com.aspose.slides/icustomdata)।

**वापसी:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```


एनीमेशन टाइमलाइन ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)।

**वापसी:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```


TransitionEx ऑब्जेक्ट लौटाता है जिसमें यह जानकारी होती है कि निर्दिष्ट स्लाइड स्लाइड शो के दौरान कैसे आगे बढ़ती है। केवल-पढ़ने योग्य [ISlideShowTransition](../../com.aspose.slides/islideshowtransition)।

**वापसी:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```


स्लाइड की पृष्ठभूमि लौटाता है। केवल-पढ़ने योग्य [IBackground](../../com.aspose.slides/ibackground)।

**वापसी:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


सम्मिलित हाइपरलिंक तक आसान पहुँच प्रदान करता है। केवल-पढ़ने योग्य [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)।

**वापसी:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


निर्धारित करता है कि मास्टर स्लाइड पर आकार स्लाइडों पर दिखाए जाने चाहिए या नहीं। मास्टर स्लाइड ख़ुद के लिए यह गुण हमेशा false लौटाता है। पढ़ने-और-लेखन योग्य boolean।

**वापसी:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


निर्धारित करता है कि मास्टर स्लाइड पर आकार स्लाइडों पर दिखाए जाने चाहिए या नहीं। मास्टर स्लाइड ख़ुद के लिए यह गुण हमेशा false लौटाता है। पढ़ने-और-लेखन योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```


निर्दिष्ट वैकल्पिक पाठ वाले आकार की पहली उपस्थिति खोजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| altText | java.lang.String | वैकल्पिक पाठ। |

**वापसी:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx ऑब्जेक्ट या null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


सभी स्वीकार्य आकारों में सभी पैराग्राफ़ में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है।

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```


निर्धारित करता है कि दो IBaseSlide उदाहरण समान हैं या नहीं। रिटर्न मान स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना किया जाता है। दो स्लाइड समान होते हैं यदि सभी आकार, शैलियाँ, पाठ, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मान, जैसे SlideId और गतिशील सामग्री, जैसे तिथि प्लेसहोल्डर में वर्तमान तिथि मान, को ध्यान में नहीं रखा जाता।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | वर्तमान IBaseSlide की तुलना करने के लिए IBaseSlide। |

**वापसी:**
boolean - **true** यदि निर्दिष्ट IBaseSlide वर्तमान IBaseSlide के बराबर है; अन्यथा, **false**.