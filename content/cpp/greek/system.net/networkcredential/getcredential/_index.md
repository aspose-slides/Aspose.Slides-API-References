---
title: GetCredential()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει διαπιστευτήρια για το καθορισμένο URI και τύπο αυθεντικοποίησης.
type: docs
weight: 92
url: /el/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) μέθοδος

Επιστρέφει διαπιστευτήρια για το καθορισμένο URI και τύπο αυθεντικοποίησης.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Το URI. |
| authenticationType | [String](../../../system/string/) | Τύπος αυθεντικοποίησης. |

## NetworkCredential::GetCredential(String, int32_t, String) μέθοδος

Επιστρέφει διαπιστευτήρια για το καθορισμένο όνομα κεντρικού υπολογιστή, θύρα και τύπο αυθεντικοποίησης.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| host | [String](../../../system/string/) | Το όνομα κεντρικού υπολογιστή. |
| port | **int32_t** | Αριθμός θύρας. |
| authenticationType | [String](../../../system/string/) | Τύπος αυθεντικοποίησης. |

## Δείτε επίσης

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [NetworkCredential](../)
* Κλάση [Uri](../../../system/uri/)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Net](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)