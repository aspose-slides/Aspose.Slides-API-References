---
title: DataLabelCollection
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/datalabelcollection/
---
## DataLabelCollection κλάση

Αντιπροσωπεύει τις ετικέτες μιας σειράς.

### getChart {#getChart}

| Όνομα | Περιγραφή |
| --- | --- |
| getChart () | Επιστρέφει το γονικό διάγραμμα. Μόνο για ανάγνωση IChart. |

 **Επιστρέφει:**
[Chart](../chart)


---


### getCount {#getCount}

| Όνομα | Περιγραφή |
| --- | --- |
| getCount () | Αποκτά τον αριθμό όλων των ετικετών δεδομένων στη συλλογή. Μόνο για ανάγνωση int. |

 **Επιστρέφει:**
int


---


### getCountOfVisibleDataLabels {#getCountOfVisibleDataLabels}

| Όνομα | Περιγραφή |
| --- | --- |
| getCountOfVisibleDataLabels () | Αποκτά τον αριθμό των ορατών ετικετών δεδομένων στη συλλογή. Μόνο για ανάγνωση int. |

 **Επιστρέφει:**
int


---


### getDefaultDataLabelFormat {#getDefaultDataLabelFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getDefaultDataLabelFormat () | Αποκτά την προεπιλεγμένη μορφή ετικέτας δεδομένων. Μόνο για ανάγνωση IDataLabelFormat. |

 **Επιστρέφει:**
[DataLabelFormat](../datalabelformat)


---


### getLeaderLinesFormat {#getLeaderLinesFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getLeaderLinesFormat () | Αντιπροσωπεύει τη μορφή γραμμών οδηγού ετικετών δεδομένων. Μόνο για ανάγνωση IChartLinesFormat. |

 **Επιστρέφει:**
[ChartLinesFormat](../chartlinesformat)


---


### getParentSeries {#getParentSeries}

| Όνομα | Περιγραφή |
| --- | --- |
| getParentSeries () | Αποκτά τη γονική σειρά. Μόνο για ανάγνωση IChartSeries. |

 **Επιστρέφει:**
[ChartSeries](../chartseries)


---


### getPresentation {#getPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentation () | Επιστρέφει την γονική παρουσίαση ενός FillFormat. Μόνο για ανάγνωση IPresentation. |

 **Επιστρέφει:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Όνομα | Περιγραφή |
| --- | --- |
| getSlide () | Επιστρέφει τη γονική διαφάνεια ενός FillFormat. Μόνο για ανάγνωση BaseSlide. |

 **Επιστρέφει:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### get_Item {#get_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| get_Item (int) | Αποκτά την ετικέτα δεδομένου για το σημείο δεδομένων με το συγκεκριμένο δείκτη. Εναλλακτικός τρόπος πρόσβασης στην ετικέτα δεδομένων είναι: - series.getDataPoints().get_Item(i).getLabel() - διαχείριση ιδιοτήτων ετικέτας. |

 **Επιστρέφει:**
[DataLabel](../datalabel)


---


### hide {#hide}

| Όνομα | Περιγραφή |
| --- | --- |
| hide () | Κάνει την ετικέτα δεδομένου κρυφή από προεπιλογή ορίζοντας όλα τα Show*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση false. Το IsVisible θα είναι false μετά από αυτό. Εάν η ετικέτα δεδομένου δεν είναι ορατή από προεπιλογή (IsVisible είναι false) μπορείτε να την κάνετε «ορατή από προεπιλογή» ορίζοντας τα Show*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση true. |

 **Επιστρέφει:**
void


---


### indexOf {#indexOf}

| Όνομα | Περιγραφή |
| --- | --- |
| indexOf ([DataLabel](../datalabel)) | Επιστρέφει έναν δείκτη της καθορισμένης DataLabel στη συλλογή. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DataLabel](../datalabel) | DataLabel για εύρεση. |

 **Επιστρέφει:**
int


---


### isVisible {#isVisible}

| Όνομα | Περιγραφή |
| --- | --- |
| isVisible () | False σημαίνει ότι η ετικέτα δεδομένου δεν είναι ορατή από προεπιλογή (και έτσι όλα τα Show*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat είναι false). Μόνο για ανάγνωση boolean. Εάν η ετικέτα δεδομένου είναι ορατή από προεπιλογή, μπορείτε να την κάνετε κρυφή από προεπιλογή με τη μέθοδο Hide(). Αλλά εάν η ετικέτα δεδομένου δεν είναι ορατή από προεπιλογή (IsVisible είναι false) μπορείτε να την κάνετε «ορατή από προεπιλογή» ορίζοντας τα Show*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση true. |

 **Επιστρέφει:**
boolean


---


### iterator {#iterator}

| Όνομα | Περιγραφή |
| --- | --- |
| iterator () | Επιστρέφει έναν απαριθμητή που διασχίζει τη συλλογή. |

 **Επιστρέφει:**



---


### iteratorJava {#iteratorJava}

| Όνομα | Περιγραφή |
| --- | --- |
| iteratorJava () | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |

 **Επιστρέφει:**



---