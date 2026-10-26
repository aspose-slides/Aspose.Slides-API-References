---
title: IControl
second_title: Aspose.Slides for Java API संदर्भ
description: एक ActiveX नियंत्रण का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icontrol/
---
**सभी लागू इंटरफ़ेस:**  
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
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | ControlEx image fill properties object लौटाता है। |
| [getFrame()](#getFrame--) | control's frame को लौटाता है या सेट करता है। |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | control's frame को लौटाता है या सेट करता है। |
| [getProperties()](#getProperties--) | ActiveX properties का संग्रह लौटाता है। |
| [getPersistence()](#getPersistence--) | ActiveX नियंत्रण की प्रॉपर्टियों को संग्रहित करने के लिए उपयोग की जाने वाली विधि प्राप्त करता है। |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | जब निरंतरता की विधि PersistStream, PersistStreamInit या PersistStorage में से कोई एक हो, तो ActiveX control की persistence निर्धारित करता है। |

### getName() {#getName--}
```
public abstract String getName()
```

इस नियंत्रण का नाम लौटाता है। Read/write String.

**रिटर्न:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

इस नियंत्रण का नाम लौटाता है। Read/write String.

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

इस नियंत्रण का class id प्राप्त करता है। Read-only java.util.UUID.

**रिटर्न:**  
java.util.UUID

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

ControlEx image fill properties object लौटाता है। Read-only [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**रिटर्न:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

control's frame को लौटाता है या सेट करता है। Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

**रिटर्न:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

control's frame को लौटाता है या सेट करता है। Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

ActiveX properties का संग्रह लौटाता है। Read-only [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**रिटर्न:**  
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

ActiveX नियंत्रण की प्रॉपर्टियों को संग्रहित करने के लिए उपयोग की जाने वाली विधि प्राप्त करता है। Read only [PersistenceType](../../com.aspose.slides/persistencetype).

**रिटर्न:**  
int

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

जब निरंतरता की विधि PersistStream, PersistStreamInit या PersistStorage में से कोई एक हो, तो ActiveX control की persistence निर्धारित करता है।

**रिटर्न:**  
byte[]