---
title: ExternalResourceResolver
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Classe Callback utilizzata per risolvere risorse esterne durante l'importazione di documenti Html e Svg.
type: docs
url: /it/com.aspose.slides/externalresourceresolver/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Classe Callback utilizzata per risolvere risorse esterne durante l'importazione di documenti Html, Svg.

--------------------

L'uso di questo resolver potrebbe creare una vulnerabilità quando un file HTML o SVG fornito dal client fa sì che il software server ottenga un file locale o di rete. Usare con cautela. Si consiglia di non specificare affatto ExternalResourceResolver (verranno letti solo gli oggetti incorporati) oppure di creare una sottoclasse che verifichi se l'uri specificato è valido.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Risolve l'URI assoluto a partire dagli URI di base e relativo. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mappa un URI a un oggetto contenente la risorsa reale. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

Risolve l'URI assoluto a partire dagli URI di base e relativo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseUri | java.lang.String | URI di base degli oggetti colleganti |
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
java.io.InputStream - Un oggetto InputStream o null se la risorsa non può essere trasmessa.