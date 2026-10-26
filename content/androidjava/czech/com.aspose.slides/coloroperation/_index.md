---
title: ColorOperation
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje různé operace barev používané pro transformace barev.
type: docs
url: /cs/com.aspose.slides/coloroperation/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Reprezentuje různé operace barev používané pro transformace barev. Neměnný objekt.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Vytvoří novou operaci transformace barev. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Vytvoří novou operaci transformace barev. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getOperationType()](#getOperationType--) | Vrací nebo nastavuje typ operace. |
| [getParameter()](#getParameter--) | Vrací parametr operace. |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda jsou dvě instance ColorOperation rovny. |
| [hashCode()](#hashCode--) | Slouží jako hashová funkce pro konkrétní typ, vhodná pro použití v hashovacích algoritmech a datových strukturách, jako je hash tabulka. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

Vytvoří novou operaci transformace barev.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| op | int | Typ operace. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

Vytvoří novou operaci transformace barev.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| op | int | Typ operace. |
| parameter | float | Parametr operace. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

Vrací nebo nastavuje typ operace. Jen pro čtení [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Návratová hodnota:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

Vrací parametr operace. Jen pro čtení float.

**Návratová hodnota:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Určuje, zda jsou dvě instance ColorOperation rovny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Instance ColorOperation, se kterou se porovnává aktuální ColorOperation. |

**Návratová hodnota:**
boolean - **true** pokud je zadaná ColorOperation rovna aktuální ColorOperation; jinak, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hashová funkce pro konkrétní typ, vhodná pro použití v hashovacích algoritmech a datových strukturách, jako je hash tabulka.

**Návratová hodnota:**
int