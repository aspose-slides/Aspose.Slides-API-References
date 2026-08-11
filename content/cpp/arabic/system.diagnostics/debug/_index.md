---
title: Debug
second_title: مرجع Aspose.Slides للـ C++ API
description: مجموعة من طرق التصحيح التي تسمح بإرسال معلومات التصحيح إلى المستمعين المسجلين. جميع وظائف الإخراج تعمل في Debug فقط. هذا نوع ثابت لا يحتوي على خدمات مثيلات. يجب ألا تنشئ مثيلات منه بأي وسيلة.
type: docs
weight: 105
url: /ar/system.diagnostics/debug/
---
## هيكل التصحيح

مجموعة من طرق التصحيح التي تسمح بإرسال معلومات التصحيح إلى المستمعين المسجلين. جميع وظائف الإخراج تعمل في [Debug](./) فقط. هذا نوع ثابت بدون خدمات مثيلات. يجب ألا تقوم بإنشاء مثيلات منه بأي وسيلة.

```cpp
class Debug
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | تحقق من الشرط وأرسل المعلومات عند الفشل. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | تحقق من الشرط وأرسل المعلومات عند الفشل. |
| static void [Assert](./assert/)(**bool**, const char *) | تحقق من الشرط وأرسل المعلومات عند الفشل. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | تحقق من الشرط وأرسل المعلومات عند الفشل. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | أرسل رسالة الفشل. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | يصل إلى القائمة الثابتة للمستمعين. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | اطبع الرسالة إلى واجهة التصحيح. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | اطبع الرسالة إلى واجهة التصحيح. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | يكتب السلسلة إلى واجهة التصحيح. |
| static void [Write](./write/)(const char_t *) | يكتب السلسلة إلى واجهة التصحيح. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | يكتب السلسلة إلى واجهة التصحيح إذا كان الشرط صحيحًا. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | يكتب سطرًا إلى واجهة التصحيح. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يكتب سطرًا إلى واجهة التصحيح. |
| static void [WriteLine](./writeline/)(const char_t *) | يكتب سطرًا إلى واجهة التصحيح. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | يكتب سطرًا إلى واجهة التصحيح. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | يكتب سطرًا إلى واجهة التصحيح إذا كان الشرط صحيحًا. |

## انظر أيضًا

* مساحة الاسم [System::Diagnostics](../)
* مكتبة [Aspose.Slides](../../)