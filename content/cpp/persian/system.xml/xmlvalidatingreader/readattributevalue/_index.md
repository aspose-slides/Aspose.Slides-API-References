---
title: ReadAttributeValue()
second_title: Aspose.Slides برای C++ مرجع API
description: مقدار ویژگی را به یک یا چند گره Text، EntityReference یا EndEntity تجزیه می‌کند.
type: docs
weight: 508
url: /fa/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() متد

مقدار ویژگی را به یک یا چند گره **[Text](../../../system.text/)**، **EntityReference** یا **EndEntity** تجزیه می‌کند.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```

### مقدار بازگشتی

**true** اگر گره‌هایی برای بازگرداندن وجود داشته باشد. **false** اگر خواننده هنگام فراخوانی اولیه بر روی گره‌ای از نوع ویژگی قرار نداشته باشد یا اگر تمام مقادیر ویژگی خوانده شده باشند. یک ویژگی خالی، مانند **misc=\"\"**، **true** را با یک گرهٔ تک که مقدار آن [String::Empty](../../../system/string/empty/) است، برمی‌گرداند.

## موارد مرتبط

* کلاس [XmlValidatingReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)