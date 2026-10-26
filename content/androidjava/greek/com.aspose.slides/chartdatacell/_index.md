---
title: ChartDataCell
second_title: Αναφορά API Java για Aspose.Slides για Android
description: Αναπαριστά κελί για δεδομένα γραφήματος.
type: docs
url: /el/com.aspose.slides/chartdatacell/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)
```
public class ChartDataCell implements IChartDataCell
```

Αναπαριστά κελί για δεδομένα γραφήματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRow()](#getRow--) | Επιστρέφει το δείκτη της γραμμής του φύλλου εργασίας στο οποίο βρίσκεται το κελί. |
| [getColumn()](#getColumn--) | Επιστρέφει το δείκτη της στήλης του φύλλου εργασίας στο οποίο βρίσκεται το κελί. |
| [getValue()](#getValue--) | Λαμβάνει ή ορίζει την τιμή ενός κελιού. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Λαμβάνει ή ορίζει την τιμή ενός κελιού. |
| [getFormula()](#getFormula--) | Λαμβάνει ή ορίζει τον τύπο A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Λαμβάνει ή ορίζει τον τύπο A1. |
| [getR1C1Formula()](#getR1C1Formula--) | Λαμβάνει ή ορίζει τον τύπο R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Λαμβάνει ή ορίζει τον τύπο R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Λαμβάνει το φύλλο εργασίας. |
| [isHidden()](#isHidden--) | Καθορίζει αν το κελί είναι κρυμμένο. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Λαμβάνει ή ορίζει την προσαρμοσμένη μορφή εμφάνισης αριθμών και ημερομηνιών. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Λαμβάνει ή ορίζει την προσαρμοσμένη μορφή εμφάνισης αριθμών και ημερομηνιών. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Λαμβάνει ή ορίζει την ενσωματωμένη μορφή εμφάνισης αριθμών και ημερομηνιών. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Λαμβάνει ή ορίζει την ενσωματωμένη μορφή εμφάνιση  αριθμών και ημερομηνιών. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Εάν το κελί περιέχει τύπο, η τιμή θα ενημερωθεί βάσει αυτού του τύπου. |
### getRow() {#getRow--}
```
public final int getRow()
```


Επιστρέφει το δείκτη της γραμμής του φύλλου εργασίας στο οποίο βρίσκεται το κελί. Μόνο ανάγνωση int.

**Επιστρέφει:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```


Επιστρέφει το δείκτη της στήλης του φύλλου εργασίας στο οποίο βρίσκεται το κελί. Μόνο ανάγνωση int.

**Επιστρέφει:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Λαμβάνει ή ορίζει την τιμή ενός κελιού. Ανάγνωση/εγγραφή Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Επιστρέφει:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Λαμβάνει ή ορίζει την τιμή ενός κελιού. Ανάγνωση/εγγραφή Object .

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
public final String getFormula()
```


Λαμβάνει ή ορίζει τον τύπο A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Επιστρέφει:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


Λαμβάνει ή ορίζει τον τύπο A1.

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
public final String getR1C1Formula()
```


Λαμβάνει ή ορίζει τον τύπο R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Επιστρέφει:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public final void setR1C1Formula(String value)
```


Λαμβάνει ή ορίζει τον τύπο R1C1.

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
public final IChartDataWorksheet getChartDataWorksheet()
```


Λαμβάνει το φύλλο εργασίας. Μόνο ανάγνωση [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Επιστρέφει:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```


Καθορίζει αν το κελί είναι κρυμμένο. Μόνο ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```


Λαμβάνει ή ορίζει την προσαρμοσμένη μορφή εμφάνισης αριθμών και ημερομηνιών. Εάν η τιμή είναι κενή, θα χρησιμοποιηθεί η τιμή PresetNumberFormat. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```


Λαμβάνει ή ορίζει την προσαρμοσμένη μορφή εμφάνισης αριθμών και ημερομηνιών. Εάν η τιμή είναι κενή, θα χρησιμοποιηθεί η τιμή PresetNumberFormat. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
```


Λαμβάνει ή ορίζει την ενσωματωμένη μορφή εμφάνισης αριθμών και ημερομηνιών. Ο αριθμός Preset πρέπει να είναι στο [0..22] ή [37..49]. Ανάγνωση/εγγραφή byte.

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
>  44	_("$"* # ##0,00_);_("$"* (# ##0,00);_("$"* "-"??_);_(@_)
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
public final void setPresetNumberFormat(byte value)
```


Λαμβάνει ή ορίζει την ενσωματωμένη μορφή εμφάνισης αριθμών και ημερομηνιών. Ο αριθμός Preset πρέπει να είναι στο [0..22] ή [37..49]. Ανάγνωση/εγγραφή byte.

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
>  44	_("$"* # ##0,00_);_("$"* (# ##0,00);_("$"* "-"??_);_(@_)
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
public final void calculate(boolean updateValues)
```


Εάν το κελί περιέχει τύπο, η τιμή θα ενημερωθεί βάσει αυτού του τύπου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| updateValues | boolean | Εάν είναι false, δεν θα πραγματοποιηθεί πραγματικός υπολογισμός. Χρησιμοποιήστε true για έλεγχο πιθανών εξαιρέσεων. |
