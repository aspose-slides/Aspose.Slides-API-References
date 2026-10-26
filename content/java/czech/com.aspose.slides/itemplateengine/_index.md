---
title: ITemplateEngine
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje šablonový engine, který převádí pár šablona a data na výsledný výstup, obvykle HTML.
type: docs
url: /cs/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Reprezentuje šablonový engine, který převádí pár šablona a data na výsledný výstup (obvykle HTML).

## Metody

| Metoda | Popis |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Přidá šablonu do kolekce šablon. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Převede šablonu s daným klíčem a objektovým modelem na výstup. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

Přidá šablonu do kolekce šablon.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| key | java.lang.String | Klíč pro šablonu v kolekci šablon. |
| template | java.lang.String | Obsah šablony. |
| modelType | com.aspose.ms.System.Type | Typ objektu modelu pro šablonu. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Převede šablonu s daným klíčem a objektovým modelem na výstup.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| key | java.lang.String | Klíč pro šablonu v kolekci šablon. |
| model | java.lang.Object | Objekt modelu s daty pro převod. |

**Vrací:**
java.lang.String - Výstup jako řetězec.