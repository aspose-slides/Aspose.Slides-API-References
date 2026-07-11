---
title: CellFormat
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αναπαριστά τη μορφή ενός κελιού πίνακα.
type: docs
url: /el/com.aspose.slides/cellformat/
---
**Κληρονομικότητα:**
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
| [getBorderLeft()](#getBorderLeft--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής αριστερής περιθώριας. |
| [getBorderTop()](#getBorderTop--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής άνω περιθώριας. |
| [getBorderRight()](#getBorderRight--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής δεξιάς περιθώριας. |
| [getBorderBottom()](#getBorderBottom--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής κάτω περιθώριας. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγωνίου γραμμής από πάνω αριστερά προς κάτω δεξιά. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγωνίου γραμμής από κάτω αριστερά προς πάνω δεξιά. |
| [getEffective()](#getEffective--) | Λαμβάνει τις αποτελεσματικές ιδιότητες μορφοποίησης κελιού πίνακα με κληρονομικότητα και εφαρμόζοντας τα στυλ πίνακα. |
| [getTransparency()](#getTransparency--) | Λαμβάνει ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. |
| [setTransparency(float value)](#setTransparency-float-) | Λαμβάνει ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Επιστρέφει ένα αντικείμενο ιδιοτήτων γεμίσματος κελιού. Μόνο για ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```


Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής αριστερής περιθώριας. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```


Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής άνω περιθώριας. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```


Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής δεξιάς περιθώριας. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```


Επιστρέφει ένα αντικείμενο ιδιοτήτων γραμμής κάτω περιθώριας. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```


Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγωνίου γραμμής από πάνω αριστερά προς κάτω δεξιά. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```


Επιστρέφει ένα αντικείμενο ιδιοτήτων διαγωνίου γραμμής από κάτω αριστερά προς πάνω δεξιά. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```


Λαμβάνει τις αποτελεσματικές ιδιότητες μορφοποίησης κελιού πίνακα με κληρονομικότητα και εφαρμόζοντας τα στυλ πίνακα.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει την απόκτηση του αποτελεσματικού μορφότυπου γεμίσματος για διαφορετικά λογικά μέρη του πίνακα.
>  Παρακαλούμε σημειώστε ότι η μορφοποίηση των κελιών έχει πάντα υψηλότερη προτεραιότητα από τη μορφοποίηση των γραμμών, η γραμμή - υψηλότερη από τη στήλη, η στήλη - υψηλότερη από ολόκληρο τον πίνακα.
>  Έτσι τελικά οι ιδιότητες του CellFormatEffectiveData χρησιμοποιούνται πάντα για τη σχεδίαση του πίνακα. Ο παρακάτω κώδικας είναι μόνο ένα παράδειγμα του API.
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


Λαμβάνει ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. Ανάγνωση/εγγραφή  float .

**Επιστρέφει:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


Λαμβάνει ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. Ανάγνωση/εγγραφή  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |