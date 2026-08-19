---
title: ICustomXmlPart
second_title: Aspose.Slides for Java API Reference
description: Represents custom xml part.
type: docs
url: /fa/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

نمایندهٔ بخش XML سفارشی.
## متدها

| متد | توضیحات |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | داده‌های XML را به صورت رشته UTF-8 برمی‌گرداند یا تنظیم می‌کند. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | داده‌های XML را به صورت رشته UTF-8 برمی‌گرداند یا تنظیم می‌کند. |
| [getXmlData()](#getXmlData--) | داده‌های XML را برمی‌گرداند یا تنظیم می‌کند. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | داده‌های XML را برمی‌گرداند یا تنظیم می‌کند. |
| [getItemId()](#getItemId--) | یک شناسه یکتا جهانی (GUID) که یک بخش XML سفارشی منفرد را در یک سند Office Open XML به طور یکتا شناسایی می‌کند. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | یک شناسه یکتا جهانی (GUID) که یک بخش XML سفارشی منفرد را در یک سند Office Open XML به طور یکتا شناسایی می‌کند. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | مجموعه‌ی طرح‌های XML مرتبط با بخش XML سفارشی را برمی‌گرداند. |
| [remove()](#remove--) | بخش XML سفارشی را از ارائه حذف می‌کند. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```


داده‌های XML را به صورت رشته UTF-8 برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**بازگرداندن:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```


داده‌های XML را به صورت رشته UTF-8 برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```


داده‌های XML را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی byte[].

**بازگرداندن:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```


داده‌های XML را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی byte[].

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte[] |  |

### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```


یک شناسه یکتا جهانی (GUID) که یک بخش XML سفارشی منفرد را در یک سند Office Open XML به طور یکتا شناسایی می‌کند. فقط-خواندنی java.util.UUID.

**بازگرداندن:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```


یک شناسه یکتا جهانی (GUID) که یک بخش XML سفارشی منفرد را در یک سند Office Open XML به طور یکتا شناسایی می‌کند. فقط-خواندنی java.util.UUID.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```


مجموعه‌ی طرح‌های XML مرتبط با بخش XML سفارشی را برمی‌گرداند. فقط-خواندنی String[].

**بازگرداندن:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```


بخش XML سفارچی را از ارائه حذف می‌کند.