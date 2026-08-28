---
title: DataLabel
second_title: Aspose.Sildes για PHP μέσω Java αναφοράς API
description: 
type: docs
url: /el/aspose.slides/datalabel/
---
## DataLabel κλάση

Αντιπροσωπεύει ετικέτες σειράς.

### DataLabel {#DataLabel}

| Όνομα | Περιγραφή |
| --- | --- |
| DataLabel([ChartDataPoint](../chartdatapoint)) | Δημιουργεί μια νέα παρουσία της κλάσης DataLabel. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| parentImmediate | [ChartDataPoint](../chartdatapoint) | Γονικό ChartDataPoint. |

**Επιστρέφει:**
DataLabel


---


### addTextFrameForOverriding {#addTextFrameForOverriding}

| Όνομα | Περιγραφή |
| --- | --- |
| addTextFrameForOverriding (String) | Αρχικοποιεί το TextFrameForOverriding με το κείμενο στην παράμετρο "text". Εάν το TextFrameForOverriding είναι ήδη αρχικοποιημένο, τότε απλώς αλλάζει το κείμενό του. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | String | Κείμενο για ένα νέο TextFrameForOverriding. |

**Επιστρέφει:**
[TextFrame](../textframe)


---


### getActualHeight {#getActualHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| getActualHeight () | Καθορίζει το πραγματικό ύψος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο για ανάγνωση float. |

**Επιστρέφει:**
float


---


### getActualLabelText {#getActualLabelText}

| Όνομα | Περιγραφή |
| --- | --- |
| getActualLabelText () | Επιστρέφει το πραγματικό κείμενο ετικέτας βάσει των ρυθμίσεων DataLabelFormat ή της τιμής TextFrameForOverriding.Text. |

**Επιστρέφει:**
String


---


### getActualWidth {#getActualWidth}

| Όνομα | Περιγραφή |
| --- | --- |
| getActualWidth () | Καθορίζει το πραγματικό πλάτος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο για ανάγνωση float. |

**Επισ returns:**
float


---


### getActualX {#getActualX}

| Όνομα | Περιγραφή |
| --- | --- |
| getActualX () | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο για ανάγνωση float. |

**Επιστρέφει:**
float


---


### getActualY {#getActualY}

| Όνομα | Περιγραφή |
| --- | --- |
| getActualY () | Καθορίζει το πραγματικό πάνω του στοιχείου διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο για ανάγνωση float. |

**Επιστρέφει:**
float


---


### getBottom {#getBottom}

| Όνομα | Περιγραφή |
| --- | --- |
| getBottom () | Κάτω. Μόνο για ανάγνωση float. |

**Επιστρέφει:**
float


---


### getChart {#getChart}

| Όνομα | Περιγραφή |
| --- | --- |
| getChart () | Επιστρέφει το γονικό διάγραμμα. Μόνο για ανάγνωση IChart. |

**Επιστρέφει:**
[Chart](../chart)


---


### getDataLabelFormat {#getDataLabelFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getDataLabelFormat () | Επιστρέφει τη μορφή ετικετών δεδομένων. Μόνο για ανάγνωση IDataLabelFormat. |

**Επιστρέφει:**
[DataLabelFormat](../datalabelformat)


---


### getHeight {#getHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| getHeight () | Επιστρέφει ή ορίζει το ύψος ενός τίτλου ως κλάσμα του ύψους του διαγράμματος. Ανάγνωση/εγγραφή float. |

**Επιστρέφει:**
float


---


### getPresentation {#getPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentation () | Επιστρέφει την γονική παρουσίαση ενός FillFormat. Μόνο για ανάγνωση IPresentation. |

**Επιστρέφει:**
[Presentation](../presentation)


---


### getRight {#getRight}

| Όνομα | Περιγραφή |
| --- | --- |
| getRight () | Δεξιά. Μόνο για ανάγνωση float. |

**Επιστρέφει:**
float


---


### getSlide {#getSlide}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlide () | Επιστρέφει τη γονική διαφάνεια ενός FillFormat. Μόνο για ανάγνωση BaseSlide. |

**Επιστρέφει:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getTextFormat {#getTextFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getTextFormat () | Επιστρέφει τη μορφή κειμένου. Μόνο για ανάγνωση IChartTextFormat. |

**Επιστρέφει:**
[ChartTextFormat](../charttextformat)


---


### getTextFrameForOverriding {#getTextFrameForOverriding}

| Όνομα | Περιγραφή |
| --- | --- |
| getTextFrameForOverriding () | Μπορεί να περιέχει εμπλουτισμένο μορφοποιημένο κείμενο. Εάν αυτή η ιδιότητα δεν είναι null, τότε αυτή η μορφοποιημένη τιμή κειμένου αντικαθιστά το αυτόματα δημιουργημένο κείμενο της ετικέτας δεδομένων. Το αυτόματα δημιουργημένο κείμενο της ετικέτας δεδομένων σημαίνει κείμενο που διαχειρίζεται από τις ιδιότητες ShowSeriesName, ShowValue, ... και μορφοποιείται με την ιδιότητα TextFormatManager.TextFormat. Μόνο για ανάγνωση ITextFrame. |

**Επιστρέφει:**
[TextFrame](../textframe)


---


### getValueFromCell {#getValueFromCell}

| Όνομα | Περιγραφή |
| --- | --- |
| getValueFromCell () | Αποθηκεύει ή ορίζει το κελί δεδομένων του βιβλίου εργασίας. Εφαρμόζεται εάν η ιδιότητα IDataLabelFormat.ShowLabelValueFromCell είναι true. |

**Επιστρέφει:**
[ChartDataCell](../chartdatacell)


---


### getWidth {#getWidth}

| Όνομα | Περιγραφή |
| --- | --- |
| getWidth () | Επιστρέφει ή ορίζει το πλάτος ενός τίτλου ως κλάσμα του πλάτους του διαγράμματος. Ανάγνωση/εγγραφή float. |

**Επιστρέφει:**
float


---


### getX {#getX}

| Όνομα | Περιγραφή |
| --- | --- |
| getX () | Επιστρέφει ή ορίζει την συντεταγμένη x ενός τίτλου ως κλάσμα του πλάτους του διαγράμματος. Ανάγνωση/εγγραφή float. |

**Επιστρέφει:**
float


---


### getY {#getY}

| Όνομα | Περιγραφή |
| --- | --- |
| getY () | Επιστρέφει ή ορίζει την συντεταγμένη y ενός τίτλου ως κλάσμα του ύψους του διαγράμματος. Ανάγνωση/εγγραφή float. |

**Επιστρέφει:**
float


---


### hide {#hide}

| Όνομα | Περιγραφή |
| --- | --- |
| hide () | Κάνει την ετικέτα δεδομένων κρυφή θέτοντας όλα τα Show*-flags (ShowValue, ...) σε κατάσταση false. Το IsVisible θα είναι false μετά από αυτό. Εάν η ετικέτα δεδομένων δεν είναι ορατή (IsVisible είναι false) μπορείτε να την κάνετε ορατή ορίζοντας τα Show*-flags (ShowValue, ...) σε κατάσταση true. |

**Επιστρέφει:**
void


---


### isVisible {#isVisible}

| Όνομα | Περιγραφή |
| --- | --- |
| isVisible () | False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή (και έτσι όλα τα Show*-flags (ShowValue, ...) είναι false). Μόνο για ανάγνωση boolean. Εάν η ετικέτα δεδομένων είναι ορατή, μπορείτε να τη κρύψετε με τη μέθοδο Hide(). Αλλά εάν η ετικέτα δεδομένων δεν είναι ορατή (IsVisible είναι false), μπορείτε να τη κάνετε ορατή ορίζοντας τα Show*-flags (ShowValue, ...) σε κατάσταση true. |

**Επισ returns:**
boolean


---


### setHeight {#setHeight}

| Όνομα | Περιγραφή |
| --- | --- |
| setHeight (float) | Επιστρέφει ή ορίζει το ύψος ενός τίτλου ως κλάσμα του ύψους του διαγράμματος. Ανάγνωση/εγγραφή float. |

**Επιστρέφει:**
void


---


### setValueFromCell {#setValueFromCell}

| Όνομα | Περιγραφή |
| --- | --- |
| setValueFromCell ([ChartDataCell](../chartdatacell)) | Αποθηκεύει ή ορίζει το κελί δεδομένων του βιβλίου εργασίας. Εφαρμόζεται εάν η ιδιότητα IDataLabelFormat.ShowLabelValueFromCell είναι true. |

**Επιστρέφει:**
void


---


### setWidth {#setWidth}

| Όνομα | Περιγραφή |
| --- | --- |
| setWidth (float) | Επιστρέφει ή ορίζει το πλάτος ενός τίτλου ως κλάσμα του πλάτους του διαγράμματος. Ανάγνωση/εγγραφή float. |

**Επισ returns:**
void


---


### setX {#setX}

| Όνομα | Περιγραφή |
| --- | --- |
| setX (float) | Επιστρέφει ή ορίζει την συντεταγμένη x ενός τίτλου ως κλάσμα του πλάτους του διαγράμματος. Ανάγνωση/εγγραφή float. |

**Επισ returns:**
void


---


### setY {#setY}

| Όνομα | Περιγραφή |
| --- | --- |
| setY (float) | Επιστρέφει ή ορίζει την συντεταγμένη y ενός τίτλου ως κλάσμα του ύψους του διαγράμματος. Ανάγνωση/εγγραφή float. |

**Επισ returns:**
void


---  