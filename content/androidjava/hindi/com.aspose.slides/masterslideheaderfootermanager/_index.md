---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस के माध्यम से
description: मास्टर स्लाइड फुटर, डेट-टाइम, पेज नंबर प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर के व्यवहार को धारण करने वाले प्रबंधक को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/masterslideheaderfootermanager/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)  
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

मास्टर स्लाइड फुटर, तिथि-समय, पेज नंबर प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर के व्यवहार को धारण करने वाले प्रबंधक को दर्शाता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग और उस पर निर्भर होते हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | मास्टर स्लाइड फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर की दृश्यता बदलता है। |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | मास्टर स्लाइड पेज नंबर प्लेसहोल्डर और सभी चाइल्ड पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है। |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | मास्टर स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर की दृश्यता बदलता है। |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | मास्टर स्लाइड फुटर प्लेसहॉल्डर और सभी चाइल्ड फुटर प्लेसहॉल्डर को टेक्स्ट सेट करता है। |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | मास्टर स्लाइड डेट-टाइम प्लेसहॉल्डर और सभी चाइल्ड डेट-टाइम प्लेसहॉल्डर को टेक्स्ट सेट करता है। |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

मास्टर स्लाइड फुटर प्लेसहॉल्डर और सभी चाइल्ड फुटर प्लेसहॉल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहॉल्डर का अर्थ है कि प्लेसहॉल्डर निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग और उस पर निर्भर होते हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - फुटर प्लेसहॉल्डर को दृश्यमान बनाता है, अन्यथा - उन्हें छिपाता है। |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

मास्टर स्लाइड पेज नंबर प्लेसहॉल्डर और सभी चाइल्ड पेज नंबर प्लेसहॉल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहॉल्डर का अर्थ है कि प्लेसहॉल्डर निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग और उस पर निर्भर होते हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - पेज नंबर प्लेसहॉल्डर को दृश्यमान बनाता है, अन्यथा - उन्हें छिपाता है। |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

मास्टर स्लाइड डेट-टाइम प्लेसहॉल्डर और सभी चाइल्ड डेट-टाइम प्लेसहॉल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहॉल्डर का अर्थ है कि प्लेसहॉल्डर निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग और उस पर निर्भर होते हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - डेट-टाइम प्लेसहॉल्डर को दृश्यमान बनाता है, अन्यथा - उन्हें छिपाता है। |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

मास्टर स्लाइड फुटर प्लेसहॉल्डर और सभी चाइल्ड फुटर प्लेसहॉल्डर को टेक्स्ट सेट करता है। चाइल्ड प्लेसहॉल्डर का अर्थ है कि प्लेसहॉल्डर निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग और उस पर निर्भर होते हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिये टेक्स्ट। |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

मास्टर स्लाइड डेट-टाइम प्लेसहॉल्डर और सभी चाइल्ड डेट-टाइम प्लेसहॉल्डर को टेक्स्ट सेट करता है। चाइल्ड प्लेसहॉल्डर का अर्थ है कि प्लेसहॉल्डर निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग और उस पर निर्भर होते हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिये टेक्स्ट। |