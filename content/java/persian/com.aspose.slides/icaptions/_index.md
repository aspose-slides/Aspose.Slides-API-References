---  
title: ICaptions  
second_title: Aspose.Slides برای Java API Reference  
description: نمایانگر زیرنویس‌های بسته WebVTT.  
type: docs  
url: /fa/com.aspose.slides/icaptions/  
---```
public interface ICaptions
```

نمایانگر زیرنویس‌های بسته WebVTT.

## متدها

| Method | Description |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | شناسهٔ منحصر به‌فرد سراسری (GUID) زیرنویس‌های بسته را برمی‌گرداند. |
| [getLabel()](#getLabel--) | برچسب زیرنویس‌های بسته را برمی‌گرداند یا تنظیم می‌کند. |
| [setLabel(String value)](#setLabel-java.lang.String-) | برچسب زیرنویس‌های بسته را برمی‌گرداند یا تنظیم می‌کند. |
| [getBinaryData()](#getBinaryData--) | داده‌های باینری زیرنویس‌های بسته را برمی‌گرداند. |
| [getDataAsString()](#getDataAsString--) | داده‌های زیرنویس‌های بسته را به عنوان رشتهٔ کدگذاری‌شدهٔ UTF-8 برمی‌گرداند (رشته فقط‌خواندنی). |

### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

شناسهٔ منحصر به‌فرد سراسری (GUID) زیرنویس‌های بسته را برمی‌گرداند. فقط‌خواندنی java.util.UUID.

**بازمی‌گرداند:**
java.util.UUID

### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

برچسب زیرنویس‌های بسته را برمی‌گرداند یا تنظیم می‌کند. خواند/نوشتن String.

**بازمی‌گرداند:**
java.lang.String

### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

برچسب زیرنویس‌های بسته را برمی‌گرداند یا تنظیم می‌کند. خواند/نوشتن String.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

داده‌های باینری زیرنویس‌های بسته را برمی‌گرداند. فقط‌خواندنی byte[].

**بازمی‌گرداند:**
byte[]

### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

داده‌های زیرنویس‌های بسته را به عنوان رشتهٔ کدگذاری‌شدهٔ UTF-8 برمی‌گرداند. فقط‌خواندنی String.

**بازمی‌گرداند:**
java.lang.String