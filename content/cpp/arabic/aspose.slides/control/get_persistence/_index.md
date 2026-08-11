---
title: get_Persistence()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على الطريقة المستخدمة لتخزين خصائص عنصر التحكم ActiveX. للقراءة فقط PersistenceType.
type: docs
weight: 1
url: /ar/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() طريقة

يحصل على الطريقة المستخدمة لتخزين خصائص عنصر التحكم ActiveX. للقراءة فقط [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```
## ملاحظات

المثال التالي يوضح استخدام خاصية Persistence للتحقق مما إذا كان يمكن تغيير خصائص كائن ActiveX كخصائص ActiveX قائمة على XML: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // استخدم طريقتك الخاصة لإدارة خصائص ActiveX المخزنة في ملفه الثنائي
    YourMethodHere(control->get_ActiveXControlBinary());
}
```
## انظر أيضًا

* التعداد [PersistenceType](../../persistencetype/)
* الفئة [Control](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)