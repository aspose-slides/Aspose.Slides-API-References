---
title: IVbaModuleCollection
second_title: Aspose.Slides per Android tramite API di riferimento Java
description: Rappresenta una raccolta di moduli del progetto VBA.
type: docs
url: /it/com.aspose.slides/ivbamodulecollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Rappresenta una raccolta di moduli del progetto VBA.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Aggiunge un nuovo modulo vuoto al progetto VBA. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Rimuove la prima occorrenza di un oggetto specifico dalla raccolta. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```


Restituisce l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Valore restituito:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```


Aggiunge un nuovo modulo vuoto al progetto VBA.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome del modulo |

**Valore restituito:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Modulo aggiunto.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```


Rimuove la prima occorrenza di un oggetto specifico dalla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Il modulo da rimuovere dalla raccolta. |