---
title: ITemplateEngine
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a template engine that transforms template and data pair into resulting output usually HTML.
type: docs
url: /zh-hant/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

表示一個將模板與資料配對轉換為最終輸出（通常為 HTML）的模板引擎。
## 方法

| 方法 | 說明 |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Adds the template to the template collection. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Transforms the template with the given key and model object to output. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

將模板新增至模板集合中。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key | java.lang.String | Key for the template in the template collection. |
| template | java.lang.String | Template content. |
| modelType | com.aspose.ms.System.Type | Type of a model object for the template. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

使用給定的鍵和模型物件轉換模板為輸出。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key | java.lang.String | Key for the template in the template collection. |
| model | java.lang.Object | Model object with data for transformation. |

**傳回值：**
java.lang.String - 結果輸出為字串。