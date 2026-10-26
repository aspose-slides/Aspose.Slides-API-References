---
title: ITemplateEngine
second_title: Aspose.Slides برای Android از طریق Java API Reference
description: نماینده‌ی یک موتور قالب است که جفت قالب و داده را به خروجی نهایی (معمولاً HTML) تبدیل می‌کند.
type: docs
url: /fa/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

نمایندهٔ یک موتور قالب است که جفت قالب و داده را به خروجی نهایی (معمولاً HTML) تبدیل می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | قالب را به مجموعه قالب‌ها اضافه می‌کند. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | قالب را با کلید داده شده و شیء مدل به خروجی تبدیل می‌کند. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

قالب را به مجموعه قالب‌ها اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| key | java.lang.String | کلید برای قالب در مجموعه قالب‌ها. |
| template | java.lang.String | محتوای قالب. |
| modelType | com.aspose.ms.System.Type | نوع شیء مدل برای قالب. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

قالب را با کلید داده شده و شیء مدل به خروجی تبدیل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| key | java.lang.String | کلید برای قالب در مجموعه قالب‌ها. |
| model | java.lang.Object | شیء مدل با داده‌ها برای تبدیل. |

**بازگشت:**
java.lang.String - خروجی نهایی به‌عنوان یک رشته.