---
title: Read()
second_title: مرجع API Aspose.Slides للـ C++
description: يقرأ حرفًا واحدًا من الدفق.
type: docs
weight: 40
url: /ar/system.io/stringreader/read/
---
## StringReader::Read() طريقة


يقرأ حرفًا واحدًا من الدفق.

```cpp
virtual int System::IO::StringReader::Read() override
```


### قيمة الإرجاع

حرف مقروء أو -1 إذا لم يتم قراءة أي حرف

## StringReader::Read(ArrayPtr\<char_t\>, int, int) طريقة


يقرا عددًا محددًا من الأحرف من الدفق إلى مصفوفة الأحرف المحددة بدءًا من الموضع المحدد.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | مصفوفة الأحرف التي سيكتب فيها الأحرف المقروءة من الدفق إليها |
| index | int | فهرس يبدأ من الصفر في **buffer** لتحديد موقع بدء الكتابة |
| count | int | عدد الأحرف التي يجب قراءتها من الدفق |

### قيمة الإرجاع

عدد الأحرف المقروءة من الدفق

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* الفئة [StringReader](../)
* نطاق الاسم [System::IO](../../)
* المكتبة [Aspose.Slides](../../../)