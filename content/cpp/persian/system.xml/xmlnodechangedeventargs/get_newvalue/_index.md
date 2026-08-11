---
title: get_NewValue()
second_title: Aspose.Slides برای مرجع API C++
description: مقدار جدید گره را برمی‌گرداند.
type: docs
weight: 66
url: /fa/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() متد

مقدار جدید گره را برمی‌گرداند.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```

### مقدار بازگشتی

مقدار جدید گره. این متد **nullptr** را برمی‌گرداند اگر گره نه یک ویژگی باشد و نه گره متنی، یا اگر گره در حال حذف باشد. اگر در رویداد **XmlDocument::NodeChanging** صدا زده شود، **get_NewValue** مقدار گره را در صورت موفقیت تغییر برمی‌گرداند. اگر در رویداد **XmlDocument::NodeChanged** صدا زده شود، **get_NewValue** مقدار فعلی گره را برمی‌گرداند.

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlNodeChangedEventArgs](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)