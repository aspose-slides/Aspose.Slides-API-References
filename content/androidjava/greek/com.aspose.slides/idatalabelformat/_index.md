---
title: IDataLabelFormat
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει τις επιλογές μορφοποίησης για το DataLabel.
type: docs
url: /el/com.aspose.slides/idatalabelformat/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Αντιπροσωπεύει τις επιλογές μορφοποίησης για το DataLabel.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Ανάγνωση/εγγραφή boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Ανάγνωση/εγγραφή boolean. |
| [getNumberFormat()](#getNumberFormat--) | Αντιπροσωπεύει τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Αντιπροσωπεύει τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. |
| [getFormat()](#getFormat--) | Αντιπροσωπεύει τη μορφή της ετικέτας δεδομένων. |
| [getPosition()](#getPosition--) | Αντιπροσωπεύει τη θέση της ετικέτας δεδομένων. |
| [setPosition(int value)](#setPosition-int-) | Αντιπροσωπεύει τη θέση της ετικέτας δεδομένων. |
| [getShowLegendKey()](#getShowLegendKey--) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος ετικέτας δεδομένων σε συγκεκριμένο γράφημα. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος ετικέτας δεδομένων σε συγκεκριμένο γράφημα. |
| [getShowValue()](#getShowValue--) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ποσοστού τιμής ετικέτας δεδομένων σε συγκεκριμένο γράφημα. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ποσοστού τιμής ετικέτας δεδομένων σε συγκεκριμένο γράφημα. |
| [getShowCategoryName()](#getShowCategoryName--) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας ετικέτας δεδομένων σε συγκεκριμένο γράφημα. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας ετικέτας δεδομένων σε συγκεκριμένο γράφημα. |
| [getShowSeriesName()](#getShowSeriesName--) | Επιστρέφει ή καθορίζει Boolean που υποδεικνύει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα γράφημα. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Επιστρέφει ή καθορίζει Boolean που υποδεικνύει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα γράφημα. |
| [getShowPercentage()](#getShowPercentage--) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ποσοστού τιμής ετικέτας δεδομένων σε συγκεκριμένο γράφημα. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ποσοστού τιμής ετικέτας δεδομένων σε συγκεκριμένο γράφημα. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του μεγέθους φυσαλίδας ετικέτας δεδομένων σε συγκεκριμένο γράφημα. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του μεγέθους φυσαλίδας ετικέτας δεδομένων σε συγκεκριμένο γράφημα. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης των γραμμών καθοδήγησης ετικέτας δεδομένων σε συγκεκριμένο γράφημα. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης των γραμμών καθοδήγησης ετικέτας δεδομένων σε συγκεκριμένο γράφημα. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Καθορίζει εάν η ετικέτα δεδομένων σε συγκεκριμένο γράφημα θα εμφανίζεται ως επαφή δεδομένων ή ως ετικέτα δεδομένων. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Καθορίζει εάν η ετικέτα δεδομένων σε συγκεκριμένο γράφημα θα εμφανίζεται ως επαφή δεδομένων ή ως ετικέτα δεδομένων. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής κελιού ετικέτας δεδομένων σε συγκεκριμένο γράφημα. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής κελιού ετικέτας δεδομένων σε συγκεκριμένο γράφημα. |
| [getSeparator()](#getSeparator--) | Ορίζει ή επιστρέφει Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Ορίζει ή επιστρέφει Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας IsNumberFormatLinkedToSource για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα IsNumberFormatLinkedToSource για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).isNumberFormatLinkedToSource() να είναι ίσες με val).

**Επιστρέφει:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας IsNumberFormatLinkedToSource για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα IsNumberFormatLinkedToSource για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).isNumberFormatLinkedToSource() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Αντιπροσωπεύει τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. Ανάγνωση/εγγραφή String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας NumberFormat για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Όταν αυτή η ιδιότητα ορίζεται με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα NumberFormat για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getNumberFormat() να είναι ίσες με val).

**Επιστρέφει:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Αντιπροσωπεύει τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. Ανάγνωση/εγγραφή String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας NumberFormat για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Όταν αυτή η ιδιότητα ορίζεται με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα NumberFormat για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getNumberFormat() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Αντιπροσωπεύει τη μορφή της ετικέτας δεδομένων. Μόνο-ανάγνωση [IFormat](../../com.aspose.slides/iformat).

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα αντιπροσωπεύει την προεπιλεγμένη μορφή για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection.

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Αντιπροσωπεύει τη θέση της ετικέτας δεδομένων. Ανάγνωση/εγγραφή [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας Position για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Αντιπροσωπεύει τη θέση για τα αντικείμενα DataLabel. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα Position για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getPosition() να είναι ίσες με val).

**Επιστρέφει:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Αντιπροσωπεύει τη θέση της ετικέτας δεδομένων. Ανάγνωση/εγγραφή [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας Position για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Αντιπροσωπεύει τη θέση για τα αντικείμενα DataLabel. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα Position για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getPosition() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος ετικέτας δεδομένων σε συγκεκριμένο γράφημα. True εάν το κλειδί υπομνήματος ετικέτας δεδομένων είναι ορατό. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowLegendKey για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowLegendKey για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowLegendKey() να είναι ίσες με val).

**Επιστρέφει:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος ετικέτας δεδομένων σε συγκεκριμένο γράφημα. True εάν το κλειδί υπομνήματος ετικέτας δεδομένων είναι ορατό. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowLegendKey για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowLegendKey για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowLegendKey() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ποσοστού τιμής ετικέτας δεδομένων σε συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False κρύβει. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowValue για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowValue για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowValue() να είναι ίσες με val).

**Επιστρέφει:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ποσοστού τιμής ετικέτας δεδομένων σε συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False κρύβει. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowValue για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowValue για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowValue() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας ετικέτας δεδομένων σε συγκεκριμένο γράφημα. True για εμφάνιση του ονόματος κατηγορίας. False για απόκρυψη. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowCategoryName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowCategoryName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowCategoryName() να είναι ίσες με val).

**Επιστρέφει:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας ετικέτας δεδομένων σε συγκεκριμένο γράφημα. True για εμφάνιση του ονόματος κατηγορίας. False για απόκρυψη. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowCategoryName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowCategoryName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowCategoryName() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Επιστρέφει ή ορίζει Boolean που υποδεικνύει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα γράφημα. True για εμφάνιση του ονόματος σειράς. False για απόκρυψη. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowSeriesName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowSeriesName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowSeriesName() να είναι ίσες με val).

**Επιστρέφει:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Επιστρέφει ή ορίζει Boolean που υποδεικνύει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα γράφημα. True για εμφάνιση του ονόματος σειράς. False για απόκρυψη. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowSeriesName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowSeriesName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowSeriesName() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ποσοστού τιμής ετικέτας δεδομένων σε συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False κρύβει. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowPercentage για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowPercentage για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowPercentage() να είναι ίσες με val).

**Επιστρέφει:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ποσοστού τιμής ετικέτας δεδομένων σε συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False κρύβει. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowPercentage για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowPercentage για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowPercentage() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του μεγέθους φυσαλίδας ετικέτας δεδομένων σε συγκεκριμένο γράφημα. True εμφανίζει το μέγεθος φυσαλίδας. False κρύβει. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowBubbleSize για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowBubbleSize για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowBubbleSize() να είναι ίσες με val).

**Επιστρέφει:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του μεγέθους φυσαλίδας ετικέτας δεδομένων σε συγκεκριμένο γράφημα. True εμφανίζει το μέγεθος φυσαλίδας. False κρύβει. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowBubbleSize για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowBubbleSize για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowBubbleSize() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης των γραμμών καθοδήγησης ετικέτας δεδομένων σε συγκεκριμένο γράφημα. True εμφανίζει τις γραμμές καθοδήγησης. False κρύβει. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowLeaderLines για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowLeaderLines για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowLeaderLines() να είναι ίσες με val).

**Επιστρέφει:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης των γραμμών καθοδήγησης ετικέτας δεδομένων σε συγκεκριμένο γράφημα. True εμφανίζει τις γραμμές καθοδήγησης. False κρύβει. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowLeaderLines για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowLeaderLines για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowLeaderLines() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Καθορίζει εάν η ετικέτα δεδομένων σε συγκεκριμένο γράφημα θα εμφανίζεται ως επαφή δεδομένων ή ως ετικέτα δεδομένων.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowLabelAsDataCallout για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowLabelAsDataCallout για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowLabelAsDataCallout() να είναι ίσες με val).

**Επιστρέφει:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Καθορίζει εάν η ετικέτα δεδομένων σε συγκεκριμένο γράφημα θα εμφανίζεται ως επαφή δεδομένων ή ως ετικέτα δεδομένων.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowLabelAsDataCallout για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowLabelAsDataCallout για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowLabelAsDataCallout() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής κελιού ετικέτας δεδομένων σε συγκεκριμένο γράφημα. True εμφανίζει την τιμή κελιού. False κρύβει. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowLabelValueFromCell για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowLabelValueFromCell για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowLabelValueFromCell() να είναι ίσες με val).

**Επιστρέφει:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής κελιού ετικέτας δεδομένων σε συγκεκριμένο γράφημα. True εμφανίζει την τιμή κελιού. False κρύβει. Ανάγνωση/εγγραφή boolean.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας ShowLabelValueFromCell για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα ShowLabelValueFromCell για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getShowLabelValueFromCell() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Ορίζει ή επιστρέφει Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. Ανάγνωση/εγγραφή String.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας Separator για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα Separator για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getSeparator() να είναι ίσες με val).

**Επιστρέφει:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Ορίζει ή επιστρέφει Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. Ανάγνωση/εγγραφή String.

--------------------

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει τη προεπιλεγμένη τιμή της ιδιότητας Separator για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτήν την ιδιότητα με τιμή, η ίδια τιμή ορίζεται επίσης για την ιδιότητα Separator για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" προκαλεί όλες οι κλήσεις DataLabels.get_Item(i).getSeparator() να είναι ίσες με val).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |