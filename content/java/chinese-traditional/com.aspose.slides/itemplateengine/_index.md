---
title: ITemplateEngine
second_title: Aspose.Slides for Java API Reference
description: 表示一個將模板和資料對轉換為最終輸出（通常為 HTML）的模板引擎。
type: docs
url: /zh-hant/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

表示一個將模板和資料對轉換為最終輸出（通常為 HTML）的模板引擎。
## 方法

| 方法 | 說明 |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | 將模板加入模板集合。 |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | 使用給定的鍵和值模型物件轉換模板為輸出。 |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

將模板加入模板集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key | java.lang.String | 模板集合中模板的鍵。 |
| template | java.lang.String | 模板內容。 |
| modelType | com.aspose.ms.System.Type | 模板的模型物件類型。 |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

使用給定的鍵和值模型物件轉換模板為輸出。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key | java.lang.String | 模板集合中模板的鍵。 |
| model | java.lang.Object | 用於轉換的模型資料物件。 |

**傳回值:**
java.lang.String - 結果輸出為字串。