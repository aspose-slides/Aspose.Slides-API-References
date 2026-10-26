---
title: ExternalResourceResolver
second_title: Aspose.Slides para Android vía Referencia de la API Java
description: Clase de devolución de llamada utilizada para resolver recursos externos durante la importación de documentos HTML y SVG.
type: docs
url: /es/com.aspose.slides/externalresourceresolver/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Clase de devolución de llamada utilizada para resolver recursos externos durante la importación de documentos Html, Svg.

--------------------

Usar este resolvedor podría crear una vulnerabilidad cuando un archivo HTML o SVG proporcionado por el cliente hace que el software del servidor obtenga un archivo local o de red. Úselo con precaución. Se recomienda no especificar ExternalResourceResolver en absoluto (solo se leerán los objetos incrustados) o crear una subclase que verifique si la uri especificada es válida.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resuelve la URI absoluta a partir de las URIs base y relativas. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mapea una URI a un objeto que contiene el recurso real. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Resuelve la URI absoluta a partir de las URIs base y relativas.

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
| absoluteUri | java.lang.String | URI absoluta al objeto. |

**Devuelve:**
java.io.InputStream - Un objeto InputStream o null si el recurso no se puede transmitir.