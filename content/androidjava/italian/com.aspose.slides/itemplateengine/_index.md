---
title: ITemplateEngine
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta un motore di template che trasforma una coppia di template e dati in un output risultante solitamente HTML.
type: docs
url: /it/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Rappresenta un motore di template che trasforma una coppia di template e dati in un output risultante (solitamente HTML).

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Adds the template to the template collection. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Transforms the template with the given key and model object to output. |

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
| modelType | com.aspose.ms.System.Type | Tipo di oggetto modello per il template. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Trasforma il template con la chiave fornita e l'oggetto modello per produrre l'output.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | Chiave per il template nella collezione di template. |
| model | java.lang.Object | Oggetto modello con i dati per la trasformazione. |

**Restituisce:**
java.lang.String - Output risultante come stringa.