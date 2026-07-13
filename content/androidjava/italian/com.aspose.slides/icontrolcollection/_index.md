---
title: IControlCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Una collezione di controlli ActiveX.
type: docs
url: /it/com.aspose.slides/icontrolcollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Una collezione di controlli ActiveX.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Rimuove un controllo ActiveX dalla collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un controllo ActiveX memorizzato nella posizione specificata dalla collezione. |
| [clear()](#clear--) | Rimuove tutti i controlli dalla collezione. |
| [get_Item(int index)](#get-Item-int-) | Restituisce un controllo nella posizione specificata. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Crea e aggiunge un nuovo controllo alla collezione. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

Rimuove un controllo ActiveX dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Un controllo da rimuovere. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove un controllo ActiveX memorizzato nella posizione specificata dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice del controllo da rimuovere. |

### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutti i controlli dalla collezione.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

Restituisce un controllo nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di un controllo. |

**Restituisce:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

Crea e aggiunge un nuovo controllo alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| controlType | int | Tipo di controllo da aggiungere. |
| x | float | La coordinata X per il lato sinistro del riquadro della forma. |
| y | float | La coordinata Y per il lato superiore del riquadro della forma. |
| width | float | La larghezza del riquadro della forma. |
| height | float | L'altezza del riquadro della forma. |

**Restituisce:**
[IControl](../../com.aspose.slides/icontrol) - Controllo creato [IControl](../../com.aspose.slides/icontrol).