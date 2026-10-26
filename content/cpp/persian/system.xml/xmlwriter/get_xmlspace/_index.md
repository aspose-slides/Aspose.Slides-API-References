---
title: get_XmlSpace()
second_title: مرجع API Aspose.Slides برای C++
description: "هنگامی که در یک کلاس مشتق‌شده بازنویسی می‌شود، یک XmlSpace که نشانگر دامنهٔ فعلی xml:space است را برمی‌گرداند."
type: docs
weight: 27
url: /fa/system.xml/xmlwriter/get_xmlspace/
---
## XmlWriter::get_XmlSpace() متد

When overridden in a derived class, gets an XmlSpace representing the current **xml:space** scope.

```cpp
virtual System::Xml::XmlSpace System::Xml::XmlWriter::get_XmlSpace()
```

### مقدار بازگشت

یک XmlSpace که نمایانگر محدوده **xml:space** فعلی است.

| مقدار | معنی |
| --- | --- |
| `None`| این مقدار پیش‌فرض است اگر هیچ محدوده `xml:space` وجود نداشته باشد. |
| `Default`| محدوده فعلی `xml:space="default"` است. |
| `Preserve`| محدوده فعلی `xml:space="preserve"` است. |

## موارد مرتبط

* Enum [XmlSpace](../../xmlspace/)
* کلاس [XmlWriter](../)
* فضای‌نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)