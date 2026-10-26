---
title: GetChildRows()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει γραμμές που θεωρούνται θυγατρικές μέσω καθορισμένης σχέσης.
type: docs
weight: 27
url: /el/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) μέθοδος

Λαμβάνει γραμμές που θεωρούνται θυγατρικές μέσω της καθορισμένης σχέσης.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### Παραμέτρους

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | Αντικείμενο σχέσης για τον καθορισμό της σχέσης γονέα γραμμής - θυγατρικής γραμμής. |

### Τιμή Επιστροφής

[Array](../../../system/array/) των θυγατρικών γραμμών που ανακτήθηκαν.

## Δείτε επίσης

* Τύπο [ArrayPtr](../../../system/arrayptr/)
* Τύπο [SharedPtr](../../../system/sharedptr/)
* Κλάση [DataRow](../)
* Κλάση [DataRelation](../../datarelation/)
* Χώρος ονομάτων [System::Data](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)