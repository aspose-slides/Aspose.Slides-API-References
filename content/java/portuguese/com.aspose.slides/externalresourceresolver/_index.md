---
title: ExternalResourceResolver
second_title: Referência da API Aspose.Slides para Java
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

Usar este resolvedor pode criar uma vulnerabilidade quando um arquivo HTML ou SVG fornecido pelo cliente fizer o software do servidor obter um arquivo local ou de rede. Use com cautela. Recomenda-se não especificar ExternalResourceResolver de forma alguma (somente objetos incorporados serão lidos) ou criar alguma subclasse que verifique se o uri especificado é válido.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolve o URI absoluto a partir dos URIs base e relativo. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mapeia um URI para um objeto que contém o recurso real. |
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
| absoluteUri | java.lang.String | URI absoluto do objeto. |

**Retorna:**
java.io.InputStream - Um objeto InputStream ou null se o recurso não puder ser transmitido.