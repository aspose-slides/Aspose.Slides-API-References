---
title: IBehavior
second_title: Aspose.Slides for Java API Reference
description: Represent base class behavior of effect.
type: docs
url: /el/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Αναπαριστά τη βασική συμπεριφορά της κλάσης του εφέ.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Αναπαριστά αν οι συμπεριφορές της κίνησης συσσωρεύονται. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Αναπαριστά αν οι συμπεριφορές της κίνησης συσσωρεύονται. |
| [getAdditive()](#getAdditive--) | Αναπαριστά αν η τρέχουσα συμπεριφορά της κίνησης συνδυάζεται με άλλες ενεργές κινήσεις. |
| [setAdditive(int value)](#setAdditive-int-) | Αναπαριστά αν η τρέχουσα συμπεριφορά της κίνησης συνδυάζεται με άλλες ενεργές κινήσεις. |
| [getProperties()](#getProperties--) | Αναπαριστά τις ιδιότητες της συμπεριφοράς. |
| [getTiming()](#getTiming--) | Αναπαριστά τις ιδιότητες του χρονισμού για τη συμπεριφορά του εφέ. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Αναπαριστά τις ιδιότητες του χρονισμού για τη συμπεριφορά του εφέ. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Αναπαριστά αν οι συμπεριφορές της κίνησης συσσωρεύονται. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Αναπαριστά αν οι συμπεριφορές της κίνησης συσσωρεύονται. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Αναπαριστά αν η τρέχουσα συμπεριφορά της κίνησης συνδυάζεται με άλλες ενεργές κινήσεις. Ανάγνωση/εγγραφή [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Επιστρέφει:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Αναπαριστά αν η τρέχουσα συμπεριφορά της κίνησης συνδυάζεται με άλλες ενεργές κινήσεις. Ανάγνωση/εγγραφή [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Αναπαριστά τις ιδιότητες της συμπεριφοράς. Μόνο ανάγνωση [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Επιστρέφει:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Αναπαριστά τις ιδιότητες του χρονισμού για τη συμπεριφορά του εφέ. Ανάγνωση/εγγραφή [ITiming](../../com.aspose.slides/itiming).

**Επιστρέφει:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Αναπαριστά τις ιδιότητες του χρονισμού για τη συμπεριφορά του εφέ. Ανάγνωση/εγγραφή [ITiming](../../com.aspose.slides/itiming).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |