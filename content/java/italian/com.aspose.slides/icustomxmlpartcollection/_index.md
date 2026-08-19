---
title: ICustomXmlPartCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di parti xml personalizzate.
type: docs
url: /it/com.aspose.slides/icustomxmlpartcollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Rappresenta una raccolta di parti xml personalizzate.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [add(byte[] xmlData)](#add-byte---) | Aggiunge una nuova parte xml personalizzata. |
| [add(String xmlString)](#add-java.lang.String-) | Aggiunge una nuova parte xml personalizzata. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Aggiunge una nuova parte xml personalizzata. |
| [removeAt(int index)](#removeAt-int-) | Rimuove la parte xml personalizzata all'indice specificato. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Rimuove la prima occorrenza di un oggetto specifico dalla raccolta. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla raccolta. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Restituisce l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero dell'elemento da ottenere. |

**Restituisce:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - L'elemento all'indice specificato.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Aggiunge una nuova parte xml personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlData | byte[] | I dati xml della nuova parte da aggiungere. |

**Restituisce:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte xml personalizzata creata.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

Aggiunge una nuova parte xml personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlString | java.lang.String | La stringa xml della nuova parte da aggiungere. |

**Restituisce:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte xml personalizzata creata.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

Aggiunge una nuova parte xml personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | java.io.InputStream | Lo stream di input con i dati xml della nuova parte da aggiungere. |

**Restituisce:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte xml personalizzata creata.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove la parte xml personalizzata all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero dell'elemento da rimuovere. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

Rimuove la prima occorrenza di un oggetto specifico dalla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | La parte xml personalizzata da rimuovere. |

**Restituisce:**
boolean - true se l'item è stato rimosso con successo; altrimenti, false.
### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutti gli elementi dalla raccolta.