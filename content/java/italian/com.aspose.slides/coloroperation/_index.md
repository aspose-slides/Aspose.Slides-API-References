---
title: ColorOperation
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta diverse operazioni di colore utilizzate per le trasformazioni dei colori.
type: docs
url: /it/com.aspose.slides/coloroperation/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Rappresenta diverse operazioni di colore utilizzate per le trasformazioni dei colori. Oggetto immutabile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Creates new color transform operation. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Creates new color transform operation. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOperationType()](#getOperationType--) | Returns or sets the type of an operation. |
| [getParameter()](#getParameter--) | Returns a parameter of an operation. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the two ColorOperation instances are equal. |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

Crea una nuova operazione di trasformazione del colore.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| op | int | Tipo di operazione. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

Crea una nuova operazione di trasformazione del colore.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| op | int | Tipo di operazione. |
| parameter | float | Parametro dell'operazione. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

Restituisce o imposta il tipo di un'operazione. Solo lettura [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Restituisce:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

Restituisce un parametro di un'operazione. Solo lettura float.

**Restituisce:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se le due istanze di ColorOperation sono uguali.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | La ColorOperation da confrontare con la ColorOperation corrente. |

**Restituisce:**
boolean - **true** se la ColorOperation specificata è uguale alla ColorOperation corrente; altrimenti, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Funziona come funzione hash per un tipo specifico, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash.

**Restituisce:**
int