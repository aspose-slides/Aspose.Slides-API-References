---
title: ICaptions
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: نمایانگر زیرنویس‌های بسته WebVTT.
type: docs
url: /fa/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

نمایانگر زیرنویس‌های بسته WebVTT.
## متدها

| متد | توضیح |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | شناسهٔ یکتا جهانی (GUID) زیرنویس‌های بسته را باز می‌گرداند. |
| [getLabel()](#getLabel--) | برچسب زیرنویس‌های بسته را باز می‌گرداند یا تنظیم می‌کند. |
| [setLabel(String value)](#setLabel-java.lang.String-) | برچسب زیرنویس‌های بسته را باز می‌گرداند یا تنظیم می‌کند. |
| [getBinaryData()](#getBinaryData--) | دادهٔ باینری زیرنویس‌های بسته را باز می‌گرداند. |
| [getDataAsString()](#getDataAsString--) | دادهٔ زیرنویس‌های بسته را به‌صورت رشتهٔ کدگذاری شده UTF-8 باز می‌گرداند. فقط‌خواندنی String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

شناسهٔ یکتا جهانی (GUID) زیرنویس‌های بسته را باز می‌گرداند. فقط‌خواندنی java.util.UUID.

**بازگشت:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

برچسب زیرنویس‌های بسته را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**بازگشت:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

برچسب زیرنویس‌های بسته را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

دادهٔ باینری زیرنویس‌های بسته را باز می‌گرداند. فقط‌خواندنی byte[].

**بازگشت:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

دادهٔ زیرنویس‌های بسته را به‌صورت رشتهٔ کدگذاری شده UTF-8 باز می‌گرداند. فقط‌خواندنی String.

**بازگشت:**
java.lang.String