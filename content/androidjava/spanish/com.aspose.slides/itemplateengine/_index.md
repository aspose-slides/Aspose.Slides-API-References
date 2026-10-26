---
title: ITemplateEngine
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa un motor de plantillas que transforma un par de plantilla y datos en la salida resultante (normalmente HTML).
type: docs
url: /es/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Representa un motor de plantillas que transforma un par de plantilla y datos en la salida resultante (normalmente HTML).

## Métodos

| Method | Description |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Agrega la plantilla a la colección de plantillas. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Transforma la plantilla con la clave proporcionada y el objeto modelo para obtener la salida. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```


Agrega la plantilla a la colección de plantillas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Clave de la plantilla en la colección de plantillas. |
| template | java.lang.String | Contenido de la plantilla. |
| modelType | com.aspose.ms.System.Type | Tipo de un objeto modelo para la plantilla. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```


Transforma la plantilla con la clave proporcionada y el objeto modelo para obtener la salida.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Clave de la plantilla en la colección de plantillas. |
| model | java.lang.Object | Objeto modelo con datos para la transformación. |

**Returns:**
java.lang.String - Salida resultante como una cadena.