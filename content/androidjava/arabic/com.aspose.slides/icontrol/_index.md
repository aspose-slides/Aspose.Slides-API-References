---
title: IControl
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: يمثل عنصر تحكم ActiveX.
type: docs
url: /ar/com.aspose.slides/icontrol/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

يمثل عنصر التحكم ActiveX.
## الطرق

| Method | Description |
| --- | --- |
| [getName()](#getName--) | يعيد اسم هذا التحكم. |
| [setName(String value)](#setName-java.lang.String-) | يعيد اسم هذا التحكم. |
| [getClassId()](#getClassId--) | يحصل على class id لهذا التحكم. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | يعيد كائن ControlEx image fill properties. |
| [getFrame()](#getFrame--) | يعيد أو يضع إطار التحكم. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | يعيد أو يضع إطار التحكم. |
| [getProperties()](#getProperties--) | يعيد مجموعة من خصائص ActiveX. |
| [getPersistence()](#getPersistence--) | يحصل على الطريقة المستخدمة لتخزين خصائص عنصر التحكم ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | يحدد بقاء عنصر التحكم ActiveX عندما تكون الطريقة المستخدمة للحفظ إما PersistStream أو PersistStreamInit أو PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```

يعيد اسم هذا التحكم. قراءة/كتابة String.

**القيمة المرجعة:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

يعيد اسم هذا التحكم. قراءة/كتابة String.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

يحصل على class id لهذا التحكم. قراءة فقط java.util.UUID.

**القيمة المرجعة:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

يعيد كائن ControlEx image fill properties. قراءة فقط [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**القيمة المرجعة:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

يعيد أو يضع إطار التحكم. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

**القيمة المرجعة:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

يعيد أو يضع إطار التحكم. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

يعيد مجموعة من خصائص ActiveX. قراءة فقط [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**القيمة المرجعة:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

يحصل على الطريقة المستخدمة لتخزين خصائص عنصر التحكم ActiveX. قراءة فقط [PersistenceType](../../com.aspose.slides/persistencetype).

**القيمة المرجعة:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

يحدد بقاء عنصر التحكم ActiveX عندما تكون الطريقة المستخدمة للحفظ إما PersistStream أو PersistStreamInit أو PersistStorage.

**القيمة المرجعة:**
byte[]