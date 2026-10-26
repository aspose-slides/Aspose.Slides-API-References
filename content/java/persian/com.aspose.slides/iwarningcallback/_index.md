---
title: IWarningCallback
second_title: Aspose.Slides for Java API Reference
description: Interface for classes which receive warning
type: docs
url: /fa/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

رابط برای کلاس‌هایی که هشدار دریافت می‌کنند
## متدها

| متد | توضیح |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | متد بازگشتی که هشدار را دریافت می‌کند و تصمیم می‌گیرد آیا عملیات باید لغو شود یا نه. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

متد بازگشتی که هشدار را دریافت می‌کند و تصمیم می‌گیرد آیا عملیات باید لغو شود یا نه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | هشدار برای پردازش. |

**بازگشت:**
int - تصمیم لغو [ReturnAction](../../com.aspose.slides/returnaction).