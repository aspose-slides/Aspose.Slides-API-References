---
title: ICellCollection
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta una raccolta di celle.
type: docs
url: /it/com.aspose.slides/icellcollection/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Rappresenta una raccolta di celle.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce una cella per la sua posizione. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```


Restituisce una cella per la sua posizione. Sola lettura [ICell](../../com.aspose.slides/icell).

--------------------

Un oggetto CellEx può essere restituito per diversi indici nel caso in cui la cella sia unita.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ICell](../../com.aspose.slides/icell)