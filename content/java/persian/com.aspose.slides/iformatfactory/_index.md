---
title: IFormatFactory
second_title: Aspose.Slides برای مرجع API جاوا
description: اجازه می‌دهد تا فرمت‌ها را از طریق رابط COM ایجاد کند.
type: docs
url: /fa/com.aspose.slides/iformatfactory/
---```
public interface IFormatFactory
```

اجازه می‌دهد تا فرمت‌ها را از طریق رابط COM ایجاد کند.

## متدها

| متد | توضیح |
| --- | --- |
| [createPortionFormat()](#createPortionFormat--) | یک [IPortionFormat](../../com.aspose.slides/iportionformat) جدید ایجاد می‌کند. |
| [createParagraphFormat()](#createParagraphFormat--) | یک [IParagraphFormat](../../com.aspose.slides/iparagraphformat) جدید ایجاد می‌کند. |
| [createTextFrameFormat()](#createTextFrameFormat--) | یک [ITextFrameFormat](../../com.aspose.slides/itextframeformat) جدید ایجاد می‌کند. |
### createPortionFormat() {#createPortionFormat--}
```
public abstract IPortionFormat createPortionFormat()
```

یک [IPortionFormat](../../com.aspose.slides/iportionformat) جدید ایجاد می‌کند.

**بازگشت:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - فرمت بخش جدید.

### createParagraphFormat() {#createParagraphFormat--}
```
public abstract IParagraphFormat createParagraphFormat()
```

یک [IParagraphFormat](../../com.aspose.slides/iparagraphformat) جدید ایجاد می‌کند.

**بازگشت:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - فرمت پاراگراف جدید.

### createTextFrameFormat() {#createTextFrameFormat--}
```
public abstract ITextFrameFormat createTextFrameFormat()
```

یک [ITextFrameFormat](../../com.aspose.slides/itextframeformat) جدید ایجاد می‌کند.

**بازگشت:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - فرمت فریم متنی جدید.