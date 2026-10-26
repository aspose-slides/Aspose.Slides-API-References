---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Android के द्वारा Java API संदर्भ
description: एक प्रबंधक को दर्शाता है जो मास्टर नोट्स स्लाइड के फुटर, दिनांक-समय, पेज नंबर प्लेसहोल्डर्स और सभी चाइल्ड प्लेसहोल्डर्स के व्यवहार को रखता है।
type: docs
url: /hi/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

एक प्रबंधक का प्रतिनिधित्व करता है जो मास्टर नोट्स स्लाइड फुटर, दिनांक-समय, पेज नंबर प्लेसहोल्डर्स और सभी चाइल्ड प्लेसहोल्डर्स के व्यवहार को रखता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स पर मौजूद हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | मास्टर नोट्स स्लाइड हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर्स की दृश्यमानता बदलता है। |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | मास्टर नोट्स स्लाइड हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर्स में पाठ सेट करता है। |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | मास्टर नोट्स स्लाइड फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर्स की दृश्यमानता बदलता है। |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | मास्टर नोट्स स्लाइड पेज नंबर प्लेसहोल्डर और सभी चाइल्ड पेज नंबर प्लेसहोल्डर्स की दृश्यमानता बदलता है। |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | मास्टर नोट्स स्लाइड दिनांक-समय प्लेसहोल्डर और सभी चाइल्ड दिनांक-समय प्लेसहोल्डर्स की दृश्यमानता बदलता है। |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | मास्टर नोट्स स्लाइड फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर्स में पाठ सेट करता है। |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | मास्टर नोट्स स्लाइड दिनांक-समय प्लेसहोल्डर और सभी चाइल्ड दिनांक-समय प्लेसहोल्डर्स में पाठ सेट करता है। |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

मास्टर नोट्स स्लाइड हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर्स की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स पर मौजूद हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - हेडर प्लेसहोल्डर्स को दृश्यमान बनाता है, अन्यथा उन्हें छुपाता है। |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

मास्टर नोट्स स्लाइड हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर्स में पाठ सेट करता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स पर मौजूद हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने हेतु पाठ। |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

मास्टर नोट्स स्लाइड फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर्स की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स पर मौजूद हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - फुटर प्लेसहोल्डर्स को दृश्यमान बनाता है, अन्यथा उन्हें छुपाता है। |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

मास्टर नोट्स स्लाइड पेज नंबर प्लेसहोल्डर और सभी चाइल्ड पेज नंबर प्लेसहोल्डर्स की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स पर मौजूद हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - पेज नंबर प्लेसहोल्डर्स को दृश्यमान बनाता है, अन्यथा उन्हें छुपाता है। |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

मास्टर नोट्स स्लाइड दिनांक-समय प्लेसहोल्डर और सभी चाइल्ड दिनांक-समय प्लेसहोल्डर्स की दृश्यमानता बदलता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स पर मौजूद हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - दिनांक-समय प्लेसहोल्डर्स को दृश्यमान बनाता है, अन्यथा उन्हें छुपाता है। |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

मास्टर नोट्स स्लाइड फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर्स में पाठ सेट करता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स पर मौजूद हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने हेतु पाठ। |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

मास्टर नोट्स स्लाइड दिनांक-समय प्लेसहोल्डर और सभी चाइल्ड दिनांक-समय प्लेसहोल्डर्स में पाठ सेट करता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स पर मौजूद हैं। निर्भर नोट्स स्लाइड्स मास्टर नोट्स स्लाइड का उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने हेतु पाठ। |