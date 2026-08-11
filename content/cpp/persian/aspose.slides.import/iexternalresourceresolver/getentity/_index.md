---
title: GetEntity()
second_title: مرجع API Aspose.Slides برای C++
description: یک URI را به شیئی که منبع واقعی را در بر دارد، نگاشت می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) متد


یک URI را به شیئی که منبع واقعی را در بر دارد، نگاشت می‌کند.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | URI مطلق برای شیء. |

### مقدار بازگشت

یک شیء [System::IO::Stream](../../../system.io/stream/) یا null اگر منبع قابل استریم نباشد.

## موارد مرتبط

* typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [String](../../../system/string/)
* کلاس [IExternalResourceResolver](../)
* فضای‌نام [Aspose::Slides::Import](../../)
* کتابخانه [Aspose.Slides](../../../)