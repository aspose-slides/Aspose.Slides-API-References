---
title: IExternalResourceResolver
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to resolve external resources during Html Svg documents import.
type: docs
url: /ar/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

واجهة رد النداء المستخدمة لحل الموارد الخارجية أثناء استيراد مستندات Html و Svg.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | يحل URI المطلق من URI الأساسي و URI النسبي. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | يربط URI كائنًا يحتوي على المورد الفعلي. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

يقوم بحل URI المطلق من URI الأساسي و URI النسبي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseUri | java.lang.String | URI الأساسي لكائنات الارتباط |
| relativeUri | java.lang.String | URI النسبي إلى الكائن المرتبط. |

**القيمة المرجعة:**
java.lang.String - URI مطلق أو null إذا تعذر حل URI النسبي.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

يربط URI كائنًا يحتوي على المورد الفعلي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI مطلق إلى الكائن. |

**القيمة المرجعة:**
java.io.InputStream - كائن InputStream أو null إذا تعذر تدفق المورد.