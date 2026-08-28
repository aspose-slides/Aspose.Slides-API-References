---
title: CustomXmlPartCollection
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/customxmlpartcollection/
---
## CustomXmlPartCollection κλάση

 Αντιπροσωπεύει τη συλλογή προσαρμοσμένων XML τμημάτων.
 
### add {#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add (String) | Adds new custom xml part. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| xmlString | String | Το xml string του νέου τμήματος που θα προστεθεί. |

 **Επιστρέφει:**
[CustomXmlPart](../customxmlpart)

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | xmlString είναι κενό ή xml-data δεν είναι έγκυρο. |


---


### add {#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add (byte[]) | Adds new custom xml part. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| xmlData | byte[] | Τα xml δεδομένα του νέου τμήματος που θα προστεθεί. |

 **Επιστρέφει:**
[CustomXmlPart](../customxmlpart)

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | xmlData είναι κενό ή μη έγκυρο. |


---


### add {#add}

| Όνομα | Περιγραφή |
| --- | --- |
| add (InputStream) | Adds new custom xml part. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputStream | InputStream | Το inputStream με xml δεδομένα του νέου τμήματος που θα προστεθεί. |

 **Επιστρέφει:**
[CustomXmlPart](../customxmlpart)

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | Τα δεδομένα στο inputStream είναι κενά ή μη έγκυρα. |


---


### clear {#clear}

| Όνομα | Περιγραφή |
| --- | --- |
| clear () | Removes all items from the collection. |

 **Επιστρέφει:**
void


---


### getSyncRoot {#getSyncRoot}

| Όνομα | Περιγραφή |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

 **Επιστρέφει:**
Object


---


### get_Item {#get_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| get_Item (int) | Returns the element at the specified index. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα ληφθεί. |

 **Επιστρέφει:**
[CustomXmlPart](../customxmlpart)

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | com.aspose.ms.System.ArgumentOutOfRangeException | index is less than 0.-or-index is equal to or greater than Count |


---


### isSynchronized {#isSynchronized}

| Όνομα | Περιγραφή |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Επιστρέφει:**
boolean


---


### iterator {#iterator}

| Όνομα | Περιγραφή |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Επιστρέφει:**



---


### iteratorJava {#iteratorJava}

| Όνομα | Περιγραφή |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Επιστρέφει:**



---


### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([CustomXmlPart](../customxmlpart)) | Removes the first occurrence of a specific object from the collection. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [CustomXmlPart](../customxmlpart) | Το προσαρμοσμένο XML τμήμα που θα αφαιρεθεί. |

 **Επιστρέφει:**
boolean

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | com.aspose.ms.System.ArgumentNullException | item είναι null. |


---


### removeAt {#removeAt}

| Όνομα | Περιγραφή |
| --- | --- |
| removeAt (int) | Removes custom xml part at the specified index. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα αφαιρεθεί. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
 | com.aspose.ms.System.ArgumentOutOfRangeException | index is less than 0.-or-index is equal to or greater than Count |


---


### size {#size}

| Όνομα | Περιγραφή |
| --- | --- |
| size () | Returns count of custom xml parts in the collection. Read-only int. |

 **Επιστρέφει:**
int


---  