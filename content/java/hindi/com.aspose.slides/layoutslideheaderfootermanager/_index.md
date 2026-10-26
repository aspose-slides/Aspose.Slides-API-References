---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides के लिए Java API संदर्भ
description: लेआउट स्लाइड फुटर, डेट-टाइम, पेज नंबर प्लेसहोल्डर्स और सभी चाइल्ड प्लेसहोल्डर्स के व्यवहार को संभालने वाले प्रबंधक का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/layoutslideheaderfootermanager/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

लेआउट स्लाइड फुटर, डेट-टाइम, पेज नंबर प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर्स का व्यवहार संभालने वाले प्रबंधक का प्रतिनिधित्व करता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर स्लाइड्स लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | लेआउट स्लाइड फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डरों की दृश्यमानता बदलता है। |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | लेआउट स्लाइड पेज नंबर प्लेसहोल्डर और सभी चाइल्ड पेज नंबर प्लेसहोल्डरों की दृश्यमानता बदलता है। |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | लेआउट स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डरों की दृश्यमानता बदलता है। |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | लेआउट स्लाइड फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डरों में पाठ सेट करता है। |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | लेआउट स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डरों में पाठ सेट करता है। |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

लेआउट स्लाइड फुटर प्लेसहॉल्डर और सभी चाइल्ड फुटर प्लेसहॉल्डरों की दृश्यमानता बदलता है। चाइल्ड प्लेसहॉल्डर का अर्थ है कि प्लेसहॉल्डर निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - फुटर प्लेसहॉल्डर को दृश्यमान बनाता है, अन्यथा - उन्हें छिपा देता है। |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

लेआउट स्लाइड पेज नंबर प्लेसहॉल्डर और सभी चाइल्ड पेज नंबर प्लेसहॉल्डरों की दृश्यमानता बदलता है। चाइल्ड प्लेसहॉल्डर का अर्थ है कि प्लेसहॉल्डर निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर स्लाइड्स लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - पेज नंबर प्लेसहॉल्डर को दृश्यमान बनाता है, अन्यथा - उन्हें छिपा देता है। |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

लेआउट स्लाइड डेट-टाइम प्लेसहॉल्डर और सभी चाइल्ड डेट-टाइम प्लेसहॉल्डरों की दृश्यमानता बदलता है। चाइल्ड प्लेसहॉल्डर का अर्थ है कि प्लेसहॉल्डर निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर स्लाइड्स लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - डेट-टाइम प्लेसहॉल्डर को दृश्यमान बनाता है, अन्यथा - उन्हें छिपा देता है। |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

लेआउट स्लाइड फुटर प्लेसहॉल्डर और सभी चाइल्ड फुटर प्लेसहॉल्डरों में पाठ सेट करता है। चाइल्ड प्लेसहॉल्डर का अर्थ है कि प्लेसहॉल्डर निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर स्लाइड्स लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए पाठ। |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

लेआउट स्लाइड डेट-टाइम प्लेसहॉल्डर और सभी चाइल्ड डेट-टाइम प्लेसहॉल्डरों में पाठ सेट करता है। चाइल्ड प्लेसहॉल्डर का अर्थ है कि प्लेसहॉल्डर निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर स्लाइड्स लेआउट स्लाइड का उपयोग करती हैं और उससे निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए पाठ। |