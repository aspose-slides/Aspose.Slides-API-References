---
title: Storage
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει προσωρινή αποθήκευση δεδομένων για .
type: docs
url: /el/com.aspose.slides/storage/
---
**Κληρονομικότητα:**
java.lang.Object
```
public final class Storage
```

Αντιπροσωπεύει προσωρινή αποθήκευση δεδομένων για [WebDocument](../../com.aspose.slides/webdocument).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Storage()](#Storage--) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Τοποθετεί την τιμή στην αποθήκευση. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Αποκτά τα δεδομένα από την αποθήκευση. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Καθορίζει εάν η αποθήκευση περιέχει στοιχείο με το συγκεκριμένο κλειδί. |

### Storage() {#Storage--}
```
public Storage()
```

### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```

Τοποθετεί την τιμή στην αποθήκευση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| key | java.lang.String | Κλειδί για την τιμή. |
| value | TValue | Τιμή. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```

Αποκτά τα δεδομένα από την αποθήκευση.

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

Καθορίζει εάν η αποθήκευση περιέχει στοιχείο με το συγκεκριμένο κλειδί.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| key | java.lang.String | Κλειδί της τιμής. |

**Επιστρέφει:**
boolean - True if the storage contains an element with the specified key, false otherwise.