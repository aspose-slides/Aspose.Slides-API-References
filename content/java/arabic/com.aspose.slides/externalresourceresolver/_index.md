---
title: ExternalResourceResolver
second_title: Aspose.Slides لمرجع API لجافا
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

استخدام هذا المحلّل قد يخلق ثغرة عندما يقوم ملف HTML أو SVG مقدَّم من العميل بجعل برنامج الخادم يحصل على ملف محلي أو شبكة. استخدمه بحذر. يوصى بعدم تحديد ExternalResourceResolver مطلقاً (سيتم قراءة الكائنات المضمنة فقط) أو إنشاء فئة فرعية تتحقق من صحة الـ uri المحدد.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | يقوم بحل الـ URI المطلق من الـ URI الأساسي والـ URI النسبي. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | يطابق URI مع كائن يحتوي على المورد الفعلي. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


يقوم بحل الـ URI المطلق من الـ URI الأساسي والـ URI النسبي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| baseUri | java.lang.String | URI الأساسي للكائنات المرتبطة |
| relativeUri | java.lang.String | URI النسبي للكائن المرتبط. |

**الإرجاع:**
java.lang.String - URI مطلق أو null إذا تعذر حل الـ URI النسبي.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


يطابق URI مع كائن يحتوي على المورد الفعلي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI مطلق للكائن. |

**الإرجاع:**
java.io.InputStream - كائن InputStream أو null إذا تعذر تدفق المورد.