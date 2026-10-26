---
title: ValueTuple
second_title: Aspose.Slides για C++ Αναφορά API
description: Κλάση που αντιπροσωπεύει μια δομή δεδομένων ValueTuple.
type: docs
weight: 1418
url: /el/system/valuetuple/
---
## ValueTuple κλάση

Κλάση που αντιπροσωπεύει μια [ValueTuple](./) δομή δεδομένων.

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | Καθορίζει εάν τα τρέχοντα και τα συγκεκριμένα αντικείμενα είναι πανομοιότυπα. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<Index, tuple_t\>\& [Item](./item/)() | Αποκτά την αναφορά στην τιμή του στοιχείου του αντικειμένου [ValueTuple](./). |
| const std::tuple_element_t\<Index, tuple_t\>\& [Item](./item/)() const | Αποκτά την τιμή του στοιχείου του αντικειμένου [ValueTuple](./). |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Αποδομεί το αντικείμενο σε αυτήν την πλειάδα τιμών. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Επιστρέφει μια αναφορά στο αντικείμενο [TypeInfo](../typeinfo/) που αντιπροσωπεύει τις πληροφορίες τύπου κλάσης [ValueTuple](./). |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | Δημιουργεί ένα αντικείμενο tuple. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)