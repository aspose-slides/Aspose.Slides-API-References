---
title: IFindResultCallback
second_title: Aspose.Slides for Java API Reference
description: رابط فراخوانی برای دریافت نتیجه جستجوی متن.
type: docs
url: /fa/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

رابط فراخوانی برای دریافت نتیجه جستجوی متن.
## متدها

| متد | توضیح |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | متد فراخوانی که داده‌های مربوط به متن یافت‌شده را دریافت می‌کند. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

متد فراخوانی که داده‌های مربوط به متن یافت‌شده را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | [ITextFrame](../../com.aspose.slides/itextframe) که متن در آن یافت شده است. |
| sourceText | java.lang.String | متن منبعی که متن در آن یافت شده است. |
| foundText | java.lang.String | متن یافت‌شده. |
| textPosition | int | موقعیت متن یافت‌شده. |