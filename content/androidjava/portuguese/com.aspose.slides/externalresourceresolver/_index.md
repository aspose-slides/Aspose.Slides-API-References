---
title: ExternalResourceResolver
second_title: Referência da API Java para Aspose.Slides para Android
description: Classe de retorno de chamada usada para resolver recursos externos durante a importação de documentos Html e Svg.
type: docs
url: /pt/com.aspose.slides/externalresourceresolver/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Classe de retorno de chamada usada para resolver recursos externos durante a importação de documentos Html, Svg.

--------------------

Usar este resolvedor pode criar uma vulnerabilidade quando um arquivo HTML ou SVG fornecido pelo cliente faz com que o software do servidor obtenha um arquivo local ou da rede. Use com cautela. Recomenda-se não especificar ExternalResourceResolver (apenas objetos incorporados serão lidos) ou criar uma subclasse que verifique se o uri especificado é válido.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Resolve o URI absoluto a partir dos URIs base e relativo.

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


Mapeia um URI para um objeto que contém o recurso real.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI to the object. |

**Retorna:**
java.io.InputStream - A InputStream object or null if resource cannot be streamed.