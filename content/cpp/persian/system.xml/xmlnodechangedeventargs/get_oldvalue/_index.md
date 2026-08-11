---
title: get_OldValue()
second_title: Aspose.Slides برای مرجع API C++
description: مقدار اصلی گره را برمی‌گرداند.
type: docs
weight: 53
url: /fa/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() متد


مقدار اصلی گره را برمی‌گرداند.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### مقدار بازگشت

مقدار اصلی گره. این متد **nullptr** برمی‌گرداند اگر گره نه یک ویژگی باشد و نه یک گره متنی، یا اگر گره در حال درج باشد. اگر در رویداد **XmlDocument::NodeChanging** فراخوانی شود، **get_OldValue** مقدار فعلی گره‌ای که در صورت موفقیت تغییر جایگزین خواهد شد را برمی‌گرداند. اگر در رویداد **XmlDocument::NodeChanged** فراخوانی شود، **get_OldValue** مقدار گره را پیش از تغییر برمی‌گرداند.

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlNodeChangedEventArgs](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)