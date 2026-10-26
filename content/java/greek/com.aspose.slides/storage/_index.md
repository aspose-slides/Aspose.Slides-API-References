---
title: Storage
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει προσωρινή αποθήκη δεδομένων για .
type: docs
url: /el/com.aspose.slides/storage/
---
**Κληρονομικότητα:**
java.lang.Object
```
public final class Storage
```

Αντιπροσωπεί προσωρινή αποθήκη δεδομένων για [WebDocument](../../com.aspose.slides/webdocument).
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Storage()](#Storage--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Τοποθετεί την τιμή στην αποθήκη. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Ανακτά τα δεδομένα από την αποθήκη. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Καθορίζει εάν η αποθήκη περιέχει ένα στοιχείο με το συγκεκριμένο κλειδί. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


Τοποθετεί την τιμή στην αποθήκη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| key | java.lang.String | Κλειδί για την τιμή. |
| value | TValue | Τιμή. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


Ανακτά τα δεδομένα από την αποθήκη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| key | java.lang.String | Κλειδί της τιμής. |

**Επιστρέφει:**
TValue - Τιμή δεδομένων εάν υπάρχει στη συλλογή δεδομένων, null otherwise.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Καθορίζει εάν η αποθήκη περιέχει ένα στοιχείο με το συγκεκριμένο κλειδί.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| key | java.lang.String | Κλειδί της τιμής. |

**Επιστρέφει:**
boolean - True εάν η αποθήκη περιέχει ένα στοιχείο με το συγκεκριμένο κλειδί, false αλλιώς.