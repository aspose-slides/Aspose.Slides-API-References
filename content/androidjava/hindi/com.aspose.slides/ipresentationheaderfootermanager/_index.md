---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides for Android, Java API रेफ़रेंस के द्वारा
description: एक प्रबंधक का प्रतिनिधित्व करता है जो प्रस्तुति के सभी फुटर, दिनांक-समय और पृष्ठ संख्या प्लेसहोल्डर के व्यवहार को संभालता है।
type: docs
url: /hi/com.aspose.slides/ipresentationheaderfootermanager/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

एक प्रबंधक का प्रतिनिधित्व करता है जो प्रस्तुति के सभी फुटर, दिनांक-समय और पृष्ठ संख्या प्लेसहोल्डर का व्यवहार संभालता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | सभी हेडर प्लेसहोल्डर की दृश्यता बदलता है, जिसमें नोट्स मास्टर, नोट्स स्लाइड और हैंडआउट मास्टर शामिल हैं। |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | सभी फुटर प्लेसहोल्डर की दृश्यता बदलता है, जिसमें मास्टर स्लाइड, लेआउट स्लाइड और स्लाइड शामिल हैं। |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | सभी पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है, जिसमें मास्टर स्लाइड, लेआउट स्लाइड और स्लाइड शामिल हैं। |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | सभी दिनांक-समय प्लेसहोल्डर की दृश्यता बदलता है, जिसमें मास्टर स्लाइड, लेआउट स्लाइड और स्लाइड शामिल हैं। |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | सभी हेडर प्लेसहोल्डर में टेक्स्ट सेट करता है, जिसमें नोट्स मास्टर, नोट्स स्लाइड और हैंडआउट मास्टर शामिल हैं। |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | सभी फुटर प्लेसहोल्डर में टेक्स्ट सेट करता है, जिसमें मास्टर स्लाइड, लेआउट स्लाइड और स्लाइड शामिल हैं। |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | सभी दिनांक-समय प्लेसहोल्डर में टेक्स्ट सेट करता है, जिसमें मास्टर स्लाइड, लेआउट स्लाइड और स्लाइड शामिल हैं। |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | सभी टाइटल स्लाइड और पहली लेआउट स्लाइड के लिए फुटर, दिनांक-समय और पेज नंबर प्लेसहॉल्डर की दृश्यता बदलता है। |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

सभी हेडर प्लेसहोल्डर की दृश्यता बदलता है, जिसमें नोट्स मास्टर, नोट्स स्लाइड और हैंडआउट मास्टर शामिल हैं।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - हेडर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा उन्हें छुपाता है। |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

सभी फुटर प्लेसहोल्डर की दृश्यता बदलता है, जिसमें मास्टर स्लाइड, लेआउट स्लाइड और स्लाइड शामिल हैं।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - फुटर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा उन्हें छुपाता है। |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

सभी पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है, जिसमें मास्टर स्लाइड, लेआउट स्लाइड और स्लाइड शामिल हैं।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - पेज नंबर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा उन्हें छुपाता है। |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

सभी दिनांक-समय प्लेसहोल्डर की दृश्यता बदलता है, जिसमें मास्टर स्लाइड, लेआउट स्लाइड और स्लाइड शामिल हैं।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - दिनांक-समय प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा उन्हें छुपाता है। |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

सभी हेडर प्लेसहोल्डर में टेक्स्ट सेट करता है, जिसमें नोट्स मास्टर, नोट्स स्लाइड और हैंडआउट मास्टर शामिल हैं।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिये टेक्स्ट। |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

सभी फुटर प्लेसहोल्डर में टेक्स्ट सेट करता है, जिसमें मास्टर स्लाइड, लेआउट स्लाइड और स्लाइड शामिल हैं।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिये टेक्स्ट। |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

सभी दिनांक-समय प्लेसहोल्डर में टेक्स्ट सेट करता है, जिसमें मास्टर स्लाइड, लेआउट स्लाइड और स्लाइड शामिल हैं।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिये टेक्स्ट। |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

सभी टाइटल स्लाइड और पहली लेआउट स्लाइड के लिए फुटर, दिनांक-समय और पेज नंबर प्लेसहॉल्डर की दृश्यता बदलता है। टाइटल स्लाइड – पहली लेआउट स्लाइड पर आधारित स्लाइड (पहली लेआउट के प्रकार की परवाह किए बिना)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा उन्हें छुपाता है। |