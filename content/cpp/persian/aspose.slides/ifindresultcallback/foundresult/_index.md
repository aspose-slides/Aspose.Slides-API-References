---
title: FoundResult()
second_title: مرجع API Aspose.Slides برای C++
description: متدی کال‌بک که داده‌های مربوط به متن یافت‌شده را دریافت می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) متد

متدی که داده‌های مربوط به متن یافت‌شده را دریافت می‌کند.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | [ITextFrame](../../itextframe/)‌ای که متن در آن یافت شد. |
| sourceText | [System::String](../../../system/string/) | متن منبعی که متن در آن یافت شد. |
| foundText | [System::String](../../../system/string/) | متن یافت‌شده. |
| textPosition | **int32_t** | موقعیت متن یافت‌شده. |

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ITextFrame](../../itextframe/)
* کلاس [String](../../../system/string/)
* کلاس [IFindResultCallback](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)