---
title: SensitivityLabel
second_title: Aspose.Slides के लिए Java API संदर्भ
description: Microsoft Purview Information Protection से संवेदनशीलता लेबल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/sensitivitylabel/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Microsoft Purview Information Protection से संवेदनशीलता लेबल को दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getId()](#getId--) | संवेदनशीलता लेबल की आईडी लौटाता या सेट करता है। |
| [setId(String value)](#setId-java.lang.String-) | संवेदनशीलता लेबल की आईडी लौटाता या सेट करता है। |
| [getSiteId()](#getSiteId--) | संवेदनशीलता लेबल नीति से संबंधित Azure Active Directory (Azure AD) साइट पहचानकर्ता लौटाता या सेट करता है जो संवेदनशीलता लेबल का वर्णन करता है। |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | संवेदनशीलता लेबल नीति से संबंधित Azure Active Directory (Azure AD) साइट पहचानकर्ता लौटाता या सेट करता है जो संवेदनशीलता लेबल का वर्णन करता है। |
| [isEnabled()](#isEnabled--) | दर्शाता है कि संवेदनशीलता लेबल सक्षम है या नहीं। |
| [setEnabled(boolean value)](#setEnabled-boolean-) | दर्शाता है कि संवेदनशीलता लेबल सक्षम है या नहीं। |
| [isRemoved()](#isRemoved--) | दर्शाता है कि संवेदनशीलता लेबल हटाया गया था या नहीं। |
| [setRemoved(boolean value)](#setRemoved-boolean-) | दर्शाता है कि संवेदनशीलता लेबल हटाया गया था या नहीं। |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | संवेदनशीलता लेबल के असाइनमेंट विधि को लौटाता या सेट करता है। |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | संवेदनशीलता लेबल के असाइनमेंट विधि को लौटाता या सेट करता है। |
| [getContentMarkTypes()](#getContentMarkTypes--) | फ़ाइल पर लागू होने वाले कंटेंट मार्किंग प्रकारों की सूची लौटाता है। |
### getId() {#getId--}
```
public final String getId()
```

संवेदनशीलता लेबल की आईडी लौटाता या सेट करता है। पढ़ें/लिखें String.

**वापसी:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

संवेदनशीलता लेबल की आईडी लौटाता या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

संवेदनशीलता लेबल नीति से संबंधित Azure Active Directory (Azure AD) साइट पहचानकर्ता लौटाता या सेट करता है जो संवेदनशीलता लेबल का वर्णन करता है। पढ़ें/लिखें java.util.UUID.

**वापसी:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

संवेदनशीलता लेबल नीति से संबंधित Azure Active Directory (Azure AD) साइट पहचानकर्ता लौटाता या सेट करता है जो संवेदनशीलता लेबल का वर्णन करता है। पढ़ें/लिखें java.util.UUID.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

संवेदनशीलता लेबल सक्षम है या नहीं, दर्शाता है।

**वापसी:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

संवेदनशीलता लेबल सक्षम है या नहीं, दर्शाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

संवेदनशीलता लेबल हटाया गया था या नहीं, दर्शाता है।

**वापसी:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

संवेदनशीलता लेबल हटाया गया था या नहीं, दर्शाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

संवेदनशीलता लेबल के असाइनमेंट विधि को लौटाता या सेट करता है। पढ़ें/लिखें [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**वापसी:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

संवेदनशीलता लेबल के असाइनमेंट विधि को लौटाता या सेट करता है। पढ़ें/लिखें [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

फ़ाइल पर लागू होने वाले कंटेंट मार्किंग प्रकारों की सूची लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - कंटेंट प्रकारों की सूची [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)