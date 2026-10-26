---
title: VerifySetDefaults()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιβεβαιώνει και ορίζει τις προεπιλεγμένες τιμές των χαρακτηριστηρίων.
type: docs
weight: 482
url: /el/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) μέθοδος

Επιβεβαιώνει και θέτει τις προεπιλεγμένες τιμές των χαρακτηριστηρίων.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | Η προδιαγραφή του cookie. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Η περίπτωση της κλάσης Uri που χρησιμοποιείται για την αρχικοποίηση των εσωτερικών πεδίων. |
| isLocalDomain | **bool** | Μια τιμή που υποδεικνύει αν το cookie προωθείται στον τοπικό τομέα. |
| localDomain | [String](../../../system/string/) | Ένα όνομα τοπικού τομέα. |
| setDefault | **bool** | Μια τιμή που υποδεικνύει αν τα χαρακτηριστικά του cookie πρέπει να αρχικοποιηθούν χρησιμοποιώντας τις προεπιλεγμένες τιμές. |
| shouldThrow | **bool** | Μια τιμή που υποδεικνύει αν πρέπει να εξαπολυθεί μια εξαίρεση όταν οι καθορισμένες τιμές είναι μη έγκυρες. |

### Return Value

Αληθές όταν όλες οι τιμές είναι έγκυρες, διαφορετικά ψευδές.

## Δείτε επίσης

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [Cookie](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)