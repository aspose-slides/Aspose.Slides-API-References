---
title: Write()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يكتب الحرف المحدد إلى التدفق.
type: docs
weight: 40
url: /ar/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) طريقة

يكتب الحرف المحدد إلى التدفق.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char_t | القيمة المراد كتابتها |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) طريقة

يكتب النطاق الفرعي المحدد من الأحرف من المصفوفة المحددة إلى التدفق.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | المصفوفة التي تحتوي على الأحرف المراد كتابتها |
| index | **int32_t** | فهرس يبدأ من الصفر للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة |
| count | **int32_t** | عدد الأحرف في النطاق الفرعي المراد كتابته |

## StringWriter::Write(const String\&) طريقة

يكتب السلسلة المحددة إلى التدفق.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | السلسلة المراد كتابتها |

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [StringWriter](../)
* فئة [String](../../../system/string/)
* مساحة اسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)