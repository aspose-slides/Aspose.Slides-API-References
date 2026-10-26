---
title: IBehavior
second_title: Aspose.Slides for Android via Java API Reference
description: Represent base class behavior of effect.
type: docs
url: /el/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Αντιπροσωπεί τη συμπεριφορά της βασικής κλάσης του εφέ.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Αντιπροσωπεί εάν οι συμπεριφορές κινούμενων εικόνων συσσωρεύονται. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Αντιπροσωπεί εάν οι συμπεριφορές κινούμενων εικόνων συσσωρεύονται. |
| [getAdditive()](#getAdditive--) | Αντιπροσωπεί εάν η τρέχουσα συμπεριφορά animation συνδυάζεται με άλλες εκτελούμενες animations. |
| [setAdditive(int value)](#setAdditive-int-) | Αντιπροσωπεί εάν η τρέχουσα συμπεριφορά animation συνδυάζεται με άλλες εκτελούμενες animations. |
| [getProperties()](#getProperties--) | Αντιπροσωπεί ιδιότητες της συμπεριφοράς. |
| [getTiming()](#getTiming--) | Αντιπροσωπεί ιδιότητες χρονομέτρησης για τη συμπεριφορά του εφέ. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Αντιπροσωπεί ιδιότητες χρονομέτρησης για τη συμπεριφορά του εφέ. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Αντιπροσωπεί εάν οι συμπεριφορές κινούμενων εικόνων συσσωρεύονται. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Αντιπροσωπεί εάν οι συμπεριφορές κινούμενων εικόνων συσσωρεύονται. Ανάγνωση/εγγραφή [NullableBool](../../com.aspose.slides/nullablebool).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Αντιπροσωπεί εάν η τρέχουσα συμπεριφορά animation συνδυάζεται με άλλες εκτελούμενες animations. Ανάγνωση/εγγραφή [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Επιστρέφει:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Αντιπροσωπεί εάν η τρέχουσα συμπεριφορά animation συνδυάζεται με άλλες εκτελούμενες animations. Ανάγνωση/εγγραφή [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Αντιπροσωπεί ιδιότητες της συμπεριφοράς. Μόνο ανάγνωση [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Επιστρέφει:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Αντιπροσωπεί ιδιότητες χρονομέτρησης για τη συμπεριφορά του εφέ. Ανάγνωση/εγγραφή [ITiming](../../com.aspose.slides/itiming).

**Επιστρέφει:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Αντιπροσωπεί ιδιότητες χρονομέτρησης για τη συμπεριφορά του εφέ. Ανάγνωση/εγγραφή [ITiming](../../com.aspose.slides/itiming).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |