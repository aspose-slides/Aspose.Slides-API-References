---
title: IExternalResourceResolver
second_title: Aspose.Slides per Android tramite Java API Reference
description: Interfaccia di callback usata per risolvere risorse esterne durante l'importazione di documenti Html e Svg.
type: docs
url: /it/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Interfaccia di callback usata per risolvere risorse esterne durante l'importazione di documenti Html, Svg.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Risolve l'URI assoluto a partire dagli URI di base e relativo. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mappa un URI a un oggetto contenente la risorsa effettiva. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```


Risolve l'URI assoluto a partire dagli URI di base e relativo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseUri | java.lang.String | URI di base degli oggetti di collegamento |
| relativeUri | java.lang.String | URI relativo all'oggetto collegato. |

**Restituisce:**
java.lang.String - URI assoluto o null se l'URI relativo non può essere risolto.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```


Mappa un URI a un oggetto contenente la risorsa effettiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI assoluto dell'oggetto. |

**Restituisce:**
java.io.InputStream - Un oggetto InputStream o null se la risorsa non può essere trasmessa in streaming.