---
title: IsNull()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ελέγχει αν η συγκεκριμένη τιμή είναι null. Έκδοση για αριθμητικούς και enum τύπους.
type: docs
weight: 1
url: /el/system/testtools/isnull/
---
## TestTools::IsNull(T) μέθοδος


Ελέγχει αν η συγκεκριμένη τιμή είναι null. [Version](../../version/) για αριθμητικούς και enum τύπους.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Type of value being checked. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | Τιμή για έλεγχο αν είναι null. |

### Τιμή Επιστροφής

Πάντα επιστρέφει false.

## TestTools::IsNull(const T\&) μέθοδος


Ελέγχει αν η συγκεκριμένη τιμή είναι null. [Version](../../version/) για μη-αριθμητικούς και μη-enum τύπους τιμών.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Type of value being checked. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | Τιμή για έλεγχο αν είναι null. |

### Τιμή Επιστροφής

True αν το αντικείμενο συγκρίνεται με nullptr ως true, false διαφορετικά.

## TestTools::IsNull(const SharedPtr\<T\>\&) μέθοδος


Ελέγχει αν η συγκεκριμένη τιμή είναι null. [Version](../../version/) για μη-αριθμητικούς τύπους τιμών.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Type of value being checked. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | Τιμή για έλεγχο αν είναι null. |

### Τιμή Επιστροφής

True αν το αντικείμενο συγκρίνεται με nullptr ως true, false διαφορετικά.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) μέθοδος


Ελέγχει αν η συγκεκριμένη τιμή είναι null. [Version](../../version/) για ζευγάρια κλειδιού-τιμής.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| K | Key type. |
| V | Value type. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | Αντικείμενο ζεύγους. |

### Τιμή Επιστροφής

True αν το ζεύγος θεωρείται null, false διαφορετικά.

## TestTools::IsNull(const System::String\&) μέθοδος


Ελέγχει αν η συμβολοσειρά είναι null.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) για έλεγχο. |

### Τιμή Επιστροφής

True αν η συμβολοσειρά θεωρείται null, false διαφορετικά.

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Κλάση [String](../../string/)
* Struct [TestTools](../)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)