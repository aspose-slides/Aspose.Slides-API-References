---
title: Add()
second_title: Aspose.Slides για C++ Αναφορά API
description: Προσθέτει τα καθορισμένα διαπιστευτήρια δικτύου στην κρυφή μνήμη.
type: docs
weight: 40
url: /el/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) method

Προσθέτει τα καθορισμένα διαπιστευτήρια δικτύου στην κρυφή μνήμη.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Το πρόθεμα URI του πόρου με το οποίο σχετίζονται τα διαπιστευτήρια. |
| authenticationType | [String](../../../system/string/) | Το σχήμα ελέγχου ταυτότητας. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Τα διαπιστευτήρια προς προσθήκη. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) method

Προσθέτει τα καθορισμένα διαπιστευτήρια δικτύου στην κρυφή μνήμη.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| host | [String](../../../system/string/) | Το όνομα κεντρικού υπολογιστή με το οποίο σχετίζονται τα διαπιστευτήρια. |
| port | **int32_t** | Ο αριθμός θύρας. |
| authenticationType | [String](../../../system/string/) | Το σχήμα ελέγχου ταυτότητας. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Τα διαπιστευτήρια προς προσθήκη. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Uri](../../../system/uri/)
* Κλάση [String](../../../system/string/)
* Κλάση [NetworkCredential](../../networkcredential/)
* Κλάση [CredentialCache](../)
* Χώρος ονομάτων [System::Net](../../)
* Library [Aspose.Slides](../../../)