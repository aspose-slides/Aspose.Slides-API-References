---
title: TableFormat
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά τη μορφή ενός πίνακα.
type: docs
url: /el/com.aspose.slides/tableformat/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Αναπαριστά τη μορφή ενός πίνακα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Επιστρέφει ένα αντικείμενο ιδιοτήτων γεμίσματος πίνακα. |
| [getTransparency()](#getTransparency--) | Λαμβάνει ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. |
| [setTransparency(float value)](#setTransparency-float-) | Λαμβάνει ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. |
| [getEffective()](#getEffective--) | Λαμβάνει τις αποτελεσματικές ιδιότητες μορφοποίησης πίνακα με κληρονομικότητα και εφαρμόζονται τα στυλ πίνακα. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Επιστρέφει ένα αντικείμενο ιδιοτήτων γεμίσματος πίνακα. Μόνο για ανάγνωση [IFillFormat](../../com.aspose.slides/ifillformat).

**Επιστρέφει:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Λαμβάνει ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. Αναγνώσιμη/εγγράψιμη  float .

**Επιστρέφει:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Λαμβάνει ή ορίζει τη διαφάνεια του χρώματος γεμίσματος. Αναγνώσιμη/εγγράψιμη  float .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

Λαμβάνει τις αποτελεσματικές ιδιότητες μορφοποίησης πίνακα με κληρονομικότητα και εφαρμόζονται τα στυλ πίνακα.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (Table)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Ένα [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Επιστρέφει το γονικό IPresentationComponent. Μόνο για ανάγνωση [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Επιστρέφει:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)