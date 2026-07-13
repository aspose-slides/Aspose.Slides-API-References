---
title: IColorOperationCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una collezione di operazioni di trasformazione del colore.
type: docs
url: /it/com.aspose.slides/icoloroperationcollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Rappresenta una collezione di operazioni di trasformazione del colore.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce o imposta l'operazione all'indice specificato. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Restituisce o imposta l'operazione all'indice specificato. |
| [add(int operation, float parameter)](#add-int-float-) | Aggiunge una nuova operazione alla fine della collezione. |
| [add(int operation)](#add-int-) | Aggiunge una nuova operazione alla fine della collezione. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Inserisce la nuova operazione in una collezione. |
| [insert(int position, int operation)](#insert-int-int-) | Inserisce la nuova operazione in una collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'operazione di colore da una collezione. |
| [clear()](#clear--) | Rimuove tutte le operazioni di colore. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

Restituisce o imposta l'operazione all'indice specificato. Lettura/scrittura [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

Restituisce o imposta l'operazione all'indice specificato. Lettura/scrittura [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

Aggiunge una nuova operazione alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| operation | int | Tipo di operazione. |
| parameter | float | Parametro dell'operazione. |

**Restituisce:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operazione aggiunta.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

Aggiunge una nuova operazione alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| operation | int | Tipo di operazione. |

**Restituisce:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operazione aggiunta.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

Inserisce la nuova operazione in una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | int | L'indice al quale l'operazione sarà inserita. |
| operation | int | Tipo di operazione. |
| parameter | float | Parametro dell'operazione. |

**Restituisce:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operazione inserita.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

Inserisce la nuova operazione in una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | int | L'indice al quale l'operazione sarà inserita. |
| operation | int | Tipo di operazione. |

**Restituisce:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operazione inserita.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove l'operazione di colore da una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'operazione di colore da rimuovere. |

### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutte le operazioni di colore.