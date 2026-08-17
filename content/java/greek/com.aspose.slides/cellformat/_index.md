---
title: CellFormat
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά τη μορφή ενός κελιού πίνακα.
type: docs
url: /el/com.aspose.slides/cellformat/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

Αναπαριστά τη μορφή ενός κελιού πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γεμίσματος κελιού. |
| [getBorderLeft()](#getBorderLeft--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής αριστερού περιγράμματος. |
| [getBorderTop()](#getBorderTop--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής άνω περιγράμματος. |
| [getBorderRight()](#getBorderRight--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής δεξιού περιγράμματος. |
| [getBorderBottom()](#getBorderBottom--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής κάτω περιγράμματος. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγώνιας γραμμής από επάνω αριστερά προς κάτω δεξιά. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγώνιας γραμμής από κάτω αριστερά προς επάνω δεξιά. |
| [getEffective()](#getEffective--) | Αντλεί τις αποτελεσματικές ιδιότητες μορφοποίησης κελιού πίνακα με κληρονομικότητα και εφαρμοσμένα στυλ πίνακα. |
| [getTransparency()](#getTransparency--) | Αντλεί ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. |
| [setTransparency(float value)](#setTransparency-float-) | Αντλεί ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο-ανάγνωση long.

**Επιστρέφει:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων γεμίσματος κελιού. Μόνο-ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής αριστερού περιγράμματος. Μόνο-ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής άνω περιγράμματος. Μόνο-ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής δεξιού περιγράμματος. Μόνο-ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής κάτω περιγράμματος. Μόνο-ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγώνιας γραμμής από επάνω αριστερά προς κάτω δεξιά. Μόνο-ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγώνιας γραμμής από κάτω αριστερά προς επάνω δεξιά. Μόνο-ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

Αντλεί τις αποτελεσματικές ιδιότητες μορφοποίησης κελιού πίνακα με κληρονομικότητα και εφαρμοσμένα στυλ πίνακα.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Αντλεί ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Αντλεί ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |