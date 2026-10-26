---
title: "System::Runtime::Serialization"
second_title: Aspose.Slides لواجهة برمجة التطبيقات C++
description: 
type: docs
weight: 794
url: /ar/system.runtime.serialization/
---
## الفئات

| الفئة | الوصف |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | يمثل تنفيذًا أساسيًا للواجهة [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/). |
| [IFormatterConverter](./iformatterconverter/) | يوفر الاتصال بين نسخة من [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) والفئة التي يوفرها المنسق والتي تكون الأنسب لتحليل البيانات داخل [System::Runtime::Serialization::SerializationInfo](./serializationinfo/). |
| [ISerializable](./iserializable/) | واجهة كائن يمكن تسلسله. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../system/makeobject/) فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيتسبب في أخطاء وقت التشغيل أو أعطال التأكيد. اغلق هذه الفئة دائمًا في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [SerializationInfo](./serializationinfo/) | تحمل مجموعة من الحقول المسماة التي تمثل كائنًا مسلسلاً. غير مطبق. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../system/makeobject/) فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيتسبب في أخطاء وقت التشغيل أو أعطال التأكيد. اغلق هذه الفئة دائمًا في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط. |
| [StreamingContext](./streamingcontext/) | فئة تجريبية لجعل الفئات المترجمة التي تستخدم StreamingContext تُجمّع. لا تدير نسخ هذه الفئة باستخدام [SmartPtr](../system/smartptr/)، يجب تخصيصها على المكدس فقط. |
## الأنواع التعريفية

| النوع التعريفي | الوصف |
| --- | --- |
| [SerializationException](./serializationexception/) |  |