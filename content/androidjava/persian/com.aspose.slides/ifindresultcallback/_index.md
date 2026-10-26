---
title: IFindResultCallback
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: رابط Callback برای دریافت نتیجه جستجوی متن استفاده می‌شود.
type: docs
url: /fa/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

رابط Callback برای دریافت نتیجه جستجوی متن استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | متد Callback که داده‌های مربوط به متن یافت‌شده را دریافت می‌کند. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

متد Callback که داده‌های مربوط به متن یافت‌شده را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | [ITextFrame](../../com.aspose.slides/itextframe) که متن در آن یافت شد. |
| sourceText | java.lang.String | متن منبع که متن در آن یافت شد. |
| foundText | java.lang.String | متن یافت‌شده. |
| textPosition | int | موقعیت متن یافت‌شده. |