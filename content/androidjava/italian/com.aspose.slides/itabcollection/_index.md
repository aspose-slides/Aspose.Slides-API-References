---
title: ITabCollection
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta una collezione di tabulazioni.
type: docs
url: /it/com.aspose.slides/itabcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Rappresenta una collezione di tabulazioni.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [add(double position, int align)](#add-double-int-) | Aggiunge una Tab alla collezione. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Aggiunge una Tab alla collezione. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della collezione. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```


Ottiene l'elemento all'indice specificato. Solo lettura [ITab](../../com.aspose.slides/itab).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```


Aggiunge una Tab alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | double | Posizione della Tab. |
| align | int | Allineamento della Tab. |

**Restituisce:**
[ITab](../../com.aspose.slides/itab) - Tab aggiunta.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```


Aggiunge una Tab alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | L'oggetto Tab da aggiungere alla fine della collezione. |

**Restituisce:**
int - L'indice al quale la tab è stata aggiunta.
### clear() {#clear--}
```
public abstract void clear()
```


Rimuove tutti gli elementi dalla collezione.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Rimuove l'elemento all'indice specificato della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |