---
title: IAudio
second_title: Aspose.Slides for Android via Java API Reference
description: یک فایل صوتی توکار را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/iaudio/
---```
public interface IAudio
```

یک فایل صوتی توکار را نمایش می‌دهد.
## متدها

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | یک نوع MIME از صوت را برمی‌گرداند، کدگذاری شده در (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | کپی داده‌های صوت را باز می‌گرداند. |
| [getStream()](#getStream--) | یک Stream برای خواندن باز می‌گرداند. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

یک نوع MIME از صوت را برمی‌گرداند، کدگذاری شده در (\#getBinaryData.getBinaryData). فقط‌خواندنی String.

**باز می‌گردد:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

کپی داده‌های صوت را باز می‌گرداند. در صورت حجم زیاد داده‌ها، استفاده از متد \#getStream.getStream را در نظر بگیرید تا از بارگذاری غیرضروری داده‌های صوت در حافظه یا حتی OutOfMemoryException جلوگیری شود. فقط‌خواندنی byte[].

**باز می‌گردد:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

یک Stream برای خواندن باز می‌گرداند. از 'using' استفاده کنید یا پس از استفاده، استریم را بسته کنید.

**باز می‌گردد:**
java.io.InputStream - Stream برای خواندن.