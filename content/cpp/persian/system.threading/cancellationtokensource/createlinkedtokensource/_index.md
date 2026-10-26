---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides برای مرجع API C++
description: یک منبع توکن مرتبط ایجاد می‌کند که هنگام لغو هر یک از توکن‌های ارائه‌شده، لغو می‌شود.
type: docs
weight: 66
url: /fa/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) method


یک منبع توکن مرتبط ایجاد می‌کند که زمانی که هر یک از توکن‌های ارائه‌شده لغو شوند، لغو می‌شود.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | توکن لغو اول برای نظارت. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | توکن لغو دوم برای نظارت. |

### مقدار بازگشتی

منبع توکن جدیدی که هنگام لغو هر یک از توکن‌های ورودی، لغو خواهد شد.
## ملاحظات



منبع برگشت‌خورده بلافاصله لغو می‌شود اگر هر یک از توکن‌های ورودی قبلاً لغو شده باشند. 

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [CancellationTokenSource](../)
* کلاس [CancellationToken](../../cancellationtoken/)
* فضای‌نام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)