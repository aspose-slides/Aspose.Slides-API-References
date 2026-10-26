---
title: ISensitivityLabel
second_title: Aspose.Slides for Java API Reference
description: Represents the sensitivity label from Microsoft Purview Information Protection.
type: docs
url: /hi/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Microsoft Purview Information Protection से संवेदनशीलता लेबल का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getId()](#getId--) | संवेदनशीलता लेबल की आईडी को प्राप्त करता है या सेट करता है। |
| [setId(String value)](#setId-java.lang.String-) | संवेदनशीलता लेबल की आईडी को प्राप्त करता है या सेट करता है। |
| [getSiteId()](#getSiteId--) | संवेदनशीलता लेबल नीति से संबंधित Azure Active Directory (Azure AD) साइट पहचानकर्ता को प्राप्त करता है या सेट करता है, जो संवेदनशीलता लेबल का वर्णन करती है। |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | संवेदनशीलता लेबल नीति से संबंधित Azure Active Directory (Azure AD) साइट पहचानकर्ता को प्राप्त करता है या सेट करता है, जो संवेदनशीलता लेबल का वर्णन करती है। |
| [isEnabled()](#isEnabled--) | यह दर्शाता है कि संवेदनशीलता लेबल सक्षम है या नहीं। |
| [setEnabled(boolean value)](#setEnabled-boolean-) | यह दर्शाता है कि संवेदनशीलता लेबल सक्षम है या नहीं। |
| [isRemoved()](#isRemoved--) | यह दर्शाता है कि संवेदनशीलता लेबल हटा दिया गया है या नहीं। |
| [setRemoved(boolean value)](#setRemoved-boolean-) | यह दर्शाता है कि संवेदनशीलता लेबल हटा दिया गया है या नहीं। |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | संवेदनशीलता लेबल के लिए असाइनमेंट मेथड को प्राप्त करता है या सेट करता है। |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | संवेदनशीलता लेबल के लिए असाइनमेंट मेथड को प्राप्त करता है या सेट करता है। |
| [getContentMarkTypes()](#getContentMarkTypes--) | फ़ाइल पर लागू की जाने वाली सामग्री मार्किंग के प्रकारों की सूची को लौटाता है। |
### getId() {#getId--}
```
public abstract String getId()
```

संवेदनशीलता लेबल की आईडी को प्राप्त करता है या सेट करता है। Read/write String.

**वापसी:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

संवेदनशीलता लेबल की आईडी को प्राप्त करता है या सेट करता है। Read/write String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

Azure Active Directory (Azure AD) साइट पहचानकर्ता को प्राप्त करता है या सेट करता है, जो संवेदनशीलता लेबल नीति से संबंधित है और संवेदनशीलता लेबल का वर्णन करती है। Read/write java.util.UUID.

**वापसी:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

Azure Active Directory (Azure AD) साइट पहचानकर्ता को प्राप्त करता है या सेट करता है, जो संवेदनशीलता लेबल नीति से संबंधित है और संवेदनशीलता लेबल का वर्णन करती है। Read/write java.util.UUID.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

संवेदनशीलता लेबल सक्षम है या नहीं, यह दर्शाता है।

**वापसी:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

संवेदनशीलता लेबल सक्षम है या नहीं, यह दर्शाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

संवेदनशीलता लेबल हटा दिया गया है या नहीं, यह दर्शाता है।

**वापसी:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

संवेदनशीलता लेबल हटा दिया गया है या नहीं, यह दर्शाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

संवेदनशीलता लेबल के लिए असाइनमेंट मेथड को प्राप्त करता है या सेट करता है। Read/write [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**वापसी:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

संवेदनशीलता लेबल के लिए असाइनमेंट मेथड को प्राप्त करता है या सेट करता है। Read/write [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

फ़ाइल पर लागू की जाने वाली सामग्री मार्किंग के प्रकारों की सूची को लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - सामग्री प्रकारों की सूची [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)