---
title: ErrorBarsFormat
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/errorbarsformat/
---
## ErrorBarsFormat κλάση

Παριστά τις γραμμές σφάλματος των σειρών γραφημάτων. Προσαρμοσμένες τιμές ErrorBars βρίσκονται στο IChartDataPointCollection (στην ιδιότητα ( IChartDataPoint#getErrorBarsCustomValues)).

### getChart {#getChart}

| Όνομα | Περιγραφή |
| --- | --- |
| getChart () | Επιστρέφει το γονικό γράφημα. Μόνο-ανάγνωση IChart. |

 **Επιστρέφει:**
[Chart](../chart)


---


### getFormat {#getFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getFormat () | Παριστά τη μορφή των γραμμών σφάλματος. Ανάγνωση/εγγραφή IFormat. |

 **Επιστρέφει:**
[Format](../format)


---


### getPresentation {#getPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentation () | Επιστρέφει την γονική παρουσίαση ενός FillFormat. Μόνο-ανάγνωση IPresentation. |

 **Επιστρέφει:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlide () | Επιστρέφει την γονική διαφάνεια ενός FillFormat. Μόνο-ανάγνωση BaseSlide. |

 **Επιστρέφει:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getType {#getType}

| Όνομα | Περιγραφή |
| --- | --- |
| getType () | Λαμβάνει ή ορίζει τον τύπο των γραμμών σφάλματος. Ανάγνωση/εγγραφή ErrorBarType. |

 **Επιστρέφει:**
int


---


### getValue {#getValue}

| Όνομα | Περιγραφή |
| --- | --- |
| getValue () | Λαμβάνει ή ορίζει την τιμή που χρησιμοποιείται με τύπους τιμών Fixed, Percentage και StandardDeviation για τον καθορισμό του μήκους των γραμμών σφάλματος. Σε οποιαδήποτε άλλη περίπτωση θα επιστρέψει NaN. Ανάγνωση/εγγραφή float. |

 **Επιστρέφει:**
float


---


### getValueType {#getValueType}

| Όνομα | Περιγραφή |
| --- | --- |
| getValueType () | Παριστά τους πιθανούς τρόπους καθορισμού του μήκους των γραμμών σφάλματος. Στην περίπτωση προσαρμοσμένου τύπου τιμής για να ορίσετε τιμή, χρησιμοποιήστε την ιδιότητα ( IChartDataPoint#getErrorBarsCustomValues) του συγκεκριμένου σημείου δεδομένων στη συλλογή DataPoints της σειράς. Στην περίπτωση τύπων Fixed, Percentage ή StandardDeviation χρησιμοποιήστε την ιδιότητα Value για να ορίσετε την τιμή. Ανάγνωση/εγγραφή ErrorBarValueType. |

 **Επιστρέφει:**
int


---


### hasEndCap {#hasEndCap}

| Όνομα | Περιγραφή |
| --- | --- |
| hasEndCap () | Καθορίζει ότι δεν σχεδιάζεται τέλος άκρου στις γραμμές σφάλματος. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### isVisible {#isVisible}

| Όνομα | Περιγραφή |
| --- | --- |
| isVisible () | Λαμβάνει ή ορίζει την ορατότητα των γραμμών σφάλματος. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### setEndCap {#setEndCap}

| Όνομα | Περιγραφή |
| --- | --- |
| setEndCap (boolean) | Καθορίζει ότι δεν σχεδιάζεται τέλος άκρου στις γραμμές σφάλματος. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
void


---


### setFormat {#setFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| setFormat ([Format](../format)) | Παριστά τη μορφή των γραμμών σφάλματος. Ανάγνωση/εγγραφή IFormat. |

 **Επιστρέφει:**
void


---


### setType {#setType}

| Όνομα | Περιγραφή |
| --- | --- |
| setType (int) | Λαμβάνει ή ορίζει τον τύπο των γραμμών σφάλματος. Ανάγνωση/εγγραφή ErrorBarType. |

 **Επιστρέφει:**
void


---


### setValue {#setValue}

| Όνομα | Περιγραφή |
| --- | --- |
| setValue (float) | Λαμβάνει ή ορίζει την τιμή που χρησιμοποιείται με τύπους τιμών Fixed, Percentage και StandardDeviation για τον καθορισμό του μήκους των γραμμών σφάλματος. Σε οποιαδήποτε άλλη περίπτωση θα επιστρέψει NaN. Ανάγνωση/εγγραφή float. |

 **Επιστρέφει:**
void


---


### setValueType {#setValueType}

| Όνομα | Περιγραφή |
| --- | --- |
| setValueType (int) | Παριστά τους πιθανούς τρόπους καθορισμού του μήκους των γραμμών σφάλματος. Στην περίπτωση προσαρμοσμένου τύπου τιμής για να ορίσετε τιμή, χρησιμοποιήστε την ιδιότητα ( IChartDataPoint#getErrorBarsCustomValues) του συγκεκριμένου σημείου δεδομένων στη συλλογή DataPoints της σειράς. Στην περίπτωση τύπων Fixed, Percentage ή StandardDeviation χρησιμοποιήστε την ιδιότητα Value για να ορίσετε την τιμή. Ανάγνωση/εγγραφή ErrorBarValueType. |

 **Επιστρέφει:**
void


---


### setVisible {#setVisible}

| Όνομα | Περιγραφή |
| --- | --- |
| setVisible (boolean) | Λαμβάνει ή ορίζει την ορατότητα των γραμμών σφάλματος. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
void


---