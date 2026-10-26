---
title: ICellFormat
second_title: Aspose.Slides for Java API Reference
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
| [getFillFormat()](#getFillFormat--) | Gibt ein Zellfüllungs-Properties-Objekt zurück. |
| [getBorderLeft()](#getBorderLeft--) | Gibt ein Objekt mit den Eigenschaften der linken Randlinie zurück. |
| [getBorderTop()](#getBorderTop--) | Gibt ein Objekt mit den Eigenschaften der oberen Randlinie zurück. |
| [getBorderRight()](#getBorderRight--) | Gibt ein Objekt mit den Eigenschaften der rechten Randlinie zurück. |
| [getBorderBottom()](#getBorderBottom--) | Gibt ein Objekt mit den Eigenschaften der unteren Randlinie zurück. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Gibt ein Objekt mit den Eigenschaften der Diagonalen von oben links nach unten rechts zurück. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Gibt ein Objekt mit den Eigenschaften der Diagonalen von unten links nach oben rechts zurück. |
| [getTransparency()](#getTransparency--) | Ruft die Transparenz der Füllfarbe ab oder legt sie fest. |
| [setTransparency(float value)](#setTransparency-float-) | Ruft die Transparenz der Füllfarbe ab oder legt sie fest. |
| [getEffective()](#getEffective--) | Ruft die effektiven Tabellenzellen-Formatierungseigenschaften mit Vererbung und angewendeten Tabellenstilen ab. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Gibt ein Zellfüllungs-Properties-Objekt zurück. Nur lesbar [IFillFormat](../../com.aspose.slides/ifillformat).

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


Gibt ein Objekt mit den Eigenschaften der Diagonalen von oben links nach unten rechts zurück. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


Gibt ein Objekt mit den Eigenschaften der Diagonalen von unten links nach oben rechts zurück. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Ruft die Transparenz der Füllfarbe ab oder legt sie fest. Lesen/Schreiben  float .

**Rückgabe:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Ruft die Transparenz der Füllfarbe ab oder legt sie fest. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```


Ruft die effektiven Tabellenzellen-Formatierungseigenschaften mit Vererbung und angewendeten Tabellenstilen ab.

**Rückgabe:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).