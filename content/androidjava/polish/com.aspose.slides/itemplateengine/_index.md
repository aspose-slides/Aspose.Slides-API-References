---
title: ITemplateEngine
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje silnik szablonów, który przekształca parę szablonu i danych w wynikowe wyjście (zazwyczaj HTML).
type: docs
url: /pl/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Reprezentuje silnik szablonów, który przekształca parę szablonu i danych w wynikowe wyjście (zazwyczaj HTML).

## Metody

| Metoda | Opis |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Dodaje szablon do kolekcji szablonów. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Przekształca szablon z podanym kluczem i obiektem modelu do wyjścia. |
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

Przekształca szablon z podanym kluczem i obiektem modelu do wyjścia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| key | java.lang.String | Klucz szablonu w kolekcji szablonów. |
| model | java.lang.Object | Obiekt modelu z danymi do przekształcenia. |

**Zwraca:**
java.lang.String - Wynikowe wyjście jako String.