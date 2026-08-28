---
title: CustomXmlPart
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs
url: /el/aspose.slides/customxmlpart/
---
## CustomXmlPart κλάση

 Αντιπροσωπεύει προσαρμοσμένο τμήμα xml.
 
### getItemId {#getItemId}

| Όνομα | Περιγραφή |
| --- | --- |
| getItemId () | Καθορίζει ένα παγκοσμίως μοναδικό αναγνωριστικό (GUID) που ταυτοποιεί μοναδικά ένα μόνο προσαρμοσμένο XML τμήμα μέσα σε ένα έγγραφο Office Open XML. Μόνο για ανάγνωση java.util.UUID. |

 **Επιστρέφει:**
UUID


---


### getNamespaceSchemas {#getNamespaceSchemas}

| Όνομα | Περιγραφή |
| --- | --- |
| getNamespaceSchemas () | Επιστρέφει τη συλλογή XML σχημάτων που σχετίζονται με το προσαρμοσμένο XML τμήμα. Μόνο για ανάγνωση String[]. |

 **Επιστρέφει:**
String


---


### getXmlAsString {#getXmlAsString}

| Όνομα | Περιγραφή |
| --- | --- |
| getXmlAsString () | Επιστρέφει ή ορίζει δεδομένα xml ως συμβολοσειρά UTF-8. Ανάγνωση/εγγραφή String. |

 **Επιστρέφει:**
String

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | η τιμή είναι κενή ή τα δεδομένα xml είναι άκυρα. |


---


### getXmlData {#getXmlData}

| Όνομα | Περιγραφή |
| --- | --- |
| getXmlData () | Επιστρέφει ή ορίζει δεδομένα xml. Ανάγνωση/εγγραφή byte[]. |

 **Επιστρέφει:**
byte

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | η τιμή είναι κενή ή τα δεδομένα xml είναι άκυρα. |


---


### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove () | Αφαιρεί το προσαρμοσμένο τμήμα xml από την παρουσίαση. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | PptxEditException | Εκτελείται αν το τμήμα xml έχει ήδη αφαιρεθεί. |


---


### setItemId {#setItemId}

| Όνομα | Περιγραφή |
| --- | --- |
| setItemId (UUID) | Καθορίζει ένα παγκοσμίως μοναδικό αναγνωριστικό (GUID) που ταυτοποιεί μοναδικά ένα μόνο προσαρμοσμένο XML τμήμα μέσα σε ένα έγγραφο Office Open XML. Μόνο για ανάγνωση java.util.UUID. |

 **Επιστρέφει:**
void


---


### setXmlAsString {#setXmlAsString}

| Όνομα | Περιγραφή |
| --- | --- |
| setXmlAsString (String) | Επιστρέφει ή ορίζει δεδομένα xml ως συμβολοσειρά UTF-8. Ανάγνωση/εγγραφή String. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | η τιμή είναι κενή ή τα δεδομένα xml είναι άκυρα. |


---


### setXmlData {#setXmlData}

| Όνομα | Περιγραφή |
| --- | --- |
| setXmlData (byte[]) | Επιστρέφει ή ορίζει δεδομένα xml. Ανάγνωση/εγγραφή byte[]. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | ArgumentException | η τιμή είναι κενή ή τα δεδομένα xml είναι άκυρα. |


---