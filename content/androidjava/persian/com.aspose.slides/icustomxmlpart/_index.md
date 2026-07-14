---
title: ICustomXmlPart
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: نمایانگر بخش XML سفارشی.
type: docs
url: /fa/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

نمایانگر بخش XML سفارشی.
## توابع

| متد | توضیح |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | داده‌های xml را به صورت رشته UTF-8 باز می‌گرداند یا تنظیم می‌کند. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | داده‌های xml را به صورت رشته UTF-8 باز می‌گرداند یا تنظیم می‌کند. |
| [getXmlData()](#getXmlData--) | داده‌های xml را باز می‌گرداند یا تنظیم می‌کند. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | داده‌های xml را باز می‌گرداند یا تنظیم می‌کند. |
| [getItemId()](#getItemId--) | یک شناسه یکتا جهانی (GUID) که یک بخش XML سفارشی را به‌طور یکتا در یک سند Office Open XML شناسایی می‌کند. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | یک شناسه یکتا جهانی (GUID) که یک بخش XML سفارشی را به‌طور یکتا در یک سند Office Open XML شناسایی می‌کند. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | مجموعه‌ی طرح‌واره‌های XML مرتبط با بخش XML سفارشی را باز می‌گرداند. |
| [remove()](#remove--) | بخش XML سفارشی را از ارائه حذف می‌کند. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

داده‌های xml را به صورت رشته UTF-8 باز می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

داده‌های xml را به صورت رشته UTF-8 باز می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

داده‌های xml را باز می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی byte[].

**بازگشت:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

داده‌های xml را باز می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی byte[].

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte[] |  |

### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

یک شناسه یکتا جهانی (GUID) که یک بخش XML سفارشی را به‌طور یکتا در یک سند Office Open XML شناسایی می‌کند. فقط خواندنی java.util.UUID.

**بازگشت:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

یک شناسه یکتا جهانی (GUID) که یک بخش XML سفارشی را به‌طور یکتا در یک سند Office Open XML شناسایی می‌کند. فقط خواندنی java.util.UUID.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

مجموعه‌ای از طرح‌واره‌های XML مرتبط با بخش XML سفارشی را باز می‌گرداند. فقط خواندنی String[].

**بازگشت:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

بخش XML سفارشی را از ارائه حذف می‌کند.