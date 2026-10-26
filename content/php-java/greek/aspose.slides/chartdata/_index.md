---
title: ChartData
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs
url: /el/aspose.slides/chartdata/
---
## ChartData κλάση

 Αναπαριστά δεδομένα που χρησιμοποιούνται για τη σχεδίαση ενός γραφήματος.
 
### getCategories {#getCategories}

| Όνομα | Περιγραφή |
| --- | --- |
| getCategories () | Λαμβάνει τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες εάν η ιδιότητα #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) είναι ψευδής). Μόνο ανάγνωση IChartCategoryCollection. Εάν η ιδιότητα #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) είναι ψευδής τότε η ιδιότητα ( #getSecondaryCategories) επιστρέφει null και τα δεδομένα σε αυτήν την ιδιότητα #getCategories χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. Εάν η ιδιότητα #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) είναι αληθής, τότε τα δεδομένα στην ιδιότητα ( #getSecondaryCategories) χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα σε αυτήν την ιδιότητα #getCategories χρησιμοποιούνται για κύριες σειρές. |

 **Επιστρέφει:**
[ChartCategoryCollection](../chartcategorycollection)


---


### getChartDataWorkbook {#getChartDataWorkbook}

| Όνομα | Περιγραφή |
| --- | --- |
| getChartDataWorkbook () | Λαμβάνει το εργοστάσιο κελιών για τη δημιουργία κελιών που χρησιμοποιούνται για σειρές ή κατηγορίες γραφήματος. Μόνο ανάγνωση IChartDataWorkbook. |

 **Επιστρέφει:**
[ChartDataWorkbook](../chartdataworkbook)

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
 | InvalidOperationException | Ρίχνεται όταν η μορφή του βιβλίου εργασίας δεν υποστηρίζεται. |


---


### getDataSourceType {#getDataSourceType}

| Όνομα | Περιγραφή |
| --- | --- |
| getDataSourceType () | Αναπαριστά τη διαδρομή εξωτερικού βιβλίου εργασίας εάν η πηγή δεδομένων είναι εξωτερική, αλλιώς null |

 **Επιστρέφει:**
int


---


### getEmbeddedWorkbookType {#getEmbeddedWorkbookType}

| Όνομα | Περιγραφή |
| --- | --- |
| getEmbeddedWorkbookType () | Λαμβάνει τον τύπο του ενσωματωμένου βιβλίου εργασίας. Επιστρέφει WorkbookType#NotDefined εάν DataSourceType( #getDataSourceType) είναι ChartDataSourceType#ExternalWorkbook. Μόνο ανάγνωση WorkbookType. |

 **Επιστρέφει:**
int


---


### getExternalWorkbookPath {#getExternalWorkbookPath}

| Όνομα | Περιγραφή |
| --- | --- |
| getExternalWorkbookPath () | Αναπαριστά την πηγή δεδομένων του γραφήματος |

 **Επιστρέφει:**
String


---


### getRange {#getRange}

| Όνομα | Περιγραφή |
| --- | --- |
| getRange () | Λαμβάνει την περιοχή δεδομένων του γραφήματος. |

 **Επιστρέφει:**
String

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
 | InvalidOperationException | Το γράφημα δεν χρησιμοποιεί βιβλίο εργασίας ως πηγή δεδομένων |


---


### getSecondaryCategories {#getSecondaryCategories}

| Όνομα | Περιγραφή |
| --- | --- |
| getSecondaryCategories () | Λαμβάνει τις δευτερεύουσες κατηγορίες εάν η ιδιότητα #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) είναι αληθής. Μόνο ανάγνωση IChartCategoryCollection. Εάν η ιδιότητα #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) είναι ψευδής τότε αυτή η ( #getSecondaryCategories) ιδιότητα επιστρέφει null και τα δεδομένα στην ιδιότητα #getCategories χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. Εάν η ιδιότητα #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) είναι αληθής, τότε τα δεδομένα σε αυτήν την ιδιότητα #getSecondaryCategories χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα #getCategories χρησιμοποιούνται για κύριες σειρές. |

 **Επιστρέφει:**
[ChartCategoryCollection](../chartcategorycollection)


---


### getSeries {#getSeries}

| Όνομα | Περιγραφή |
| --- | --- |
| getSeries () | Λαμβάνει τις σειρές. Μόνο ανάγνωση IChartSeriesCollection. |

 **Επιστρέφει:**
[ChartSeriesCollection](../chartseriescollection)


---


### getSeriesGroups {#getSeriesGroups}

| Όνομα | Περιγραφή |
| --- | --- |
| getSeriesGroups () | Λαμβάνει τις ομάδες σειρών. Μόνο ανάγνωση IChartSeriesGroupCollection. 1) Κάθε ομάδα σειρών περιέχει σειρές με συνδυάσιμους τύπους. Οι ομάδες συνδυάσιμων τύπων σειρών ορίζονται και περιγράφονται με το enum CombinableSeriesTypesGroup. Επίσης, κάθε ομάδα σειρών περιέχει σειρές που σχεδιάζονται είτε σε κύριους άξονες είτε σε δευτερεύοντες άξονες (όχι και τα δύο σε μία ομάδα). Έτσι, η αρχή της ομαδοποίησης σειρών είναι η ομαδοποίηση κατά τις παραπάνω ομάδες τύπων και κατά τύπο σχεδίασης κύριου/δευτερεύοντος. 2) Μια ομάδα σειρών περιέχει κάποιες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»). Οι «ιδιότητες ομάδας σειρών» στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή. Κάθε μία από τις «ιδιότητες ομάδας σειρών» μπορεί να έχει μια μόνο-ανάγνωση προβολή στην κλάση ChartSeries. |

 **Επιστρέφει:**
ChartSeriesGroupCollection


---


### getUseSecondaryCategories {#getUseSecondaryCategories}

| Όνομα | Περιγραφή |
| --- | --- |
| getUseSecondaryCategories () | Εάν είναι ψευδής, τότε η ιδιότητα #getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα #getCategories χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. Εάν είναι αληθής, τότε τα δεδομένα στην ιδιότητα #getSecondaryCategories χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα #getCategories χρησιμοποιούνται για κύριες σειρές. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### readWorkbookStream {#readWorkbookStream}

| Όνομα | Περιγραφή |
| --- | --- |
| readWorkbookStream () | Γράφει το εσωτερικά περι-contained Excel workbook σε μια ροή μνήμης. |

 **Επιστρέφει:**
byte


---


### setExternalWorkbook {#setExternalWorkbook}

| Όνομα | Περιγραφή |
| --- | --- |
| setExternalWorkbook (String) | Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το γράφημα. Τα δεδομένα του γραφήματος θα ενημερωθούν από το στόχο βιβλίου εργασίας. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| workbookPath | String | Διαδρομή προς το βιβλίο εργασίας στόχο |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
 | InvalidOperationException | Το εξωτερικό βιβλίο εργασίας δεν είναι διαθέσιμο ή δεν μπορεί να φορτωθεί. |


---


### setExternalWorkbook {#setExternalWorkbook}

| Όνομα | Περιγραφή |
| --- | --- |
| setExternalWorkbook (String, boolean) | Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το γράφημα. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| workbookPath | String | Διαδρομή προς το βιβλίο εργασίας στόχο |
| updateChartData | boolean | Εάν η τιμή είναι ψευδής, ενημερώνεται μόνο η διαδρομή του βιβλίου εργασίας. Τα δεδομένα του γραφήματος δεν θα φορτωθούν και δεν θα ενημερωθούν από το βιβλίο εργασίας στόχο. Μπορεί να χρησιμοποιηθεί όταν το βιβλίο εργασίας στόχο δεν υπάρχει ή δεν είναι διαθέσιμο. Εάν η τιμή είναι αληθής, τα δεδομένα του γραφήματος θα ενημερωθούν από το βιβλίο εργασίας στόχο. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
 | InvalidOperationException | Το εξωτερικό βιβλίο εργασίας δεν είναι διαθέσιμο ή δεν μπορεί να φορτωθεί. |


---


### setRange {#setRange}

| Όνομα | Περιγραφή |
| --- | --- |
| setRange (String) | Ορίζει την περιοχή δεδομένων του γραφήματος. Οι σειρές και οι κατηγορίες θα ενημερωθούν βάσει της νέας περιοχής δεδομένων. Εάν ο αριθμός των σειρών στην περιοχή δεδομένων είναι μεγαλύτερος από τον αριθμό των σειρών στα δεδομένα του γραφήματος, τότε επιπλέον σειρές με τον ίδιο τύπο με την τελευταία σειρά στην τρέχουσα συλλογή θα προστεθούν στο τέλος της συλλογής. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| formula | String | Τύπος περιοχής δεδομένων κελιών. Π.χ.: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
 | ArgumentException | Η φόρμουλα έχει εσφαλμένη μορφή. |


---


### setUseSecondaryCategories {#setUseSecondaryCategories}

| Όνομα | Περιγραφή |
| --- | --- |
| setUseSecondaryCategories (boolean) | Εάν είναι ψευδής, τότε η ιδιότητα #getSecondaryCategories επιστρέφει null και τα δεδομένα στην ιδιότητα #getCategories χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. Εάν είναι αληθής, τότε τα δεδομένα στην ιδιότητα #getSecondaryCategories χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα στην ιδιότητα #getCategories χρησιμοποιούνται για κύριες σειρές. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
void


---


### switchRowColumn {#switchRowColumn}

| Όνομα | Περιγραφή |
| --- | --- |
| switchRowColumn () | Αντιστρέφει τα δεδομένα πάνω στον άξονα. Τα δεδομένα που σχεδιάζονται στον άξονα X θα μετακινηθούν στον άξονα Y και αντίστροφα. |

 **Επιστρέφει:**
void


---


### writeWorkbookStream {#writeWorkbookStream}

| Όνομα | Περιγραφή |
| --- | --- |
| writeWorkbookStream (byte[]) | Αρχικοποιεί το εσωτερικά περι-contained Excel workbook με την τιμή που καθορίστηκε από τον χρήστη. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| ms | byte[] | Η ροή που παρέχεται από τον χρήστη, η οποία περιέχει ολόκληρο το Excel workbook. |

 **Επιστρέφει:**
void


---  