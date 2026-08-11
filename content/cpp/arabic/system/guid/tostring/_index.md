---
title: ToString()
second_title: Aspose.Slides for C++ مرجع API
description: يقوم بتحويل الـ GUID الممثَّل بواسطة الكائن الحالي إلى تمثيله النصي.
type: docs
weight: 79
url: /ar/system/guid/tostring/
---
## Guid::ToString() const طريقة

يقوم بتحويل الـ GUID الممثَّل بواسطة الكائن الحالي إلى تمثيله النصي.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const طريقة

يقوم بتحويل الـ GUID الممثَّل بواسطة الكائن الحالي إلى تمثيله النصي باستخدام صيغة النص المحددة.

```cpp
String System::Guid::ToString(const String &format) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | const [String](../../string/)\& | الصيغة المراد استخدامها |

### قيمة الإرجاع

تمثيل النصي لقيمة الـ GUID الممثَّلة بواسطة الكائن الحالي

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const طريقة

يقوم بتحويل الـ GUID الممثَّل بواسطة الكائن الحالي إلى تمثيله النصي باستخدام صيغة النص المحددة والثقافة.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | const [String](../../string/)\& | الصيغة المراد استخدامها |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | الثقافة المراد استخدامها |

### قيمة الإرجاع

تمثيل النصي لقيمة الـ GUID الممثَّلة بواسطة الكائن الحالي

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [Guid](../)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)