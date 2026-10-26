---
title: MoveToContent()
second_title: مرجع API Aspose.Slides برای C++
description: "بررسی می‌کند که آیا گره فعلی یک گره محتوا (متن غیر فضا سفید، CDATA، Element، EndElement، EntityReference یا EndEntity) است یا خیر. اگر گره یک گره محتوا نباشد، خواننده به گره محتوای بعدی یا انتهای فایل می‌پرد. همچنین گره‌های نوع زیر را نادیده می‌گیرد: ProcessingInstruction، DocumentType، Comment، Whitespace یا SignificantWhitespace."
type: docs
weight: 833
url: /fa/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() متد

بررسی می‌کند که آیا گره فعلی یک گره محتوا (متن غیر فضا سفید، **CDATA**، **Element**، **EndElement**، **EntityReference** یا **EndEntity**) است یا خیر. اگر گره یک گره محتوا نباشد، خواننده به گره محتوای بعدی یا انتهای فایل می‌پرد. همچنین گره‌های از نوع زیر را نادیده می‌گیرد: **ProcessingInstruction**، **DocumentType**، **Comment**، **Whitespace** یا **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```

### مقدار بازگشت

مقدار [XmlReader::get_NodeType](../get_nodetype/) گره فعلی که توسط متد یافت شده یا [XmlNodeType::None](../../xmlnodetype/) اگر خواننده به انتهای جریان ورودی رسیده باشد.

## موارد مرتبط

* Enum [XmlNodeType](../../xmlnodetype/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)