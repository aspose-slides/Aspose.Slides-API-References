---
title: CaptionsCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una collezione di sottotitoli chiusi.
type: docs
url: /it/com.aspose.slides/captionscollection/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Rappresenta una collezione di sottotitoli chiusi.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce i sottotitoli chiusi all&#39;indice specificato. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Aggiunge i sottotitoli chiusi WebVTT alla fine della collezione. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Aggiunge i sottotitoli chiusi WebVTT alla fine della collezione da uno stream. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Rimuove i sottotitoli chiusi specificati dalla collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove i sottotitoli chiusi all&#39;indice specificato. |
| [clear()](#clear--) | Rimuove tutti i sottotitoli chiusi dalla collezione. |
| [getCount()](#getCount--) | Restituisce il numero di elementi nella collezione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

Restituisce i sottotitoli chiusi all&#39;indice specificato. Solo lettura [ICaptions](../../com.aspose.slides/icaptions).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

Aggiunge i sottotitoli chiusi WebVTT alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| label | java.lang.String | L&#39;etichetta dei sottotitoli chiusi. |
| filePath | java.lang.String | Il percorso del file WebVTT. |

**Restituisce:**
[ICaptions](../../com.aspose.slides/icaptions) - L&#39;istanza [ICaptions](../../com.aspose.slides/icaptions) aggiunta.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

Aggiunge i sottotitoli chiusi WebVTT alla fine della collezione da uno stream.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| label | java.lang.String | L&#39;etichetta dei sottotitoli chiusi. |
| stream | java.io.InputStream | Lo stream di input contenente dati in formato WebVTT. |

**Restituisce:**
[ICaptions](../../com.aspose.slides/icaptions) - L&#39;istanza [ICaptions](../../com.aspose.slides/icaptions) aggiunta.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

Rimuove i sottotitoli chiusi specificati dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | I sottotitoli chiusi da rimuovere. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove i sottotitoli chiusi all&#39;indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L&#39;indice dei sottotitoli chiusi da rimuovere. |

### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti i sottotitoli chiusi dalla collezione.

### getCount() {#getCount--}
```
public final int getCount()
```

Restituisce il numero di elementi nella collezione. Solo lettura  int .

**Restituisce:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - Un System.Collections.Generic.IEnumerator1 che può essere usato per iterare attraverso la collezione.