---
title: WriteState
second_title: Aspose.Slides – مرجع API لـ C++
description: يحدد حالة XmlWriter.
type: docs
weight: 755
url: /ar/system.xml/writestate/
---
## WriteState تعداد

يحدد حالة [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Start | 0 | يشير إلى أن طريقة XmlWriter::Write لم يتم استدعاؤها بعد. |
| Prolog | 1 | يشير إلى أن prolog يتم كتابته. |
| Element | 2 | يشير إلى أن وسم بداية العنصر يتم كتابته. |
| Attribute | 3 | يشير إلى أن قيمة السمة يتم كتابتها. |
| Content | 4 | يشير إلى أن محتوى العنصر يتم كتابته. |
| Closed | 5 | يشير إلى أن طريقة [XmlWriter::Close](../xmlwriter/close/) تم استدعاؤها. |
| Error | 6 | تم إلقاء استثناء، مما ترك [XmlWriter](../xmlwriter/) في حالة غير صالحة. يمكنك استدعاء طريقة [XmlWriter::Close](../xmlwriter/close/) لوضع [XmlWriter](../xmlwriter/) في الحالة [WriteState::Closed](./). أي استدعاءات أخرى لطريقة [XmlWriter](../xmlwriter/) تؤدي إلى InvalidOperationException. |

## انظر أيضًا

* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)