---
title: SmartArtNodeCollection
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει μια συλλογή κόμβων SmartArt.
type: docs
url: /el/com.aspose.slides/smartartnodecollection/
---
**Κληρονομικότητα:**  
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**  
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)  
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Αντιπροσωπεύει μια συλλογή κόμβων SmartArt.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει κόμβο με δείκτη |
| [size()](#size--) | Επιστρέφει τον αριθμό των κόμβων στη συλλογή Μόνο για ανάγνωση int Μόνο για ανάγνωση int . |
| [addNode()](#addNode--) | Προσθέτει νέο κόμβο smart art ή υποκόμβο. |
| [removeNode(int index)](#removeNode-int-) | Αφαιρεί κόμβο ή υποκόμβο με δείκτη |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Αφαιρεί κόμβο ή υποκόμβο |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Προσθέτει νέο κόμβο στη επιλεγμένη θέση της συλλογής κόμβων |
| [iterator()](#iterator--) | Επιστρέφει έναν ενομετρητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία της συλλογής στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |

### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

Επιστρέφει κόμβο με δείκτη

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης του στοιχείου |

**Επιστρέφει:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Ο κόμβος SmartArt

### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό των κόμβων στη συλλογή Μόνο για ανάγνωση int Μόνο για ανάγνωση int .

**Επιστρέφει:**
int

### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

Προσθέτει νέο κόμβο smart art ή υποκόμβο.

**Επιστρέφει:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Προστιθέμενος κόμβος

### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

Αφαιρεί κόμβο ή υποκόμβο με δείκτη

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Μηδενικός δείκτης του κόμβου |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

Αφαιρεί κόμβο ή υποκόμβο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Κόμβος προς αφαίρεση |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

Προσθέτει νέο κόμβο στη επιλεγμένη θέση της συλλογής κόμβων

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | int | Μηδενική θέση του κόμβου |

**Επιστρέφει:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Προστιθέμενος κόμβος

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Επιστρέφει έναν ενομετρητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την διαπέραση της συλλογής.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει όλα τα στοιχεία της συλλογής στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας προορισμού. |
| index | int | Αρχικός δείκτης στον πίνακα προορισμού. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean .

**Επιστρέφει:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει τη ρίζα συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object