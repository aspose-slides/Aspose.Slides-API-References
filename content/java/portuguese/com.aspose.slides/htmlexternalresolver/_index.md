---
title: HtmlExternalResolver
second_title: Referência da API Aspose.Slides para Java
description: Objeto de retorno de chamada usado pela rotina de importação HTML para obter objetos referenciados, como imagens.
type: docs
url: /pt/com.aspose.slides/htmlexternalresolver/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Objeto de retorno de chamada usado pela rotina de importação HTML para obter objetos referenciados, como imagens.

--------------------

Usar este resolvedor pode criar uma vulnerabilidade quando um arquivo HTML fornecido pelo cliente faz com que o software do servidor obtenha um arquivo local ou de rede. Use com cautela. Recomenda-se não especificar HtmlExternalResolver de forma alguma (apenas objetos incorporados serão lidos) ou criar alguma subclasse que verifique se o uri especificado é válido.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Resolves the absolute URI from the base and relative URIs.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseUri | java.lang.String | Base URI of linking objects |
| relativeUri | java.lang.String | Relative URI to the linked object. |

**Retorna:**
java.lang.String - Absolute URI or null if the relative URI cannot be resolved.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Maps a URI to an object containing the actual resource.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI to the object. |

**Retorna:**
java.io.InputStream - A InputStream object or null if resource cannot be streamed.