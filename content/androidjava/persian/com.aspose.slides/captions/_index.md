---
title: Captions
second_title: مرجع API جاوا برای Aspose.Slides برای اندروید
description: نمایانگر زیرنویس‌های بستهٔ WebVTT.
type: docs
url: /fa/com.aspose.slides/captions/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)  
```
public class Captions implements ICaptions
```

نمایانگر زیرنویس‌های بستهٔ WebVTT.
## متدها

| متد | شرح |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | شناسهٔ یکتای سراسری (GUID) زیرنویس‌های بسته را برمی‌گرداند. |
| [getLabel()](#getLabel--) | برچسب زیرنویس‌های بسته را برمی‌گرداند یا تنظیم می‌کند. |
| [setLabel(String value)](#setLabel-java.lang.String-) | برچسب زیرنویس‌های بسته را برمی‌گرداند یا تنظیم می‌کند. |
| [getBinaryData()](#getBinaryData--) | داده‌های باینری زیرنویس‌های بسته را برمی‌گرداند. |
| [getDataAsString()](#getDataAsString--) | داده‌های زیرنویس بسته را به صورت رشتهٔ رمزگذاری‌شدهٔ UTF-8 برمی‌گرداند فقط خواندنی String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```

شناسهٔ یکتای سراسری (GUID) زیرنویس‌های بسته را برمی‌گرداند فقط خواندنی java.util.UUID.

**Returns:**  
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```

برچسب زیرنویس‌های بسته را برمی‌گرداند یا تنظیم می‌کند قابل خواندن و نوشتن String.

**Returns:**  
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```

برچسب زیرنویس‌های بسته را برمی‌گرداند یا تنظیم می‌کند قابل خواندن و نوشتن String.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

داده‌های باینری زیرنویس‌های بسته را برمی‌گرداند فقط خواندنی byte[] .

**Returns:**  
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```

داده‌های زیرنویس بسته را به صورت رشتهٔ رمزگذاری‌شدهٔ UTF-8 برمی‌گرداند فقط خواندنی String.

**Returns:**  
java.lang.String