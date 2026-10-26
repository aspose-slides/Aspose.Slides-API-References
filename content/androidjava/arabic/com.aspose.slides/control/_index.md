---
title: Control
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل عنصر تحكم ActiveX.
type: docs
url: /ar/com.aspose.slides/control/
---
**التوريث:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)  
```
public class Control extends DomObject<ControlCollection> implements IControl
```

**يمثل عنصر تحكم ActiveX.**
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPersistence()](#getPersistence--) | يحصل على الطريقة المستخدمة لتخزين خصائص عنصر التحكم ActiveX. |
| [getName()](#getName--) | يحصل أو يعيّن اسم هذا العنصر التحكم. |
| [setName(String value)](#setName-java.lang.String-) | يحصل أو يعيّن اسم هذا العنصر التحكم. |
| [getClassId()](#getClassId--) | يحصل على معرف الفئة لهذا العنصر التحكم. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | يحصل على معرف الفئة لهذا العنصر التحكم. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | يرجع كائن خصائص تعبئة صورة العنصر التحكم. |
| [getFrame()](#getFrame--) | يرجع أو يعيّن إطار العنصر التحكم. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | يرجع أو يعيّن إطار العنصر التحكم. |
| [getProperties()](#getProperties--) | يرجع مجموعة من خصائص ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | يحدد بقاء عنصر التحكم ActiveX عندما تكون الطريقة المستخدمة للحفظ إما PersistStream أو PersistStreamInit أو PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |

### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

يحصل على الطريقة المستخدمة لتخزين خصائص عنصر التحكم ActiveX. قراءة فقط [PersistenceType](../../com.aspose.slides/persistencetype).

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
>      YourMethodHere(control.getActiveXControlBinary()); //استخدم طريقتك الخاصة لإدارة خصائص ActiveX المخزنة في ملفها الثنائي
>  }
> ```

**الإرجاع:**  
int

### getName() {#getName--}
```
public final String getName()
```

يحصل أو يعيّن اسم هذا العنصر التحكم. قراءة/كتابة String.

**الإرجاع:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

يحصل أو يعيّن اسم هذا العنصر التحكم. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

يحصل على معرف الفئة لهذا العنصر التحكم. قراءة فقط java.util.UUID.

**الإرجاع:**  
java.util.UUID

### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

يحصل على معرف الفئة لهذا العنصر التحكم. قراءة فقط java.util.UUID.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

يرجع كائن خصائص تعبئة صورة العنصر التحكم. قراءة فقط [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**الإرجاع:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

يرجع أو يعيّن إطار العنصر التحكم. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

**الإرجاع:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

يرجع أو يعيّن إطار العنصر التحكم. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

يرجع مجموعة من خصائص ActiveX. قراءة فقط [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

ملاحظة: يدعم Aspose.Slides فقط خصائص ActiveX المستندة إلى XML. إذا تم تخزين الخصائص بتنسيق ثنائي، ستُعيد هذه الخاصية قيمة null.

**الإرجاع:**  
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

يحدد بقاء عنصر التحكم ActiveX عندما تكون الطريقة المستخدمة للحفظ إما PersistStream أو PersistStreamInit أو PersistStorage.

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
>      YourMethodHere(control.getActiveXControlBinary()); //استخدم طريقتك الخاصة لإدارة خصائص ActiveX المخزنة في ملفها الثنائي
>  }
> ```

**الإرجاع:**  
byte[]

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يرجع الشريحة الأساسية. قراءة فقط [IBaseSlide](../../com.aspose.slides/ibaseslide).

**الإرجاع:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يرجع العرض التقديمي. قراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**  
[IPresentation](../../com.aspose.slides/ipresentation)