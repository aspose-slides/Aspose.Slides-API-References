---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a table cell.
type: docs
url: /de/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Stellt das Format einer Tabellenzelle dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Gibt ein Objekt mit Zellfüllungs-Eigenschaften zurück. |
| [getBorderLeft()](#getBorderLeft--) | Gibt ein Objekt mit den Eigenschaften der linken Randlinie zurück. |
| [getBorderTop()](#getBorderTop--) | Gibt ein Objekt mit den Eigenschaften der oberen Randlinie zurück. |
| [getBorderRight()](#getBorderRight--) | Gibt ein Objekt mit den Eigenschaften der rechten Randlinie zurück. |
| [getBorderBottom()](#getBorderBottom--) | Gibt ein Objekt mit den Eigenschaften der unteren Randlinie zurück. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Gibt ein Objekt mit den Eigenschaften der diagonal von oben-links nach unten-rechts verlaufenden Linie zurück. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Gibt ein Objekt mit den Eigenschaften der diagonal von unten-links nach oben-rechts verlaufenden Linie zurück. |
| [getTransparency()](#getTransparency--) | Liest oder setzt die Transparenz der Füllfarbe. |
| [setTransparency(float value)](#setTransparency-float-) | Liest oder setzt die Transparenz der Füllfarbe. |
| [getEffective()](#getEffective--) | Liest die effektiven Formatierungseigenschaften einer Tabellenzelle unter Berücksichtigung von Vererbung und angewendeten Tabellenstilen. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Gibt ein Objekt mit Zellfüllungs-Eigenschaften zurück. Nur lesbar [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```


Gibt ein Objekt mit den Eigenschaften der linken Randlinie zurück. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


Gibt ein Objekt mit den Eigenschaften der oberen Randlinie zurück. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


Gibt ein Objekt mit den Eigenschaften der rechten Randlinie zurück. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


Gibt ein Objekt mit den Eigenschaften der unteren Randlinie zurück. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


Gibt ein Objekt mit den Eigenschaften der diagonal von oben-links nach unten-rechts verlaufenden Linie zurück. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


Gibt ein Objekt mit den Eigenschaften der diagonal von unten-links nach oben-rechts verlaufenden Linie zurück. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
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
public abstract ICellFormatEffectiveData getEffective()
```


Liest die effektiven Formatierungseigenschaften einer Tabellenzelle unter Berücksichtigung von Vererbung und angewendeten Tabellenstilen.

**Rückgabe:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).