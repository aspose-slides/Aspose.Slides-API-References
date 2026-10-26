---
title: DataLabelFormat
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/datalabelformat/
---
## DataLabelFormat κλάση

Αναπαριστά τις επιλογές μορφοποίησης για το DataLabel.

### getChart {#getChart}

| Name | Description |
| --- | --- |
| getChart () | Επιστρέφει το γράφημα. Μόνο-ανάγνωση IChart. |

**Επιστρέφει:**
[Chart](../chart)

---

### getFormat {#getFormat}

| Name | Description |
| --- | --- |
| getFormat () | Αντιπροσωπεύει τη μορφή της ετικέτας δεδομένων. Μόνο-ανάγνωση IFormat. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα αντιπροσωπεύει τη μορφή προεπιλογής για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. |

**Επιστρέφει:**
[Format](../format)

---

### getNumberFormat {#getNumberFormat}

| Name | Description |
| --- | --- |
| getNumberFormat () | Αντιπροσωπεύει το αλφαριθμητικό μορφοποίησης για το αντικείμενο DataLabels. Ανάγνωση/Εγγραφή String. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας NumberFormat για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Όταν αυτή η ιδιότητα ορίζεται με μια τιμή, η τιμή αυτή ορίζεται επίσης για την ιδιότητα NumberFormat για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" προκαλεί όλες τις DataLabels.get_Item(i).getNumberFormat() να ισούται με val). |

**Επιστρέφει:**
String

---

### getPosition {#getPosition}

| Name | Description |
| --- | --- |
| getPosition () | Αντιπροσωπεύει τη θέση της ετικέτας δεδομένων. Ανάγνωση/Εγγραφή LegendDataLabelPosition. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας Position για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Αντιπροσωπεύει τη θέση για τα αντικείμενα DataLabel. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα Position για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" προκαλεί όλα τα DataLabels.get_Item(i).getPosition() να είναι ίσα με val). |

**Επιστρέφει:**
int

---

### getSeparator {#getSeparator}

| Name | Description |
| --- | --- |
| getSeparator () | Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. Ανάγνωση/Εγγραφή String. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας Separator για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα Separator για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" προκαλεί όλα τα DataLabels.get_Item(i).getSeparator() να είναι ίσα με val). |

**Επιστρέφει:**
String

---

### getShowBubbleSize {#getShowBubbleSize}

| Name | Description |
| --- | --- |
| getShowBubbleSize () | Αντιπροσωπεύει τη συμπεριμότητα εμφάνισης της τιμής μεγέθους φυσαλίδας της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει τη τιμή μεγέθους φυσαλίδας. False την αποκρύπτει. Ανάγνωση/Εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowBubbleSize για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα ShowBubbleSize για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowBubbleSize() να είναι ίσα με val). |

**Επιστρέφει:**
boolean

---

### getShowCategoryName {#getShowCategoryName}

| Name | Description |
| --- | --- |
| getShowCategoryName () | Αντιπροσωπεύει τη συμπεριμότητα εμφάνισης του ονόματος κατηγορίας της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει το όνομα κατηγορίας για τις ετικέτες δεδομένων σε ένα γράφημα. False το αποκρύπτει. Ανάγνωση/Εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowCategoryName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα ShowCategoryName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowCategoryName() να είναι ίσα με val). |

**Επιστρέφει:**
boolean

---

### getShowLabelAsDataCallout {#getShowLabelAsDataCallout}

| Name | Description |
| --- | --- |
| getShowLabelAsDataCallout () | Καθορίζει αν η ετικέτα δεδομένων ενός συγκεκριμένου γραφήματος θα εμφανίζεται ως επεσιγραφία δεδομένων ή ως ετικέτα δεδομένων. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLabelAsDataCallout για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα ShowLabelAsDataCallout για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowLabelAsDataCallout() να είναι ίσα με val). |

**Επιστρέφει:**
boolean

---

### getShowLabelValueFromCell {#getShowLabelValueFromCell}

| Name | Description |
| --- | --- |
| getShowLabelValueFromCell () | Αντιπροσωπεύει τη συμπεριμότητα εμφάνισης της τιμής του κελιού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή του κελιού. False την αποκρύπτει. Ανάγνωση/Εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLabelValueFromCell για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα ShowLabelValueFromCell για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowLabelValueFromCell() να είναι ίσα με val). |

**Επιστρέφει:**
boolean

---

### getShowLeaderLines {#getShowLeaderLines}

| Name | Description |
| --- | --- |
| getShowLeaderLines () | Αντιπροσωπεύει τη συμπεριμότητα εμφάνισης των γραμμών οδηγού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει τις γραμμές οδηγού. False τις αποκρύπτει. Ανάγνωση/Εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLeaderLines για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα ShowLeaderLines για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowLeaderLines() να είναι ίσα με val). |

**Επιστρέφει:**
boolean

---

### getShowLegendKey {#getShowLegendKey}

| Name | Description |
| --- | --- |
| getShowLegendKey () | Αντιπροσωπεύει τη συμπεριμότητα εμφάνισης του κλειδιού υπομνήματος της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εάν το κλειδί υπομνήματος της ετικέτας δεδομένων είναι ορατό. Ανάγνωση/Εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLegendKey για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα ShowLegendKey για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowLegendKey() να είναι ίσα με val). |

**Επιστρέφει:**
boolean

---

### getShowPercentage {#getShowPercentage}

| Name | Description |
| --- | --- |
| getShowPercentage () | Αντιπροσωπεύει τη συμπεριμότητα εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False την αποκρύπτει. Ανάγνωση/Εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowPercentage για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα ShowPercentage για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowPercentage() να είναι ίσα με val). |

**Επιστρέφει:**
boolean

---

### getShowSeriesName {#getShowSeriesName}

| Name | Description |
| --- | --- |
| getShowSeriesName () | Επιστρέφει ή ορίζει ένα Boolean για να υποδεικνύει τη συμπεριμότητα εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα γράφημα. True εμφανίζει το όνομα σειράς. False το αποκρύπτει. Ανάγνωση/Εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowSeriesName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα ShowSeriesName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowSeriesName() να είναι ίσα με val). |

**Επιστρέφει:**
boolean

---

### getShowValue {#getShowValue}

| Name | Description |
| --- | --- |
| getShowValue () | Αντιπροσωπεύει τη συμπεριμότητα εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False την αποκρύπτει. Ανάγνωση/Εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowValue για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα ShowValue για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" προκαλεί όλα τα DataLabels.get_Item(i).getShowValue() να είναι ίσα με val). |

**Επιστρέφει:**
boolean

---

### getTextFormat {#getTextFormat}

| Name | Description |
| --- | --- |
| getTextFormat () | Επιστρέφει τη μορφή κειμένου του γραφήματος. Μόνο-ανάγνωση IChartTextFormat. |

**Επιστρέφει:**
[ChartTextFormat](../charttextformat)

---

### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

**Επιστρέφει:**
long

---

### isNumberFormatLinkedToSource {#isNumberFormatLinkedToSource}

| Name | Description |
| --- | --- |
| isNumberFormatLinkedToSource () | Ανάγνωση/Εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας IsNumberFormatLinkedToSource για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ιδιότητα IsNumberFormatLinkedToSource για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" προκαλεί όλα τα DataLabels.get_Item(i).isNumberFormatLinkedToSource() να είναι ίσα με val). |

**Επιστρέφει:**
boolean

---

### setNumberFormat {#setNumberFormat}

| Name | Description |
| --- | --- |
| setNumberFormat (String) | Αντιπροσωπεύει το αλφαριθμητικό μορφοποίησης για το αντικείμενο DataLabels. Ανάγνωση/Εγγραφή String. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας NumberFormat για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Όταν αυτή η ιδιότητα ορίζεται με μια τιμή, η τιμή αυτή ορίζεται επίσης για την ιδιότητα NumberFormat για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" προκαλεί όλες τις DataLabels.get_Item(i).getNumberFormat() να ισούται με val). |

**Επιστρέφει:**
void
### setNumberFormatLinkedToSource {#setNumberFormatLinkedToSource}

| Όνομα | Περιγραφή |
| --- | --- |
| setNumberFormatLinkedToSource (boolean) | Ανάγνωση/εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection από ετικέτες δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας IsNumberFormatLinkedToSource για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, ορίζει επίσης αυτήν την τιμή στην ιδιότητα IsNumberFormatLinkedToSource για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" προκαλεί ώστε όλες οι κλήσεις DataLabels.get_Item(i).isNumberFormatLinkedToSource() να είναι ίσες με val). |

**Επιστρέφει:**  
void


---


### setPosition {#setPosition}

| Όνομα | Περιγραφή |
| --- | --- |
| setPosition (int) | Αντιπροσωπεύει τη θέση της ετικέτας δεδομένων. Ανάγνωση/εγγραφή LegendDataLabelPosition. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection από ετικέτες δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας Position για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Αντιπροσωπεύει τη θέση για τα αντικείμενα DataLabel. Ορίζοντας αυτή την ιδιότητα με τιμή, ορίζει επίσης αυτήν την τιμή στην ιδιότητα Position για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" προκαλεί ώστε όλες οι κλήσεις DataLabels.get_Item(i).getPosition() να είναι ίσες με val). |

**Επιστρέφει:**  
void


---


### setSeparator {#setSeparator}

| Όνομα | Περιγραφή |
| --- | --- |
| setSeparator (String) | Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα διάγραμμα. Ανάγνωση/εγγραφή String. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection από ετικέτες δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας Separator για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, ορίζει επίσης αυτήν την τιμή στην ιδιότητα Separator για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" προκαλεί ώστε όλες οι κλήσεις DataLabels.get_Item(i).getSeparator() να είναι ίσες με val). |

**Επιστρέφει:**  
void


---


### setShowBubbleSize {#setShowBubbleSize}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowBubbleSize (boolean) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής μεγέθους φυσαλίδας της ετικέτας δεδομένων σε συγκεκριμένο διάγραμμα. True εμφανίζει την τιμή μεγέθους φυσαλίδας. False για απόκρυψη. Ανάγνωση/εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection από ετικέτες δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowBubbleSize για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, ορίζει επίσης αυτήν την τιμή στην ιδιότητα ShowBubbleSize για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" προκαλεί ώστε όλες οι κλήσεις DataLabels.get_Item(i).getShowBubbleSize() να είναι ίσες με val). |

**Επιστρέφει:**  
void


---


### setShowCategoryName {#setShowCategoryName}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowCategoryName (boolean) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας της ετικέτας δεδομένων σε συγκεκριμένο διάγραμμα. True για εμφάνιση του ονόματος κατηγορίας στις ετικέτες δεδομένων του διαγράμματος. False για απόκρυψη. Ανάγνωση/εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection από ετικέτες δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowCategoryName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, ορίζει επίσης αυτήν την τιμή στην ιδιότητα ShowCategoryName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" προκαλεί ώστε όλες οι κλήσεις DataLabels.get_Item(i).getShowCategoryName() να είναι ίσες με val). |

**Επιστρέφει:**  
void


---


### setShowLabelAsDataCallout {#setShowLabelAsDataCallout}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowLabelAsDataCallout (boolean) | Καθορίζει αν η ετικέτα δεδομένων του συγκεκριμένου διαγράμματος θα εμφανίζεται ως κλήση δεδομένων (data callout) ή ως ετικέτα δεδομένων. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection από ετικέτες δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLabelAsDataCallout για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, ορίζει επίσης αυτήν την τιμή στην ιδιότητα ShowLabelAsDataCallout για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" προκαλεί ώστε όλες οι κλήσεις DataLabels.get_Item(i).getShowLabelAsDataCallout() να είναι ίσες με val). |

**Επιστρέφει:**  
void


---


### setShowLabelValueFromCell {#setShowLabelValueFromCell}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowLabelValueFromCell (boolean) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής κελιού της ετικέτας δεδομένων σε συγκεκριμένο διάγραμμα. True εμφανίζει την τιμή του κελιού. False για απόκρυψη. Ανάγνωση/εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection από ετικέτες δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLabelValueFromCell για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, ορίζει επίσης αυτήν την τιμή στην ιδιότητα ShowLabelValueFromCell για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" προκαλεί ώστε όλες οι κλήσεις DataLabels.get_Item(i).getShowLabelValueFromCell() να είναι ίσες με val). |

**Επιστρέφει:**  
void


---


### setShowLeaderLines {#setShowLeaderLines}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowLeaderLines (boolean) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης των γραμμών οδηγού (leader lines) της ετικέτας δεδομένων σε συγκεκριμένο διάγραμμα. True εμφανίζει τις γραμμές οδηγού. False για απόκρυψη. Ανάγνωση/εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection από ετικέτες δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLeaderLines για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, ορίζει επίσης αυτήν την τιμή στην ιδιότητα ShowLeaderLines για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" προκαλεί ώστε όλες οι κλήσεις DataLabels.get_Item(i).getShowLeaderLines() να είναι ίσες με val). |

**Επιστρέφει:**  
void


---


### setShowLegendKey {#setShowLegendKey}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowLegendKey (boolean) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος της ετικέτας δεδομένων σε συγκεκριμένο διάγραμμα. True εάν το κλειδί υπομνήματος της ετικέτας δεδομένων είναι ορατό. Ανάγνωση/εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection από ετικέτες δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLegendKey για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, ορίζει επίσης αυτήν την τιμή στην ιδιότητα ShowLegendKey για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" προκαλεί ώστε όλες οι κλήσεις DataLabels.get_Item(i).getShowLegendKey() να είναι ίσες με val). |

**Επιστρέφει:**  
void


---


### setShowPercentage {#setShowPercentage}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowPercentage (boolean) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων σε συγκεκριμένο διάγραμμα. True εμφανίζει την τιμή ποσοστού. False για απόκρυψη. Ανάγνωση/εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection από ετικέτες δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowPercentage για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, ορίζει επίσης αυτήν την τιμή στην ιδιότητα ShowPercentage για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" προκαλεί ώστε όλες οι κλήσεις DataLabels.get_Item(i).getShowPercentage() να είναι ίσες με val). |

**Επιστρέφει:**  
void


---


### setShowSeriesName {#setShowSeriesName}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowSeriesName (boolean) | Επιστρέφει ή ορίζει ένα Boolean για να υποδείξει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα διάγραμμα. True για εμφάνιση του ονόματος σειράς. False για απόκρυψη. Ανάγνωση/εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection από ετικέτες δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowSeriesName για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, ορίζει επίσης αυτήν την τιμή στην ιδιότητα ShowSeriesName για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" προκαλεί ώστε όλες οι κλήσεις DataLabels.get_Item(i).getShowSeriesName() να είναι ίσες με val). |

**Επιστρέφει:**  
void


---


### setShowValue {#setShowValue}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowValue (boolean) | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής του δεδομένου της ετικέτας δεδομένων σε συγκεκριμένο διάγραμμα. True εμφανίζει την τιμή. False για απόκρυψη. Ανάγνωση/εγγραφή boolean. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection από ετικέτες δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowValue για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, ορίζει επίσης αυτήν την τιμή στην ιδιότητα ShowValue για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" προκαλεί ώστε όλες οι κλήσεις DataLabels.get_Item(i).getShowValue() να είναι ίσες με val). |

**Επιστρέφει:**  
void


---