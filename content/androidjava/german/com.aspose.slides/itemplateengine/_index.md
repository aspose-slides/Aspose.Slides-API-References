---
title: ITemplateEngine
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt eine Vorlagen-Engine dar, die Vorlagen- und Datenpaare in die resultierende Ausgabe (in der Regel HTML) transformiert.
type: docs
url: /de/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Stellt eine Vorlagen-Engine dar, die Vorlagen- und Datenpaare in die resultierende Ausgabe (in der Regel HTML) transformiert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Fügt die Vorlage zur Vorlagensammlung hinzu. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Transformiert die Vorlage mit dem angegebenen Schlüssel und dem Modellobjekt zur Ausgabe. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```


Fügt die Vorlage zur Vorlagensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | java.lang.String | Schlüssel für die Vorlage in der Vorlagensammlung. |
| template | java.lang.String | Vorlageninhalt. |
| modelType | com.aspose.ms.System.Type | Typ des Modellobjekts für die Vorlage. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```


Transformiert die Vorlage mit dem angegebenen Schlüssel und dem Modellobjekt zur Ausgabe.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | java.lang.String | Schlüssel für die Vorlage in der Vorlagensammlung. |
| model | java.lang.Object | Modellobjekt mit Daten für die Transformation. |

**Rückgabewert:**
java.lang.String - Resultierende Ausgabe als String.