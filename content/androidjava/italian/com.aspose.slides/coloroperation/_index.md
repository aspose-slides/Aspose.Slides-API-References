---
title: ColorOperation
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta diverse operazioni di colore utilizzate per le trasformazioni di colore.
type: docs
url: /it/com.aspose.slides/coloroperation/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Rappresenta diverse operazioni di colore utilizzate per le trasformazioni di colore. Oggetto immutabile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Crea una nuova operazione di trasformazione del colore. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Crea una nuova operazione di trasformazione del colore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOperationType()](#getOperationType--) | Restituisce o imposta il tipo di un'operazione. |
| [getParameter()](#getParameter--) | Restituisce un parametro di un'operazione. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se le due istanze di ColorOperation sono uguali. |
| [hashCode()](#hashCode--) | Funziona come funzione hash per un tipo particolare, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash. |
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
| obj | java.lang.Object | Il ColorOperation da confrontare con l'attuale ColorOperation. |

**Restituisce:**
boolean - **true** se il ColorOperation specificato è uguale al ColorOperation corrente; altrimenti, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Funziona come funzione hash per un tipo particolare, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash.

**Restituisce:**
int