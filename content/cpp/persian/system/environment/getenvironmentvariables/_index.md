---
title: GetEnvironmentVariables()
second_title: Aspose.Slides برای C++ مرجع API
description: یک دیکشنری شامل تمام نام‌های متغیرهای محیطی و مقادیر آن‌ها که با فرآیند جاری مرتبط هستند را برمی‌گرداند.
type: docs
weight: 326
url: /fa/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() متد

یک دیکشنری شامل تمام نام‌های متغیرهای محیطی و مقادیرشان که با فرآیند جاری مرتبط هستند را برمی‌گرداند.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) متد

یک دیکشنری شامل تمام نام‌های متغیرهای محیطی و مقادیرشان از مکان مشخص‌شده را برمی‌گرداند.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | مکان متغیرها |

### مقدار بازگشت

یک دیکشنری شامل تمام نام‌های متغیرهای محیطی و مقادیرشان از مکان مشخص‌شده

## موارد مرتبط

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* کلاس [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* کلاس [String](../../string/)
* ساختار [Environment](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)