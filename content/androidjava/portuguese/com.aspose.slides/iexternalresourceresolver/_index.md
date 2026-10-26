---
title: IExternalResourceResolver
second_title: Aspose.Slides para Android via Referência da API Java
description: Interface de callback usada para resolver recursos externos durante a importação de documentos Html e Svg.
type: docs
url: /pt/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Interface de callback usada para resolver recursos externos durante a importação de documentos Html, Svg.
## Métodos

| Método | Descrição |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolve o URI absoluto a partir dos URIs base e relativo. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mapeia um URI para um objeto que contém o recurso real. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```


Resolve o URI absoluto a partir dos URIs base e relativo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseUri | java.lang.String | URI base dos objetos de ligação |
| relativeUri | java.lang.String | URI relativo ao objeto ligado. |

**Retorno:**
java.lang.String - URI absoluto ou null se o URI relativo não puder ser resolvido.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```


Mapeia um URI para um objeto que contém o recurso real.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI absoluto para o objeto. |

**Retorno:**
java.io.InputStream - Um objeto InputStream ou null se o recurso não puder ser transmitido.