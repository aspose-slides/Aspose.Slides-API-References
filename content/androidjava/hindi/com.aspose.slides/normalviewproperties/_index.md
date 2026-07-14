---
title: NormalViewProperties
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: सामान्य दृश्य गुणों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/normalviewproperties/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

सामान्य दृश्य गुणों का प्रतिनिधित्व करता है। सामान्य दृश्य में तीन सामग्री क्षेत्र होते हैं: स्वयं स्लाइड, एक साइड सामग्री क्षेत्र, और एक बॉटम सामग्री क्षेत्र।

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाला प्रस्तुति ऑब्जेक्ट बनाएं
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | निर्दिष्ट करता है कि क्या एप्लिकेशन को सामान्य दृश्य मोड में किसी भी सामग्री क्षेत्र में रूपरेखा सामग्री प्रदर्शित करते समय आइकन दिखाने चाहिए। |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | निर्दिष्ट करता है कि क्या एप्लिकेशन को सामान्य दृश्य मोड में किसी भी सामग्री क्षेत्र में रूपरेखा सामग्री प्रदर्शित करते समय आइकन दिखाने चाहिए। |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | निर्दिष्ट करता है कि जब साइड क्षेत्र पर्याप्त छोटा हो तो वर्टिकल स्प्लिटर को न्यूनतम स्थिति में स्नैप करना चाहिए या नहीं। |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | निर्दिष्ट करता है कि जब साइड क्षेत्र पर्याप्त छोटा हो तो वर्टिकल स्प्लिटर को न्यूनतम स्थिति में स्नैप करना चाहिए या नहीं। |
| [getVerticalBarState()](#getVerticalBarState--) | निर्दिष्ट करता है कि वर्टिकल स्प्लिटर बार कौन सी स्थिति में दिखाया जाना चाहिए। |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | निर्दिष्ट करता है कि वर्टिकल स्प्लिटर बार कौन सी स्थिति में दिखाया जाना चाहिए। |
| [getHorizontalBarState()](#getHorizontalBarState--) | निर्दिष्ट करता है कि हॉरिज़ोन्टल स्प्लिटर बार कौन सी स्थिति में दिखाया जाना चाहिए। |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | निर्दिष्ट करता है कि हॉरिज़ोन्टल स्प्लिटर बार कौन सी स्थिति में दिखाया जाना चाहिए। |
| [getPreferSingleView()](#getPreferSingleView--) | निर्दिष्ट करता है कि क्या उपयोगकर्ता तीन सामग्री क्षेत्रों वाले मानक सामान्य दृश्य के बजाय पूर्ण-खिड़की एकल-सामग्री क्षेत्र देखना पसंद करता है। |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | निर्दिष्ट करता है कि क्या उपयोगकर्ता तीन सामग्री क्षेत्रों वाले मानक सामान्य दृश्य के बजाय पूर्ण-खिड़की एकल-सामग्री क्षेत्र देखना पसंद करता है। |
| [getRestoredLeft()](#getRestoredLeft--) | यह तत्व सामान्य दृश्य के साइड सामग्री क्षेत्र का आकार निर्दिष्ट करता है, जब वह क्षेत्र परिवर्तनशील पुनर्स्थापित आकार (न्यूनतम न किया गया हो और न अधिकतम) में हो। |
| [getRestoredTop()](#getRestoredTop--) | यह तत्व सामान्य दृश्य के शीर्ष स्लाइड क्षेत्र का आकार निर्धारित करता है, जब वह क्षेत्र परिवर्तनशील पुनर्स्थापित आकार (न्यूनतम न किया गया हो और न अधिकतम) में हो। |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

निर्दिष्ट करता है कि क्या एप्लिकेशन को सामान्य दृश्य मोड में किसी भी सामग्री क्षेत्र में रूपरेखा सामग्री प्रदर्शित करते समय आइकन दिखाने चाहिए। पढ़ें/लिखें बूलियन।

**रिटर्न:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

निर्दिष्ट करता है कि क्या एप्लिकेशन को सामान्य दृश्य मोड में किसी भी सामग्री क्षेत्र में रूपरेखा सामग्री प्रदर्शित करते समय आइकन दिखाने चाहिए। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

निर्दिष्ट करता है कि जब साइड क्षेत्र पर्याप्त छोटा हो तो वर्टिकल स्प्लिटर को न्यूनतम स्थिति में स्नैप करना चाहिए या नहीं। पढ़ें/लिखें बूलियन।

**रिटर्न:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

निर्दिष्ट करता है कि जब साइड क्षेत्र पर्याप्त छोटा हो तो वर्टिकल स्प्लिटर को न्यूनतम स्थिति में स्नैप करना चाहिए या नहीं। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

निर्दिष्ट करता है कि वर्टिकल स्प्लिटर बार कौन सी स्थिति में दिखाया जाना चाहिए। एक वर्टिकल स्प्लिटर बार स्लाइड को साइड कंटेंट क्षेत्र से अलग करता है।

**रिटर्न:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

निर्दिष्ट करता है कि वर्टिकल स्प्लिटर बार कौन सी स्थिति में दिखाया जाना चाहिए। एक वर्टिकल स्प्लिटर बार स्लाइड को साइड कंटेंट क्षेत्र से अलग करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

निर्दिष्ट करता है कि हॉरिज़ोन्टल स्प्लिटर बार कौन सी स्थिति में दिखाया जाना चाहिए। एक हॉरिज़ोन्टल स्प्लिटर बार स्लाइड को स्लाइड के नीचे की सामग्री क्षेत्र से अलग करता है।

**रिटर्न:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

निर्दिष्ट करता है कि हॉरिज़ोन्टल स्प्लिटर बार कौन सी स्थिति में दिखाया जाना चाहिए। एक हॉरिज़ोन्टल स्प्लिटर बार स्लाइड को स्लाइड के नीचे की सामग्री क्षेत्र से अलग करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

निर्दिष्ट करता है कि क्या उपयोगकर्ता तीन सामग्री क्षेत्रों वाले मानक सामान्य दृश्य के बजाय पूर्ण-खिड़की एकल-सामग्री क्षेत्र देखना पसंद करता है। यदि सक्षम किया गया है, तो एप्लिकेशन एक सामग्री क्षेत्र को पूरे विंडो में प्रदर्शित करने का विकल्प चुन सकता है। पढ़ें/लिखें बूलियन।

**रिटर्न:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

निर्दिष्ट करता है कि क्या उपयोगकर्ता तीन सामग्री क्षेत्रों वाले मानक सामान्य दृश्य के बजाय पूर्ण-खिड़की एकल-सामग्री क्षेत्र देखना पसंद करता है। यदि सक्षम किया गया है, तो एप्लिकेशन एक सामग्री क्षेत्र को पूरे विंडो में प्रदर्शित करने का विकल्प चुन सकता है। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

यह तत्व सामान्य दृश्य के साइड सामग्री क्षेत्र का आकार निर्दिष्ट करता है, जब वह क्षेत्र परिवर्तनशील पुनर्स्थापित आकार (न्यूनतम न किया गया हो और न अधिकतम) में हो। केवल पढ़ने योग्य [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)।

**रिटर्न:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

यह तत्व सामान्य दृश्य के शीर्ष स्लाइड क्षेत्र का आकार निर्दिष्ट करता है, जब वह क्षेत्र परिवर्तनशील पुनर्स्थापित आकार (न्यूनतम न किया गया हो और न अधिकतम) में हो। केवल पढ़ने योग्य [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)।

**रिटर्न:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)