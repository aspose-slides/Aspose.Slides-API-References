---
title: IsEmpty()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ελέγχει αν η συμβολοσειρά είναι κενή.
type: docs
weight: 14
url: /el/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) μέθοδος


Ελέγχει αν η συμβολοσειρά είναι κενή.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) για έλεγχο κενότητας. |

### Τιμή επιστροφής

Αληθές αν η συμβολοσειρά είναι κενή (μηδενικού μήκους), ψευδές διαφορετικά.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) μέθοδος


Ελέγχει αν η συλλογή είναι κενή.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος συλλογής. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Συλλογή για έλεγχο. |

### Τιμή επιστροφής

Αληθές αν η συλλογή έχει μηδενικό πλήθος στοιχείων, ψευδές διαφορετικά.

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Struct [TestTools](../)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)