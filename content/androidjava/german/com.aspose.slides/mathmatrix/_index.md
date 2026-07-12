---
title: MathMatrix
second_title: Aspose.Slides für Android über Java API-Referenz
description: Gibt das Matrix-Objekt an, das aus Kindelementen besteht, die in einer oder mehreren Zeilen und Spalten angeordnet sind.
type: docs
url: /de/com.aspose.slides/mathmatrix/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Gibt das Matrix-Objekt an, das aus Kindelementen besteht, die in einer oder mehreren Zeilen und Spalten angeordnet sind. Es ist wichtig zu beachten, dass Matrizen keine eingebauten Trennzeichen besitzen. Um die Matrix in Klammern zu setzen, sollten Sie das Trennzeichen-Objekt (IMathDelimiter) verwenden. Null-Argumente können verwendet werden, um Lücken in Matrizen zu erzeugen.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Initialisiert eine neue Instanz der MathMatrix-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRowCount()](#getRowCount--) | Anzahl der Zeilen in der Matrix |
| [getColumnCount()](#getColumnCount--) | Anzahl der Spalten in der Matrix |
| [getHidePlaceholders()](#getHidePlaceholders--) | Versteckt die Platzhalter für leere Matrizenelemente. Standard: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Versteckt die Platzhalter für leere Matrizenelemente. Standard: false |
| [getBaseJustification()](#getBaseJustification--) | Gibt die vertikale Ausrichtung in Bezug auf den umgebenden Text an. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Gibt die vertikale Ausrichtung in Bezug auf den umgebenden Text an. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimale Spaltenbreite in twips (1/20th of a point) The gap spacing (also referred to as \u201cColumn Gap\u201d or \u201cGap Width\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimale Spaltenbreite in twips (1/20th of a point) The gap spacing (also referred to as \u201cColumn Gap\u201d or \u201cGap Width\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
| [getColumnGapRule()](#getColumnGapRule--) | Der Typ des horizontalen Abstands zwischen Spalten einer Matrix; horizontale Abstandseinheiten können ems oder Punkte sein (als twips gespeichert). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Der Typ des horizontalen Abstands zwischen Spalten einer Matrix; horizontale Abstandseinheiten können ems oder Punkte sein (als twips gespeichert). |
| [getColumnGap()](#getColumnGap--) | Der Wert des horizontalen Abstands zwischen Spalten einer Matrix; Wenn ColumnGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als twips (1/20th of a point) interpretiert. Wenn ColumnGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als Anzahl von 0.5 em Inkrementen interpretiert. |
| [setColumnGap(long value)](#setColumnGap-long-) | Der Wert des horizontalen Abstands zwischen Spalten einer Matrix; Wenn ColumnGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als twips (1/20th of a point) interpretiert. Wenn ColumnGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als Anzahl von 0.5 em Inkrementen interpretiert. |
| [getRowGapRule()](#getRowGapRule--) | Der Typ des vertikalen Abstands zwischen Zeilen einer Matrix; vertikale Abstandseinheiten können Zeilen oder Punkte sein (als twips gespeichert). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Der Typ des vertikalen Abstands zwischen Zeilen einer Matrix; vertikale Abstandseinheiten können Zeilen oder Punkte sein (als twips gespeichert). |
| [getRowGap()](#getRowGap--) | Der Wert des vertikalen Abstands zwischen Zeilen einer Matrix; Wenn RowGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als twips (1/20th of a point) interpretiert. Wenn RowGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als halbe Zeilen interpretiert. |
| [setRowGap(long value)](#setRowGap-long-) | Der Wert des vertikalen Abstands zwischen Zeilen einer Matrix; Wenn RowGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als twips (1/20th of a point) interpretiert. Wenn RowGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als halbe Zeilen interpretiert. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Element der Matrix |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Element der Matrix |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Steuerzeichen-Eigenschaften |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Gibt die horizontale Ausrichtung der angegebenen Spalte zurück |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Setzt die horizontale Ausrichtung der angegebenen Spalte |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Setzt die horizontale Ausrichtung der angegebenen Spalten |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Fügt eine neue Zeile vor der angegebenen ein. Anfangs sind alle Elemente in der neuen Zeile null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Fügt eine neue Zeile nach der angegebenen ein. Anfangs sind alle Elemente in der neuen Zeile null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Löscht die angegebene Zeile |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Fügt eine neue Spalte vor der angegebenen ein. Anfangs sind alle Elemente in der neuen Spalte null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Fügt eine neue Spalte nach der angegebenen ein. Anfangs sind alle Elemente in der neuen Spalte null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Löscht die angegebene Spalte |
| [getChildren()](#getChildren--) | Gibt Kindelemente zurück |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

Initialisiert eine neue Instanz der MathMatrix-Klasse.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rowCount | int | Zeilenanzahl |
| columnCount | int | Spaltenanzahl |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```

Anzahl der Zeilen in der Matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Rückgabe:**
int
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Anzahl der Spalten in der Matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Rückgabe:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

Versteckt die Platzhalter für leere Matrizenelemente. Standard: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Rückgabe:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```

Versteckt die Platzhalter für leere Matrizenelemente. Standard: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Gibt die vertikale Ausrichtung in Bezug auf den umgebenden Text an. Mögliche Werte sind top, bottom und center. Standard: Center

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Rückgabe:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Gibt die vertikale Ausrichtung in Bezug auf den umgebenden Text an. Mögliche Werte sind top, bottom und center. Standard: Center

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

Minimale Spaltenbreite in twips (1/20th of a point) The gap spacing (also referred to as \u201cColumn Gap\u201d or \u201cGap Width\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Standard: 0.

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Rückgabe:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

Minimale Spaltenbreite in twips (1/20th of a point) The gap spacing (also referred to as \u201cColumn Gap\u201d or \u201cGap Width\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Standard: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```

Der Typ des horizontalen Abstands zwischen Spalten einer Matrix; horizontale Abstandseinheiten können ems oder Punkte sein (als twips gespeichert). Standard: SingleSpacingGap (0)

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Rückgabe:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

Der Typ des horizontalen Abstands zwischen Spalten einer Matrix; horizontale Abstandseinheiten können ems oder Punkte sein (als twips gespeichert). Standard: SingleSpacingGap (0)

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

Der Wert des horizontalen Abstands zwischen Spalten einer Matrix; Wenn ColumnGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als twips (1/20th of a point) interpretiert. Wenn ColumnGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als Anzahl von 0.5 em Inkrementen interpretiert. In anderen Fällen ignoriert. Standard: 0

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Rückgabe:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

Der Wert des horizontalen Abstands zwischen Spalten einer Matrix; Wenn ColumnGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als twips (1/20th of a point) interpretiert. Wenn ColumnGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als Anzahl von 0.5 em Inkrementen interpretiert. In anderen Fällen ignoriert. Standard: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```

Der Typ des vertikalen Abstands zwischen Zeilen einer Matrix; vertikale Abstandseinheiten können Zeilen oder Punkte sein (als twips gespeichert). Standard: SingleSpacingGap (0)

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Rückgabe:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

Der Typ des vertikalen Abstands zwischen Zeilen einer Matrix; vertikale Abstandseinheiten können Zeilen oder Punkte sein (als twips gespeichert). Standard: SingleSpacingGap (0)

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```

Der Wert des vertikalen Abstands zwischen Zeilen einer Matrix; Wenn RowGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als twips (1/20th of a point) interpretiert. Wenn RowGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als halbe Zeilen interpretiert. Standard: 0

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Rückgabe:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

Der Wert des vertikalen Abstands zwischen Zeilen einer Matrix; Wenn RowGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als twips (1/20th of a point) interpretiert. Wenn RowGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als halbe Zeilen interpretiert. Standard: 0

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

Element der Matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| row | int | Der nullbasierte Index der Zeile, deren Element abgerufen werden soll |
| column | int | Der nullbasierte Index der Spalte, deren Element abgerufen werden soll |

**Rückgabe:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

Element der Matrix

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| row | int | Der nullbasierte Index der Zeile, deren Element abgerufen werden soll |
| column | int | Der nullbasierte Index der Spalte, deren Element abgerufen werden soll |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Steuerzeichen-Eigenschaften

**Rückgabe:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

Gibt die horizontale Ausrichtung der angegebenen Spalte zurück

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | int | Nullbasierter Spaltenindex |

**Rückgabe:**
int - Horizontale Ausrichtung der angegebenen Spalte
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

Setzt die horizontale Ausrichtung der angegebenen Spalte

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | int | Nullbasierter Spaltenindex |
| val | int | Neuer Wert der horizontalen Ausrichtung der angegebenen Spalte |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Setzt die horizontale Ausrichtung der angegebenen Spalten

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | int | Nullbasierter Index der ersten Spalte, deren Ausrichtung gesetzt werden soll |
| columnsCount | long | Die Anzahl der Spalten, für die die Ausrichtung festgelegt wird |
| val | int | Neuer Wert der horizontalen Ausrichtung der angegebenen Spalte |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Fügt eine neue Zeile vor der angegebenen ein. Anfangs sind alle Elemente in der neuen Zeile null.

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rowIndex | int | Index der Zeile, vor der eine neue eingefügt werden soll |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

Fügt eine neue Zeile nach der angegebenen ein. Anfangs sind alle Elemente in der neuen Zeile null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rowIndex | int | Index der Zeile, nach der eine neue eingefügt werden soll |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

Löscht die angegebene Zeile

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rowIndex | int | Der nullbasierte Index der zu löschenden Zeile. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

Fügt eine neue Spalte vor der angegebenen ein. Anfangs sind alle Elemente in der neuen Spalte null.

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | int | Index der Spalte, vor der eine neue eingefügt werden soll |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

Fügt eine neue Spalte nach der angegebenen ein. Anfangs sind alle Elemente in der neuen Spalte null.

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | int | Index der Spalte, nach der eine neue eingefügt werden soll |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

Löscht die angegebene Spalte

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | int | Der nullbasierte Index der zu löschenden Spalte. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gibt Kindelemente zurück

**Rückgabe:**
com.aspose.slides.IMathElement[]