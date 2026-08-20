---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides for Java API संदर्भ
description: मास्टर स्लाइड फुटर, डेट-टाइम, पेज नंबर प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर के व्यवहार को धारण करने वाले प्रबंधक का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/imasterslideheaderfootermanager/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

एक प्रबंधक का प्रतिनिधित्व करता है जो मास्टर स्लाइड फुटर, डेट-टाइम, पेज नंबर प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर के व्यवहार को संधारित करता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में मौजूद होते हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | मास्टर स्लाइड फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर हैं। |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | मास्टर स्लाइड पेज नंबर प्लेसहोल्डर और सभी चाइल्ड पेज नंबर प्लेसहोल्डर की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर हैं। |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | मास्टर स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर हैं। |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | मास्टर स्लाइड फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर में टेक्स्ट सेट करता है। |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | मास्टर स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर में टेक्स्ट सेट करता है। |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

मास्टर स्लाइड फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर हैं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - फुटर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा उन्हें छुपाता है। |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

मास्टर स्लाइड पेज नंबर प्लेसहोल्डर और सभी चाइल्ड पेज नंबर प्लेसहोल्डर की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर हैं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - पेज नंबर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा उन्हें छुपाता है। |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

मास्टर स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर हैं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - डेट-टाइम प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा उन्हें छुपाता है। |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

मास्टर स्लाइड फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर में टेक्स्ट सेट करता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर हैं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए टेक्स्ट। |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

मास्टर स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर में टेक्स्ट सेट करता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर हैं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए टेक्स्ट। |