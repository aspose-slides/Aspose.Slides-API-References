---
title: ReadBlock()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقرأ الحد الأقصى المحدد لعدد الأحرف من قارئ النص الحالي ويكتب البيانات إلى مخزن مؤقت، بدءًا من الفهرس المحدد.
type: docs
weight: 53
url: /ar/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) طريقة

Reads the specified maximum number of characters from the current text reader and writes the data to a buffer, starting at the specified index.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | مخزن محارف لكتابة البيانات المقروءة إليه |
| index | int | فهرس يبدأ من الصفر في **buffer** للبدء بالكتابة |
| count | int | الحد الأقصى لعدد المحارف للقراءة |

### قيمة الإرجاع

عدد المحارف المقروءة فعليًا

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [TextReader](../)
* مساحة اسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)