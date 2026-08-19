---
title: IVideo
second_title: Aspose.Slides for Java API Reference
description: نمایی از یک ویدیو جاساز شده در یک ارائه.
type: docs
url: /fa/com.aspose.slides/ivideo/
---```
public interface IVideo
```

نمایش یک ویدیو جاساز شده در یک ارائه.
## متدها

| متد | توضیح |
| --- | --- |
| [getContentType()](#getContentType--) | یک MIME type از ویدیو را بر می‌گرداند که در (\#getBinaryData.getBinaryData) رمزگذاری شده است. |
| [getBinaryData()](#getBinaryData--) | یک کپی از داده‌های صوتی را بر می‌گرداند. |
| [getStream()](#getStream--) | یک Stream برای خواندن بر می‌گرداند. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

یک MIME type از ویدیو را بر می‌گرداند که در (\#getBinaryData.getBinaryData) رمزگذاری شده است. فقط خواندنی String.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

یک کپی از داده‌های صوتی را بر می‌گرداند. در صورت وجود مقدار زیاد داده، استفاده از متد \#getStream.getStream را در نظر بگیرید تا از بارگذاری غیرضروری داده‌های ویدیو در حافظه یا حتی OutOfMemoryException جلوگیری شود. فقط خواندنی byte[].

**Returns:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

یک Stream برای خواندن بر می‌گرداند. از 'using' استفاده کنید یا پس از استفاده جریان را ببندید.

**Returns:**
java.io.InputStream - Stream برای خواندن.