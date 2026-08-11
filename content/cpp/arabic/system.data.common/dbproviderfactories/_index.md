---
title: DbProviderFactories
second_title: Aspose.Slides لمرجع API C++
description: "API للحصول على مصانع موفر قاعدة البيانات. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة System::MakeObject(). لا تقم أبداً بإنشاء مثال من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيسبّب ذلك أخطاءً في وقت التشغيل و/أو أعطالاً في التحقق. دائماً قم بلف هذه الفئة داخل مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 53
url: /ar/system.data.common/dbproviderfactories/
---
## DbProviderFactories الفئة

API للحصول على مصانع موفر قاعدة البيانات. كائنات هذه الفئة يجب أن تُخصَّص فقط باستخدام الدالة [System::MakeObject()](../../system/makeobject/). لا تقم أبداً بإنشاء مثيل من هذا النوع على المكدس أو باستخدام المشغل new، حيث سيسبّب ذلك أخطاءً أثناء التشغيل و/أو أعطالًا في التحقق. دائمًا قم بلف هذه الفئة داخل مؤشر [System::SmartPtr](../../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class DbProviderFactories
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | يسترجع مصنع موفر قاعدة البيانات بالاسم. |
## انظر أيضًا

* النطاق [System::Data::Common](../)
* المكتبة [Aspose.Slides](../../)