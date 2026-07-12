---
title: HtmlExternalResolver
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Objeto de devolución de llamada utilizado por la rutina de importación HTML para obtener objetos referenciados, como imágenes.
type: docs
url: /es/com.aspose.slides/htmlexternalresolver/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Objeto de devolución de llamada utilizado por la rutina de importación HTML para obtener objetos referenciados como imágenes.

El uso de este resolvedor podría crear una vulnerabilidad cuando un archivo HTML proporcionado por el cliente hace que el software del servidor obtenga un archivo local o de red. Úselo con precaución. Se recomienda no especificar HtmlExternalResolver en absoluto (solo se leerán los objetos incrustados) o crear alguna subclase que verifique si la uri especificada es válida.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resuelve la URI absoluta a partir de la URI base y la URI relativa. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mapea una URI a un objeto que contiene el recurso real. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Resuelve la URI absoluta a partir de la URI base y la URI relativa.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | java.lang.String | URI base de los objetos enlazados |
| relativeUri | java.lang.String | URI relativa al objeto enlazado. |

**Devuelve:**
java.lang.String - URI absoluta o null si la URI relativa no puede resolverse.
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
java.io.InputStream - Un objeto InputStream o null si el recurso no puede transmitirse.