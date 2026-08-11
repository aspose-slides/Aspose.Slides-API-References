---
title: Hyperlink()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه از پیوند ایجاد می‌کند.
type: docs
weight: 339
url: /fa/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) سازنده

یک نمونه از پیوند ایجاد می‌کند.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) سازنده

یک نمونه از پیوند که به اسلاید خاصی اشاره می‌کند، ایجاد می‌کند. تذکر: پیوند ساخته شده باید به شی‌ای از همان ارائه اختصاص یابد، در غیر این صورت لینک به‌عنوان NoAction ذخیره خواهد شد.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | اسلاید هدف. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) سازنده

یک نمونه از پیوند با استفاده از پیوند دیگر به عنوان منبع ایجاد می‌کند و خصوصیات ثانویه را بازنویسی می‌کند.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | پیوند منبع |
| targetFrame | [System::String](../../../system/string/) | قاب هدف |
| tooltip | [System::String](../../../system/string/) | متن راهنما |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [Hyperlink](../)
* کلاس [ISlide](../../islide/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)