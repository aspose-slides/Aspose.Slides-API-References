---
title: SmartArtNodeCollection
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά μια συλλογή από κόμβους SmartArt.
type: docs
url: /el/com.aspose.slides/smartartnodecollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Αναπαριστά μια συλλογή από κόμβους SmartArt.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει τον κόμβο με βάση τον δείκτη |
| [size()](#size--) | Επιστρέφει τον αριθμό των κόμβων στη συλλογή Read-only  int  Read-only  int . |
| [addNode()](#addNode--) | Προσθέτει νέο κόμβο smart art ή υποκόμβο. |
| [removeNode(int index)](#removeNode-int-) | Αφαιρεί κόμβο ή υποκόμβο με βάση τον δείκτη |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Αφαιρεί κόμβο ή υποκόμβο |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Προσθέτει νέο κόμβο στη επιλεγμένη θέση της συλλογής κόμβων |
| [iterator()](#iterator--) | Επιστρέφει έναν αριθμητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

Επιστρέφει τον κόμβο με βάση τον δείκτη

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης του στοιχείου, αρχής από το μηδέν |

**Επιστρέφει:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Ο κόμβος SmartArt
### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό των κόμβων στη συλλογή Read-only  int  Read-only  int .

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

Αφαιρεί κόμβο ή υποκόμβο με βάση τον δείκτη

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης κόμβου, αρχής από το μηδέν |

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
| position | int | Θέση κόμβου, αρχής από το μηδέν |

**Επιστρέφει:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Προστιθέμενος κόμβος
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Επιστρέφει έναν αριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Ένα java.util.Iterator για ολόκληρη τη συλλογή.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας προορισμού. |
| index | int | Αρχικός δείκτης στον πίνακα προορισμού. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Read-only  boolean .

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει τη ρίζα συγχρονισμού. Read-only Object.

**Επιστρέφει:**
java.lang.Object