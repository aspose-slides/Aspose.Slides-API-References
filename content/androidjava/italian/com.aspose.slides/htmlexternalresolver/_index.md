---
title: HtmlExternalResolver
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Oggetto di callback utilizzato dalla routine di importazione HTML per ottenere oggetti di riferimento come immagini.
type: docs
url: /it/com.aspose.slides/htmlexternalresolver/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Oggetto di callback usato dalla routine di importazione HTML per ottenere oggetti di riferimento come immagini.

--------------------

L'utilizzo di questo resolver potrebbe creare una vulnerabilità quando un file HTML fornito dal client fa sì che il software server ottenga un file locale o di rete. Usare con cautela. Si consiglia di non specificare HtmlExternalResolver affatto (verranno letti solo gli oggetti incorporati) o di creare una sottoclasse che verifichi se l'uri specificato è valido.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Risolve l'URI assoluto dalla base e dagli URI relativi. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mappa un URI a un oggetto contenente la risorsa reale. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Risolve l'URI assoluto dalla base e dagli URI relativi.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseUri | java.lang.String | Base URI of linking objects |
| relativeUri | java.lang.String | Relative URI to the linked object. |

**Restituisce:**
java.lang.String - URI assoluto o null se l'URI relativo non può essere risolto.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Mappa un URI a un oggetto contenente la risorsa reale.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI to the object. |

**Restituisce:**
java.io.InputStream - Un oggetto InputStream o null se la risorsa non può essere trasmessa in streaming.