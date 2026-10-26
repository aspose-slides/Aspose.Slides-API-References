---
title: GetNameValueListLength()
second_title: Αναφορά API Aspose.Slides για C++
description: Μετατρέπει μια δοσμένη συμβολοσειρά από το καθορισμένο ευρετήριο στη συλλογή των αντικειμένων κλάσης NameValueHeaderValue και επιστρέφει το μήκος μιας επεξεργασμένης υποσυμβολοσειράς.
type: docs
weight: 131
url: /el/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) μέθοδος

Μετατρέπει μια δοσμένη συμβολοσειρά από το καθορισμένο ευρετήριο στη συλλογή των αντικειμένων κλάσης NameValueHeaderValue και επιστρέφει το μήκος ενός αναλύτου υποσυμβολοσειράς.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [String](../../../system/string/) | Μια συμβολοσειρά προς ανάλυση. |
| startIndex | **int32_t** | Μια αρχική θέση για ανάλυση. |
| delimiter | char16_t | Μια συμβολοσειρά που χρησιμοποιείται για το διαχωρισμό των στοιχείων στην καθορισμένη συμβολοσειρά. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Η παράμετρος εξόδου όπου θα ανατεθεί μια επεξεργασμένη συλλογή. |

### Τιμή Επιστροφής

Το μήκος μιας επεξεργασμένης υποσυμβολοσειράς.

## Δείτε επίσης

* Τυποπροσδιορισμός [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [ObjectCollection](../../objectcollection/)
* Κλάση [NameValueHeaderValue](../)
* Χώρος ονομάτων [System::Net::Http::Headers](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)