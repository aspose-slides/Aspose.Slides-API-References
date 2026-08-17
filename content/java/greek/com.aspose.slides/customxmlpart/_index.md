---
title: CustomXmlPart
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά προσαρμοσμένο τμήμα xml.
type: docs
url: /el/com.aspose.slides/customxmlpart/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Αναπαριστά προσαρμοσμένο τμήμα xml.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getXmlData()](#getXmlData--) | Επιστρέφει ή ορίζει δεδομένα xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Επιστρέφει ή ορίζει δεδομένα xml. |
| [getXmlAsString()](#getXmlAsString--) | Επιστρέφει ή ορίζει δεδομένα xml ως συμβολοσειρά UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Επιστρέφει ή ορίζει δεδομένα xml ως συμβολοσειρά UTF-8. |
| [getItemId()](#getItemId--) | Καθορίζει ένα καθολικά μοναδικό αναγνωριστικό (GUID) που προσδιορίζει μοναδικά ένα μοναδικό προσαρμοσμένο τμήμα xml εντός ενός εγγράφου Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Καθορίζει ένα καθολικά μοναδικό αναγνωριστικό (GUID) που προσδιορίζει μοναδικά ένα μοναδικό προσαρμοσμένο τμήμα xml εντός ενός εγγράφου Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Επιστρέφει τη συλλογή XML σχημάτων που είναι συσχετισμένα με το προσαρμοσμένο τμήμα xml. |
| [remove()](#remove--) | Αφαιρεί το προσαρμοσμένο τμήμα xml από την παρουσίαση. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


Επιστρέφει ή ορίζει δεδομένα xml. Ανάγνωση/εγγραφή byte[].

**Επιστρέφει:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


Επιστρέφει ή ορίζει δεδομένα xml. Ανάγνωση/εγγραφή byte[].

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


Επιστρέφει ή ορίζει δεδομένα xml ως συμβολοσειρά UTF-8. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


Επιστρέφει ή ορίζει δεδομένα xml ως συμβολοσειρά UTF-8. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


Καθορίζει ένα καθολικά μοναδικό αναγνωριστικό (GUID) που προσδιορίζει μοναδικά ένα μοναδικό προσαρμοσμένο τμήμα xml εντός ενός εγγράφου Office Open XML. Μόνο-ανάγωση java.util.UUID.

**Επιστρέφει:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


Καθορίζει ένα καθολικά μοναδικό αναγνωριστικό (GUID) που προσδιορίζει μοναδικά ένα μοναδικό προσαρμοσμένο τμήμα xml εντός ενός εγγράφου Office Open XML. Μόνο-ανάγωση java.util.UUID.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


Επιστρέφει τη συλλογή XML σχημάτων που είναι συσχετισμένα με το προσαρμοσμένο τμήμα xml. Μόνο-ανάγωση String[].

**Επιστρέφει:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


Αφαιρεί το προσαρμοσμένο τμήμα xml από την παρουσίαση.