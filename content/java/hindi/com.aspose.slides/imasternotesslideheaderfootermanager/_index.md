---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Java API संदर्भ
description: एक मैनेजर का प्रतिनिधित्व करता है जो मास्टर नोट्स स्लाइड फ़ूटर, डेट-टाइम, पेज नंबर प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर के व्यवहार को रखता है।
type: docs
url: /hi/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

मास्टर नोट्स स्लाइड फ़ूटर, डेट-टाइम, पेज नंबर प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर का व्यवहार नियंत्रित करने वाले मैनेजर को दर्शाता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | मास्टर नोट्स स्लाइड हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर की दृश्यमानता बदलता है। |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | मास्टर नोट्स स्लाइड हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर में टेक्स्ट सेट करता है। |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | मास्टर नोट्स स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहोल्डर की दृश्यमानता बदलता है। |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | मास्टर नोट्स स्लाइड पेज नंबर प्लेसहोल्डर और सभी चाइल्ड पेज नंबर प्लेसहोल्डर की दृश्यमानता बदलता है। |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | मास्टर नोट्स स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर की दृश्यमानता बदलता है। |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | मास्टर नोट्स स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहोल्डर में टेक्स्ट सेट करता है। |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | मास्टर नोट्स स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर में टेक्स्ट सेट करता है। |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

मास्टर नोट्स स्लाइड हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - हेडर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा - उन्हें छिपा देता है। |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

मास्टर नोट्स स्लाइड हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर में टेक्स्ट सेट करता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए टेक्स्ट। |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

मास्टर नोट्स स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहोल्डर की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - फ़ूटर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा - उन्हें छिपा देता है। |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

मास्टर नोट्स स्लाइड पेज नंबर प्लेसहोल्डर और सभी चाइल्ड पेज नंबर प्लेसहोल्डर की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - पेज नंबर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा - उन्हें छिपा देता है। |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

मास्टर नोट्स स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - डेट-टाइम प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा - उन्हें छिपा देता है। |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

मास्टर नोट्स स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहोल्डर में टेक्स्ट सेट करता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए टेक्स्ट। |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

मास्टर नोट्स स्लाइड डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर में टेक्स्ट सेट करता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर नोट्स स्लाइड्स में सम्मिलित होते हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए टेक्स्ट। |