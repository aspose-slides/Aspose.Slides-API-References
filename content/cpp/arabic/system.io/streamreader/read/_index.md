---
title: Read()
second_title: مرجع API Aspose.Slides للغة C++
description: يقرأ حرفًا واحدًا من الدفق.
type: docs
weight: 40
url: /ar/system.io/streamreader/read/
---
## StreamReader::Read() طريقة

يقرأ حرفًا واحدًا من الدفق.

```cpp
virtual int System::IO::StreamReader::Read() override
```

### قيمة الإرجاع

حرف القراءة مُرمّز بترميز UTF-16؛ إذا كان حرف القراءة يُمثَّل بنقطتي كود في ترميز UTF-16 فسيتم إرجاع الجزء العالي فقط.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) طريقة

يقرأ العدد المحدد من الأحرف من الدفق، يحوّله إلى ترميز UTF-16 ويكتب الأحرف الناتجة بترميز UTF-16 إلى مصفوفة الأحرف المحددة بدءًا من الموضع المحدد.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | مصفوفة الأحرف UTF-16 لكتابة الأحرف المقروءة من الدفق فيها |
| index | int | فهرس يبدأ من الصفر في **buffer** لتحديد موضع بدء الكتابة |
| count | int | عدد الأحرف المطلوب قراءتها من الدفق |

### قيمة الإرجاع

عدد الأحرف المقروءة من الدفق

## راجع أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)