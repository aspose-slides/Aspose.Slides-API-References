---
title: PortionFormat
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/portionformat/
---
## PortionFormat κλάση

 Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμήματος κειμένου. Σε αντίθεση με IPortionFormatEffectiveData, όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.
 Η κλάση αυτή χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης τμήματος κειμένου που ορίζονται για το συγκεκριμένο τμήμα. Αυτό σημαίνει ότι
 δεν εφαρμόζεται κληρονομικότητα κατά την λήψη τιμών, οπότε στις περισσότερες περιπτώσεις θα λαμβάνετε τιμές που σημαίνουν «αορίστους».
 Για να λάβετε τις τιμές παραμέτρων της αποτελεσματικής μορφοποίησης, συμπεριλαμβανομένης της κληρονομικότητας, πρέπει να χρησιμοποιήσετε τη μέθοδο PortionFormat#getEffective
 η οποία επιστρέφει ένα στιγμιότυπο IPortionFormatEffectiveData.
### PortionFormat {#PortionFormat}

| Όνομα | Περιγραφή |
| --- | --- |
| PortionFormat() | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης PortionFormat. |

 **Επιστρέφει:**
PortionFormat


---


### getBookmarkId {#getBookmarkId}

| Όνομα | Περιγραφή |
| --- | --- |
| getBookmarkId () | Επιστρέφει ή ορίζει το αναγνωριστικό σελιδοδείκτη. Ανάγνωση/εγγραφή String. |

 **Επιστρέφει:**
String


---


### getEffective {#getEffective}

| Όνομα | Περιγραφή |
| --- | --- |
| getEffective () | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης τμήματος με την εφαρμογή κληρονομικότητας. |

 **Επιστρέφει:**
PortionFormatEffectiveData


---


### getHyperlinkClick {#getHyperlinkClick}

| Όνομα | Περιγραφή |
| --- | --- |
| getHyperlinkClick () | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/εγγραφή IHyperlink. |

 **Επιστρέφει:**
[Hyperlink](../hyperlink)


---


### getHyperlinkManager {#getHyperlinkManager}

| Όνομα | Περιγραφή |
| --- | --- |
| getHyperlinkManager () | Διαχειριστής υπερσυνδέσμων. Μόνο-ανάγνωση IHyperlinkManager. |

 **Επιστρέφει:**
[HyperlinkManager](../hyperlinkmanager)


---


### getHyperlinkMouseOver {#getHyperlinkMouseOver}

| Όνομα | Περιγραφή |
| --- | --- |
| getHyperlinkMouseOver () | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για πέρασμα ποντικιού. Ανάγνωση/εγγραφή IHyperlink. |

 **Επιστρέφει:**
[Hyperlink](../hyperlink)


---


### getSmartTagClean {#getSmartTagClean}

| Όνομα | Περιγραφή |
| --- | --- |
| getSmartTagClean () | Καθορίζει αν η έξυπνη ετικέτα πρέπει να καθαριστεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
boolean


---


### setBookmarkId {#setBookmarkId}

| Όνομα | Περιγραφή |
| --- | --- |
| setBookmarkId (String) | Επιστρέφει ή ορίζει το αναγνωριστικό σελιδοδείκτη. Ανάγνωση/εγγραφή String. |

 **Επιστρέφει:**
void


---


### setHyperlinkClick {#setHyperlinkClick}

| Όνομα | Περιγραφή |
| --- | --- |
| setHyperlinkClick ([Hyperlink](../hyperlink)) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/εγγραφή IHyperlink. |

 **Επιστρέφει:**
void


---


### setHyperlinkMouseOver {#setHyperlinkMouseOver}

| Όνομα | Περιγραφή |
| --- | --- |
| setHyperlinkMouseOver ([Hyperlink](../hyperlink)) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για πέρασμα ποντικιού. Ανάγνωση/εγγραφή IHyperlink. |

 **Επιστρέφει:**
void


---


### setSmartTagClean {#setSmartTagClean}

| Όνομα | Περιγραφή |
| --- | --- |
| setSmartTagClean (boolean) | Καθορίζει αν η έξυπνη ετικέτα πρέπει να καθαριστεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή boolean. |

 **Επιστρέφει:**
void


---