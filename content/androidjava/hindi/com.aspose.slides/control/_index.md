---
title: Control
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक ActiveX नियंत्रण का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/control/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

एक ActiveX नियंत्रण का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getPersistence()](#getPersistence--) | ActiveX नियंत्रण की प्रॉपर्टीज़ को संग्रहीत करने के लिए उपयोग की जाने वाली विधि प्राप्त करता है। |
| [getName()](#getName--) | इस नियंत्रण का नाम प्राप्त करता है या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | इस नियंत्रण का नाम प्राप्त करता है या सेट करता है। |
| [getClassId()](#getClassId--) | इस नियंत्रण का क्लास आईडी प्राप्त करता है। |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | इस नियंत्रण का क्लास आईडी प्राप्त करता है। |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | नियंत्रण की इमेज़ फ़िल प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। |
| [getFrame()](#getFrame--) | नियंत्रण का फ्रेम प्राप्त करता है या सेट करता है। |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | नियंत्रण का फ्रेम प्राप्त करता है या सेट करता है। |
| [getProperties()](#getProperties--) | ActiveX प्रॉपर्टीज़ का एक संग्रह लौटाता है। |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | जब निरंतरता के लिए उपयोग की जाने वाली विधि PersistStream, PersistStreamInit या PersistStorage हो, तो ActiveX नियंत्रण की निरंतरता निर्दिष्ट करता है। |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |

### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

ActiveX नियंत्रण की प्रॉपर्टीज़ को संग्रहित करने के लिए उपयोग की जाने वाली विधि प्राप्त करता है। केवल पढ़ने योग्य [PersistenceType](../../com.aspose.slides/persistencetype)।

--------------------

> ```
> Next example shows the using Persistence property for checking if properties of ActiveX object may be changed as XML based ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //अपनेअपनेस्वयंकेमेथडकाआपयोगकरेंActiveXप्रॉपर्टीज़कोउनकेबाइनरीफ़ाइलमेंसंग्रहीतकरनेकेलिए
>  }
> ```

**वापसी:**
int
### getName() {#getName--}
```
public final String getName()
```

इस नियंत्रण का नाम प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String।

**वापसी:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

इस नियंत्रण का नाम प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

इस नियंत्रण का क्लास आईडी प्राप्त करता है। केवल पढ़ने योग्य java.util.UUID।

**वापसी:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

इस नियंत्रण का क्लास आईडी प्राप्त करता है। केवल पढ़ने योग्य java.util.UUID।

**पैरामीटर:**
| पैरामीटर | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

नियंत्रण की इमेज़ फ़िल प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)।

**वापसी:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

नियंत्रण का फ्रेम प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [IShapeFrame](../../com.aspose.slides/ishapeframe)।

**वापसी:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

नियंत्रण का फ्रेम प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [IShapeFrame](../../com.aspose.slides/ishapeframe)।

**पैरामीटर:**
| पैरामीटर | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

ActiveX प्रॉपर्टीज़ का एक संग्रह लौटाता है। केवल पढ़ने योग्य [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)।

--------------------

नोट: Aspose.Slides केवल XML आधारित ActiveX प्रॉपर्टीज़ को समर्थन देता है। यदि प्रॉपर्टीज़ बाइनरी फ़ॉर्मेट में संग्रहीत हैं, तो यह प्रॉपर्टी null लौटाएगी।

**वापसी:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

जब निरंतरता के लिए उपयोग की जाने वाली विधि PersistStream, PersistStreamInit या PersistStorage हो, तो ActiveX नियंत्रण की निरंतरता निर्दिष्ट करता है।

--------------------

> ```
> Next example shows the using ActiveXControlBinary property for changing ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //अपनीस्वयंकीमेथडका उपयोगकरेंActiveXप्रॉपर्टीजकोउनकीबाइनरीफ़ाइलमेंसंग्रहीतकरनेकेलिए
>  }
> ```

**वापसी:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

बेस स्लाइड लौटाता है। केवल पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide)।

**वापसी:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

प्रेज़ेंटेशन लौटाता है। केवल पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)