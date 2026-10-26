---
title: ITableFormat
second_title: Aspose.Slides for Java API Reference
description: Stellt das Format einer Tabelle dar.
type: docs
url: /de/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Stellt das Format einer Tabelle dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Gibt ein Tabellenfüll-Eigenschaftsobjekt zurück. |
| [getTransparency()](#getTransparency--) | Liest oder setzt die Transparenz der Füllfarbe. |
| [setTransparency(float value)](#setTransparency-float-) | Liest oder setzt die Transparenz der Füllfarbe. |
| [getEffective()](#getEffective--) | Gibt effektive Tabellenformatierungseigenschaften mit Vererbung und angewendeten Tabellenstilen zurück. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Gibt ein Tabellenfüll-Eigenschaftsobjekt zurück. Nur lesbar [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Liest oder setzt die Transparenz der Füllfarbe. Lesen/Schreiben  float .

**Rückgabe:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Liest oder setzt die Transparenz der Füllfarbe. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Gibt effektive Tabellenformatierungseigenschaften mit Vererbung und angewendeten Tabellenstilen zurück.

**Rückgabe:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Ein [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).