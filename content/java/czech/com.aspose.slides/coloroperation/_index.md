---
title: ColorOperation
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje různé operace s barvou používané pro transformace barev.
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

Reprezentuje různé operace s barvou používané pro transformace barev. Neměnný objekt.
## Konstruktory

| Constructor | Description |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Vytvoří novou operaci transformace barvy. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Vytvoří novou operaci transformace barvy. |
## Metody

| Method | Description |
| --- | --- |
| [getOperationType()](#getOperationType--) | Vrací nebo nastavuje typ operace. |
| [getParameter()](#getParameter--) | Vrací parametr operace. |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda jsou dvě instance ColorOperation si rovny. |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ, vhodná pro použití v hashovacích algoritmech a datových strukturách, jako je hashovací tabulka. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

Vytvoří novou operaci transformace barvy.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| op | int | Typ operace. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

Vytvoří novou operaci transformace barvy.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| op | int | Typ operace. |
| parameter | float | Parametr operace. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

Vrací nebo nastavuje typ operace. Pouze pro čtení [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Vrací:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

Vrací parametr operace. Pouze pro čtení float.

**Vrací:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Určuje, zda jsou dvě instance ColorOperation si rovny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | ColorOperation, který se porovnává s aktuální ColorOperation. |

**Vrací:**
boolean – **true**, pokud je určená ColorOperation rovna aktuální ColorOperation; jinak **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hashovací funkce pro konkrétní typ, vhodná pro použití v hashovacích algoritmech a datových strukturách, jako je hashovací tabulka.

**Vrací:**
int