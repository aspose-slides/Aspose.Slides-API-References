---
title: IRow
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een rij in een tabel voor.
type: docs
url: /nl/com.aspose.slides/irow/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Stelt een rij in een tabel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHeight()](#getHeight--) | Retourneert de hoogte van een rij. |
| [getMinimalHeight()](#getMinimalHeight--) | Retourneert of stelt de minimaal mogelijke hoogte van een rij in. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Retourneert of stelt de minimaal mogelijke hoogte van een rij in. |
| [getRowFormat()](#getRowFormat--) | Retourneert het RowFormat-object dat de opmaak-eigenschappen voor deze rij bevat. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Retourneert de hoogte van een rij. Alleen-lezen double.

**Retour:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Retourneert of stelt de minimaal mogelijke hoogte van een rij in. Lezen/Schrijven double.

**Retour:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

Retourneert of stelt de minimaal mogelijke hoogte van een rij in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

Retourneert het RowFormat-object dat de opmaak-eigenschappen voor deze rij bevat. Alleen-lezen [IRowFormat](../../com.aspose.slides/irowformat).

**Retour:**
[IRowFormat](../../com.aspose.slides/irowformat)