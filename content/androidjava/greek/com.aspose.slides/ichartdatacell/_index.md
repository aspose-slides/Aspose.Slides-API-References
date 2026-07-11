---
title: IChartDataCell
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά κελί για δεδομένα γραφήματος.
type: docs
url: /el/com.aspose.slides/ichartdatacell/
---```
public interface IChartDataCell
```

Αναπαριστά κελί για δεδομένα γραφήματος.
## Μέθοδοι

| Method | Περιγραφή |
| --- | --- |
| [getRow()](#getRow--) | Επιστρέφει τον δείκτη της γραμμής του φύλλου εργασίας στο οποίο βρίσκεται το κελί. |
| [getColumn()](#getColumn--) | Επιστρέφει τον δείκτη της στήλης του φύλλου εργασίας στο οποίο βρίσκεται το κελί. |
| [getValue()](#getValue--) | Προέρχεται ή ορίζει την τιμή ενός κελιού. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Προέρχεται ή ορίζει την τιμή ενός κελιού. |
| [getFormula()](#getFormula--) | Προέρχεται ή ορίζει τον τύπο σε στυλ A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Προέρχεται ή ορίζει τον τύπο σε στυλ A1. |
| [getR1C1Formula()](#getR1C1Formula--) | Προέρχεται ή ορίζει τον τύπο σε στυλ R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Προέρχεται ή ορίζει τον τύπο σε στυλ R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Προέρχεται το φύλλο εργασίας. |
| [isHidden()](#isHidden--) | Καθορίζει εάν το κελί είναι κρυφό. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Προέρχεται ή ορίζει την προσαρμοσμένη μορφή εμφάνισης αριθμών και ημερομηνιών. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Προέρχεται ή ορίζει την προσαρμοσμένη μορφή εμφάνισης αριθμών και ημερομηνιών. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Προέρχεται ή ορίζει την ενσωματωμένη μορφή εμφάνισης αριθμών και ημερομηνιών. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Προέρχεται ή ορίζει την ενσωματωμένη μορφή εμφάνισης αριθμών και ημερομηνιών. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Εάν το κελί περιέχει τύπο, η τιμή θα ενημερωθεί βάσει αυτού του τύπου. |
### getRow() {#getRow--}
```
public abstract int getRow()
```


Επιστρέφει τον δείκτη της γραμμής του φύλλου εργασίας στο οποίο βρίσκεται το κελί. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Επιστρέφει τον δείκτη της στήλης του φύλλου εργασίας στο οποίο βρίσκεται το κελί. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Προέρχεται ή ορίζει την τιμή ενός κελιού. Ανάγνωση/εγγραφή Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Επιστρέφει:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Προέρχεται ή ορίζει την τιμή ενός κελιού. Ανάγνωση/εγγραφή Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```


Προέρχεται ή ορίζει τον τύπο σε στυλ A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Επιστρέφει:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```


Προέρχεται ή ορίζει τον τύπο σε στυλ A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public abstract String getR1C1Formula()
```


Προέρχεται ή ορίζει τον τύπο σε στυλ R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Επιστρέφει:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public abstract void setR1C1Formula(String value)
```


Προέρχεται ή ορίζει τον τύπο σε στυλ R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public abstract IChartDataWorksheet getChartDataWorksheet()
```


Προέρχεται το φύλλο εργασίας. Μόνο για ανάγνωση [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Επιστρέφει:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


Καθορίζει εάν το κελί είναι κρυφό. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```


Προέρχεται ή ορίζει την προσαρμοσμένη μορφή εμφάνισης αριθμών και ημερομηνιών. Εάν η τιμή είναι κενή, θα χρησιμοποιηθεί η τιμή PresetNumberFormat. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```


Προέρχεται ή ορίζει την προσαρμοσμένη μορφή εμφάνισης αριθμών και ημερομηνιών. Εάν η τιμή είναι κενή, θα χρησιμοποιηθεί η τιμή PresetNumberFormat. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```


Προέρχεται ή ορίζει την ενσωματωμένη μορφή εμφάνισης αριθμών και ημερομηνιών. Ο προεπιλεγμένος αριθμός πρέπει να είναι στο [0..22] ή [37..49]. Ανάγνωση/εγγραφή byte.

--------------------

> ```
> 0	General
>  1	0
>  2	0.00
>  3	#,##0
>  4	#,##0.00
>  5	$#,##0;$-#,##0
>  6	$#,##0;[Red]$-#,##0
>  7	$#,##0.00;$-#,##0.00
>  8	$#,##0.00;[Red]$-#,##0.00
>  9	0%
>  10	0.00%
>  11	0.00E+00
>  12	# ?/?
>  13	# /
>  14	m/d/yy
>  15	d-mmm-yy
>  16	d-mmm
>  17	mmm-yy
>  18	h:mm AM/PM
>  19	h:mm:ss AM/PM
>  20	h:mm
>  21	h:mm:ss
>  22	m/d/yy h:mm
>  37	#,##0;-#,##0
>  38	#,##0;[Red]-#,##0
>  39	#,##0.00;-#,##0.00
>  40	#,##0.00;[Red]-#,##0.00
>  41	_ * #,##0_ ;_ * "_ ;_ @_
>  42	_ $* #,##0_ ;_ $* "_ ;_ @_
>  43	_ * #,##0.00_ ;_ * "??_ ;_ @_
>  44	_ $* #,##0.00_ ;_ $* "??_ ;_ @_
>  45	mm:ss
>  46	h :mm:ss
>  47	mm:ss.0
>  48	##0.0E+00
>  49	@
> ```

**Επιστρέφει:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public abstract void setPresetNumberFormat(byte value)
```


Προέρχεται ή ορίζει την ενσωματωμένη μορφή εμφάνισης αριθμών και ημερομηνιών. Ο προεπιλεγμένος αριθμός πρέπει να είναι στο [0..22] ή [37..49]. Ανάγνωση/εγγραφή byte.

--------------------

> ```
> 0	General
>  1	0
>  2	0.00
>  3	#,##0
>  4	#,##0.00
>  5	$#,##0;$-#,##0
>  6	$#,##0;[Red]$-#,##0
>  7	$#,##0.00;$-#,##0.00
>  8	$#,##0.00;[Red]$-#,##0.00
>  9	0%
>  10	0.00%
>  11	0.00E+00
>  12	# ?/?
>  13	# /
>  14	m/d/yy
>  15	d-mmm-yy
>  16	d-mmm
>  17	mmm-yy
>  18	h:mm AM/PM
>  19	h:mm:ss AM/PM
>  20	h:mm
>  21	h:mm:ss
>  22	m/d/yy h:mm
>  37	#,##0;-#,##0
>  38	#,##0;[Red]-#,##0
>  39	#,##0.00;-#,##0.00
>  40	#,##0.00;[Red]-#,##0.00
>  41	_ * #,##0_ ;_ * "_ ;_ @_
>  42	_ $* #,##0_ ;_ $* "_ ;_ @_
>  43	_ * #,##0.00_ ;_ * "??_ ;_ @_
>  44	_ $* #,##0.00_ ;_ $* "??_ ;_ @_
>  45	mm:ss
>  46	h :mm:ss
>  47	mm:ss.0
>  48	##0.0E+00
>  49	@
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public abstract void calculate(boolean updateValues)
```


Εάν το κελί περιέχει τύπο, η τιμή θα ενημερωθεί βάσει αυτού του τύπου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| updateValues | boolean | Εάν είναι false, δεν θα γίνει πραγματικός υπολογισμός. Χρησιμοποιήστε true για έλεγχο πιθανών εξαιρέσεων. |