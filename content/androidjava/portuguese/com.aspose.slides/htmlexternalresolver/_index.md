---
title: HtmlExternalResolver
second_title: Aspose.Slides para Android via Referência da API Java
description: Objeto de callback usado pela rotina de importação HTML para obter objetos referenciados, como imagens.
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

Objeto de callback usado pela rotina de importação HTML para obter objetos referenciados, como imagens.

--------------------

Usar este resolvedor pode criar uma vulnerabilidade quando um arquivo HTML fornecido pelo cliente faz com que o software do servidor obtenha um arquivo local ou de rede. Use com cautela. É recomendado não especificar HtmlExternalResolver de forma alguma (apenas objetos incorporados serão lidos) ou criar alguma subclasse que verifique se o URI especificado é válido.
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


Resolve o URI absoluto a partir dos URIs base e relativo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseUri | java.lang.String | URI base dos objetos de ligação |
| relativeUri | java.lang.String | URI relativo ao objeto vinculado. |

**Retorna:**
java.lang.String - URI absoluto ou null se o URI relativo não puder ser resolvido.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Mapeia um URI para um objeto que contém o recurso real.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI absoluto para o objeto. |

**Retorna:**
java.io.InputStream - Um objeto InputStream ou null se o recurso não puder ser transmitido.