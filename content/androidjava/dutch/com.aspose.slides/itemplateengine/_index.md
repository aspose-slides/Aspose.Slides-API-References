---
title: ITemplateEngine
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt een template-engine voor die een sjabloon- en gegevenspaar omzet in de resulterende output, meestal HTML.
type: docs
url: /nl/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Stelt een template-engine voor die een sjabloon- en gegevenspaar omzet in de resulterende output (meestal HTML).

## Methodes

| Methode | Beschrijving |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Voegt de template toe aan de template-verzameling. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Transformeert de template met de opgegeven sleutel en modelobject naar output. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

Voegt de template toe aan de template-verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | java.lang.String | Sleutel voor de template in de template-verzameling. |
| template | java.lang.String | Inhoud van de template. |
| modelType | com.aspose.ms.System.Type | Type van een modelobject voor de template. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Transformeert de template met de opgegeven sleutel en modelobject naar output.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | java.lang.String | Sleutel voor de template in de template-verzameling. |
| model | java.lang.Object | Modelobject met gegevens voor de transformatie. |

**Returns:**
java.lang.String - Resulterende output als een String.