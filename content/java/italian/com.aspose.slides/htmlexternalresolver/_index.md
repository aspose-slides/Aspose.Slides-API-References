---
title: HtmlExternalResolver
second_title: Riferimento API Aspose.Slides per Java
description: Oggetto di callback utilizzato dalla routine di importazione HTML per ottenere gli oggetti referenziati, come le immagini.
type: docs
url: /it/com.aspose.slides/htmlexternalresolver/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Oggetto di callback utilizzato dalla routine di importazione HTML per ottenere gli oggetti referenziati, come le immagini.

--------------------

L'uso di questo resolver potrebbe creare una vulnerabilità quando un file HTML fornito dal client fa sì che il software server ottenga file locali o di rete. Usare con cautela. Si raccomanda di non specificare HtmlExternalResolver affatto (verranno letti solo gli oggetti incorporati) o di creare una sottoclasse che verifichi se l'URI specificato è valido.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Restituisce l'URI assoluto a partire dagli URI base e relativo. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mappa un URI a un oggetto contenente la risorsa reale. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Restituisce l'URI assoluto a partire dagli URI base e relativo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseUri | java.lang.String | URI di base degli oggetti collegati |
| relativeUri | java.lang.String | URI relativo all'oggetto collegato. |

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
| absoluteUri | java.lang.String | URI assoluto dell'oggetto. |

**Restituisce:**
java.io.InputStream - Un oggetto InputStream o null se la risorsa non può essere trasmessa in streaming.