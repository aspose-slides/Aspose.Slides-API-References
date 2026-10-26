---
title: PeekChar()
second_title: مرجع API Aspose.Slides للغة C++
description: يقرأ حرفًا واحدًا من تدفق الإدخال دون تغيير مؤشر القراءة الخاص بالتدفق.
type: docs
weight: 53
url: /ar/system.io/binaryreader/peekchar/
---
## طريقة BinaryReader::PeekChar()

يقرأ حرفًا واحدًا من تدفق الإدخال دون تغيير مؤشر القراءة الخاص بالتدفق.

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```

### قيمة الإرجاع

الحرف المقروء مشفر بترميز UTF-16؛ إذا كان الحرف المقروء ممثلاً برمزين كوديّن في ترميز UTF-16 فسيتم إرجاع الجزء العالي من السوروجيت فقط؛ إذا لم يُقرأ أي حرف يتم إرجاع -1

## انظر أيضًا

* الفئة [BinaryReader](../)
* النطاق [System::IO](../../)
* المكتبة [Aspose.Slides](../../../)