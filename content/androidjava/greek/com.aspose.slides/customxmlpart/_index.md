---
title: CustomXmlPart
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
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
| [getItemId()](#getItemId--) | Καθορίζει έναν παγκοσμίου στίγματος μοναδικό αναγνωστικό (GUID) που αναγνωρίζει μοναδικά ένα μόνο προσαρμοσμένο τμήμα XML μέσα σε ένα έγγραφο Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Καθορίζει έναν παγκοσμίου στίγματος μοναδικό αναγνωστικό (GUID) που αναγνωρίζει μοναδικά ένα μόνο προσαρμοσμένο τμήμα XML μέσα σε ένα έγγραφο Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Επιστρέφει τη συλλογή των σχημάτων XML που σχετίζονται με το προσαρμοσμένο τμήμα XML. |
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


Καθορίζει έναν παγκοσμίου στίγματος μοναδικό αναγνωστικό (GUID) που αναγνωρίζει μοναδικά ένα μόνο προσαρμοσμένο τμήμα XML μέσα σε ένα έγγραφο Office Open XML. Μόνο ανάγνωση java.util.UUID.

**Επιστρέφει:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


Καθορίζει έναν παγκοσμίου στίγματος μοναδικό αναγνωστικό (GUID) που αναγνωρίζει μοναδικά ένα μόνο προσαρμοσμένο τμήμα XML μέσα σε ένα έγγραφο Office Open XML. Μόνο ανάγνωση java.util.UUID.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


Επιστρέφει τη συλλογή των σχημάτων XML που σχετίζονται με το προσαρμοσμένο τμήμα XML. Μόνο ανάγνωση String[].

**Επιστρέφει:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


Αφαιρεί το προσαρμοσμένο τμήμα xml από την παρουσίαση.