---
title: Control
second_title: Aspose.Slides for Android via Java API Referansı
description: ActiveX denetimini temsil eder.
type: docs
url: /tr/com.aspose.slides/control/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

Bir ActiveX denetimini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPersistence()](#getPersistence--) | ActiveX denetiminin özelliklerini depolamak için kullanılan yöntemi alır. |
| [getName()](#getName--) | Bu denetimin adını alır veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Bu denetimin adını alır veya ayarlar. |
| [getClassId()](#getClassId--) | Bu denetimin sınıf kimliğini alır. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Bu denetimin sınıf kimliğini alır. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Denetim görüntü dolgu özellikleri nesnesini döndürür. |
| [getFrame()](#getFrame--) | Denetimin çerçevesini alır veya ayarlar. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Denetimin çerçevesini alır veya ayarlar. |
| [getProperties()](#getProperties--) | ActiveX özelliklerinin bir koleksiyonunu döndürür. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | PersistStream, PersistStreamInit veya PersistStorage yöntemlerinden biri kullanıldığında bir ActiveX denetiminin kalıcılığını belirtir. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```


ActiveX denetiminin özelliklerini depolamak için kullanılan yöntemi alır. Salt okunur [PersistenceType](../../com.aspose.slides/persistencetype).

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
>      YourMethodHere(control.getActiveXControlBinary()); //ActiveX özelliklerini ikili dosyada saklayan kendi yönteminizi kullanın
>  }
> ```

**Döndürür:**
int
### getName() {#getName--}
```
public final String getName()
```


Bu denetimin adını alır veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Bu denetimin adını alır veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```


Bu denetimin sınıf kimliğini alır. Salt okunur java.util.UUID.

**Döndürür:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```


Bu denetimin sınıf kimliğini alır. Salt okunur java.util.UUID.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```


Denetim görüntü dolgu özellikleri nesnesini döndürür. Salt okunur [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Döndürür:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```


Denetimin çerçevesini alır veya ayarlar. Okuma/Yazma [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Döndürür:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```


Denetimin çerçevesini alır veya ayarlar. Okuma/Yazma [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```


ActiveX özelliklerinin bir koleksiyonunu döndürür. Salt okunur [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Not: Aspose.Slides yalnızca XML tabanlı ActiveX özelliklerini destekler. Özellikler ikili formatta depolanıyorsa, bu özellik null döndürecektir.

**Döndürür:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```


PersistStream, PersistStreamInit veya PersistStorage yöntemlerinden biri kullanıldığında bir ActiveX denetiminin kalıcılığını belirtir.

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
>      YourMethodHere(control.getActiveXControlBinary()); //İkili dosyasında saklanan ActiveX özelliklerini yönetmek için kendi yönteminizi kullanın
>  }
> ```

**Döndürür:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Temel slaytı döndürür. Salt okunur [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Sunumu döndürür. Salt okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)