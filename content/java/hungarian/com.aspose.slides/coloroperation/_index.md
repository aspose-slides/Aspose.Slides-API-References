---
title: ColorOperation
second_title: Aspose.Slides Java API referenciája
description: Különböző színműveleteket reprezentál, amelyeket színtranszformációkhoz használnak.
type: docs
url: /hu/com.aspose.slides/coloroperation/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Különböző színműveleteket reprezentál, amelyeket színtranszformációkhoz használnak. Változtathatatlan objektum.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Új színtranszformációs műveletet hoz létre. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Új színtranszformációs műveletet hoz létre. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getOperationType()](#getOperationType--) | Visszaadja vagy beállítja egy művelet típusát. |
| [getParameter()](#getParameter--) | Visszaad egy paramétert egy műveletből. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a két ColorOperation példány egyenlő-e. |
| [hashCode()](#hashCode--) | Hash-funkcióként szolgál egy adott típushoz, amely alkalmas hash-algoritmusokban és adatstruktúrákban, például hash-táblában való használatra. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```


Új színtranszformációs műveletet hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| op | int | Művelet típusa. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```


Új színtranszformációs műveletet hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| op | int | Művelet típusa. |
| parameter | float | Művelet paramétere. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```


Visszaadja vagy beállítja egy művelet típusát. Csak olvasás [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Visszatérési érték:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```


Visszaad egy paramétert egy műveletből. Csak olvasás float.

**Visszatérési érték:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Megállapítja, hogy a két ColorOperation példány egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Az összehasonlítandó ColorOperation az aktuális ColorOperation-hoz. |

**Visszatérési érték:**
boolean – **true**, ha a megadott ColorOperation egyenlő az aktuális ColorOperation-nal; egyébként **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash-funkcióként szolgál egy adott típushoz, amely alkalmas hash-algoritmusokban és adatstruktúrákban, például hash-táblában való használatra.

**Visszatérési érték:**
int