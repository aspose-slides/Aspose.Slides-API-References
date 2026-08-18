---
title: ExternalResourceResolver
second_title: Referencia de API de Aspose.Slides para Java
description: Clase de devolución de llamada utilizada para resolver recursos externos durante la importación de documentos Html y Svg.
type: docs
url: /es/com.aspose.slides/externalresourceresolver/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Clase de devolución de llamada utilizada para resolver recursos externos durante la importación de documentos Html y Svg.

--------------------

El uso de este resolvedor podría crear una vulnerabilidad cuando un archivo HTML o SVG proporcionado por el cliente haga que el software del servidor obtenga un archivo local o de red. Úselo con precaución. Se recomienda no especificar ExternalResourceResolver en absoluto (solo se leerán los objetos incrustados) o crear una subclase que verifique si la URI especificada es válida.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resuelve la URI absoluta a partir de las URIs base y relativa. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mapea una URI a un objeto que contiene el recurso real. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

Resuelve la URI absoluta a partir de las URIs base y relativa.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | java.lang.String | URI base de los objetos enlazados |
| relativeUri | java.lang.String | URI relativa al objeto enlazado. |

**Devuelve:**
java.lang.String - URI absoluta o null si la URI relativa no se puede resolver.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

Mapea una URI a un objeto que contiene el recurso real.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI absoluta del objeto. |

**Devuelve:**
java.io.InputStream - Un objeto InputStream o null si el recurso no se puede transmitir.