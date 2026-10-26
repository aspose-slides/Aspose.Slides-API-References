---
title: ICustomXmlPart
second_title: Aspose.Slides for Java API Reference
description: Represents custom xml part.
type: docs
url: /el/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Αναπαριστά προσαρμοσμένο τμήμα xml.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Επιστρέφει ή ορίζει δεδομένα xml ως συμβολοσειρά UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Επιστρέφει ή ορίζει δεδομένα xml ως συμβολοσειρά UTF-8. |
| [getXmlData()](#getXmlData--) | Επιστρέφει ή ορίζει δεδομένα xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Επιστρέφει ή ορίζει δεδομένα xml. |
| [getItemId()](#getItemId--) | Καθορίζει έναν παγκοσμίως μοναδικό ταυτοποιητή (GUID) που αναγνωρίζει μοναδικά ένα προσαρμοσμένο XML τμήμα εντός ενός εγγράφου Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Καθορίζει έναν παγκοσμίως μοναδικό ταυτοποιητή (GUID) που αναγνωρίζει μοναδικά ένα προσαρμοσμένο XML τμήμα εντός ενός εγγράφου Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Επιστρέφει τη συλλογή XML σχήματος που σχετίζονται με το προσαρμοσμένο XML τμήμα. |
| [remove()](#remove--) | Αφαιρεί το προσαρμοσμένο xml τμήμα από την παρουσίαση. |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Καθορίζει έναν παγκοσμίως μοναδικό ταυτοποιητή (GUID) που αναγνωρίζει μοναδικά ένα προσαρμοσμένο XML τμήμα εντός ενός εγγράφου Office Open XML. Μόνο για ανάγνωση java.util.UUID.

**Επιστρέφει:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Καθορίζει έναν παγκοσμίως μοναδικό ταυτοποιητή (GUID) που αναγνωρίζει μοναδικά ένα προσαρμοσμένο XML τμήμα εντός ενός εγγράφου Office Open XML. Μόνο για ανάγνωση java.util.UUID.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Επιστρέφει τη συλλογή XML σχήματος που σχετίζονται με το προσαρμοσμένο XML τμήμα. Μόνο για ανάγνωση String[].

**Επιστρέφει:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Αφαιρεί το προσαρμοσμένο xml τμήμα από την παρουσίαση.