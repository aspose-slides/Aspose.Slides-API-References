---
title: ExternalResourceResolver
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: فئة رد النداء المستخدمة لحل الموارد الخارجية أثناء استيراد مستندات Html و Svg.
type: docs
url: /ar/com.aspose.slides/externalresourceresolver/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

فئة رد النداء المستخدمة لحل الموارد الخارجية أثناء استيراد مستندات Html و Svg.

--------------------

يمكن أن يخلق استخدام هذا المفسِّر ثغرة عندما يؤدي ملف HTML أو SVG مقدم من العميل إلى جعل برنامج الخادم يحصل على ملف محلي أو شبكي. استخدمه بحذر. يُنصح بعدم تحديد ExternalResourceResolver على الإطلاق (سيتم قراءة الكائنات المدمجة فقط) أو إنشاء فئة فرعية تقوم بالتحقق مما إذا كان الـ uri المحدد صالحًا.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | يحل الـ URI المطلق من URI الأساسي والـ URI النسبي. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | يربط URI بجسم يحتوي على المورد الفعلي. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


يحل الـ URI المطلق من URI الأساسي والـ URI النسبي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseUri | java.lang.String | URI الأساسي للكائنات المرتبطة |
| relativeUri | java.lang.String | URI النسبي للكائن المرتبط. |

**القيمة المرجعة:**
java.lang.String - URI مطلق أو null إذا تعذر حل الـ URI النسبي.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


يربط URI بجسم يحتوي على المورد الفعلي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI مطلق إلى الكائن. |

**القيمة المرجعة:**
java.io.InputStream - كائن InputStream أو null إذا تعذر تدفق المورد.