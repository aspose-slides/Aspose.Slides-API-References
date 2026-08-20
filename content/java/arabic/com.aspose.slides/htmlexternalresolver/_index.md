---
title: HtmlExternalResolver
second_title: مرجع API Aspose.Slides للـ Java
description: كائن رد النداء يُستخدم في روتين استيراد HTML للحصول على الكائنات المشار إليها مثل الصور.
type: docs
url: /ar/com.aspose.slides/htmlexternalresolver/
---
**Inheritance:**  
الوراثة:

java.lang.Object

**All Implemented Interfaces:**  
جميع الواجهات المنفذة:

[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)  
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

كائن رد نداء يستخدمه روتين استيراد HTML للحصول على الكائنات المشار إليها مثل الصور.

--------------------

يمكن أن يتسبب استخدام هذا المحلل في خلق ثغرة عندما يقوم ملف HTML مقدم من العميل بجعل برنامج الخادم يحصل على ملف محلي أو شبكة. استخدمه بحذر. يُنصح بعدم تحديد HtmlExternalResolver نهائيًا (سيتم قراءة الكائنات المضمّنة فقط) أو إنشاء فئة فرعية تتحقق مما إذا كان الـ uri المحدد صالحًا.

## Constructors
## المُنشئات

| Constructor | Description |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |

## Methods
## الطرق

| Method | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |

### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

يقوم بحل الـ URI المطلق من الـ URI الأساسي والـ URI النسبي.

**Parameters:**  
**المعلمات:**

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | java.lang.String | URI الأساسي للكائنات المرتبطة |
| relativeUri | java.lang.String | URI النسبي للكائن المرتبط. |

**Returns:**  
**الإرجاع:**

java.lang.String - URI مطلق أو ‎null‎ إذا تعذر حل الـ URI النسبي.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

يربط URI بكائن يحتوي على المورد الفعلي.

**Parameters:**  
**المعلمات:**

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI المطلق للكائن. |

**Returns:**  
**الإرجاع:**

java.io.InputStream - كائن InputStream أو ‎null‎ إذا تعذر بث المورد.