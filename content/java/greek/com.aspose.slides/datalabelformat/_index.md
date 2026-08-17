---
title: DataLabelFormat
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει τις επιλογές μορφοποίησης για το DataLabel.
type: docs
url: /el/com.aspose.slides/datalabelformat/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Αναπαριστά επιλογές μορφοποίησης για το DataLabel.
## Μεθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Ανάγνωση/εγγραφή boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Ανάγνωση/εγγραφή boolean. |
| [getNumberFormat()](#getNumberFormat--) | Αναπαριστά το string μορφής για το αντικείμενο DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Αναπαριστά το string μορφής για το αντικείμενο DataLabels. |
| [getFormat()](#getFormat--) | Αναπαριστά τη μορφή της ετικέτας δεδομένων. |
| [getPosition()](#getPosition--) | Αναπαριστά τη θέση της ετικέτας δεδομένων. |
| [setPosition(int value)](#setPosition-int-) | Αναπαριστά τη θέση της ετικέτας δεδομένων. |
| [getShowLegendKey()](#getShowLegendKey--) | Αναπαριστά τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Αναπαριστά τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. |
| [getShowValue()](#getShowValue--) | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. |
| [getShowCategoryName()](#getShowCategoryName--) | Αναπαριστά τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Αναπαριστά τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. |
| [getShowSeriesName()](#getShowSeriesName--) | Επιστρέφει ή ορίζει ένα Boolean για να υποδείξει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα γράφημα. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Επιστρέφει ή ορίζει ένα Boolean για να υποδείξει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα γράφημα. |
| [getShowPercentage()](#getShowPercentage--) | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής μεγέθους φυσαλίδας ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής μεγέθους φυσαλίδας ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Αναπαριστά τη συμπεριφορά εμφάνισης των γραμμών οδηγού ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Αναπαριστά τη συμπεριφορά εμφάνισης των γραμμών οδηγού ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής κελιού ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής κελιού ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Καθορίζει αν η ετικέτα δεδομένων του συγκεκριμένου γραφήματος θα εμφανίζεται ως επεξήγηση δεδομένων ή ως ετικέτα δεδομένων. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Καθορίζει αν η ετικέτα δεδομένων του συγκεκριμένου γραφήματος θα εμφανίζεται ως επεξήγηση δεδομένων ή ως ετικέτα δεδομένων. |
| [getSeparator()](#getSeparator--) | Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. |
| [getTextFormat()](#getTextFormat--) | Επιστρέφει τη μορφή κειμένου του γραφήματος. |
| [getChart()](#getChart--) | Επιστρέφει το γράφημα. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας IsNumberFormatLinkedToSource για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα IsNumberFormatLinkedToSource για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" προκαλεί όλα τα DataLabels.get_Item(i).isNumberFormatLinkedToSource() να είναι ίσα με val).

**Επιστρέφει:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συγκεντρωση DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας IsNumberFormatLinkedToSource για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα IsNumberFormatLinkedToSource για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" προκαλεί όλα τα DataLabels.get_Item(i).isNumberFormatLinkedToSource() να είναι ίσα με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Αναπαριστά το string μορφής για το αντικείμενο DataLabels. Ανάγνωση/εγγραφή String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας NumberFormat για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Όταν αυτή η ιδιότητα οριστεί με τιμή, η τιμή αυτή επίσης ορίζεται στην ιδιότητα NumberFormat για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" προκαλεί όλα τα DataLabels.get_Item(i).getNumberFormat() να είναι ίσα με val).

**Επιστρέφει:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Αναπαριστά το string μορφής για το αντικείμενο DataLabels. Ανάγνωση/εγγραφή String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας NumberFormat για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Όταν αυτή η ιδιότητα οριστεί με τιμή, η τιμή αυτή επίσης ορίζεται στην ιδιότητα NumberFormat για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" προκαλεί όλα τα DataLabels.get_Item(i).getNumberFormat() να είναι ίσα με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Αναπαριστά τη μορφή της ετικέτας δεδομένων. Μόνο για ανάγνωση [IFormat](../../com.aspose.slides/iformat).

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα αναπαριστά την προεπιλεγμένη μορφή για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection.

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Αναπαριστά τη θέση της ετικέτας δεδομένων. Ανάγνωση/εγγραφή [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας Position για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Αναπαριστά τη θέση για τα αντικείμενα DataLabel. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα Position για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" προκαλεί όλα τα DataLabels.get_Item(i).getPosition() να είναι ίσα με val).

**Επιστρέφει:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Αναπαριστά τη θέση της ετικέτας δεδομένων. Ανάγνωση/εγγραφή [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας Position για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Αναπαριστά τη θέση για τα αντικείμενα DataLabel. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα Position για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" προκαλεί όλα τα DataLabels.get_Item(i).getPosition() να είναι ίσα με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Αναπαριστά τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. True εάν το κλειδί υπομνήματος ετικέτας δεδομένων είναι ορατό. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLegendKey για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα ShowLegendKey για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowLegendKey() να είναι ίσα με val).

**Επιστρέφει:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Αναπαριστά τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. True εάν το κλειδί υπομνήματος ετικέτας δεδομένων είναι ορατό. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLegendKey για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα ShowLegendKey για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowLegendKey() να είναι ίσα με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False για απόκρυψη. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowValue για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα ShowValue για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowValue() να είναι ίσα με val).

**Επιστρέφει:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False για απόκρυψη. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowValue για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα ShowValue για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowValue() να είναι ίσα με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Αναπαριστά τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. True για εμφάνιση του ονόματος κατηγορίας για τις ετικέτες δεδομένων σε ένα γράφημα. False για απόκρυψη. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowCategoryName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα ShowCategoryName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowCategoryName() να είναι ίσα με val).

**Επιστρέφει:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Αναπαριστά τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας ετικέτας δεδομένων για ένα συγκεκριμένο γράφημα. True για εμφάνιση του ονόματος κατηγορίας για τις ετικέτες δεδομένων σε ένα γράφημα. False για απόκρυψη. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowCategoryName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα ShowCategoryName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowCategoryName() να είναι ίσα με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, αυτή η ιδιότητα επιστρέφει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowCategoryName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, η τιμή αυτή ορίζεται επίσης στην ιδιότητα ShowCategoryName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. «DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);» με αποτέλεσμα όλες οι κλήσεις DataLabels.get_Item(i).getShowCategoryName() να είναι ίσες με val).

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Επιστρέφει ή ορίζει ένα Boolean που υποδεικνύει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα γράφημα. True για εμφάνιση του ονόματος σειράς. False για απόκρυψή του. Με δυνατότητα ανάγνωσης/εγγραφής boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, αυτή η ιδιότητα επιστρέφει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowSeriesName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, η τιμή αυτή ορίζεται επίσης στην ιδιότητα ShowSeriesName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. «DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);» με αποτέλεσμα όλες οι κλήσεις DataLabels.get_Item(i).getShowSeriesName() να είναι ίσες με val).

**Επιστρέφει:**  
boolean  
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Επιστρέφει ή ορίζει ένα Boolean που υποδεικνύει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα γράφημα. True για εμφάνιση του ονόματος σειράς. False για απόκρυψή του. Με δυνατότητα ανάγνωσης/εγγραφής boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, αυτή η ιδιότητα επιστρέφει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowSeriesName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, η τιμή αυτή ορίζεται επίσης στην ιδιότητα ShowSeriesName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. «DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);» με αποτέλεσμα όλες οι κλήσεις DataLabels.get_Item(i).getShowSeriesName() να είναι ίσες με val).

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False για απόκρυψη. Με δυνατότητα ανάγνωσης/εγγραφής boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, αυτή η ιδιότητα επιστρέφει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowPercentage για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, η τιμή αυτή ορίζεται επίσης στην ιδιότητα ShowPercentage για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. «DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);» με αποτέλεσμα όλες οι κλήσεις DataLabels.get_Item(i).getShowPercentage() να είναι ίσες με val).

**Επιστρέφει:**  
boolean  
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False για απόκρυψη. Με δυνατότητα ανάγνωσης/εγγραφής boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, αυτή η ιδιότητα επιστρέφει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowPercentage για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, η τιμή αυτή ορίζεται επίσης στην ιδιότητα ShowPercentage για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. «DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);» με αποτέλεσμα όλες οι κλήσεις DataLabels.get_Item(i).getShowPercentage() να είναι ίσες με val).

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής μεγέθους φούσκας της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή μεγέθους φούσκας. False για απόκρυψη. Με δυνατότητα ανάγνωσης/εγγραφής boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, αυτή η ιδιότητα επιστρέφει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowBubbleSize για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, η τιμή αυτή ορίζεται επίσης στην ιδιότητα ShowBubbleSize για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. «DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);» με αποτέλεσμα όλες οι κλήσεις DataLabels.get_Item(i).getShowBubbleSize() να είναι ίσες με val).

**Επιστρέφει:**  
boolean  
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής μεγέθους φούσκας της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή μεγέθους φούσκας. False για απόκρυψη. Με δυνατότητα ανάγνωσης/εγγραφής boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, αυτή η ιδιότητα επιστρέφει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowBubbleSize για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, η τιμή αυτή ορίζεται επίσης στην ιδιότητα ShowBubbleSize για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. «DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);» με αποτέλεσμα όλες οι κλήσεις DataLabels.get_Item(i).getShowBubbleSize() να είναι ίσες με val).

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Αναπαριστά τη συμπεριφορά εμφάνισης των γραμμών οδηγού (leader lines) της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει τις γραμμές οδηγού. False για απόκρυψη. Με δυνατότητα ανάγνωσης/εγγραφής boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, αυτή η ιδιότητα επιστρέφει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLeaderLines για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, η τιμή αυτή ορίζεται επίσης στην ιδιότητα ShowLeaderLines για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. «DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);» με αποτέλεσμα όλες οι κλήσεις DataLabels.get_Item(i).getShowLeaderLines() να είναι ίσες με val).

**Επιστρέφει:**  
boolean  
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Αναπαριστά τη συμπεριφορά εμφάνισης των γραμμών οδηγού (leader lines) της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει τις γραμμές οδηγού. False για απόκρυψη. Με δυνατότητα ανάγνωσης/εγγραφής boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, αυτή η ιδιότητα επιστρέφει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLeaderLines για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, η τιμή αυτή ορίζεται επίσης στην ιδιότητα ShowLeaderLines για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. «DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);» με αποτέλεσμα όλες οι κλήσεις DataLabels.get_Item(i).getShowLeaderLines() να είναι ίσες με val).

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής κελιού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή του κελιού. False για απόκρυψη. Με δυνατότητα ανάγνωσης/εγγραφής boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, αυτή η ιδιότητα επιστρέφει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLabelValueFromCell για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, η τιμή αυτή ορίζεται επίσης στην ιδιότητα ShowLabelValueFromCell για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. «DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);» με αποτέλεσμα όλες οι κλήσεις DataLabels.get_Item(i).getShowLabelValueFromCell() να είναι ίσες με val).

**Επιστρέφει:**  
boolean  
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής κελιού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή του κελιού. False για απόκρυψη. Με δυνατότητα ανάγνωσης/εγγραφής boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, αυτή η ιδιότητα επιστρέφει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLabelValueFromCell για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, η τιμή αυτή ορίζεται επίσης στην ιδιότητα ShowLabelValueFromCell για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. «DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);» με αποτέλεσμα όλες οι κλήσεις DataLabels.get_Item(i).getShowLabelValueFromCell() να είναι ίσες με val).

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Καθορίζει εάν η ετικέτα δεδομένων ενός συγκεκριμένου γραφήματος θα εμφανίζεται ως κλήση δεδομένων (data callout) ή ως ετικέτα δεδομένων.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, αυτή η ιδιότητα επιστρέφει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLabelAsDataCallout για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, η τιμή αυτή ορίζεται επίσης στην ιδιότητα ShowLabelAsDataCallout για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. «DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);» με αποτέλεσμα όλες οι κλήσεις DataLabels.get_Item(i).getShowLabelAsDataCallout() να είναι ίσες με val).

**Επιστρέφει:**  
boolean  
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Καθορίζει εάν η ετικέτα δεδομένων ενός συγκεκριμένου γραφήματος θα εμφανίζεται ως κλήση δεδομένων (data callout) ή ως ετικέτα δεδομένων.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, αυτή η ιδιότητα επιστρέφει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLabelAsDataCallout για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, η τιμή αυτή ορίζεται επίσης στην ιδιότητα ShowLabelAsDataCallout για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. «DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);» με αποτέλεσμα όλες οι κλήσεις DataLabels.get_Item(i).getShowLabelAsDataCallout() να είναι ίσες με val).

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. Με δυνατότητα ανάγνωσης/εγγραφής String.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, αυτή η ιδιότητα επιστρέφει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας Separator για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, η τιμή αυτή ορίζεται επίσης στην ιδιότητα Separator για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. «DataLabels.getDefaultDataLabelFormat().setSeparator(val);» με αποτέλεσμα όλες οι κλήσεις DataLabels.get_Item(i).getSeparator() να είναι ίσες με val).

**Επιστρέφει:**  
java.lang.String  
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. Με δυνατότητα ανάγνωσης/εγγραφής String.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, αυτή η ιδιότητα επιστρέφει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας Separator για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, η τιμή αυτή ορίζεται επίσης στην ιδιότητα Separator για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. «DataLabels.getDefaultDataLabelFormat().setSeparator(val);» με αποτέλεσμα όλες οι κλήσεις DataLabels.get_Item(i).getSeparator() να είναι ίσες με val).
**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Επιστρέφει τη μορφή κειμένου του διαγράμματος. Μόνο ανάγνωση [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Επιστρέφει:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Επιστρέφει το διάγραμμα. Μόνο ανάγνωση [IChart](../../com.aspose.slides/ichart).

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart)