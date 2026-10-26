---
title: HtmlExternalResolver
second_title: Referencia de la API de Aspose.Slides para Java
description: Objeto de devolución de llamada utilizado por la rutina de importación HTML para obtener objetos referenciados como imágenes.
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

--------------------

Usar este resolvedor podría crear una vulnerabilidad cuando un archivo HTML provisto por el cliente hace que el software del servidor obtenga un archivo local o de red. Úselo con precaución. Se recomienda no especificar HtmlExternalResolver en absoluto (solo se leerán los objetos incrustados) o crear una subclase que verifique si el URI especificado es válido.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resuelve el URI absoluto a partir de los URI base y relativo. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Asocia un URI a un objeto que contiene el recurso real. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Resuelve el URI absoluto a partir de los URI base y relativo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | java.lang.String | URI base de los objetos que enlazan |
| relativeUri | java.lang.String | URI relativo al objeto enlazado. |

**Devuelve:**
java.lang.String - URI absoluto o null si el URI relativo no puede resolverse.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Asocia un URI a un objeto que contiene el recurso real.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI absoluto al objeto. |

**Devuelve:**
java.io.InputStream - Un objeto InputStream o null si el recurso no puede transmitirse.