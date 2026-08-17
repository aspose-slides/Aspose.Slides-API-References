---
title: ControlPropertiesCollection
second_title: Aspose.Slides για Java Αναφορά API
description: Μια συλλογή ιδιοτήτων AcitveX.
type: docs
url: /el/com.aspose.slides/controlpropertiescollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

Μια συλλογή ιδιοτήτων AcitveX.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Adds a property to the collection. |
| [remove(String name)](#remove-java.lang.String-) | Removes a property with the specified name. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returns or sets property. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Returns or sets property. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Returns the collection of properties names. |
| [clear()](#clear--) | Removes all properties. |
| [getCount()](#getCount--) | Returns a number of properties in the collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

Adds a property to the collection.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της ιδιότητας. |
| value | java.lang.String | Η τιμή της ιδιότητας. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Removes a property with the specified name.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της ιδιότητας προς αφαίρεση. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Returns or sets property.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της ιδιότητας. |

**Επιστρέφει:**
java.lang.String - Ιδιότητα.

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Returns or sets property.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Το όνομα της ιδιότητας. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Returns the collection of properties names. Read-only [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Επιστρέφει:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```

Removes all properties.

### getCount() {#getCount--}
```
public final int getCount()
```

Returns a number of properties in the collection. Read-only int.

**Επιστρέφει:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Returns an enumerator that iterates through the collection.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Returns a java iterator for the entire collection.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.