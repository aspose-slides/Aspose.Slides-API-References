---
title: GetEnvironmentVariables()
second_title: Aspose.Slides لـ C++ مرجع API
description: يعيد قاموساً يحتوي على جميع أسماء متغيرات البيئة وقيمها المرتبطة بالعملية الحالية.
type: docs
weight: 326
url: /ar/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() طريقة

يعيد قاموساً يحتوي على جميع أسماء متغيرات البيئة وقيمها المرتبطة بالعملية الحالية.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) طريقة

يعيد قاموساً يحتوي على جميع أسماء متغيرات البيئة وقيمها من الموقع المحدد.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | موقع المتغيرات |

### قيمة الإرجاع

قاموس يحتوي على جميع أسماء متغيرات البيئة وقيمها من الموقع المحدد

## انظر أيضًا

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* فئة [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* فئة [String](../../string/)
* بنية [Environment](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)