---
title: Behavior
second_title: Αναφορά API Java για Aspose.Slides για Android
description: Αναπαριστά τη συμπεριφορά της βασικής κλάσης του εφέ.
type: docs
url: /el/com.aspose.slides/behavior/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Αναπαριστά τη συμπεριφορά της βασικής κλάσης του εφέ.
## Methods

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Αναπαριστά εάν οι συμπεριφορές κίνησης συσσωρεύονται. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Αναπαριστά εάν οι συμπεριφορές κίνησης συσσωρεύονται. |
| [getAdditive()](#getAdditive--) | Αναπαριστά εάν η τρέχουσα συμπεριφορά κίνησης συνδυάζεται με άλλες τρέχουσες κινήσεις. |
| [setAdditive(int value)](#setAdditive-int-) | Αναπαριστά εάν η τρέχουσα συμπεριφορά κίνησης συνδυάζεται με άλλες τρέχουσες κινήσεις. |
| [getProperties()](#getProperties--) | Αναπαριστά ιδιότητες της συμπεριφοράς. |
| [getTiming()](#getTiming--) | Αναπαριστά ιδιότητες χρονοπτυχίας για τη συμπεριφορά του εφέ. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Αναπαριστά ιδιότητες χρονοπτυχίας για τη συμπεριφορά του εφέ. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```


Αναπαριστά εάν οι συμπεριφορές κίνησης συσσωρεύονται. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```


Αναπαριστά εάν οι συμπεριφορές κίνησης συσσωρεύονται. Ανάγνωση/Εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```


Αναπαριστά εάν η τρέχουσα συμπεριφορά κίνησης συνδυάζεται με άλλες τρέχουσες κινήσεις. Ανάγνωση/Εγγραφή [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Επιστρέφει:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```


Αναπαριστά εάν η τρέχουσα συμπεριφορά κίνησης συνδυάζεται με άλλες τρέχουσες κινήσεις. Ανάγνωση/Εγγραφή [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```


Αναπαριστά ιδιότητες της συμπεριφοράς. Μόνο ανάγνωση [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Επιστρέφει:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


Αναπαριστά ιδιότητες χρονοπτυχίας για τη συμπεριφορά του εφέ. Ανάγνωση/Εγγραφή [ITiming](../../com.aspose.slides/itiming).

**Επιστρέφει:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


Αναπαριστά ιδιότητες χρονοπτυχίας για τη συμπεριφορά του εφέ. Ανάγνωση/Εγγραφή [ITiming](../../com.aspose.slides/itiming).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |