---
title: ICustomXmlPart
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει προσαρμοσμένο τμήμα xml.
type: docs
url: /el/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Αντιπροσωπεύει προσαρμοσμένο τμήμα xml.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Επιστρέφει ή ορίζει δεδομένα xml ως συμβολοσειρά UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Επιστρέφει ή ορίζει δεδομένα xml ως συμβολοσειρά UTF-8. |
| [getXmlData()](#getXmlData--) | Επιστρέφει ή ορίζει δεδομένα xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Επιστρέφει ή ορίζει δεδομένα xml. |
| [getItemId()](#getItemId--) | Καθορίζει έναν παγκόσμιο μοναδικό αναγνωριστικό (GUID) που αναγνωρίζει μοναδικά ένα μόνο προσαρμοσμένο τμήμα XML σε ένα έγγραφο Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Καθορίζει έναν παγκόσμιο μοναδικό αναγνωριστικό (GUID) που αναγνωρίζει μοναδικά ένα μόνο προσαρμοσμένο τμήμα XML σε ένα έγγραφο Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Επιστρέφει τη συλλογή των σχημάτων XML που σχετίζονται με το προσαρμοσμένο τμήμα XML. |
| [remove()](#remove--) | Αφαιρεί το προσαρμοσμένο τμήμα xml από την παρουσίαση. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Επιστρέφει ή ορίζει δεδομένα xml ως συμβολοσειρά UTF-8. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Επιστρέφει ή ορίζει δεδομένα xml ως συμβολοσειρά UTF-8. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Επιστρέφει ή ορίζει δεδομένα xml. Ανάγνωση/εγγραφή byte[].

**Επιστρέφει:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Επιστρέφει ή ορίζει δεδομένα xml. Ανάγνωση/εγγραφή byte[].

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Καθορίζει έναν παγκόσμιο μοναδικό αναγνωριστικό (GUID) που αναγνωρίζει μοναδικά ένα μόνο προσαρμοσμένο τμήμα XML σε ένα έγγραφο Office Open XML. Μόνο για ανάγνωση java.util.UUID.

**Επιστρέφει:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Καθορίζει έναν παγκόσμιο μοναδικό αναγνωριστικό (GUID) που αναγνωρίζει μοναδικά ένα μόνο προσαρμοσμένο τμήμα XML σε ένα έγγραφο Office Open XML. Μόνο για ανάγνωση java.util.UUID.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Επιστρέφει τη συλλογή των σχημάτων XML που σχετίζονται με το προσαρμοσμένο τμήμα XML. Μόνο για ανάγνωση String[].

**Επιστρέφει:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Αφαιρεί το προσαρμοσμένο τμήμα xml από την παρουσίαση.