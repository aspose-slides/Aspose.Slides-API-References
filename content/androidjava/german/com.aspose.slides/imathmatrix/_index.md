---
title: IMathMatrix
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Gibt das Matrix-Objekt an, das aus Kindelementen besteht, die in einer oder mehreren Zeilen und Spalten angeordnet sind.
type: docs
url: /de/com.aspose.slides/imathmatrix/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Gibt das Matrix-Objekt an, das aus Kindelementen besteht, die in einer oder mehreren Zeilen und Spalten angeordnet sind. Es ist wichtig zu beachten, dass Matrizen keine eingebauten Trennzeichen besitzen. Um die Matrix in Klammern zu setzen, sollten Sie das Trennzeichen-Objekt (IMathDelimiter) verwenden. Null-Argumente können verwendet werden, um Lücken in Matrizen zu erzeugen.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elemente der Matrix |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elemente der Matrix |
| [getRowCount()](#getRowCount--) | Anzahl der Zeilen in der Matrix |
| [getColumnCount()](#getColumnCount--) | Anzahl der Spalten in der Matrix |
| [getHidePlaceholders()](#getHidePlaceholders--) | Ausblenden der Platzhalter für leere Matrixelemente Standard: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Ausblenden der Platzhalter für leere Matrixelemente Standard: false |
| [getBaseJustification()](#getBaseJustification--) | Gibt die vertikale Ausrichtung im Verhältnis zum umgebenden Text an. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Gibt die vertikale Ausrichtung im Verhältnis zum umgebenden Text an. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Mindestspaltenbreite in Twips (1/20 eines Punktes) Der Abstand (auch als \u201cColumn Gap\u201d oder \u201cGap Width\u201d bezeichnet) wird zur MinColumnWidth addiert, um den gesamten Matrix-Spaltenabstand zu bestimmen (Abstand zwischen den gleichen Kanten verschiedener Spalten). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Mindestspaltenbreite in Twips (1/20 eines Punktes) Der Abstand (auch als \u201cColumn Gap\u201d oder \u201cGap Width\u201d bezeichnet) wird zur MinColumnWidth addiert, um den gesamten Matrix-Spaltenabstand zu bestimmen (Abstand zwischen den gleichen Kanten verschiedener Spalten). |
| [getColumnGapRule()](#getColumnGapRule--) | Der Typ des horizontalen Abstands zwischen Spalten einer Matrix; Horizontale Abstandseinheiten können ems oder Punkte sein (in Twips gespeichert). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Der Typ des horizontalen Abstands zwischen Spalten einer Matrix; Horizontale Abstandseinheiten können ems oder Punkte sein (in Twips gespeichert). |
| [getColumnGap()](#getColumnGap--) | Der Wert des horizontalen Abstands zwischen Spalten einer Matrix; Wenn ColumnGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn ColumnGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als Anzahl von 0,5-em-Schritten interpretiert. |
| [setColumnGap(long value)](#setColumnGap-long-) | Der Wert des horizontalen Abstands zwischen Spalten einer Matrix; Wenn ColumnGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn ColumnGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als Anzahl von 0,5-em-Schritten interpretiert. |
| [getRowGapRule()](#getRowGapRule--) | Der Typ des vertikalen Abstands zwischen Zeilen einer Matrix; Vertikale Abstandseinheiten können Zeilen oder Punkte sein (in Twips gespeichert). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Der Typ des vertikalen Abstands zwischen Zeilen einer Matrix; Vertikale Abstandseinheiten können Zeilen oder Punkte sein (in Twips gespeichert). |
| [getRowGap()](#getRowGap--) | Der Wert des vertikalen Abstands zwischen Zeilen einer Matrix; Wenn RowGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn RowGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als Halblinien interpretiert. |
| [setRowGap(long value)](#setRowGap-long-) | Der Wert des vertikalen Abstands zwischen Zeilen einer Matrix; Wenn RowGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn RowGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als Halblinien interpretiert. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Ermittelt die horizontale Ausrichtung der angegebenen Spalte |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Legt die horizontale Ausrichtung der angegebenen Spalte fest |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Legt die horizontale Ausrichtung der angegebenen Spalten fest |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Fügt vor der angegebenen Zeile eine neue Zeile ein. Anfangs sind alle Elemente in der neuen Zeile null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Fügt nach der angegebenen Zeile eine neue Zeile ein. Anfangs sind alle Elemente in der neuen Zeile null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Löscht die angegebene Zeile |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Fügt vor der angegebenen Spalte eine neue Spalte ein. Anfangs sind alle Elemente in der neuen Spalte null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Fügt nach der angegebenen Spalte eine neue Spalte ein. Anfangs sind alle Elemente in der neuen Spalte null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Löscht die angegebene Spalte |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

Elemente der Matrix

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
| row | int | Der nullbasierte Index der Zeile, aus der das Element abgerufen wird |
| column | int | Der nullbasierte Index der Spalte, aus der das Element abgerufen wird |

**Rückgabewert:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement

### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

Elemente der Matrix

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
| row | int | Der nullbasierte Index der Zeile, aus der das Element abgerufen wird |
| column | int | Der nullbasierte Index der Spalte, aus der das Element abgerufen wird |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

Anzahl der Zeilen in der Matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Rückgabewert:**
int

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Anzahl der Spalten in der Matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Rückgabewert:**
int

### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

Ausblenden der Platzhalter für leere Matrixelemente Standard: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Rückgabewert:**
boolean

### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

Ausblenden der Platzhalter für leere Matrixelemente Standard: false

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
public abstract int getBaseJustification()
```

Gibt die vertikale Ausrichtung im Verhältnis zum umgebenden Text an. Mögliche Werte sind top, bottom, and center. Standard: Center

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Rückgabewert:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Gibt die vertikale Ausrichtung im Verhältnis zum umgebenden Text an. Mögliche Werte sind top, bottom, and center. Standard: Center

--------------------

> ```
> Example:
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
public abstract long getMinColumnWidth()
```

Mindestspaltenbreite in Twips (1/20 eines Punktes) Der Abstand (auch als \u201cColumn Gap\u201d oder \u201cGap Width\u201d bezeichnet) wird zur MinColumnWidth addiert, um den gesamten Matrix-Spaltenabstand zu bestimmen (Abstand zwischen den gleichen Kanten verschiedener Spalten). Standard: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Rückgabewert:**
long

### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

Mindestspaltenbreite in Twips (1/20 eines Punktes) Der Abstand (auch als \u201cColumn Gap\u201d oder \u201cGap Width\u201d bezeichnet) wird zur MinColumnWidth addiert, um den gesamten Matrix-Spaltenabstand zu bestimmen (Abstand zwischen den gleichen Kanten verschiedener Spalten). Standard: 0.

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
public abstract int getColumnGapRule()
```

Der Typ des horizontalen Abstands zwischen Spalten einer Matrix; Horizontale Abstandseinheiten können ems oder Punkte sein (in Twips gespeichert). Standard: SingleSpacingGap (0)

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Rückgabewert:**
int

### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

Der Typ des horizontalen Abstands zwischen Spalten einer Matrix; Horizontale Abstandseinheiten können ems oder Punkte sein (in Twips gespeichert). Standard: SingleSpacingGap (0)

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
public abstract long getColumnGap()
```

Der Wert des horizontalen Abstands zwischen Spalten einer Matrix; Wenn ColumnGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn ColumnGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als Anzahl von 0,5-em-Schritten interpretiert. In anderen Fällen ignoriert. Standard: 0

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Rückgabewert:**
long

### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

Der Wert des horizontalen Abstands zwischen Spalten einer Matrix; Wenn ColumnGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn ColumnGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als Anzahl von 0,5-em-Schritten interpretiert. In anderen Fällen ignoriert. Standard: 0

--------------------

> ```
> Beispiel:
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
public abstract int getRowGapRule()
```

Der Typ des vertikalen Abstands zwischen Zeilen einer Matrix; Vertikale Abstandseinheiten können Zeilen oder Punkte sein (in Twips gespeichert). Standard: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Rückgabewert:**
int

### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

Der Typ des vertikalen Abstands zwischen Zeilen einer Matrix; Vertikale Abstandseinheiten können Zeilen oder Punkte sein (in Twips gespeichert). Standard: SingleSpacingGap (0)

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
public abstract long getRowGap()
```

Der Wert des vertikalen Abstands zwischen Zeilen einer Matrix; Wenn RowGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn RowGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als Halblinien interpretiert. Standard: 0

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Rückgabewert:**
long

### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

Der Wert des vertikalen Abstands zwischen Zeilen einer Matrix; Wenn RowGapRule auf 3 („Exactly“) gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn RowGapRule auf 4 („Multiple“) gesetzt ist, wird die Einheit als Halblinien interpretiert. Standard: 0

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

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

Ermittelt die horizontale Ausrichtung der angegebenen Spalte

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

**Rückgabewert:**
int - Horizontale Ausrichtung der angegebenen Spalte

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

Legt die horizontale Ausrichtung der angegebenen Spalte fest

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
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Legt die horizontale Ausrichtung der angegebenen Spalten fest

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | int | Nullbasierter Index der ersten Spalte, deren Ausrichtung gesetzt werden soll |
| columnsCount | long | Anzahl der Spalten, für die die Ausrichtung festgelegt werden soll |
| val | int | Neuer Wert der horizontalen Ausrichtung der angegebenen Spalte |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Fügt vor der angegebenen Zeile eine neue Zeile ein. Anfangs sind alle Elemente in der neuen Zeile null.

--------------------

> ```
> Example:
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
public abstract void insertRowAfter(int rowIndex)
```

Fügt nach der angegebenen Zeile eine neue Zeile ein. Anfangs sind alle Elemente in der neuen Zeile null.

--------------------

> ```
> Beispiel:
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
public abstract void deleteRow(int rowIndex)
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
public abstract void insertColumnBefore(int columnIndex)
```

Fügt vor der angegebenen Spalte eine neue Spalte ein. Anfangs sind alle Elemente in der neuen Spalte null.

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
public abstract void insertColumnAfter(int columnIndex)
```

Fügt nach der angegebenen Spalte eine neue Spalte ein. Anfangs sind alle Elemente in der neuen Spalte null.

--------------------

> ```
> Example:
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
public abstract void deleteColumn(int columnIndex)
```

Löscht die angegebene Spalte

--------------------

> ```
> Beispiel:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | int | Der nullbasierte Index der zu löschenden Spalte. |