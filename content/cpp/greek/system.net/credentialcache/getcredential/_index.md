---
title: GetCredential()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει διαπιστευτήρια για το καθορισμένο πρόθεμα URI και τύπο ελέγχου ταυτότητας.
type: docs
weight: 66
url: /el/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) μέθοδος

Επιστρέφει διαπιστευτήρια για το καθορισμένο πρόθεμα URI και τύπο ελέγχου ταυτότητας.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Το πρόθεμα URI. |
| authenticationType | [String](../../../system/string/) | Ένας τύπος ελέγχου ταυτότητας. |

## CredentialCache::GetCredential(String, int32_t, String) μέθοδος

Επιστρέφει διαπιστευτήρια για το καθορισμένο όνομα κεντρικού υπολογιστή, θύρα και τύπο ελέγχου ταυτότητας.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| host | [String](../../../system/string/) | Το όνομα κεντρικού υπολογιστή με το οποίο σχετίζονται τα διαπιστευτήρια. |
| port | **int32_t** | Ο αριθμός θύρας. |
| authenticationType | [String](../../../system/string/) | Ο τύπος ελέγχου ταυτότητας. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [NetworkCredential](../../networkcredential/)
* Κλάση [Uri](../../../system/uri/)
* Κλάση [String](../../../system/string/)
* Κλάση [CredentialCache](../)
* Χώρος ονομάτων [System::Net](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)