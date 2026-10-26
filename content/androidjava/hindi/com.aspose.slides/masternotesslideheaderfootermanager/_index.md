---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: एक प्रबंधक को दर्शाता है जो master notes slide के फुटर, डेट-टाइम, पेज नंबर प्लेसहोल्डर्स और सभी चाइल्ड प्लेसहोल्डर्स के व्यवहार को रखता है।
type: docs
url: /hi/com.aspose.slides/masternotesslideheaderfootermanager/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager), [com.aspose.slides.BaseHandoutNotesSlideHeaderFooterManager](../../com.aspose.slides/basehandoutnotesslideheaderfootermanager)

**सभी लागू इंटरफेस:**  
[com.aspose.slides.IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)  
```
public final class MasterNotesSlideHeaderFooterManager extends BaseHandoutNotesSlideHeaderFooterManager implements IMasterNotesSlideHeaderFooterManager
```

एक प्रबंधक का प्रतिनिधित्व करता है जो master notes slide के फुटर, तिथि-समय, पृष्ठ संख्या प्लेसहोल्डर्स और सभी चाइल्ड प्लेसहोल्डर्स के व्यवहार को रखता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स में समाहित होते हैं। निर्भर नोट्स स्लाइड्स master notes slide को उपयोग करती हैं और उस पर निर्भर करती हैं।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | master notes slide हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर्स की विज़िबिलिटी बदलता है। |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | master notes slide हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर्स में पाठ सेट करता है। |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | master slide फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर्स की विज़िबिलिटी बदलता है। |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | master slide पेज नंबर प्लेसहोल्डर और सभी चाइल्ड पेज नंबर प्लेसहोल्डर्स की विज़िबिलिटी बदलता है। |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | master slide डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर्स की विज़िबिलिटी बदलता है। |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | master slide फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर्स में पाठ सेट करता है। |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | master slide डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर्स में पाठ सेट करता है। |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public final void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

master notes slide हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर्स की विज़िबिलिटी बदलता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स में समाहित होते हैं। निर्भर नोट्स स्लाइड्स master notes slide को उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - हेडर प्लेसहोल्डर्स को दृश्यमान बनाता है, अन्यथा - उन्हें छिपा देता है। |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public final void setHeaderAndChildHeadersText(String text)
```

master notes slide हेडर प्लेसहोल्डर और सभी चाइल्ड हेडर प्लेसहोल्डर्स में पाठ सेट करता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स में समाहित होते हैं। निर्भर नोट्स स्लाइड्स master notes slide को उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए पाठ। |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

master slide फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर्स की विज़िबिलिटी बदलता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स में समाहित होते हैं। निर्भर नोट्स स्लाइड्स master notes slide को उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - फुटर प्लेसहोल्डर्स को दृश्यमान बनाता है, अन्यथा - उन्हें छिपा देता है। |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

master slide पेज नंबर प्लेसहोल्डर और सभी चाइल्ड पेज नंबर प्लेसहोल्डर्स की विज़िबिलिटी बदलता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स में समाहित होते हैं। निर्भर नोट्स स्लाइड्स master notes slide को उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - पेज नंबर प्लेसहोल्डर्स को दृश्यमान बनाता है, अन्यथा - उन्हें छिपा देता है। |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

master slide डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर्स की विज़िबिलिटी बदलता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स में समाहित होते हैं। निर्भर नोट्स स्लाइड्स master notes slide को उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - डेट-टाइम प्लेसहोल्डर्स को दृश्यमान बनाता है, अन्यथा - उन्हें छिपा देता है। |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

master slide फुटर प्लेसहोल्डर और सभी चाइल्ड फुटर प्लेसहोल्डर्स में पाठ सेट करता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स में समाहित होते हैं। निर्भर नोट्स स्लाइड्स master notes slide को उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए पाठ। |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

master slide डेट-टाइम प्लेसहोल्डर और सभी चाइल्ड डेट-टाइम प्लेसहोल्डर्स में पाठ सेट करता है। चाइल्ड प्लेसहोल्डर्स का अर्थ है कि प्लेसहोल्डर्स निर्भर नोट्स स्लाइड्स में समाहित होते हैं। निर्भर नोट्स स्लाइड्स master notes slide को उपयोग करती हैं और उस पर निर्भर करती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए पाठ। |