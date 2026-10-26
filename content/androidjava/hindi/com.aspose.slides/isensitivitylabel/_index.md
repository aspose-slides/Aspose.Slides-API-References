---
title: ISensitivityLabel
second_title: Aspose.Slides for Android via Java API Reference
description: Microsoft Purview Information Protection से संवेदनशीलता लेबल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Microsoft Purview Information Protection से संवेदनशीलता लेबल का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getId()](#getId--) | संवेदनशीलता लेबल की आईडी लौटाता है या सेट करता है। |
| [setId(String value)](#setId-java.lang.String-) | संवेदनशीलता लेबल की आईडी लौटाता है या सेट करता है। |
| [getSiteId()](#getSiteId--) | संवेदनशीलता लेबल नीति जो संवेदनशीलता लेबल का वर्णन करती है, उससे संबंधित Azure Active Directory (Azure AD) साइट पहचानकर्ता को लौटाता है या सेट करता है। |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | संवेदनशीलता लेबल नीति जो संवेदनशीलता लेबल का वर्णन करती है, उससे संबंधित Azure Active Directory (Azure AD) साइट पहचानकर्ता को लौटाता है या सेट करता है। |
| [isEnabled()](#isEnabled--) | संवेदनशीलता लेबल सक्षम है या नहीं दर्शाता है। |
| [setEnabled(boolean value)](#setEnabled-boolean-) | संवेदनशीलता लेबल सक्षम है या नहीं दर्शाता है। |
| [isRemoved()](#isRemoved--) | संवेदनशीलता लेबल हटाया गया था या नहीं दर्शाता है। |
| [setRemoved(boolean value)](#setRemoved-boolean-) | संवेदनशीलता लेबल हटाया गया था या नहीं दर्शाता है। |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | संवेदनशीलता लेबल के लिए असाइनमेंट विधि को लौटाता है या सेट करता है। |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | संवेदनशीलता लेबल के लिए असाइनमेंट विधि को लौटाता है या सेट करता है। |
| [getContentMarkTypes()](#getContentMarkTypes--) | फ़ाइल पर लागू होने वाली कंटेंट मार्किंग प्रकारों की सूची लौटाता है। |
### getId() {#getId--}
```
public abstract String getId()
```


संवेदनशीलता लेबल की आईडी लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


संवेदनशीलता लेबल की आईडी लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```


संवेदनशीलता लेबल नीति जो संवेदनशीलता लेबल का वर्णन करती है, उससे संबंधित Azure Active Directory (Azure AD) साइट पहचानकर्ता को लौटाता है या सेट करता है। पढ़ें/लिखें java.util.UUID.

**रिटर्न:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```


संवेदनशीलता लेबल नीति जो संवेदनशीलता लेबल का वर्णन करती है, उससे संबंधित Azure Active Directory (Azure AD) साइट पहचानकर्ता को लौटाता है या सेट करता है। पढ़ें/लिखें java.util.UUID.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```


संवेदनशीलता लेबल सक्षम है या नहीं दर्शाता है।

**रिटर्न:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```


संवेदनशीलता लेबल सक्षम है या नहीं दर्शाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```


संवेदनशीलता लेबल हटाया गया था या नहीं दर्शाता है।

**रिटर्न:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```


संवेदनशीलता लेबल हटाया गया था या नहीं दर्शाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```


संवेदनशीलता लेबल के लिए असाइनमेंट विधि को लौटाता है या सेट करता है। पढ़ें/लिखें [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**रिटर्न:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```


संवेदनशीलता लेबल के लिए असाइनमेंट विधि को लौटाता है या सेट करता है। पढ़ें/लिखें [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


फ़ाइल पर लागू होने वाली कंटेंट मार्किंग प्रकारों की सूची लौटाता है।

**रिटर्न:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - कंटेंट प्रकारों की सूची [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)