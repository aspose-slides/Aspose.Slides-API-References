---
title: IControl
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक ActiveX नियंत्रण का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icontrol/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

एक ActiveX नियंत्रण का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getName()](#getName--) | इस नियंत्रण का नाम लौटाता है। |
| [setName(String value)](#setName-java.lang.String-) | इस नियंत्रण का नाम लौटाता है। |
| [getClassId()](#getClassId--) | इस नियंत्रण का class id प्राप्त करता है। |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | ControlEx इमेज फ़िल प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getFrame()](#getFrame--) | नियंत्रण के फ्रेम को लौटाता या सेट करता है। |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | नियंत्रण के फ्रेम को लौटाता या सेट करता है। |
| [getProperties()](#getProperties--) | ActiveX प्रॉपर्टीज़ का संग्रह लौटाता है। |
| [getPersistence()](#getPersistence--) | ActiveX नियंत्रण की प्रॉपर्टीज़ को स्टोर करने के लिए प्रयुक्त मेथड प्राप्त करता है। |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | जब स्थायित्व के लिए प्रयुक्त मेथड PersistStream, PersistStreamInit या PersistStorage हो, तो ActiveX नियंत्रण की स्थायित्व को निर्दिष्ट करता है। |
### getName() {#getName--}
```
public abstract String getName()
```

इस नियंत्रण का नाम लौटाता है। पढ़ें/लिखें String.

**वापसी:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

इस नियंत्रण का नाम लौटाता है। पढ़ें/लिखें String.

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

इस नियंत्रण का class id प्राप्त करता है। केवल पढ़ने योग्य java.util.UUID.

**वापसी:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

ControlEx इमेज फ़िल प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**वापसी:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

नियंत्रण के फ्रेम को लौटाता या सेट करता है। पढ़ें/लिखें [IShapeFrame](../../com.aspose.slides/ishapeframe).

**वापसी:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

नियंत्रण के फ्रेम को लौटाता या सेट करता है। पढ़ें/लिखें [IShapeFrame](../../com.aspose.slides/ishapeframe).

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

ActiveX प्रॉपर्टीज़ का संग्रह लौटाता है। केवल पढ़ने योग्य [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**वापसी:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

ActiveX नियंत्रण की प्रॉपर्टीज़ को स्टोर करने के लिए प्रयुक्त मेथड प्राप्त करता है। केवल पढ़ने योग्य [PersistenceType](../../com.aspose.slides/persistencetype).

**वापसी:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

जब स्थायित्व के लिए प्रयुक्त मेथड PersistStream, PersistStreamInit या PersistStorage हो, तो ActiveX नियंत्रण की स्थायित्व को निर्दिष्ट करता है।

**वापसी:**
byte[]