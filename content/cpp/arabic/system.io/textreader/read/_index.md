---
title: Read()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بقراءة حرف واحد من الدفق.
type: docs
weight: 40
url: /ar/system.io/textreader/read/
---
## TextReader::Read() طريقة

يقوم بقراءة حرف واحد من الدفق.

```cpp
virtual int System::IO::TextReader::Read()
```

### قيمة الإرجاع

حرف مقروء مشفر بترميز UTF-16؛ إذا كان الحرف المقروء ممثلاً بنقطتي شفرة في ترميز UTF-16 فسيتم إرجاع الجزء العلوي من الـ surrogate فقط.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) طريقة

يقوم بقراءة عدد محدد من الأحرف من الدفق ويكتبها في مصفوفة الأحرف المحددة بدءًا من الموضع المحدد.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | مصفوفة أحرف UTF-16 لكتابة الأحرف المقروءة من الدفق إليها |
| index | int | فهرس يبدأ من الصفر في **buffer** لتحديد موقع بدء الكتابة |
| count | int | عدد الأحرف التي سيتم قراءتها من الدفق |

### قيمة الإرجاع

عدد الأحرف المقروءة من الدفق

## انظر أيضا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* الفئة [TextReader](../)
* نطاق الاسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)