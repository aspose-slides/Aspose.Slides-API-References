---
title: ControlPropertiesCollection
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Μια συλλογή ιδιοτήτων AcitveX.
type: docs
url: /el/com.aspose.slides/controlpropertiescollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

Μια συλλογή ιδιοτήτων AcitveX.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Προσθέτει μια ιδιότητα στη συλλογή. |
| [remove(String name)](#remove-java.lang.String-) | Αφαιρεί μια ιδιότητα με το συγκεκριμένο όνομα. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Επιστρέφει ή ορίζει την ιδιότητα. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Επιστρέφει ή ορίζει την ιδιότητα. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Επιστρέφει τη συλλογή των ονομάτων ιδιοτήτων. |
| [clear()](#clear--) | Αφαιρεί όλες τις ιδιότητες. |
| [getCount()](#getCount--) | Επιστρέφει έναν αριθμό ιδιοτήτων στη συλλογή. |
| [iterator()](#iterator--) | Επιστρέφει έναν αμετρητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```


Προσθέτει μια ιδιότητα στη συλλογή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της ιδιότητας. |
| value | java.lang.String | Η τιμή της ιδιότητας. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```


Αφαιρεί μια ιδιότητα με το συγκεκριμένο όνομα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της ιδιότητας που θα αφαιρεθεί. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


Επιστρέφει ή ορίζει την ιδιότητα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της ιδιότητας. |

**Επιστρέφει:**
java.lang.String - Property.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


Επιστρέφει ή ορίζει την ιδιότητα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της ιδιότητας. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


Επιστρέφει τη συλλογή των ονομάτων ιδιοτήτων. Μόνο ανάγνωση [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Επιστρέφει:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```


Αφαιρεί όλες τις ιδιότητες.

### getCount() {#getCount--}
```
public final int getCount()
```


Επιστρέφει έναν αριθμό ιδιοτήτων στη συλλογή. Μόνο ανάγνωση int.

**Επιστρέφει:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```


Επιστρέφει έναν αμετρητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```


Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.