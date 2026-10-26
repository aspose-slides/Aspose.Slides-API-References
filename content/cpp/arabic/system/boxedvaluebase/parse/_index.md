---
title: Parse()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يعبئ قيمة ثابت التعداد المحدد بالتعداد المحدد بالاسم المحدد. يحدد أحد المعاملات ما إذا كان يجب تجاهل حالة الأحرف عند تفسير السلسلة التي تحدد اسم ثابت التعداد.
type: docs
weight: 53
url: /ar/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) طريقة

يعبئ قيمة ثابت التعداد المحدد بالتعداد المحدد بالاسم المحدد. يحدد أحد المعاملات ما إذا كان يجب تجاهل حالة الأحرف عند تفسير السلسلة التي تحدد اسم ثابت التعداد.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | يحدد نوع التعداد |
| str | const [String](../../string/)\& | اسم ثابت التعداد الذي سيتم تعبئته |
| ignoreCase | **bool** | يحدد ما إذا كان يجب تجاهل حالة الأحرف عند تفسير السلسلة التي تمثل اسم ثابت التعداد |

### قيمة الإرجاع

مؤشر مشترك إلى الكائن الذي يمثل القيمة المعبأة لثابت التعداد المحدد

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) طريقة

يعبئ قيمة ثابت التعداد المحدد بالاسم المحدد.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | يحدد نوع التعداد |
| str | const [String](../../string/)\& | اسم ثابت التعداد الذي سيتم تعبئته |

### قيمة الإرجاع

مؤشر مشترك إلى الكائن الذي يمثل القيمة المعبأة لثابت التعداد المحدد

## انظر أيضًا

* Typedef [SharedPtr](../../sharedptr/)
* فئة [Object](../../object/)
* فئة [TypeInfo](../../typeinfo/)
* فئة [String](../../string/)
* فئة [BoxedValueBase](../)
* نطاق [System](../../)
* Library [Aspose.Slides](../../../)