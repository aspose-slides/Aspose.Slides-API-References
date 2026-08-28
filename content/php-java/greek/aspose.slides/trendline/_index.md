---
title: Trendline
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/trendline/
---
## Trendline κλάση

 Η κλάση αντιπροσωπεύει τη γραμμή τάσης της σειράς διαγράμματος

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

### getBackward {#getBackward}

| Όνομα | Περιγραφή |
| --- | --- |
| getBackward () | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης επεκτείνεται πριν από τα δεδομένα της σειράς που ακολουθείται. Σε διαγράμματα διασποράς και μη-διασποράς, η τιμή πρέπει να είναι οποιαδήποτε μη αρνητική τιμή. Ανάγνωση/Εγγραφή double. |

**Επιστρέφει:**
double

---

### getChart {#getChart}

| Όνομα | Περιγραφή |
| --- | --- |
| getChart () | Επιστρέφει το γονικό διάγραμμα. Μόνο για ανάγνωση IChart. |

**Επιστρέφει:**
[Chart](../chart)

---

### getDisplayEquation {#getDisplayEquation}

| Όνομα | Περιγραφή |
| --- | --- |
| getDisplayEquation () | Καθορίζει ότι η εξίσωση για τη γραμμή τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την τιμή Rsquared). Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
boolean

---

### getDisplayRSquaredValue {#getDisplayRSquaredValue}

| Όνομα | Περιγραφή |
| --- | --- |
| getDisplayRSquaredValue () | Καθορίζει ότι η τιμή R-squared της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την εξίσωση). Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
boolean

---

### getFormat {#getFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| getFormat () | Αντιπροσωπεύει τη μορφή της γραμμής τάσης. Ανάγνωση/Εγγραφή IFormat. |

**Επιστρέφει:**
[Format](../format)

---

### getForward {#getForward}

| Όνομα | Περιγραφή |
| --- | --- |
| getForward () | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης επεκτείνεται μετά τα δεδομένα της σειράς που ακολουθείται. Σε διαγράμματα διασποράς και μη-διασποράς, η τιμή πρέπει να είναι οποιαδήποτε μη-αρνητική τιμή. Ανάγνωση/Εγγραφή double. |

**Επιστρέφει:**
double

---

### getIntercept {#getIntercept}

| Όνομα | Περιγραφή |
| --- | --- |
| getIntercept () | Καθορίζει την τιμή όπου η γραμμή τάσης θα διασχίσει τον άξονα y. Η ιδιότητα υποστηρίζεται μόνο όταν ο τύπος γραμμής τάσης είναι exp, linear ή poly. Ανάγνωση/Εγγραφή double. |

**Επιστρέφει:**
double

---

### getOrder {#getOrder}

| Όνομα | Περιγραφή |
| --- | --- |
| getOrder () | Καθορίζει τη σειρά της πολυωνυμικής γραμμής τάσης. Παραβλέπεται για άλλους τύπους γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 6. Ανάγνωση/Εγγραφή byte. |

**Επιστρέφει:**
byte

---

### getPeriod {#getPeriod}

| Όνομα | Περιγραφή |
| --- | --- |
| getPeriod () | Καθορίζει την περίοδο της γραμμής τάσης για μια γραμμή τάσης κινητού μέσου. Παραβλέπεται για άλλες παραλλαγές γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 255. Ανάγνωση/Εγγραφή byte. |

**Επιστρέφει:**
byte

---

### getPresentation {#getPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentation () | Επιστρέφει την γονική παρουσίαση ενός FillFormat. Μόνο για ανάγνωση IPresentation. |

**Επιστρέφει:**
[Presentation](../presentation)

---

### getRelatedLegendEntry {#getRelatedLegendEntry}

| Όνομα | Περιγραφή |
| --- | --- |
| getRelatedLegendEntry () | Αντιπροσωπεύει την καταχώριση υπομνήματος που σχετίζεται με αυτή τη γραμμή τάσης. Μόνο για ανάγνωση ILegendEntryProperties. |

**Επιστρέφει:**
[LegendEntryProperties](../legendentryproperties)

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
| getTextFormat () | Επιστρέφει μορφή κειμένου. Μόνο για ανάγνωση IChartTextFormat. |

**Επιστρέφει:**
[ChartTextFormat](../charttextformat)

---

### getTextFrameForOverriding {#getTextFrameForOverriding}

| Όνομα | Περιγραφή |
| --- | --- |
| getTextFrameForOverriding () | Μπορεί να περιέχει κειμένο με πλούσια μορφοποίηση. Εάν αυτή η ιδιότητα δεν είναι κενή, τότε αυτή η τιμή κειμένου με μορφοποίηση αντικαθιστά το αυτόματα παραγόμενο κείμενο ετικέτας δεδομένων. Το αυτόματα παραγόμενο κείμενο ετικέτας δεδομένων σημαίνει κείμενο που διαχειρίζεται οι ιδιότητες ShowSeriesName, ShowValue, … και μορφοποιείται με την ιδιότητα TextFormatManager.TextFormat. Μόνο για ανάγνωση ITextFrame. |

**Επιστρέφει:**
[TextFrame](../textframe)

---

### getTrendlineName {#getTrendlineName}

| Όνομα | Περιγραφή |
| --- | --- |
| getTrendlineName () | Λαμβάνει ή ορίζει το όνομα της γραμμής τάσης. Ανάγνωση/Εγγραφή String. |

**Επιστρέφει:**
String

---

### getTrendlineType {#getTrendlineType}

| Όνομα | Περιγραφή |
| --- | --- |
| getTrendlineType () | Λαμβάνει ή ορίζει τον τύπο της γραμμής τάσης. Ανάγνωση/Εγγραφή TrendlineType. |

**Επιστρέφει:**
int

---

### setBackward {#setBackward}

| Όνομα | Περιγραφή |
| --- | --- |
| setBackward (double) | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης επεκτείνεται πριν από τα δεδομένα της σειράς που ακολουθείται. Σε διαγράμματα διασποράς και μη-διασποράς, η τιμή πρέπει να είναι οποιαδήποτε μη αρνητική τιμή. Ανάγνωση/Εγγραφή double. |

**Επιστρέφει:**
void

---

### setDisplayEquation {#setDisplayEquation}

| Όνομα | Περιγραφή |
| --- | --- |
| setDisplayEquation (boolean) | Καθορίζει ότι η εξίσωση για τη γραμμή τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την τιμή Rsquared). Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
void

---

### setDisplayRSquaredValue {#setDisplayRSquaredValue}

| Όνομα | Περιγραφή |
| --- | --- |
| setDisplayRSquaredValue (boolean) | Καθορίζει ότι η τιμή R-squared της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την εξίσωση). Ανάγνωση/Εγγραφή boolean. |

**Επιστρέφει:**
void

---

### setFormat {#setFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| setFormat ([Format](../format)) | Αντιπροσωπεύει τη μορφή της γραμμής τάσης. Ανάγνωση/Εγγραφή IFormat. |

**Επιστρέφει:**
void

---

### setForward {#setForward}

| Όνομα | Περιγραφή |
| --- | --- |
| setForward (double) | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης επεκτείνεται μετά τα δεδομένα της σειράς που ακολουθείται. Σε διαγράμματα διασποράς και μη-διασποράς, η τιμή πρέπει να είναι οποιαδήποτε μη-αρνητική τιμή. Ανάγνωση/Εγγραφή double. |

**Επιστρέφει:**
void

---

### setIntercept {#setIntercept}

| Όνομα | Περιγραφή |
| --- | --- |
| setIntercept (double) | Καθορίζει την τιμή όπου η γραμμή τάσης θα διασχίσει τον άξονα y. Η ιδιότητα υποστηρίζεται μόνο όταν ο τύπος γραμμής τάσης είναι exp, linear ή poly. Ανάγνωση/Εγγραφή double. |

**Επιστρέφει:**
void

---

### setOrder {#setOrder}

| Όνομα | Περιγραφή |
| --- | --- |
| setOrder (byte) | Καθορίζει τη σειρά της πολυωνυμικής γραμμής τάσης. Παραβλέπεται για άλλους τύπους γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 6. Ανάγνωση/Εγγραφή byte. |

**Επιστρέφει:**
void

---

### setPeriod {#setPeriod}

| Όνομα | Περιγραφή |
| --- | --- |
| setPeriod (byte) | Καθορίζει την περίοδο της γραμμής τάσης για μια γραμμή τάσης κινητού μέσου. Παραβλέπεται για άλλες παραλλαγές γραμμής τάσης. Η τιμή πρέπει να είναι μεταξύ 2 και 255. Ανάγνωση/Εγγραφή byte. |

**Επιστρέφει:**
void

---

### setTrendlineName {#setTrendlineName}

| Όνομα | Περιγραφή |
| --- | --- |
| setTrendlineName (String) | Λαμβάνει ή ορίζει το όνομα της γραμμής τάσης. Ανάγνωση/Εγγραφή String. |

**Επιστρέφει:**
void

---

### setTrendlineType {#setTrendlineType}

| Όνομα | Περιγραφή |
| --- | --- |
| setTrendlineType (int) | Λαμβάνει ή ορίζει τον τύπο της γραμμής τάσης. Ανάγνωση/Εγγραφή TrendlineType. |

**Επιστρέφει:**
void

---