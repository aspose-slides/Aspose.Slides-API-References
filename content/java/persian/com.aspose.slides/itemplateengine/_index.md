---
title: ITemplateEngine
second_title: Aspose.Slides for Java API Reference
description: Represents a template engine that transforms template and data pair into resulting output usually HTML.
type: docs
url: /fa/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

قالبی را که قالب و جفت داده را به خروجی نهایی (معمولاً HTML) تبدیل می‌کند، نشان می‌دهد.
## متدها

| Method | Description |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | قالب را به مجموعه قالب‌ها اضافه می‌کند. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | قالب را با کلید داده‌شده و شی مدل به خروجی تبدیل می‌کند. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```


قالب را به مجموعه قالب‌ها اضافه می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | کلید برای قالب در مجموعه قالب‌ها. |
| template | java.lang.String | محتوای قالب. |
| modelType | com.aspose.ms.System.Type | نوع شی مدل برای قالب. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```


قالب را با کلید داده‌شده و شی مدل به خروجی تبدیل می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | کلید برای قالب در مجموعه قالب‌ها. |
| model | java.lang.Object | شی مدل با داده برای تبدیل. |

**بازگشت:**
java.lang.String - خروجی حاصل به‌صورت یک رشته.