---
title: IOverridableText
second_title: مرجع API Aspose.Slides برای جاوا
description: متن قابل بازنویسی برای یک نمودار را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ioverridabletext/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

متن قابل بازنویسی برای یک نمودار را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | می‌تواند متن قالب‌بندی شده غنی داشته باشد. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | TextFrameForOverriding را با متنی که در پارامتر "text" است مقداردهی اولیه می‌کند. |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


می‌تواند متن قالب‌بندی شده غنی داشته باشد. اگر این ویژگی null نباشد، این مقدار متن قالب‌بندی شده متن خودکار تولید شده را بازنویسی می‌کند. متن خودکار تولید شده یک ویژگی ضمنی برای برچسب داده، برچسب واحد نمایش محور مقدار، عنوان محور، عنوان نمودار، برچسب خط روند است. متن خودکار تولید شده با ویژگی IFormattedTextContainer.TextFormat قالب‌بندی می‌شود. فقط خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بازگرداندن:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


TextFrameForOverriding را با متنی که در پارامتر "text" است مقداردهی اولیه می‌کند. اگر TextFrameForOverriding از پیش مقداردهی اولیه شده باشد، به سادگی متن آن را تغییر می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن برای یک TextFrameForOverriding جدید. |

**بازگرداندن:**
[ITextFrame](../../com.aspose.slides/itextframe) - قاب متن [ITextFrame](../../com.aspose.slides/itextframe)