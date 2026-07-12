---
title: ITableFormat
second_title: Aspose.Slides for Android via Java API Reference
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
| [getFillFormat()](#getFillFormat--) | Gibt ein TableFillProperties-Objekt zurück. |
| [getTransparency()](#getTransparency--) | Liest oder setzt die Transparenz der Füllfarbe. |
| [setTransparency(float value)](#setTransparency-float-) | Liest oder setzt die Transparenz der Füllfarbe. |
| [getEffective()](#getEffective--) | Liest die effektiven Tabellenformatierungseigenschaften mit Vererbung und angewendeten Tabellenstilen. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Gibt ein TableFillProperties-Objekt zurück. Nur-Lesen [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabewert:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

Liest oder setzt die Transparenz der Füllfarbe. Lesen/Schreiben  float .

**Rückgabewert:**
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

Liest die effektiven Tabellenformatierungseigenschaften mit Vererbung und angewendeten Tabellenstilen.

**Rückgabewert:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Ein [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).