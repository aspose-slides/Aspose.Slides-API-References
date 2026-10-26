---
title: Storage
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un archivio di dati temporaneo per .
type: docs
url: /it/com.aspose.slides/storage/
---
**Eredità:**
java.lang.Object
```
public final class Storage
```

Rappresenta un archivio di dati temporaneo per [WebDocument](../../com.aspose.slides/webdocument).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Storage()](#Storage--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Inserisce il valore nell'archivio. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Recupera i dati dall'archivio. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determina se l'archivio contiene un elemento con la chiave specificata. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


Inserisce il valore nell'archivio.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | Chiave per il valore. |
| value | TValue | Valore. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


Recupera i dati dall'archivio.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | Chiave del valore. |

**Restituisce:**
TValue - Valore dei dati se è presente nella raccolta di dati, null altrimenti.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Determina se l'archivio contiene un elemento con la chiave specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key | java.lang.String | Chiave del valore. |

**Restituisce:**
boolean - True se l'archivio contiene un elemento con la chiave specificata, false altrimenti.