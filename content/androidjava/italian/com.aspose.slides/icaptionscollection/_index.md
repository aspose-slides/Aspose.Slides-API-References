---
title: ICaptionsCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una raccolta di sottotitoli chiusi.
type: docs
url: /it/com.aspose.slides/icaptionscollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

Rappresenta una raccolta di sottotitoli chiusi.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce i sottotitoli chiusi nell'indice specificato. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Aggiunge i sottotitoli chiusi WebVTT alla fine della raccolta. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Aggiunge i sottotitoli chiusi WebVTT alla fine della raccolta da uno stream. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Rimuove i sottotitoli chiusi specificati dalla raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove i sottotitoli chiusi nell'indice specificato. |
| [clear()](#clear--) | Rimuove tutti i sottotitoli chiusi dalla raccolta. |
| [getCount()](#getCount--) | Restituisce il numero di elementi nella raccolta. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```


Restituisce i sottotitoli chiusi nell'indice specificato. Solo lettura [ICaptions](../../com.aspose.slides/icaptions).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```


Aggiunge i sottotitoli chiusi WebVTT alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| label | java.lang.String | L'etichetta dei sottotitoli chiusi. |
| filePath | java.lang.String | Il percorso del file WebVTT. |

**Restituisce:**
[ICaptions](../../com.aspose.slides/icaptions) - L'istanza [ICaptions](../../com.aspose.slides/icaptions) aggiunta.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```


Aggiunge i sottotitoli chiusi WebVTT alla fine della raccolta da uno stream.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| label | java.lang.String | L'etichetta dei sottotitoli chiusi. |
| stream | java.io.InputStream | Il flusso di input contenente dati in formato WebVTT. |

**Restituisce:**
[ICaptions](../../com.aspose.slides/icaptions) - L'istanza [ICaptions](../../com.aspose.slides/icaptions) aggiunta.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```


Rimuove i sottotitoli chiusi specificati dalla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | I sottotitoli chiusi da rimuovere. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Rimuove i sottotitoli chiusi nell'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice dei sottotitoli chiusi da rimuovere. |

### clear() {#clear--}
```
public abstract void clear()
```


Rimuove tutti i sottotitoli chiusi dalla raccolta.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Restituisce il numero di elementi nella raccolta. Solo lettura  int .

**Restituisce:**
int