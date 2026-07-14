---
title: IOverridableText
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: متنی قابل بازنویسی برای یک نمودار را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ioverridabletext/
---
**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

متن قابل بازنویسی برای یک نمودار را نمایندگی می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | می‌تواند متنی با قالب‌بندی غنی داشته باشد. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | TextFrameForOverriding را با متنی در پارامتر "text" مقداردهی اولیه می‌کند. |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

می‌تواند متنی با قالب‌بندی غنی داشته باشد. اگر این ویژگی null نباشد، مقدار متن قالب‌بندی شده، متن تولید خودکار را نادیده می‌گیرد. متن تولید خودکار یک ویژگی ضمنی برچسب داده، برچسب واحد نمایش محور مقدار، عنوان محور، عنوان نمودار و برچسب خط روند است. متن تولید خودکار با ویژگی IFormattedTextContainer.TextFormat قالب‌بندی می‌شود. فقط‌خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**برگشت:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

TextFrameForOverriding را با متنی در پارامتر "text" مقداردهی اولیه می‌کند. اگر TextFrameForOverriding از قبل مقداردهی شده باشد، به سادگی متن آن را تغییر می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن برای یک TextFrameForOverriding جدید. |

**برگشت:**
[ITextFrame](../../com.aspose.slides/itextframe) - قاب متن [ITextFrame](../../com.aspose.slides/itextframe)