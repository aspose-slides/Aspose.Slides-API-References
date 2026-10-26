---
title: Supports()
second_title: Aspose.Slides برای C++ مرجع API
description: آزمون می‌کند که آیا پیاده‌سازی DOM ویژگی خاصی را پیاده‌سازی می‌کند.
type: docs
weight: 482
url: /fa/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) متد


Tests if the DOM implementation implements a specific feature.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| feature | [String](../../../system/string/) | نام بسته ویژگی برای آزمایش. این نام حساس به حروف نیست. |
| version | [String](../../../system/string/) | شماره نسخهٔ نام بسته برای آزمایش. اگر نسخه مشخص نشود (null)، پشتیبانی از هر نسخه‌ای از ویژگی باعث می‌شود متد مقدار **true** برگرداند. |

### مقدار بازگشت

**true** اگر ویژگی در نسخهٔ مشخص پیاده‌سازی شده باشد؛ در غیر این صورت، **false**.
## توضیحات



The following table describes the combinations that return **true**. 

| ویژگی | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlNode](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)