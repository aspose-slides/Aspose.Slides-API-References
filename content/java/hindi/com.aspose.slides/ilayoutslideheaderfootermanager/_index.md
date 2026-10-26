---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides for Java API संदर्भ
description: लेआउट स्लाइड फ़ुटर, दिनांक-समय, पृष्ठ संख्या प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर के व्यवहार को संभालने वाले प्रबंधक को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

लेआउट स्लाइड फ़ुटर, दिनांक-समय, पृष्ठ संख्या प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर के व्यवहार को संभालने वाले मैनेजर को दर्शाता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइडों में शामिल हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर रहती हैं।

## Methods

| Method | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | लेआउट स्लाइड फ़ुटर प्लेसहोल्डर और सभी चाइल्ड फ़ुटर प्लेसहोल्डर की दृश्यता बदलता है। |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | लेआउट स्लाइड पृष्ठ संख्या प्लेसहोल्डर और सभी चाइल्ड पृष्ठ संख्या प्लेसहोल्डर की दृश्यता बदलता है। |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | लेआउट स्लाइड दिनांक-समय प्लेसहोल्डर और सभी चाइल्ड दिनांक-समय प्लेसहोल्डर की दृश्यता बदलता है। |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | लेआउट स्लाइड फ़ुटर प्लेसहोल्डर और सभी चाइल्ड फ़ुटर प्लेसहोल्डर में पाठ सेट करता है। |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | लेआउट स्लाइड दिनांक-समय प्लेसहोल्डर और सभी चाइल्ड दिनांक-समय प्लेसहोल्डर में पाठ सेट करता है। |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

लेआउट स्लाइड फ़ुटर प्लेसहोल्डर और सभी चाइल्ड फ़ुटर प्लेसहोल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइडों में शामिल हैं। निर्भर स्लाइडें मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर रहती हैं।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - फ़ुटर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा उन्हें छुपा देता है। |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

लेआउट स्लाइड पृष्ठ संख्या प्लेसहोल्डर और सभी चाइल्ड पृष्ठ संख्या प्लेसहोल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइडों में शामिल हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर रहती हैं।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - पृष्ठ संख्या प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा उन्हें छुपा देता है। |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

लेआउट स्लाइड दिनांक-समय प्लेसहोल्डर और सभी चाइल्ड दिनांक-समय प्लेसहोल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइडों में शामिल हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर रहती हैं।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - दिनांक-समय प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा उन्हें छुपा देता है। |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

लेआउट स्लाइड फ़ुटर प्लेसहोल्डर और सभी चाइल्ड फ़ुटर प्लेसहोल्डर में पाठ सेट करता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइडों में शामिल हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर रहती हैं।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए पाठ। |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

लेआउट स्लाइड दिनांक-समय प्लेसहोल्डर और सभी चाइल्ड दिनांक-समय प्लेसहोल्डर में पाठ सेट करता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइडों में शामिल हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर रहती हैं।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए पाठ। |