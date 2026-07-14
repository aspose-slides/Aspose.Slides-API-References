---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides for Android के माध्यम से Java API रेफ़रेंस
description: एक प्रबंधक का प्रतिनिधित्व करता है जो मास्टर स्लाइड फ़ूटर, दिनांक-समय, पृष्ठ संख्या प्लेसहोल्डर्स और सभी चाइल्ड प्लेसहॉल्डर्स के व्यवहार को धारण करता है।
type: docs
url: /hi/com.aspose.slides/imasterslideheaderfootermanager/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

एक प्रबंधक का प्रतिनिधित्व करता है जो मास्टर स्लाइड फ़ूटर, दिनांक-समय, पृष्ठ संख्या प्लेसहोल्डर्स और सभी चाइल्ड प्लेसहोल्डर्स का व्यवहार धारण करता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | मास्टर स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहोल्डर्स की दृश्यमानता बदलता है। |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | मास्टर स्लाइड पेज नंबर प्लेसहोल्डर और सभी चाइल्ड पेज नंबर प्लेसहोल्डर्स की दृश्यमानता बदलता है। |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | मास्टर स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर्स की दृश्यमानता बदलता है। |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | मास्टर स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहोल्डर्स पर पाठ सेट करता है। |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | मास्टर स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर्स पर पाठ सेट करता है। |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

मास्टर स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहोल्डर्स की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - फ़ूटर प्लेसहोल्डर्स को दृश्यमान बनाता है, अन्यथा उन्हें छिपा देता है। |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

मास्टर स्लाइड पेज नंबर प्लेसहोल्डर और सभी चाइल्ड पेज नंबर प्लेसहोल्डर्स की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - पेज नंबर प्लेसहोल्डर्स को दृश्यमान बनाता है, अन्यथा उन्हें छिपा देता है। |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

मास्टर स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर्स की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - डेट-टाइम प्लेसहोल्डर्स को दृश्यमान बनाता है, अन्यथा उन्हें छिपा देता है। |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

मास्टर स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहोल्डर्स पर पाठ सेट करता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने हेतु पाठ। |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

मास्टर स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर्स पर पाठ सेट करता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर लेआउट स्लाइड्स और निर्भर स्लाइड्स में सम्मिलित होते हैं। निर्भर लेआउट स्लाइड्स और स्लाइड्स मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने हेतु पाठ। |