---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: نمایانگر یک فایل صوتی توکار.
type: docs
url: /fa/com.aspose.slides/iaudio/
---```
public interface IAudio
```

نمایانگر یک فایل صوتی توکار.
## متدها

| متد | توضیح |
| --- | --- |
| [getContentType()](#getContentType--) | نوع MIME یک صدا را برمی‌گرداند که در (\#getBinaryData.getBinaryData) رمزگذاری شده است. |
| [getBinaryData()](#getBinaryData--) | کپی داده‌های یک صدا را برمی‌گرداند. |
| [getStream()](#getStream--) | جریانی از نوع Stream را برای خواندن برمی‌گرداند. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

نوع MIME یک صدا را برمی‌گرداند که در (\#getBinaryData.getBinaryData) رمزگذاری شده است. فقط‌خواندنی String.

**باز می‌گردد:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

کپی داده‌های یک صدا را برمی‌گرداند. در صورت حجم زیاد داده‌ها، استفاده از متد \#getStream.getStream را در نظر بگیرید تا از بارگذاری غیرضروری داده‌های صدا در حافظه یا حتی بروز OutOfMemoryException جلوگیری شود. فقط‌خواندنی byte[].

**باز می‌گردد:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

جریانی از نوع Stream را برای خواندن برمی‌گرداند. از 'using' استفاده کنید یا پس از استفاده، جریان را ببندید.

**باز می‌گردد:**  
java.io.InputStream - Stream for reading.