---
title: BaseSlide
second_title: Aspose.Slides जावा API संदर्भ
description: सभी स्लाइड प्रकारों के लिए सामान्य डेटा का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/baseslide/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

सभी स्लाइड प्रकारों के लिए सामान्य डेटा का प्रतिनिधित्व करता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getShapes()](#getShapes--) | स्लाइड के आकार लौटाता है। |
| [getControls()](#getControls--) | स्लाइड पर ActiveX नियंत्रणों का संग्रह लौटाता है। |
| [getName()](#getName--) | स्लाइड का नाम लौटाता है या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | स्लाइड का नाम लौटाता है या सेट करता है। |
| [getSlideId()](#getSlideId--) | स्लाइड का ID लौटाता है। |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | निर्धारित करता है कि दो IBaseSlide उदाहरण समान हैं या नहीं। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | सभी स्वीकार्य आकारों के सभी अनुच्छेदों में समान स्वरूपण वाले रन को जोड़ता है। |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | सभी स्वीकार्य आकारों में सभी अनुच्छेदों में समान स्वरूपण वाले रन को जोड़ता है। |
| [createThemeEffective()](#createThemeEffective--) | इस स्लाइड के लिए प्रभावी थीम लौटाता है। |
| [getCustomData()](#getCustomData--) | स्लाइड का कस्टम डेटा लौटाता है। |
| [getTimeline()](#getTimeline--) | एनिमेशन टाइमलाइन ऑब्जेक्ट लौटाता है। |
| [getSlideShowTransition()](#getSlideShowTransition--) | ट्रांज़िशन ऑब्जेक्ट लौटाता है जिसमें निर्दिष्ट स्लाइड स्लाइड शो के दौरान कैसे आगे बढ़ती है, इसकी जानकारी होती है। |
| [getBackground()](#getBackground--) | स्लाइड की पृष्ठभूमि लौटाता है। |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | समाहित हाइपरलिंक तक आसान पहुंच प्रदान करता है। |
| [getShowMasterShapes()](#getShowMasterShapes--) | निर्दिष्ट करता है कि मास्टर स्लाइड पर आकार स्लाइडों पर दिखाए जाने चाहिए या नहीं। |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | निर्दिष्ट करता है कि मास्टर स्लाइड पर आकार स्लाइडों पर दिखाए जाने चाहिए या नहीं। |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | निर्दिष्ट वैकल्पिक पाठ वाले आकार की पहली घटना को खोजता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | IPresentation इंटरफ़ेस लौटाता है। |
| [getSlide()](#getSlide--) |  |
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

स्लाइड के आकार लौटाता है। केवल-पढ़ने योग्य [IShapeCollection](../../com.aspose.slides/ishapecollection).

**वापसी:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

स्लाइड पर ActiveX नियंत्रणों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IControlCollection](../../com.aspose.slides/icontrolcollection).

**वापसी:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

स्लाइड का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

स्लाइड का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String.

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

स्लाइड का ID लौटाता है। केवल-पढ़ने योग्य long.

**वापसी:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

निर्धारित करता है कि दो IBaseSlide उदाहरण समान हैं या नहीं। रिटर्न मान स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना किया जाता है। दो स्लाइड समान होते हैं यदि सभी आकार, शैलियाँ, पाठ, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मान, जैसे SlideId, और गतिशील सामग्री, जैसे Date Placeholder में वर्तमान तिथि मान को नहीं माना जाता।

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | तुलना करने के लिए वर्तमान IBaseSlide के साथ IBaseSlide। |

**वापसी:**
boolean -  **true**  यदि निर्दिष्ट IBaseSlide वर्तमान IBaseSlide के समान है; अन्यथा,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

सभी स्वीकार्य आकारों के सभी अनुच्छेदों में समान स्वरूपण वाले रन को जोड़ता है।
### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

सभी स्वीकार्य आकारों में सभी अनुच्छेदों में समान स्वरूपण वाले रन को जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

इस स्लाइड के लिए प्रभावी थीम लौटाता है।

**वापसी:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

स्लाइड का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../../com.aspose.slides/icustomdata).

**वापसी:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

एनिमेशन टाइमलाइन ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**वापसी:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

ट्रांज़िशन ऑब्जेक्ट लौटाता है जिसमें निर्दिष्ट स्लाइड स्लाइड शो के दौरान कैसे आगे बढ़ती है, इसकी जानकारी होती है। केवल-पढ़ने योग्य [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**वापसी:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

स्लाइड की पृष्ठभूमि लौटाता है। केवल-पढ़ने योग्य [IBackground](../../com.aspose.slides/ibackground).

**वापसी:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

समाहित हाइपरलिंक तक आसान पहुंच प्रदान करता है। केवल-पढ़ने योग्य [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**वापसी:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

निर्दिष्ट करता है कि मास्टर स्लाइड पर आकार स्लाइडों पर दिखाए जाने चाहिए या नहीं। मास्टर स्लाइड के लिए यह गुण हमेशा false लौटाता है। पढ़ने/लिखने योग्य boolean.

**वापसी:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

निर्दिष्ट करता है कि मास्टर स्लाइड पर आकार स्लाइडों पर दिखाए जाने चाहिए या नहीं। मास्टर स्लाइड के लिए यह गुण हमेशा false लौटाता है। पढ़ने/लिखने योग्य boolean.

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

निर्दिष्ट वैकल्पिक पाठ वाले आकार की पहली घटना को खोजता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| altText | java.lang.String | वैकल्पिक पाठ। |

**वापसी:**
[IShape](../../com.aspose.slides/ishape) - Shape ऑब्जेक्ट या null।
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject.

**वापसी:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

IPresentation इंटरफ़ेस लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation).

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

बेस स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide).

**वापसी:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)