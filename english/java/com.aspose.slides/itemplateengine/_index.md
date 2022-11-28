---
title: ITemplateEngine
second_title: Aspose.Slides for Java API Reference
description: Represents a template engine that transforms template and data pair into resulting output usually HTML.
type: docs
weight: 1066
url: /java/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Represents a template engine that transforms template and data pair into resulting output (usually HTML).
## Methods

| Method | Description |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Adds the template to the template collection. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Transforms the template with the given key and model object to output. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```


Adds the template to the template collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key for the template in the template collection. |
| template | java.lang.String | Template content. |
| modelType | com.aspose.ms.System.Type | Type of a model object for the template. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```


Transforms the template with the given key and model object to output.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key for the template in the template collection. |
| model | java.lang.Object | Model object with data for transformation. |

**Returns:**
java.lang.String - Resulting output as a String.
