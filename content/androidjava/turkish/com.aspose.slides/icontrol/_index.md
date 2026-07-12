---
title: IControl
second_title: Aspose.Slides Android için Java API Referansı
description: Bir ActiveX denetimini temsil eder.
type: docs
url: /tr/com.aspose.slides/icontrol/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Bir ActiveX denetimini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getName()](#getName--) | Bu denetimin adını döndürür. |
| [setName(String value)](#setName-java.lang.String-) | Bu denetimin adını döndürür. |
| [getClassId()](#getClassId--) | Bu denetimin sınıf kimliğini alır. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | ControlEx görüntü doldurma özellikleri nesnesini döndürür. |
| [getFrame()](#getFrame--) | Denetimin çerçevesini döndürür veya ayarlar. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Denetimin çerçevesini döndürür veya ayarlar. |
| [getProperties()](#getProperties--) | ActiveX özelliklerinin bir koleksiyonunu döndürür. |
| [getPersistence()](#getPersistence--) | ActiveX denetiminin özelliklerini depolamak için kullanılan yöntemi alır. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | PersistStream, PersistStreamInit veya PersistStorage kullanılan bir durumda bir ActiveX denetiminin kalıcılığını belirtir. |
### getName() {#getName--}
```
public abstract String getName()
```


Bu denetimin adını döndürür. Okuma/yazma String.

**Döndürür:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Bu denetimin adını döndürür. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```


Bu denetimin sınıf kimliğini alır. Yalnızca okuma java.util.UUID.

**Döndürür:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


ControlEx görüntü doldurma özellikleri nesnesini döndürür. Yalnızca okuma [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Döndürür:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```


Denetimin çerçevesini döndürür veya ayarlar. Okuma/yazma [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Döndürür:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```


Denetimin çerçevesini döndürür veya ayarlar. Okuma/yazma [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```


ActiveX özelliklerinin bir koleksiyonunu döndürür. Yalnızca okuma [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Döndürür:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```


ActiveX denetiminin özelliklerini depolamak için kullanılan yöntemi alır. Yalnızca okuma [PersistenceType](../../com.aspose.slides/persistencetype).

**Döndürür:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```


PersistStream, PersistStreamInit veya PersistStorage kullanılan bir durumda bir ActiveX denetiminin kalıcılığını belirtir.

**Döndürür:**
byte[]