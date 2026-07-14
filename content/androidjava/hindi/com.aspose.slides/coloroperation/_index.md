---
title: ColorOperation
second_title: Aspose.Slides Android के लिए Java API संदर्भ के माध्यम से
description: रंग रूपांतरणों के लिए उपयोग किए जाने वाले विभिन्न रंग संचालन का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/coloroperation/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)  
```
public class ColorOperation implements IColorOperation
```

वर्णन विभिन्न रंग संचालन को दर्शाता है जो रंग रूपांतरणों के लिए उपयोग किए जाते हैं। अपरिवर्तनीय वस्तु।

## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | नया रंग रूपांतरण संचालन बनाता है। |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | नया रंग रूपांतरण संचालन बनाता है। |

## विधियां

| विधि | विवरण |
| --- | --- |
| [getOperationType()](#getOperationType--) | एक संचालन के प्रकार को लौटाता या सेट करता है। |
| [getParameter()](#getParameter--) | एक संचालन का पैरामीटर लौटाता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि दो ColorOperation उदाहरण समान हैं या नहीं। |
| [hashCode()](#hashCode--) | एक विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, जो हैश तालिका जैसे हैशिंग एल्गोरिदम और डेटा संरचनाओं में उपयोग के लिए उपयुक्त है। |

### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

नया रंग रूपांतरण संचालन बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| op | int | संचालन प्रकार। |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

नया रंग रूपांतरण संचालन बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| op | int | संचालन प्रकार। |
| parameter | float | संचालन पैरामीटर। |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

एक संचालन के प्रकार को लौटाता या सेट करता है। केवल-पढ़ने योग्य [ColorTransformOperation](../../com.aspose.slides/colortransformoperation)।

**वापसी:**
int

### getParameter() {#getParameter--}
```
public final float getParameter()
```

एक संचालन का पैरामीटर लौटाता है। केवल-पढ़ने योग्य float।

**वापसी:**
float

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि दो ColorOperation उदाहरण समान हैं या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | वर्तमान ColorOperation के साथ तुलना करने के लिए ColorOperation। |

**वापसी:**
boolean - **true** यदि निर्दिष्ट ColorOperation वर्तमान ColorOperation के समान है; अन्यथा, **false**।

### hashCode() {#hashCode--}
```
public int hashCode()
```

एक विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, जो हैश तालिका जैसे हैशिंग एल्गोरिदम और डेटा संरचनाओं में उपयोग के लिए उपयुक्त है।

**वापसी:**
int