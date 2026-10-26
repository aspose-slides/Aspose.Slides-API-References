---
title: GetCultureInfo()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على الثقافة وفقًا لاسمها. نفس CreateSpecificCulture.
type: docs
weight: 586
url: /ar/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) method

يحصل على الثقافة وفقًا لاسمها. نفس CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```

### المعلمات

| معلم | نوع | الوصف |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | اسم ثقافة معرف مسبقًا أو اسم كائن ثقافة موجود. |

### قيمة الإرجاع

كائن ثقافة تم إنشاؤه حديثًا.

## CultureInfo::GetCultureInfo(const String\&, const String\&) method

يحصل على الثقافة وفقًا لاسمها.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```

### المعلمات

| معلم | نوع | الوصف |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | اسم الثقافة. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | اسم الثقافة المستخدم لكائنات [TextInfo](../../textinfo/) و[CompareInfo](../../compareinfo/). |

### قيمة الإرجاع

كائن ثقافة.

## CultureInfo::GetCultureInfo(int32_t) method

يحصل على الثقافة وفقًا للمعرف.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```

### المعلمات

| معلم | نوع | الوصف |
| --- | --- | --- |
| culture | **int32_t** | معرف الثقافة. |

### قيمة الإرجاع

كائن ثقافة تم إنشاؤه حديثًا.

## انظر أيضًا

* تعريف نوع [CultureInfoPtr](../../cultureinfoptr/)
* فئة [String](../../../system/string/)
* فئة [CultureInfo](../)
* مساحة الاسم [System::Globalization](../../)
* مكتبة [Aspose.Slides](../../../)