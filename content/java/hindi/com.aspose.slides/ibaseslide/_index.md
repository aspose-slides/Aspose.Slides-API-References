---
title: IBaseSlide
second_title: Aspose.Slides for Java API संदर्भ
description: सभी स्लाइड प्रकारों के लिए सामान्य डेटा का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ibaseslide/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

सभी स्लाइड प्रकारों के लिए सामान्य डेटा का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getShapes()](#getShapes--) | एक स्लाइड के आकार को लौटाता है। |
| [getControls()](#getControls--) | स्लाइड पर ActiveX नियंत्रणों के संग्रह को लौटाता है। |
| [getName()](#getName--) | स्लाइड का नाम लौटाता है या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | स्लाइड का नाम लौटाता है या सेट करता है। |
| [getSlideId()](#getSlideId--) | स्लाइड का ID लौटाता है। |
| [getCustomData()](#getCustomData--) | स्लाइड के कस्टम डेटा को लौटाता है। |
| [getTimeline()](#getTimeline--) | एनिमेशन टाइमलाइन ऑब्जेक्ट को लौटाता है। |
| [getSlideShowTransition()](#getSlideShowTransition--) | TransitionEx ऑब्जेक्ट को लौटाता है जिसमें स्लाइड शो के दौरान स्लाइड के आगे बढ़ने की जानकारी रहती है। |
| [getBackground()](#getBackground--) | स्लाइड का बैकग्राउंड लौटाता है। |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | समावेशित हाइपरलिंक्स तक आसान पहुंच प्रदान करता है। |
| [getShowMasterShapes()](#getShowMasterShapes--) | निर्धारित करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड पर दिखाना चाहिए या नहीं। |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | निर्धारित करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड पर दिखाना चाहिए या नहीं। |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | निर्दिष्ट वैकल्पिक टेक्स्ट वाली आकृति की पहली घटना को खोजता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | सभी स्वीकृत आकृतियों में सभी अनुच्छेदों में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | निर्धारित करता है कि दो IBaseSlide इंस्टेंस समान हैं या नहीं। |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

एक स्लाइड के आकार को लौटाता है। केवल-पढ़ने योग्य [IShapeCollection](../../com.aspose.slides/ishapecollection).

**वापसी:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

स्लाइड पर ActiveX नियंत्रणों के संग्रह को लौटाता है। केवल-पढ़ने योग्य [IControlCollection](../../com.aspose.slides/icontrolcollection).

**वापसी:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```

स्लाइड का नाम लौटाता है या सेट करता है। पढ़ने-लिखने योग्य String.

**वापसी:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

स्लाइड का नाम लौटाता है या सेट करता है। पढ़ने-लिखने योग्य String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

स्लाइड का ID लौटाता है। केवल-पढ़ने योग्य long.

**वापसी:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

स्लाइड के कस्टम डेटा को लौटाता है। केवल-पढ़ने योग्य [ICustomData](../../com.aspose.slides/icustomdata).

**वापसी:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

एनिमेशन टाइमलाइन ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**वापसी:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

TransitionEx ऑब्जेक्ट को लौटाता है जिसमें स्लाइड शो के दौरान स्लाइड के आगे बढ़ने की जानकारी रहती है। केवल-पढ़ने योग्य [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**वापसी:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

स्लाइड का बैकग्राउंड लौटाता है। केवल-पढ़ने योग्य [IBackground](../../com.aspose.slides/ibackground).

**वापसी:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

समावेशित हाइपरलिंक्स तक आसान पहुंच प्रदान करता है। केवल-पढ़ने योग्य [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**वापसी:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

निर्धारित करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड पर दिखाना चाहिए या नहीं। मास्टर स्लाइड के लिए यह प्रॉपर्टी हमेशा false लौटाती है। पढ़ने-लिखने योग्य boolean।

**वापसी:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

निर्धारित करता है कि मास्टर स्लाइड पर आकृतियों को स्लाइड पर दिखाना चाहिए या नहीं। मास्टर स्लाइड के लिए यह प्रॉपर्टी हमेशा false लौटाती है। पढ़ने-लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```

निर्दिष्ट वैकल्पिक टेक्स्ट वाली आकृति की पहली घटना को खोजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| altText | java.lang.String | वैकल्पिक टेक्स्ट। |

**वापसी:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx object or null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

सभी स्वीकृत आकृतियों में सभी अनुच्छेदों में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है।
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

निर्धारित करता है कि दो IBaseSlide इंस्टेंस समान हैं या नहीं। रिटर्न वैल्यू स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना की जाती है। दो स्लाइड समान होते हैं यदि सभी आकृतियां, शैलियां, पाठ, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचान मान जैसे SlideId और गतिशील कंटेंट जैसे वर्तमान तिथि मान को ध्यान नहीं दिया जाता।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | तुलना करने के लिए वर्तमान IBaseSlide के साथ IBaseSlide। |

**वापसी:**
boolean - **true** if the specified IBaseSlide is equal to the current IBaseSlide; otherwise, **false**.