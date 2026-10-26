---
title: TextFrameFormat
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/textframeformat/
---
## TextFrameFormat κλάση

  Περιέχει τις ιδιότητες formatTextFrameFormatting του TextFrame.
 
### TextFrameFormat {#TextFrameFormat}

| Name | Description |
| --- | --- |
| TextFrameFormat() | Αρχικοποιεί μια νέα实例 της κλάση TextFrameFormat. |

 **Επιστρέφει:**
TextFrameFormat


---


### getAnchoringType {#getAnchoringType}

| Name | Description |
| --- | --- |
| getAnchoringType () | Επιστρέφει ή ορίζει το κάθετο αγκίστρωμα του κειμένου σε ένα TextFrame. Ανάγνωση/εγγραφή TextAnchorType. |

 **Επιστρέφει:**
byte


---


### getAutofitType {#getAutofitType}

| Name | Description |
| --- | --- |
| getAutofitType () | Επιστρέφει ή ορίζει τη λειτουργία αυτόματης προσαρμογής κειμένου. Ανάγνωση/εγγραφή TextAutofitType. |

 **Επιστρέφει:**
byte


---


### getCenterText {#getCenterText}

| Name | Description |
| --- | --- |
| getCenterText () | Εάν NullableBool.True τότε το κείμενο πρέπει να κεντραριστεί οριζόντια στο κουτί. Ανάγνωση/εγγραφή NullableBool. |

 **Επιστρέφει:**
byte


---


### getColumnCount {#getColumnCount}

| Name | Description |
| --- | --- |
| getColumnCount () | Επιστρέφει ή ορίζει τον αριθμό των στηλών στην περιοχή κειμένου. Η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί σε μηδέν. Η τιμή 0 σημαίνει ακαθόριστη τιμή. Ανάγνωση/εγγραφή int. |

 **Επιστρέφει:**
int


---


### getColumnSpacing {#getColumnSpacing}

| Name | Description |
| --- | --- |
| getColumnSpacing () | Επιστρέφει ή ορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε points). Αυτό ισχύει μόνο όταν υπάρχει περισσότερη από 1 στήλη. Η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί σε μηδέν. Ανάγνωση/εγγραφή double. |

 **Επιστρέφει:**
double


---


### getEffective {#getEffective}

| Name | Description |
| --- | --- |
| getEffective () | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης πλαισίου κειμένου με την κληρονομιά που έχει εφαρμοστεί. |

 **Επιστρέφει:**
TextFrameFormatEffectiveData


---


### getKeepTextFlat {#getKeepTextFlat}

| Name | Description |
| --- | --- |
| getKeepTextFlat () | Λαμβάνει ή ορίζει τη διατήρηση του κειμένου επίπεδο ακόμα και αν έχει εφαρμοστεί εφέ 3-Δ περιστροφής. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### getMarginBottom {#getMarginBottom}

| Name | Description |
| --- | --- |
| getMarginBottom () | Επιστρέφει ή ορίζει το κάτω περιθώριο (points) σε ένα TextFrame. Ανάγνωση/εγγραφή double. |

 **Επιστρέφει:**
double


---


### getMarginLeft {#getMarginLeft}

| Name | Description |
| --- | --- |
| getMarginLeft () | Επιστρέφει ή ορίζει το αριστερό περιθώριο (points) σε ένα TextFrame. Ανάγνωση/εγγραφή double. |

 **Επιστρέφει:**
double


---


### getMarginRight {#getMarginRight}

| Name | Description |
| --- | --- |
| getMarginRight () | Επιστρέφει ή ορίζει το δεξιό περιθώριο (points) σε ένα TextFrame. Ανάγνωση/εγγραφή double. |

 **Επιστρέφει:**
double


---


### getMarginTop {#getMarginTop}

| Name | Description |
| --- | --- |
| getMarginTop () | Επιστρέφει ή ορίζει το πάνω περιθώριο (points) σε ένα TextFrame. Ανάγνωση/εγγραφή double. |

 **Επιστρέφει:**
double


---


### getRotationAngle {#getRotationAngle}

| Name | Description |
| --- | --- |
| getRotationAngle () | Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο εντός του περιοριστικού κουτιού. Εάν δεν καθοριστεί, χρησιμοποιείται η περιστροφή του συνοδευτικού σχήματος. Εάν καθοριστεί, η τιμή αυτή εφαρμόζεται ανεξάρτητα από το σχήμα. Δηλαδή, το σχήμα μπορεί να έχει περιστροφή επιπλέον της περιστροφής του κειμένου. Η τελική τιμή της οπτικής περιστροφής κειμένου προκύπτει από αυτήν την ιδιότητα και τον προεπιλεγμένο κάθετο τύπο στην ιδιότητα TextVerticalType. Ανάγνωση/εγγραφή float. |

 **Επιστρέφει:**
float


---


### getTextStyle {#getTextStyle}

| Name | Description |
| --- | --- |
| getTextStyle () | Επιστρέφει το στυλ του κειμένου. Μόνο για ανάγνωση ITextStyle. |

 **Επιστρέφει:**
[TextStyle](../textstyle)


---


### getTextVerticalType {#getTextVerticalType}

| Name | Description |
| --- | --- |
| getTextVerticalType () | Καθορίζει τον προσανατολισμό του κειμένου. Η τελική τιμή της οπτικής περιστροφής κειμένου προκύπτει από αυτήν την ιδιότητα και την προσαρμοσμένη γωνία στην ιδιότητα RotationAngle. Ανάγνωση/εγγραφή TextVerticalType. |

 **Επιστρέφει:**
byte


---


### getThreeDFormat {#getThreeDFormat}

| Name | Description |
| --- | --- |
| getThreeDFormat () | Επιστρέφει το αντικείμενο ThreeDFormat που αντιπροσωπεύει τις ιδιότητες εφέ 3-Δ για κείμενο. Μόνο για ανάγνωση IThreeDFormat. |

 **Επιστρέφει:**
[ThreeDFormat](../threedformat)


---


### getTransform {#getTransform}

| Name | Description |
| --- | --- |
| getTransform () | Λαμβάνει ή ορίζει το σχήμα αναδίπλωσης κειμένου. Ανάγνωση/εγγραφή TextShapeType. |

 **Επιστρέφει:**
byte


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

 **Επιστρέφει:**
long


---


### getWrapText {#getWrapText}

| Name | Description |
| --- | --- |
| getWrapText () | Αληθές εάν το κείμενο περιτυλίγεται στα περιθώρια του TextFrame. Ανάγνωση/εγγραφή NullableBool. |

 **Επιστρέφει:**
byte


---


### setAnchoringType {#setAnchoringType}

| Name | Description |
| --- | --- |
| setAnchoringType (byte) | Επιστρέφει ή ορίζει το κάθετο αγκίστρωμα του κειμένου σε ένα TextFrame. Ανάγνωση/εγγραφή TextAnchorType. |

 **Επιστρέφει:**
void


---


### setAutofitType {#setAutofitType}

| Name | Description |
| --- | --- |
| setAutofitType (byte) | Επιστρέφει ή ορίζει τη λειτουργία αυτόματης προσαρμογής κειμένου. Ανάγνωση/εγγραφή TextAutofitType. |

 **Επιστρέφει:**
void


---


### setCenterText {#setCenterText}

| Name | Description |
| --- | --- |
| setCenterText (byte) | Εάν NullableBool.True τότε το κείμενο πρέπει να κεντραριστεί οριζόντια στο κουτί. Ανάγνωση/εγγραφή NullableBool. |

 **Επιστρέφει:**
void


---


### setColumnCount {#setColumnCount}

| Name | Description |
| --- | --- |
| setColumnCount (int) | Επιστρέφει ή ορίζει τον αριθμό των στηλών στην περιοχή κειμένου. Η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί σε μηδέν. Η τιμή 0 σημαίνει ακαθόριστη τιμή. Ανάγνωση/εγγραφή int. |

 **Επιστρέφει:**
void


---


### setColumnSpacing {#setColumnSpacing}

| Name | Description |
| --- | --- |
| setColumnSpacing (double) | Επιστρέφει ή ορίζει το διάστημα μεταξύ των στηλών κειμένου στην περιοχή κειμένου (σε points). Αυτό ισχύει μόνο όταν υπάρχει περισσότερη από 1 στήλη. Η τιμή πρέπει να είναι θετικός αριθμός. Διαφορετικά, η τιμή θα οριστεί σε μηδέν. Ανάγνωση/εγγραφή double. |

 **Επιστρέφει:**
void


---


### setKeepTextFlat {#setKeepTextFlat}

| Name | Description |
| --- | --- |
| setKeepTextFlat (boolean) | Λαμβάνει ή ορίζει τη διατήρηση του κειμένου επίπεδο ακόμα και αν έχει εφαρμοστεί εφέ 3-Δ περιστροφής. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
void


---


### setMarginBottom {#setMarginBottom}

| Name | Description |
| --- | --- |
| setMarginBottom (double) | Επιστρέφει ή ορίζει το κάτω περιθώριο (points) σε ένα TextFrame. Ανάγνωση/εγγραφή double. |

 **Επιστρέφει:**
void


---


### setMarginLeft {#setMarginLeft}

| Name | Description |
| --- | --- |
| setMarginLeft (double) | Επιστρέφει ή ορίζει το αριστερό περιθώριο (points) σε ένα TextFrame. Ανάγνωση/εγγραφή double. |

 **Επιστρέφει:**
void


---


### setMarginRight {#setMarginRight}

| Name | Description |
| --- | --- |
| setMarginRight (double) | Επιστρέφει ή ορίζει το δεξιό περιθώριο (points) σε ένα TextFrame. Ανάγνωση/εγγραφή double. |

 **Επιστρέφει:**
void


---


### setMarginTop {#setMarginTop}

| Name | Description |
| --- | --- |
| setMarginTop (double) | Επιστρέφει ή ορίζει το πάνω περιθώριο (points) σε ένα TextFrame. Ανάγνωση/εγγραφή double. |

 **Επιστρέφει:**
void


---


### setRotationAngle {#setRotationAngle}

| Name | Description |
| --- | --- |
| setRotationAngle (float) | Καθορίζει την προσαρμοσμένη περιστροφή που εφαρμόζεται στο κείμενο εντός του περιοριστικού κουτιού. Εάν δεν καθοριστεί, χρησιμοποιείται η περιστροφή του συνοδευτικού σχήματος. Εάν καθοριστεί, η τιμή αυτή εφαρμόζεται ανεξάρτητα από το σχήμα. Δηλαδή, το σχήμα μπορεί να έχει περιστροφή επιπλέον της περιστροφής του κειμένου. Η τελική τιμή της οπτικής περιστροφής κειμένου προκύπτει από αυτήν την ιδιότητα και τον προεπιλεγμένο κάθετο τύπο στην ιδιότητα TextVerticalType. Ανάγνωση/εγγραφή float. |

 **Επιστρέφει:**
void


---


### setTextVerticalType {#setTextVerticalType}

| Name | Description |
| --- | --- |
| setTextVerticalType (byte) | Καθορίζει τον προσανατολισμό του κειμένου. Η τελική τιμή της οπτικής περιστροφής κειμένου προκύπτει από αυτήν την ιδιότητα και την προσαρμοσμένη γωνία στην ιδιότητα RotationAngle. Ανάγνωση/εγγραφή TextVerticalType. |

 **Επιστρέφει:**
void


---


### setTransform {#setTransform}

| Name | Description |
| --- | --- |
| setTransform (byte) | Λαμβάνει ή ορίζει το σχήμα αναδίπλωσης κειμένου. Ανάγνωση/εγγραφή TextShapeType. |

 **Επιστρέφει:**
void


---


### setWrapText {#setWrapText}

| Name | Description |
| --- | --- |
| setWrapText (byte) | Αληθές εάν το κείμενο περιτυλίγεται στα περιθώρια του TextFrame. Ανάγνωση/εγγραφή NullableBool. |

 **Επιστρέφει:**
void


---