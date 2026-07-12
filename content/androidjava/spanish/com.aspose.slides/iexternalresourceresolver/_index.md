---
title: IExternalResourceResolver
second_title: Aspose.Slides for Android via Java API Reference
description: Interfaz de devolución de llamada utilizada para resolver recursos externos durante la importación de documentos Html, Svg.
type: docs
url: /es/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Interfaz de devolución de llamada utilizada para resolver recursos externos durante la importación de documentos Html, Svg.
## Métodos

| Método | Descripción |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resuelve el URI absoluto a partir de los URI base y relativo. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mapea un URI a un objeto que contiene el recurso real. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```


Resuelve el URI absoluto a partir de los URI base y relativo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | java.lang.String | URI base de los objetos de enlace |
| relativeUri | java.lang.String | URI relativo al objeto enlazado. |

**Devuelve:**
java.lang.String - URI absoluto o null si el URI relativo no se puede resolver.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```


Mapea un URI a un objeto que contiene el recurso real.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI absoluto al objeto. |

**Devuelve:**
java.io.InputStream - Un objeto InputStream o null si el recurso no se puede transmitir.