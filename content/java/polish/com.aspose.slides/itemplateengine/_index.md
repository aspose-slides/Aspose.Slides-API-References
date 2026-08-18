---
title: ITemplateEngine
second_title: Aspose.Slides for Java API Reference
description: Represents a template engine that transforms template and data pair into resulting output usually HTML.
type: docs
url: /pl/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Reprezentuje silnik szablonów, który przekształca parę szablon i dane w wynikowe wyjście (zwykle HTML).
## Metody

| Metoda | Opis |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Dodaje szablon do kolekcji szablonów. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Przekształca szablon przy użyciu podanego klucza i obiektu modelu w wyjście. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

Dodaje szablon do kolekcji szablonów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| key | java.lang.String | Klucz szablonu w kolekcji szablonów. |
| template | java.lang.String | Zawartość szablonu. |
| modelType | com.aspose.ms.System.Type | Typ obiektu modelu dla szablonu. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Przekształca szablon przy użyciu podanego klucza i obiektu modelu w wyjście.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| key | java.lang.String | Klucz szablonu w kolekcji szablonów. |
| model | java.lang.Object | Obiekt modelu zawierający dane do przekształcenia. |

**Zwraca:**
java.lang.String - Wynikowe wyjście jako ciąg znaków.