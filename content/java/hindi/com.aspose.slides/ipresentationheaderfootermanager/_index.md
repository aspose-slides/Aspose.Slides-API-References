---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides for Java API संदर्भ
description: प्रस्तुति के सभी फ़ूटर, दिनांक-समय और पृष्ठ संख्या प्लेसहोल्डर्स के व्यवहार को रखने वाले प्रबंधक को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ipresentationheaderfootermanager/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

प्रस्तुति के सभी फ़ूटर, दिनांक-समय और पृष्ठ संख्या प्लेसहोल्डर्स के व्यवहार को रखने वाले प्रबंधक को दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | सभी हेडर प्लेसहोल्डर्स की दृश्यता बदलता है, जिसमें नोट्स मास्टर, नोट्स स्लाइड्स और हैंडआउट मास्टर शामिल हैं। |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | सभी फ़ूटर प्लेसहोल्डर्स की दृश्यता बदलता है, जिसमें मास्टर स्लाइड्स, लेआउट स्लाइड्स और सामान्य स्लाइड्स शामिल हैं। |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | सभी पृष्ठ संख्या प्लेसहोल्डर्स की दृश्यता बदलता है, जिसमें मास्टर स्लाइड्स, लेआउट स्लाइड्स और सामान्य स्लाइड्स शामिल हैं। |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | सभी दिनांक-समय प्लेसहोल्डर्स की दृश्यता बदलता है, जिसमें मास्टर स्लाइड्स, लेआउट स्लाइड्स और सामान्य स्लाइड्स शामिल हैं। |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | सभी हेडर प्लेसहोल्डर्स पर टेक्स्ट सेट करता है, जिसमें नोट्स मास्टर, नोट्स स्लाइड्स और हैंडआउट मास्टर शामिल हैं। |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | सभी फ़ूटर प्लेसहोल्डर्स पर टेक्स्ट सेट करता है, जिसमें मास्टर स्लाइड्स, लेआउट स्लाइड्स और सामान्य स्लाइड्स शामिल हैं। |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | सभी दिनांक-समय प्लेसहोल्डर्स पर टेक्स्ट सेट करता है, जिसमें मास्टर स्लाइड्स, लेआउट स्लाइड्स और सामान्य स्लाइड्स शामिल हैं। |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | सभी टाइटल स्लाइड्स और प्रथम लेआउट स्लाइड के लिए फ़ूटर, दिनांक-समय और पृष्ठ संख्या प्लेसहोल्डर्स की दृश्यता बदलता है। |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

सभी हेडर प्लेसहोल्डर्स की दृश्यता बदलता है, जिसमें नोट्स मास्टर, नोट्स स्लाइड्स और हैंडआउट मास्टर शामिल हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - हेडर प्लेसहोल्डर को दृश्य बनाता है, अन्यथा उन्हें छुपाता है। |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

सभी फ़ूटर प्लेसहोल्डर्स की दृश्यता बदलता है, जिसमें मास्टर स्लाइड्स, लेआउट स्लाइड्स और सामान्य स्लाइड्स शामिल हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - फ़ूटर प्लेसहोल्डर को दृश्य बनाता है, अन्यथा उन्हें छुपाता है। |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

सभी पृष्ठ संख्या प्लेसहोल्डर्स की दृश्यता बदलता है, जिसमें मास्टर स्लाइड्स, लेआउट स्लाइड्स और सामान्य स्लाइड्स शामिल हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - पृष्ठ संख्या प्लेसहोल्डर को दृश्य बनाता है, अन्यथा उन्हें छुपाता है। |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

सभी दिनांक-समय प्लेसहोल्डर्स की दृश्यता बदलता है, जिसमें मास्टर स्लाइड्स, लेआउट स्लाइड्स और सामान्य स्लाइड्स शामिल हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - दिनांक-समय प्लेसहोल्डर को दृश्य बनाता है, अन्यथा उन्हें छुपाता है। |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

सभी हेडर प्लेसहोल्डर्स पर टेक्स्ट सेट करता है, जिसमें नोट्स मास्टर, नोट्स स्लाइड्स और हैंडआउट मास्टर शामिल हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए टेक्स्ट। |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

सभी फ़ूटर प्लेसहोल्डर्स पर टेक्स्ट सेट करता है, जिसमें मास्टर स्लाइड्स, लेआउट स्लाइड्स और सामान्य स्लाइड्स शामिल हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए टेक्स्ट। |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

सभी दिनांक-समय प्लेसहोल्डर्स पर टेक्स्ट सेट करता है, जिसमें मास्टर स्लाइड्स, लेआउट स्लाइड्स और सामान्य स्लाइड्स शामिल हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए टेक्स्ट। |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

सभी टाइटल स्लाइड्स और प्रथम लेआउट स्लाइड के लिए फ़ूटर, दिनांक-समय और पृष्ठ संख्या प्लेसहोल्डर्स की दृश्यता बदलता है। टाइटल स्लाइड्स — पहली लेआउट स्लाइड पर आधारित स्लाइड्स (पहली लेआउट के प्रकार की परवाह किए बिना)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - प्लेसहोल्डर्स को दृश्य बनाता है, अन्यथा उन्हें छुपाता है। |