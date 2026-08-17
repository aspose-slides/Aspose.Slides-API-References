---
title: TextAnimationCollection
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά μια συλλογή κειμενικών κινήσεων.
type: docs
url: /el/com.aspose.slides/textanimationcollection/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

Αναπαριστά μια συλλογή κειμενικών κινήσεων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. |
| [add()](#add--) | Προσθέτει νέα κειμενική κίνηση στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο με βάση το ευρετήριο. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Επιστρέφει όλα τα στοιχεία |
| [iterator()](#iterator--) | Επιστρέφει έναν αριθμητή που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```


### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό των στοιχείων στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### add() {#add--}
```
public final TextAnimation add()
```

Προσθέτει νέα κειμενική κίνηση στη συλλογή.

**Επιστρέφει:**
[TextAnimation](../../com.aspose.slides/textanimation) - Added [TextAnimation](../../com.aspose.slides/textanimation)
### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```

Επιστρέφει το στοιχείο με βάση το ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```

Επιστρέφει όλα τα στοιχεία

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) για αφαίρεση. |

**Επιστρέφει:**
com.aspose.slides.ITextAnimation[] - Πίνακας των [ITextAnimation](../../com.aspose.slides/itextanimation)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```

Επιστρέφει έναν αριθμητή που διασχίζει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας για γεμίσμα. |
| index | int | Αρχική θέση στον πίνακα προορισμού. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει τη ρίζα συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object