---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a video embedded into a presentation.
type: docs
url: /fa/com.aspose.slides/ivideo/
---```
public interface IVideo
```

یک ویدیو را که در یک ارائه جاسازی شده است، نمایان می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getContentType()](#getContentType--) | MIME type یک ویدیو را برمی‌گرداند که در (\#getBinaryData.getBinaryData) رمزگذاری شده است. |
| [getBinaryData()](#getBinaryData--) | یک کپی از داده‌های صدا را برمی‌گرداند. |
| [getStream()](#getStream--) | یک Stream برای خواندن برمی‌گرداند. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

MIME type یک ویدیو را برمی‌گرداند که در (\#getBinaryData.getBinaryData) رمزگذاری شده است. فقط خواندنی String.

**بازگرداندن:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

یک کپی از داده‌های صدا را برمی‌گرداند. در صورت حجم بزرگ داده‌ها، استفاده از متد \#getStream.getStream را در نظر بگیرید تا از بارگذاری غیرضروری داده‌های ویدیو در حافظه یا حتی بروز OutOfMemoryException جلوگیری شود. فقط خواندنی byte[].

**بازگرداندن:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

یک Stream برای خواندن برمی‌گرداند. از 'using' استفاده کنید یا پس از استفاده، جریان را ببندید.

**بازگرداندن:**  
java.io.InputStream - Stream برای خواندن.