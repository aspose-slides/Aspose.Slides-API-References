---
title: ReadState
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد حالة القارئ.
type: docs
weight: 703
url: /ar/system.xml/readstate/
---
## عدد ReadState enum

يحدد حالة القارئ.

```cpp
enum class ReadState
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Initial | 0 | لم يتم استدعاء الطريقة [XmlReader::Read](../xmlreader/read/). |
| Interactive | 1 | تم استدعاء الطريقة [XmlReader::Read](../xmlreader/read/). قد يتم استدعاء طرق إضافية على القارئ. |
| Error | 2 | حدث خطأ يمنع استمرار عملية القراءة. |
| EndOfFile | 3 | تم الوصول إلى نهاية الملف بنجاح. |
| Closed | 4 | تم استدعاء الطريقة [XmlReader::Close](../xmlreader/close/). |

## انظر أيضًا

* النطاق [System::Xml](../)
* المكتبة [Aspose.Slides](../../)