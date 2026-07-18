---
title: Remove()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αφαιρεί τα διαπιστευτήρια δικτύου για το καθορισμένο πρόθεμα URI και τον τύπο πιστοποίησης.
type: docs
weight: 53
url: /el/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) μέθοδος

Αφαιρεί τα διαπιστευτήρια δικτύου για το καθορισμένο πρόθεμα URI και τον τύπο πιστοποίησης.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Το πρόθεμα URI. |
| authenticationType | [String](../../../system/string/) | Ο τύπος πιστοποίησης. |

## CredentialCache::Remove(String, int32_t, String) μέθοδος

Αφαιρεί τα διαπιστευτήρια δικτύου για το καθορισμένο όνομα κεντρικού υπολογιστή, θύρα και τύπο πιστοποίησης.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| host | [String](../../../system/string/) | Το όνομα κεντρικού υπολογιστή με το οποίο σχετίζονται τα διαπιστευτήρια. |
| port | **int32_t** | Ο αριθμός θύρας. |
| authenticationType | [String](../../../system/string/) | Ένας τύπος πιστοποίησης. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Uri](../../../system/uri/)
* Κλάση [String](../../../system/string/)
* Κλάση [CredentialCache](../)
* Χώρος ονομάτων [System::Net](../../)
* Library [Aspose.Slides](../../../)