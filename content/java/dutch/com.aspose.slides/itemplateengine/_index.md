---
title: ITemplateEngine
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een sjabloonengine voor die een sjabloon- en gegevenspaar transformeert naar de resulterende uitvoer, meestal HTML.
type: docs
url: /nl/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Stelt een sjabloonengine voor die een sjabloon- en gegevenspaar transformeert naar de resulterende uitvoer (meestal HTML).
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Voegt de sjabloon toe aan de sjabloonverzameling. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Transformeert de sjabloon met de opgegeven sleutel en modelobject naar de uitvoer. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```


Voegt de sjabloon toe aan de sjabloonverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | java.lang.String | Sleutel voor de sjabloon in de sjabloonverzameling. |
| template | java.lang.String | Inhoud van de sjabloon. |
| modelType | com.aspose.ms.System.Type | Type van een modelobject voor de sjabloon. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```


Transformeert de sjabloon met de opgegeven sleutel en modelobject naar de uitvoer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | java.lang.String | Sleutel voor de sjabloon in de sjabloonverzameling. |
| model | java.lang.Object | Modelobject met gegevens voor de transformatie. |

**Retourwaarde:**
java.lang.String - Resulterende uitvoer als een String.