---
title: WriteState
second_title: Aspose.Slides برای C++ مرجع API
description: وضعیت XmlWriter را مشخص می‌کند.
type: docs
weight: 755
url: /fa/system.xml/writestate/
---
## WriteState enum


وضعیت [XmlWriter](../xmlwriter/) را مشخص می‌کند.

```cpp
enum class WriteState
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| Start | 0 | نشان می‌دهد که متد XmlWriter::Write هنوز فراخوانی نشده است. |
| Prolog | 1 | نشان می‌دهد که پیش‌مقدمه در حال نوشتن است. |
| Element | 2 | نشان می‌دهد که تگ شروع یک عنصر در حال نوشتن است. |
| Attribute | 3 | نشان می‌دهد که مقدار یک ویژگی در حال نوشتن است. |
| Content | 4 | نشان می‌دهد که محتوای عنصر در حال نوشتن است. |
| Closed | 5 | نشان می‌دهد که متد [XmlWriter::Close](../xmlwriter/close/) فراخوانی شده است. |
| Error | 6 | یک استثنا رخ داده است که باعث شده [XmlWriter](../xmlwriter/) در وضعیت نامعتبر قرار گیرد. می‌توانید متد [XmlWriter::Close](../xmlwriter/close/) را فراخوانی کنید تا [XmlWriter](../xmlwriter/) را در وضعیت [WriteState::Closed](./) قرار دهید. هر فراخوانی دیگر متد [XmlWriter](../xmlwriter/) منجر به InvalidOperationException می‌شود. |

## موارد مرتبط

* فضای‌نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)