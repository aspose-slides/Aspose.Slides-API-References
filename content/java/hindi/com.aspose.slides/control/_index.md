---
title: Control
second_title: Aspose.Slides for Java API संदर्भ
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
## विधियां

| विधि | विवरण |
| --- | --- |
| [getPersistence()](#getPersistence--) | ActiveX नियंत्रण के गुणों को संग्रहित करने के लिए उपयोग की जाने वाली विधि को प्राप्त करता है। |
| [getName()](#getName--) | इस नियंत्रण के नाम को प्राप्त करता या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | इस नियंत्रण के नाम को प्राप्त करता या सेट करता है। |
| [getClassId()](#getClassId--) | इस नियंत्रण का क्लास आईडी प्राप्त करता है। |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | इस नियंत्रण का क्लास आईडी प्राप्त करता है। |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | नियंत्रण छवि भरने गुण वस्तु को लौटाता है। |
| [getFrame()](#getFrame--) | नियंत्रण के फ्रेम को लौटाता या सेट करता है। |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | नियंत्रण के फ्रेम को लौटाता या सेट करता है। |
| [getProperties()](#getProperties--) | ActiveX गुणों का संग्रह लौटाता है। |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | जब स्थायित्व विधि PersistStream, PersistStreamInit या PersistStorage हो, तब ActiveX नियंत्रण की स्थायित्व को निर्दिष्ट करता है। |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```


ActiveX नियंत्रण के गुणों को संग्रहित करने के लिए उपयोग की जाने वाली विधि को प्राप्त करता है। केवल पढ़ने योग्य [PersistenceType](../../com.aspose.slides/persistencetype).

--------------------

> ```
> अगला उदाहरण Persistence प्रॉपर्टी का उपयोग दिखाता है जिससे यह जांचा जा सके कि ActiveX ऑब्जेक्ट की प्रॉपर्टी को XML आधारित ActiveX प्रॉपर्टी के रूप में बदला जा सकता है या नहीं:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //ActiveX प्रॉपर्टी को उसके बाइनरी फ़ाइल में संग्रहित करने के प्रबंधन के लिए अपनी स्वयं की विधि उपयोग करें
>  }
> ```


**वापसी:** 
int
### getName() {#getName--}
```
public final String getName()
```


इस नियंत्रण का नाम प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य String.

**वापसी:** 
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


इस नियंत्रण का नाम प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य String.

**पैरामीटर:** 
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```


इस नियंत्रण का क्लास आईडी प्राप्त करता है। केवल पढ़ने योग्य java.util.UUID.

**वापसी:** 
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```


इस नियंत्रण का क्लास आईडी प्राप्त करता है। केवल पढ़ने योग्य java.util.UUID.

**पैरामीटर:** 
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```


नियंत्रण छवि भरने गुण वस्तु को लौटाता है। केवल पढ़ने योग्य [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**वापसी:** 
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```


नियंत्रण के फ्रेम को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [IShapeFrame](../../com.aspose.slides/ishapeframe).

**वापसी:** 
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```


नियंत्रण के फ्रेम को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [IShapeFrame](../../com.aspose.slides/ishapeframe).

**पैरामीटर:** 
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```


ActiveX गुणों का संग्रह लौटाता है। केवल पढ़ने योग्य [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

ध्यान दें: Aspose.Slides केवल XML आधारित ActiveX गुणों का समर्थन करता है। यदि गुण बाइनरी स्वरूप में संग्रहित हैं, तो यह गुण null लौटाएगा।

**वापसी:** 
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```


जब स्थायित्व विधि PersistStream, PersistStreamInit या PersistStorage हो, तब ActiveX नियंत्रण की स्थायित्व को निर्दिष्ट करता है।

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
>      YourMethodHere(control.getActiveXControlBinary()); //ActiveX प्रॉपर्टी को उसकी बाइनरी फ़ाइल में संग्रहित करने के प्रबंधन के लिए अपनी स्वयं की विधि का उपयोग करें
>  }
> ```

**वापसी:** 
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


बेस स्लाइड लौटाता है। केवल पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide).

**वापसी:** 
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


प्रेजेंटेशन लौटाता है। केवल पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation).

**वापसी:** 
[IPresentation](../../com.aspose.slides/ipresentation)