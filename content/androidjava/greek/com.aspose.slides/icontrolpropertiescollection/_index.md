---
title: IControlPropertiesCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Μια συλλογή ελέγχων ActiveX.
type: docs
url: /el/com.aspose.slides/icontrolpropertiescollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

Συλλογή ελέγχων ActiveX.

## Μέθοδοι

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Επιστρέφει έναν αριθμό ιδιοτήτων στη συλλογή. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Προσθέτει μια ιδιότητα στη συλλογή. |
| [remove(String name)](#remove-java.lang.String-) | Αφαιρεί μια ιδιότητα με το συγκεκριμένο όνομα. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Επιστρέφει ή ορίζει την ιδιότητα. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Επιστρέφει ή ορίζει την ιδιότητα. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Επιστρέφει έναν αριθμό ιδιοτήτων στη συλλογή. |
| [clear()](#clear--) | Αφαιρεί όλες τις ιδιότητες. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Επιστρέφει έναν αριθμό ιδιοτήτων στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```

Προσθέτει μια ιδιότητα στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της ιδιότητας. |
| value | java.lang.String | Η τιμή της ιδιότητας. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Αφαιρεί μια ιδιότητα με το συγκεκριμένο όνομα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της ιδιότητας προς αφαίρεση. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Επιστρέφει ή ορίζει την ιδιότητα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα ιδιότητας. |

**Επιστρέφει:**
java.lang.String - Ιδιότητα.

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Επιστρέφει ή ορίζει την ιδιότητα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα ιδιότητας. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Επιστρέφει έναν αριθμό ιδιοτήτων στη συλλογή. Μόνο για ανάγνωση [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Επιστρέφει:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλες τις ιδιότητες.