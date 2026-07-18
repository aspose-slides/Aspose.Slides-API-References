---
title: Ref()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δημιουργεί αναφορά σε αντικείμενο DynamicWeakPtr. Χρησιμοποιείται από το μεταγλωττιστή όταν περνιούνται επιχειρήματα συνάρτησης με αναφορά.
type: docs
weight: 2419
url: /el/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) συνάρτηση


Δημιουργεί αναφορά στο αντικείμενο [DynamicWeakPtr](../dynamicweakptr/). Χρησιμοποιείται από το μεταγλωττιστή όταν περνιούνται επιχειρήματα συνάρτησης με αναφορά.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος του αντικειμένου που δείχνει. |
| trunkMode | Κατάσταση του έξυπνου δείκτη. |
| weakLeafs | Ευρετήρια των παραμέτρων προτύπου για τις οποίες πρέπει να κληθεί η μέθοδος SetTemplateWeakPtr. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Έξυπνος δείκτης στον οποίο δημιουργείται η αναφορά. |

### Τιμή επιστροφής

Αναφορά σε έξυπνο δείκτη.

## System::Ref(T\&) συνάρτηση


Βοηθητική συνάρτηση για την απόκτηση αναφορών σε αντικείμενα. Χρησιμοποιείται για να εγγυηθεί ότι το [System::DynamicWeakPtr](../dynamicweakptr/) ενημερώνει το αναφερόμενο αντικείμενο μετά τις εκχωρήσεις.

```cpp
template<typename T> T & System::Ref(T &value)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος του αντικειμένου στον οποίο θα δημιουργηθεί η αναφορά. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | T\& | Τιμή στην οποία θα δημιουργηθεί η αναφορά. |

### Τιμή επιστροφής

Αναφορά στην τιμή που περάστηκε σε αυτή τη συνάρτηση.

## Δείτε επίσης

* Class [DynamicWeakPtr](../dynamicweakptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)