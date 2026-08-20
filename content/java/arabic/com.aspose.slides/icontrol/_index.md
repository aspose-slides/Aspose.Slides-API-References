---
title: IControl
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل عنصر تحكم ActiveX.
type: docs
url: /ar/com.aspose.slides/icontrol/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

يمثل عنصر تحكم ActiveX.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | يعيد اسم هذا العنصر. |
| [setName(String value)](#setName-java.lang.String-) | يعيد اسم هذا العنصر. |
| [getClassId()](#getClassId--) | يحصل على معرف الفئة لهذا العنصر. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | يعيد كائن خصائص تعبئة الصورة لـ ControlEx. |
| [getFrame()](#getFrame--) | يعيد أو يضبط إطار العنصر. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | يعيد أو يضبط إطار العنصر. |
| [getProperties()](#getProperties--) | يعيد مجموعة من خصائص ActiveX. |
| [getPersistence()](#getPersistence--) | يحصل على الطريقة المستخدمة لتخزين خصائص عنصر التحكم ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | يحدد بقاء عنصر التحكم ActiveX عندما تكون الطريقة المستخدمة للبعث إما PersistStream أو PersistStreamInit أو PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```


يعيد اسم هذا العنصر. قراءة/كتابة String.

**إرجاع:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


يعيد اسم هذا العنصر. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```


يحصل على معرف الفئة لهذا العنصر. قراءة فقط java.util.UUID.

**إرجاع:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


يعيد كائن خصائص تعبئة الصورة لـ ControlEx. قراءة فقط [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**إرجاع:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```


يعيد أو يضبط إطار العنصر. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

**إرجاع:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```


يعيد أو يضبط إطار العنصر. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```


يعيد مجموعة من خصائص ActiveX. قراءة فقط [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**إرجاع:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```


يحصل على الطريقة المستخدمة لتخزين خصائص عنصر التحكم ActiveX. قراءة فقط [PersistenceType](../../com.aspose.slides/persistencetype).

**إرجاع:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```


يحدد بقاء عنصر التحكم ActiveX عندما تكون الطريقة المستخدمة للبعث إما PersistStream أو PersistStreamInit أو PersistStorage.

**إرجاع:**
byte[]