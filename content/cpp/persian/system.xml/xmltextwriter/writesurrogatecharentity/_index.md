---
title: WriteSurrogateCharEntity()
second_title: مرجع API Aspose.Slides برای C++
description: موجودیت کاراکتر جانشین را برای جفت کاراکتر جانشین تولید و می‌نویسد.
type: docs
weight: 391
url: /fa/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) متد

موجودیت کاراکتر جانشین را برای جفت کاراکتر جانشین تولید و می‌نویسد.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| lowChar | char16_t | جانشین پایین. این مقدار باید بین **0xDC00** و **0xDFFF** باشد. |
| highChar | char16_t | جانشین بالا. این مقدار باید بین **0xD800** و **0xDBFF** باشد. |

## موارد مرتبط

* کلاس [XmlTextWriter](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)