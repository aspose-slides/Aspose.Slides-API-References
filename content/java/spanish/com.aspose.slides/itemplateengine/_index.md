---
title: ITemplateEngine
second_title: Aspose.Slides para Java Referencia de API
description: Representa un motor de plantillas que transforma un par de plantilla y datos en una salida resultante, generalmente HTML.
type: docs
url: /es/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Representa un motor de plantillas que transforma un par de plantilla y datos en una salida resultante (generalmente HTML).

## Métodos

| Método | Descripción |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Adds the template to the template collection. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Transforms the template with the given key and model object to output. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

Adds the template to the template collection.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | Clave de la plantilla en la colección de plantillas. |
| template | java.lang.String | Contenido de la plantilla. |
| modelType | com.aspose.ms.System.Type | Tipo de un objeto modelo para la plantilla. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Transforms the template with the given key and model object to output.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key | java.lang.String | Clave de la plantilla en la colección de plantillas. |
| model | java.lang.Object | Objeto modelo con datos para la transformación. |

**Devuelve:**
java.lang.String - Salida resultante como una cadena.