---
title: operator==()
second_title: Aspose.Slides για το API του C++
description: Καθορίζει εάν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι null.
type: docs
weight: 118
url: /el/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const method


Καθορίζει εάν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι null.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```


### Τιμή Επιστροφής

True αν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι null, διαφορετικά - false

## Nullable::operator==(const T1\&) const method


Καθορίζει εάν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι ίση με την καθορισμένη τιμή.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```


### Παράμετροι Προτύπου

| Parameter | Description |
| --- | --- |
| T1 | The type of the value to compare with |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | A constant reference to the value to compare with |

### Τιμή Επιστροφής

True αν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι ίση με την καθορισμένη τιμή, διαφορετικά - false

## Nullable::operator==(const Nullable\<T1\>\&) const method


Καθορίζει εάν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι ίση με την τιμή που αντιπροσωπεύεται από το καθορισμένο [Nullable](../) αντικείμενο.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```


### Παράμετροι Προτύπου

| Parameter | Description |
| --- | --- |
| T1 | The underlying type of the [Nullable](../) object to compare with |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | A constant reference to the [Nullable](../) object to compare with |

### Τιμή Επιστροφής

True αν η τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι ίση με την τιμή που αντιπροσωπεύεται από το καθορισμένο [Nullable](../) αντικείμενο, διαφορετικά - false

## Δείτε επίσης

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)