---
title: get_ActiveXControlBinary()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides لـ C++
description: يحدد بقاء عنصر تحكم ActiveX عندما تكون الطريقة المستخدمة للحفظ إما PersistStream أو PersistStreamInit أو PersistStorage.
type: docs
weight: 118
url: /ar/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() طريقة

يحدد بقاء عنصر تحكم ActiveX عندما تكون الطريقة المستخدمة للحفظ إما PersistStream أو PersistStreamInit أو PersistStorage.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## ملاحظات

المثال التالي يوضح استخدام خاصية ActiveXControlBinary لتغيير خصائص ActiveX:

```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // استخدم طريقتك الخاصة لإدارة خصائص ActiveX المخزنة في ملفها الثنائي
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [Control](../)
* نطاق الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)