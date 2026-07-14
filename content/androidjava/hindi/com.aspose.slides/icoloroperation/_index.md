---
title: IColorOperation
second_title: Aspose.Slides for Android via Java API Reference
description: Represents different color operations used for color transformations.
type: docs
url: /hi/com.aspose.slides/icoloroperation/
---```
public interface IColorOperation
```

रंग परिवर्तन के लिए उपयोग किए जाने वाले विभिन्न रंग संचालन का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getOperationType()](#getOperationType--) | ऑपरेशन के प्रकार को लौटाता या सेट करता है। |
| [getParameter()](#getParameter--) | ऑपरेशन का एक पैरामीटर लौटाता है। |
### getOperationType() {#getOperationType--}
```
public abstract int getOperationType()
```


ऑपरेशन के प्रकार को लौटाता या सेट करता है। केवल पढ़ने योग्य [ColorTransformOperation](../../com.aspose.slides/colortransformoperation)।

**वापसी:**
int
### getParameter() {#getParameter--}
```
public abstract float getParameter()
```


ऑपरेशन का एक पैरामीटर लौटाता है। केवल पढ़ने योग्य float।

**वापसी:**
float