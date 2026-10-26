---
title: FileVersionInfo
second_title: Aspose.Slides لـ C++ مرجع API
description: "يقدم معلومات حول نسخة الملف. يجب إنشاء كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبدًا بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيسبّب ذلك أخطاءً وقت التشغيل أو فشلًا في التأكيد. يجب دائمًا تغليف هذه الفئة بمؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 1
url: /ar/system.diagnostics/fileversioninfo/
---
## FileVersionInfo فئة

Provides information on file version. Objects of this فئة should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this فئة into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FileVersionInfo
```

## الطرق

| Method | Description |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | Gets product version field. |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | Gets file version info; not implemented. |

## انظر أيضًا

* النطاق [System::Diagnostics](../)
* المكتبة [Aspose.Slides](../../)