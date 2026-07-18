---
title: InitObject()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ξεκινά την αρχικοποίηση ενός αντικειμένου με κοινή ιδιοκτησία.
type: docs
weight: 2237
url: /el/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) συνάρτηση


Ξεκινά την αρχικοποίηση ενός αντικειμένου με κοινή ιδιοκτησία.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Τύπος αντικειμένου για αρχικοποίηση |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) για αρχικοποίηση |

### Τιμή Επιστροφής

ObjectBuilder ρυθμισμένο για κατασκευή shared pointer

## Σχόλια



[Object](../object/) η αρχικοποίηση πρέπει να ολοκληρωθεί με [Get()](../get/) κλήση 

## Δείτε επίσης

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)