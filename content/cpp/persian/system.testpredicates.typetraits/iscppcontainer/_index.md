---
title: IsCppContainer
second_title: Aspose.Slides برای C++ مرجع API
description: "بررسی می‌کند که آیا نوع خاصی یک container به سبک STL است. برای این کار، وجود انواع عضو iterator و const_iterator را بررسی می‌کند. اگر هر دو موجود باشند، از std::true_type ارث‌بری می‌کند، در غیر اینصورت از std::false_type ارث‌بری می‌کند."
type: docs
weight: 40
url: /fa/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer ساختار


بررسی می‌کند که آیا نوع خاصی یک container به سبک STL است یا خیر. برای این کار، وجود انواع عضو iterator و const_iterator را بررسی می‌کند. اگر هر دو موجود باشند، از std::true_type ارث‌بری می‌کند، در غیر اینصورت از std::false_type ارث‌بری می‌کند.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع برای بررسی. |
| Enable | آرگومان رسمی برای کارکرد SFINAE. |

## موارد مرتبط

* فضای‌نام [System::TestPredicates::TypeTraits](../)
* کتابخانه [Aspose.Slides](../../)