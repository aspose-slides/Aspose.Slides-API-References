---
title: ColorOperation
second_title: Aspose.Slides for Java API संदर्भ
description: रंग परिवर्तन के लिए उपयोग किए जाने वाले विभिन्न रंग संचालन को दर्शाता है।
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

विभिन्न रंग परिवर्तन के लिए उपयोग होने वाले विभिन्न रंग संचालन को दर्शाता है। अपरिवर्तनीय वस्तु।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | नया रंग परिवर्तन संचालन बनाता है। |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | नया रंग परिवर्तन संचालन बनाता है। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getOperationType()](#getOperationType--) | एक ऑपरेशन का प्रकार प्राप्त करता है या सेट करता है। |
| [getParameter()](#getParameter--) | एक ऑपरेशन का पैरामीटर लौटाता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि दो ColorOperation इंस्टेंसेस बराबर हैं या नहीं। |
| [hashCode()](#hashCode--) | विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा स्ट्रक्चर में उपयोग के योग्य। |

### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

नया रंग परिवर्तन संचालन बनाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| op | int | ऑपरेशन प्रकार। |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

नया रंग परिवर्तन संचालन बनाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| op | int | ऑपरेशन प्रकार। |
| parameter | float | ऑपरेशन पैरामीटर। |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

एक ऑपरेशन का प्रकार प्राप्त करता है या सेट करता है। केवल-पढ़नेयोग्य [ColorTransformOperation](../../com.aspose.slides/colortransformoperation)।

**वापसी:**  
int

### getParameter() {#getParameter--}
```
public final float getParameter()
```

एक ऑपरेशन का पैरामीटर लौटाता है। केवल-पढ़नेयोग्य float।

**वापसी:**  
float

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि दो ColorOperation इंस्टेंसेस बराबर हैं या नहीं।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | वर्तमान ColorOperation के साथ तुलना करने हेतु ColorOperation। |

**वापसी:**  
boolean - **true** यदि निर्दिष्ट ColorOperation वर्तमान ColorOperation के बराबर है; अन्यथा, **false**।

### hashCode() {#hashCode--}
```
public int hashCode()
```

विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा स्ट्रक्चर में उपयोग के योग्य।

**वापसी:**  
int