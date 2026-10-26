---
title: ConstrainedCopy()
second_title: Aspose.Slides για Αναφορά API C++
description: Αντιγράφει μια περιοχή στοιχείων από ένα System.Array που ξεκινά από την καθορισμένη πηγή.
type: docs
weight: 716
url: /el/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) μέθοδος


Αντιγράφει μια περιοχή στοιχείων από ένα [System.Array](../) που ξεκινά από την καθορισμένη πηγή.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| SrcType | Τύπος των στοιχείων στον πηγαίο πίνακα |
| DstType | Τύπος των στοιχείων στον πίνακα προορισμού |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Πίνακας πηγής |
| srcIndex | **int64_t** | Δείκτης στον πηγαίο πίνακα που προσδιορίζει την αρχή της περιοχής των στοιχείων προς αντιγραφή |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Πίνακας προορισμού |
| dstIndex | **int64_t** | Δείκτης στον πίνακα προορισμού για να ξεκινήσει η εισαγωγή των αντιγραμμένων στοιχείων |
| count | **int64_t** | Αριθμός των στοιχείων προς αντιγραφή |
## Σχόλια


ΠΡΟΤΟΡΙΚΗ ΑΓΚΥΡΗ ΥΛΟΠΟΙΗΣΗ ΧΩΡΙΣ ΚΑΜΙΑ ΔΙΟΡΘΩΣΗ!
## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Κλάση [Array](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)