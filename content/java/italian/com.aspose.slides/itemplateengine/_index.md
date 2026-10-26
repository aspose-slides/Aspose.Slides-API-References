---
title: ITemplateEngine
second_title: Aspose.Slides for Java API Reference
description: Represents a template engine that transforms template and data pair into resulting output usually HTML.
type: docs
url: /it/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Rappresenta un motore di template che trasforma una coppia di template e dati in un output risultante (di solito HTML).

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Aggiunge il template alla collezione di template. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Trasforma il template con la chiave specificata e l'oggetto modello per produrre l'output. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

Aggiunge il template alla collezione di template.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | Chiave per il template nella collezione di template. |
| template | java.lang.String | Contenuto del template. |
| modelType | com.aspose.ms.System.Type | Tipo di un oggetto modello per il template. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Trasforma il template con la chiave specificata e l'oggetto modello per produrre l'output.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | Chiave per il template nella collezione di template. |
| model | java.lang.Object | Oggetto modello con i dati per la trasformazione. |

**Restituisce:**
java.lang.String - Output risultante come Stringa.