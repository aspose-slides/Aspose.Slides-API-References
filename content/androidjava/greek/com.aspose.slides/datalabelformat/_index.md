---
title: DataLabelFormat
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεύει επιλογές μορφοποίησης για το DataLabel.
type: docs
url: /el/com.aspose.slides/datalabelformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Αντιπροσωπεύει επιλογές μορφοποίησης για το DataLabel.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Ανάγνωση/εγγραφή boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Ανάγνωση/εγγραφή boolean. |
| [getNumberFormat()](#getNumberFormat--) | Αντιπροσωπεύει τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Αντιπροσωπεύει τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. |
| [getFormat()](#getFormat--) | Αντιπροσωπεύει τη μορφή της ετικέτας δεδομένων. |
| [getPosition()](#getPosition--) | Αντιπροσωπεύει τη θέση της ετικέτας δεδομένων. |
| [setPosition(int value)](#setPosition-int-) | Αντιπροσωπεύει τη θέση της ετικέτας δεδομένων. |
| [getShowLegendKey()](#getShowLegendKey--) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. |
| [getShowValue()](#getShowValue--) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. |
| [getShowCategoryName()](#getShowCategoryName--) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. |
| [getShowSeriesName()](#getShowSeriesName--) | Επιστρέφει ή ορίζει ένα Boolean για να υποδείξει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα διάγραμμα. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Επιστρέφει ή ορίζει ένα Boolean για να υποδείξει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα διάγραμμα. |
| [getShowPercentage()](#getShowPercentage--) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής μεγέθους φυσαλίδας ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής μεγέθους φυσαλίδας ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης των γραμμών οδηγού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης των γραμμών οδηγού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής κελιού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής κελιού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Καθορίζει εάν η ετικέτα δεδομένων ενός καθορισμένου διαγράμματος θα εμφανίζεται ως κλήση δεδομένων ή ως ετικέτα δεδομένων. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Καθορίζει εάν η ετικέτα δεδομένων ενός καθορισμένου διαγράμματος θα εμφανίζεται ως κλήση δεδομένων ή ως ετικέτα δεδομένων. |
| [getSeparator()](#getSeparator--) | Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα διάγραμμα. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα διάγραμμα. |
| [getTextFormat()](#getTextFormat--) | Επιστρέφει τη μορφή κειμένου του διαγράμματος. |
| [getChart()](#getChart--) | Επιστρέφει το διάγραμμα. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο-ανάγνωση long.

**Επιστρέφει:**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας IsNumberFormatLinkedToSource για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα IsNumberFormatLinkedToSource για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" προκαλεί όλες οι DataLabels.get_Item(i).isNumberFormatLinkedToSource() να είναι ίσες με val).

**Επιστρέφει:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας IsNumberFormatLinkedToSource για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα IsNumberFormatLinkedToSource για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" προκαλεί όλες οι DataLabels.get_Item(i).isNumberFormatLinkedToSource() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Αντιπροσωπεύει τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. Ανάγνωση/εγγραφή String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας NumberFormat για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Όταν αυτή η ιδιότητα ορίζεται με τιμή, η τιμή αυτή τίθεται επίσης για την ιδιότητα NumberFormat όλων των ετικετών δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" προκαλεί όλες οι DataLabels.get_Item(i).getNumberFormat() να είναι ίσες με val).

**Επιστρέφει:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Αντιπροσωπεύει τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. Ανάγνωση/εγγραφή String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας NumberFormat για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Όταν αυτή η ιδιότητα ορίζεται με τιμή, η τιμή αυτή τίθεται επίσης για την ιδιότητα NumberFormat όλων των ετικετών δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" προκαλεί όλες οι DataLabels.get_Item(i).getNumberFormat() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Αντιπροσωπεύει τη μορφή της ετικέτας δεδομένων. Μόνο-ανάγνωση [IFormat](../../com.aspose.slides/iformat).

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα αντιπροσωπεύει την προεπιλεγμένη μορφή για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection.

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Αντιπροσωπεύει τη θέση της ετικέτας δεδομένων. Ανάγνωση/εγγραφή [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας Position για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Αντιπροσωπεύει τη θέση για τα αντικείμενα DataLabel. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα Position για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" προκαλεί όλες οι DataLabels.get_Item(i).getPosition() να είναι ίσες με val).

**Επιστρέφει:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Αντιπροσωπεύει τη θέση της ετικέτας δεδομένων. Ανάγνωση/εγγραφή [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας Position για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Αντιπροσωπεύει τη θέση για τα αντικείμενα DataLabel. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα Position για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" προκαλεί όλες οι DataLabels.get_Item(i).getPosition() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. Αληθές εάν το κλειδί υπομνήματος είναι ορατό. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLegendKey για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowLegendKey για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowLegendKey() να είναι ίσες με val).

**Επιστρέφει:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. Αληθές εάν το κλειδί υπομνήματος είναι ορατό. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLegendKey για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowLegendKey για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowLegendKey() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. Αληθές εμφανίζει την τιμή ποσοστού. Ψευδές κρύβει την τιμή. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowValue για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowValue για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowValue() να είναι ίσες με val).

**Επιστρέφει:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. Αληθές εμφανίζει την τιμή ποσοστού. Ψευδές κρύβει την τιμή. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowValue για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowValue για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowValue() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. Αληθές εμφανίζει το όνομα κατηγορίας. Ψευδές κρύβει το όνομα. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowCategoryName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowCategoryName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowCategoryName() να είναι ίσες με val).

**Επιστρέφει:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. Αληθές εμφανίζει το όνομα κατηγορίας. Ψευδές κρύβει το όνομα. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowCategoryName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowCategoryName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowCategoryName() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Επιστρέφει ή ορίζει ένα Boolean για να υποδείξει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα διάγραμμα. Αληθές εμφανίζει το όνομα σειράς. Ψευδές κρύβει το όνομα. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowSeriesName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowSeriesName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowSeriesName() να είναι ίσες με val).

**Επιστρέφει:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Επιστρέφει ή ορίζει ένα Boolean για να υποδείξει τη συμπεριφορά εμφάνιση του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα διάγραμμα. Αληθές εμφανίζει το όνομα σειράς. Ψευδές κρύβει το όνομα. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowSeriesName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowSeriesName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowSeriesName() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. Αληθές εμφανίζει την τιμή ποσοστού. Ψευδές κρύβει την τιμή. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowPercentage για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowPercentage για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowPercentage() να είναι ίσες με val).

**Επιστρέφει:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. Αληθές εμφανίζει την τιμή ποσοστού. Ψευδές κρύβει την τιμή. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowPercentage για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowPercentage για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowPercentage() να είναι ίσα με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής μεγέθους φυσαλίδας ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. Αληθές εμφανίζει τη τιμή μεγέθους φυσαλίδας. Ψευδές κρύβει τη τιμή. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowBubbleSize για τις νέες ετικέτες δεδομένων στη συλλοχή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowBubbleSize για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowBubbleSize() να είναι ίσες με val).

**Επιστρέφει:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής μεγέθους φυσαλίδας ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. Αληθές εμφανίζει τη τιμή μεγέθους φυσαλίδας. Ψευδές κρύβει τη τιμή. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowBubbleSize για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowBubbleSize για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowBubbleSize() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης των γραμμών οδηγού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. Αληθές εμφανίζει τις γραμμές οδηγού. Ψευδές κρύβει τις γραμμές. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowLeaderLines για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowLeaderLines για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowLeaderLines() να είναι ίσες με val).

**Επιστρέφει:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης των γραμμών οδηγού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. Αληθές εμφανίζει τις γραμμές οδηγού. Ψευδές κρύβει τις γραμμές. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowLeaderLines για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowLeaderLines για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowLeaderLines() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής κελιού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. Αληθές εμφανίζει την τιμή κελιού. Ψευδές κρύβει την τιμή. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowLabelValueFromCell για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowLabelValueFromCell για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowLabelValueFromCell() να είναι ίσες με val).

**Επιστρέφει:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής κελιού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος. Αληθές εμφανίζει την τιμή κελιού. Ψευδές κρύβει την τιμή. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowLabelValueFromCell για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowLabelValueFromCell για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowLabelValueFromCell() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Καθορίζει εάν η ετικέτα δεδομένων ενός καθορισμένου διαγράμματος θα εμφανίζεται ως κλήση δεδομένων ή ως ετικέτα δεδομένων.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowLabelAsDataCallout για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowLabelAsDataCallout για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowLabelAsDataCallout() να είναι ίσες με val).

**Επιστρέφει:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Καθορίζει εάν η ετικέτα δεδομένων ενός καθορισμένου διαγράμματος θα εμφανίζεται ως κλήση δεδομένων ή ως ετικέτα δεδομένων.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowLabelAsDataCallout για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowLabelAsDataCallout για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" προκαλεί όλες οι DataLabels.get_Item(i).getShowLabelAsDataCallout() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα διάγραμμα. Ανάγνωση/εγγραφή String.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας Separator για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα Separator για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" προκαλεί όλες οι DataLabels.get_Item(i).getSeparator() να είναι ίσες με val).

**Επιστρέφει:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα διάγραμμα. Ανάγνωση/εγγραφή String.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας Separator για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα Separator για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" προκαλεί όλες οι DataLabels.get_Item(i).getSeparator() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Επιστρέφει τη μορφή κειμένου του διαγράμματος. Μόνο-ανάγνωση [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Επιστρέφει:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

Επιστρέφει το διάγραμμα. Μόνο-ανάγνωση [IChart](../../com.aspose.slides/ichart).

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart)