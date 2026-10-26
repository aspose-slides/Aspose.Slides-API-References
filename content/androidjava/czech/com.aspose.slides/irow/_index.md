---
title: IRow
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Představuje řádek v tabulce.
type: docs
url: /cs/com.aspose.slides/irow/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Představuje řádek v tabulce.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeight()](#getHeight--) | Vrací výšku řádku. |
| [getMinimalHeight()](#getMinimalHeight--) | Vrací nebo nastavuje minimální možnou výšku řádku. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Vrací nebo nastavuje minimální možnou výšku řádku. |
| [getRowFormat()](#getRowFormat--) | Vrací objekt RowFormat, který obsahuje vlastnosti formátování pro tento řádek. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Vrací výšku řádku. Pouze pro čtení double.

**Vrací:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Vrací nebo nastavuje minimální možnou výšku řádku. Čtení/zápis double.

**Vrací:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

Vrací nebo nastavuje minimální možnou výšku řádku. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

Vrací objekt RowFormat, který obsahuje vlastnosti formátování pro tento řádek. Pouze pro čtení [IRowFormat](../../com.aspose.slides/irowformat).

**Vrací:**
[IRowFormat](../../com.aspose.slides/irowformat)