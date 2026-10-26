---
title: IConnectorLock
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στον γονικό Connector.
type: docs
url: /el/com.aspose.slides/iconnectorlock/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IConnectorLock extends IBaseShapeLock
```

Καθορίζει ποιες λειτουργίες είναι απενεργοποιημένες στον γονικό Connector.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | Καθορίζει εάν η προσθήκη αυτού του σχήματος σε ομάδα απαγορεύεται. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | Καθορίζει εάν η προσθήκη αυτού του σχήματος σε ομάδα απαγορεύεται. |
| [getSelectLocked()](#getSelectLocked--) | Καθορίζει εάν η επιλογή αυτού του σχήματος απαγορεύεται. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | Καθορίζει εάν η επιλογή αυτού του σχήματος απαγορεύεται. |
| [getRotateLocked()](#getRotateLocked--) | Καθορίζει εάν η αλλαγή της γωνίας περιστροφής αυτού του σχήματος απαγορεύεται. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | Καθορίζει εάν η αλλαγή της γωνίας περιστροφής αυτού του σχήματος απαγορεύεται. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | Καθορίζει εάν το σχήμα πρέπει να διατηρεί την αναλογία διαστάσεων κατά την αλλαγή μεγέθους. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | Καθορίζει εάν το σχήμα πρέπει να διατηρεί την αναλογία διαστάσεων κατά την αλλαγή μεγέθους. |
| [getPositionMove()](#getPositionMove--) | Καθορίζει εάν η μετακίνηση αυτού του σχήματος απαγορεύεται. |
| [setPositionMove(boolean value)](#setPositionMove-boolean-) | Καθορίζει εάν η μετακίνηση αυτού του σχήματος απαγορεύεται. |
| [getSizeLocked()](#getSizeLocked--) | Καθορίζει εάν η αλλαγή μεγέθους αυτού του σχήματος απαγορεύεται. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | Καθορίζει εάν η αλλαγή μεγέθους αυτού του σχήματος απαγορεύεται. |
| [getEditPointsLocked()](#getEditPointsLocked--) | Καθορίζει εάν η απευθείας αλλαγή του περιγράμματος αυτού του σχήματος απαγορεύεται. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | Καθορίζει εάν η απευθείας αλλαγή του περιγράμματος αυτού του σχήματος απαγορεύεται. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | Καθορίζει εάν η αλλαγή των τιμών προσαρμογής απαγορεύεται. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | Καθορίζει εάν η αλλαγή των τιμών προσαρμογής απαγορεύεται. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | Καθορίζει εάν η αλλαγή των άκρων βέλους απαγορεύεται. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | Καθορίζει εάν η αλλαγή των άκρων βέλους απαγορεύεται. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | Καθορίζει εάν η αλλαγή τύπου σχήματος απαγορεύεται. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | Καθορίζει εάν η αλλαγή τύπου σχήματος απαγορεύεται. |

### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

Καθορίζει εάν η προσθήκη αυτού του σχήματος σε ομάδα απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

Καθορίζει εάν η προσθήκη αυτού του σχήματος σε ομάδα απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

Καθορίζει εάν η επιλογή αυτού του σχήματος απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

Καθορίζει εάν η επιλογή αυτού του σχήματος απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```

Καθορίζει εάν η αλλαγή της γωνίας περιστροφής αυτού του σχήματος απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```

Καθορίζει εάν η αλλαγή της γωνίας περιστροφής αυτού του σχήματος απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

Καθορίζει εάν το σχήμα πρέπει να διατηρεί την αναλογία διαστάσεων κατά την αλλαγή μεγέθους. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

Καθορίζει εάν το σχήμα πρέπει να διατηρεί την αναλογία διαστάσεων κατά την αλλαγή μεγέθους. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getPositionMove() {#getPositionMove--}
```
public abstract boolean getPositionMove()
```

Καθορίζει εάν η μετακίνηση αυτού του σχήματος απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setPositionMove(boolean value) {#setPositionMove-boolean-}
```
public abstract void setPositionMove(boolean value)
```

Καθορίζει εάν η μετακίνηση αυτού του σχήματος απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

Καθορίζει εάν η αλλαγή μεγέθους αυτού του σχήματος απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

Καθορίζει εάν η αλλαγή μεγέθους αυτού του σχήματος απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

Καθορίζει εάν η απευθείας αλλαγή του περιγράμματος αυτού του σχήματος απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

Καθορίζει εάν η απευθείας αλλαγή του περιγράμματος αυτού του σχήματος απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

Καθορίζει εάν η αλλαγή των τιμών προσαρμογής απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

Καθορίζει εάν η αλλαγή των τιμών προσαρμογής απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

Καθορίζει εάν η αλλαγή των άκρων βέλους απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

Καθορίζει εάν η αλλαγή των άκρων βέλους απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

Καθορίζει εάν η αλλαγή τύπου σχήματος απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

Καθορίζει εάν η αλλαγή τύπου σχήματος απαγορεύεται. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |