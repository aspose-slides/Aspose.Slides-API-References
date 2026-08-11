---
title: GetValue()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار ویژگی را از شیء خاص دریافت می‌کند.
type: docs
weight: 1
url: /fa/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) متد

مقدار ویژگی را از شیء مشخص دریافت می‌کند.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) برای خواندن ویژگی از. |

### مقدار بازگشت

مقدار ویژگی مشخص برای شیء مشخص.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) متد

مقدار ویژگی را از شیء مشخص دریافت می‌کند.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) برای خواندن ویژگی از. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | اینها مقادیر ایندکس اختیاری برای ویژگی‌های ایندکس‌شده هستند. برای ویژگی‌های غیرایندکس‌شده، این مقدار باید خالی باشد. |

### مقدار بازگشت

مقدار ویژگی مشخص برای شیء مشخص.

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [Object](../../../system/object/)
* کلاس [PropertyInfo](../)
* فضای نام [System::Reflection](../../)
* Library [Aspose.Slides](../../../)