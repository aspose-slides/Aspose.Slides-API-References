---
title: ITemplateEngine
second_title: Aspose.Slides for Java API Reference
description: 表示一个模板引擎，将模板和数据对转换为结果输出（通常为 HTML）。
type: docs
url: /zh/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

表示一个模板引擎，将模板和数据对转换为结果输出（通常为 HTML）。
## 方法

| 方法 | 描述 |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | 将模板添加到模板集合中。 |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | 使用给定的键和模型对象转换模板以生成输出。 |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

将模板添加到模板集合中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 模板集合中模板的键。 |
| template | java.lang.String | 模板内容。 |
| modelType | com.aspose.ms.System.Type | 模板的模型对象的类型。 |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

使用给定的键和模型对象转换模板以生成输出。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | java.lang.String | 模板集合中模板的键。 |
| model | java.lang.Object | 用于转换的数据模型对象。 |

**返回值:**
java.lang.String - 作为字符串的结果输出。