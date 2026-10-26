---
title: ITemplateEngine
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a template engine that transforms template and data pair into resulting output usually HTML.
type: docs
url: /ar/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

يمثل محرك قوالب يحول زوج القالب والبيانات إلى المخرجات الناتجة (عادةً HTML).

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | يضيف القالب إلى مجموعة القوالب. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | يحوّل القالب باستخدام المفتاح والنموذج المحددين إلى المخرجات. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

يضيف القالب إلى مجموعة القوالب.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| key | java.lang.String | المفتاح للقالب في مجموعة القوالب. |
| template | java.lang.String | محتوى القالب. |
| modelType | com.aspose.ms.System.Type | نوع كائن النموذج للقالب. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

يحوّل القالب باستخدام المفتاح والنموذج المحددين إلى المخرجات.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| key | java.lang.String | المفتاح للقالب في مجموعة القوالب. |
| model | java.lang.Object | كائن النموذج بالبيانات للتحويل. |

**القيمة المرجعة:**
java.lang.String - المخرجات الناتجة كسلسلة.