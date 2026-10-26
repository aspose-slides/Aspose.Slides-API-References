---
title: CloneNode()
second_title: مرجع API Aspose.Slides برای C++
description: یک کپی از این گره ایجاد می‌کند. گره‌های Entity نمی‌توانند کلون شوند. فراخوانی این متد بر روی یک شیء XmlEntity استثنا ایجاد می‌کند.
type: docs
weight: 170
url: /fa/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) method


یک کپی از این گره ایجاد می‌کند. گره‌های Entity نمی‌توانند کلون شوند. فراخوانی این متد بر روی یک شیء [XmlEntity](../) استثنا ایجاد می‌کند.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```


### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| deep | **bool** | **true** برای کلون بازگشتی زیر درخت زیر گرهٔ مشخص‌شده؛ **false** برای کلون فقط خود گره. |

### Return Value

یک کپی از [XmlNode](../../xmlnode/) که متد از آن فراخوانی شده است.

## See Also

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [XmlEntity](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)