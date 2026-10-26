---
title: Read()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بقراءة حرف واحد من تدفق الإدخال.
type: docs
weight: 66
url: /ar/system.io/binaryreader/read/
---
## BinaryReader::Read() طريقة

يقوم بقراءة حرف واحد من تدفق الإدخال.

```cpp
virtual int System::IO::BinaryReader::Read()
```

### قيمة الإرجاع

قراءة الحرف المشفر بترميز UTF-16؛ إذا كان الحرف المقروء ممثلاً بنقطتي كود في ترميز UTF-16 فسيتم إرجاع الجزء العلوي فقط.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) طريقة

يقوم بقراءة العدد المحدد من البايتات من تدفق الإدخال وكتابتها إلى مصفوفة البايت المحددة.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت لكتابة البايتات المقروءة فيها |
| index | int | موضع يبدأ من الصفر في **buffer** للبدء بالكتابة |
| count | int | عدد البايتات للقراءة |

### قيمة الإرجاع

عدد البايتات المقروءة

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) طريقة

يقوم بقراءة العدد المحدد من الأحرف من تدفق الإدخال، وتحويلها إلى ترميز UTF-16 وكتابة الأحرف الناتجة بترميز UTF-16 إلى مصفوفة الأحرف المحددة بدءًا من الموضع المحدد.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | مصفوفة الأحرف UTF-16 لكتابة الأحرف المقروءة من تدفق الإدخال |
| index | int | فهرس يبدأ من الصفر في **buffer** الذي سيبدأ الكتابة فيه |
| count | int | عدد الأحرف لقراءتها من التدفق |

### قيمة الإرجاع

عدد الأحرف المقروءة من تدفق الإدخال

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [BinaryReader](../)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)