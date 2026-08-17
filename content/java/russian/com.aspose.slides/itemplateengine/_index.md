---
title: ITemplateEngine
second_title: Aspose.Slides for Java API Reference
description: Представляет движок шаблонов, который преобразует пару шаблон-данные в результирующий вывод, обычно HTML.
type: docs
url: /ru/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Представляет движок шаблонов, который преобразует пару шаблон-данные в результирующий вывод (обычно HTML).
## Методы

| Method | Description |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Добавляет шаблон в коллекцию шаблонов. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Преобразует шаблон с указанным ключом и объектом модели в вывод. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

Добавляет шаблон в коллекцию шаблонов.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Ключ шаблона в коллекции шаблонов. |
| template | java.lang.String | Содержимое шаблона. |
| modelType | com.aspose.ms.System.Type | Тип объекта модели для шаблона. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Преобразует шаблон с указанным ключом и объектом модели в вывод.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Ключ шаблона в коллекции шаблонов. |
| model | java.lang.Object | Объект модели с данными для преобразования. |

**Возвращаемое значение:**
java.lang.String - Полученный вывод в виде строки.