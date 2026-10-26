---
title: BinaryWriter()
second_title: Aspose.Slides للغة C++ مرجع API
description: ينشئ مثيلاً من الفئة BinaryWriter يكتب البيانات إلى الدفق المحدد باستخدام الترميز المحدد.
type: docs
weight: 1
url: /ar/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) البنّاء

ينشئ مثيلاً من فئة [BinaryWriter](../) يكتب البيانات إلى الدفق المحدد باستخدام الترميز المحدد.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | دفق الإخراج |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | الترميز المستخدم |
| leaveopen | **bool** | يحدد ما إذا كان يجب ترك الدفق **stream** مفتوحًا (true) بعد التخلص من الكائن الحالي أم لا (false) |

## انظر أيضًا

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* الفئة [BinaryWriter](../)
* النطاق [System::IO](../../)
* المكتبة [Aspose.Slides](../../../)