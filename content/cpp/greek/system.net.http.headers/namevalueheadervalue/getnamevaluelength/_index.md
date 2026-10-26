---
title: GetNameValueLength()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει μια δοσμένη συμβολοσειρά από το καθορισμένο ευρετήριο σε μια παρουσία της κλάσης NameValueHeaderValue.
type: docs
weight: 118
url: /el/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) μέθοδος


Μετατρέπει μια δοσμένη συμβολοσειρά από το καθορισμένο ευρετήριο σε μια παρουσία της [NameValueHeaderValue](../) κλάσης.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Μια συμβολοσειρά προς ανάλυση. |
| startIndex | **int32_t** | Μια θέση έναρξης για την ανάλυση. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Μια παρουσία στην οποία θα εκχωρηθεί το αναλυμένο αντικείμενο. |

### Τιμή Επιστροφής

Επιστρέφει το μήκος ενός αναλυμένου υποσυμβολοσειράς, διαφορετικά 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) μέθοδος


Μετατρέπει μια δοσμένη συμβολοσειρά από το καθορισμένο ευρετήριο σε μια παρουσία της [NameValueHeaderValue](../) κλάσης.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Μια συμβολοσειρά προς ανάλυση. |
| startIndex | **int32_t** | Μια θέση έναρξης για την ανάλυση. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | Μια συνάρτηση που χρησιμοποιείται για τη δημιουργία νέων παρουσιών της [NameValueHeaderValue](../) κλάσης. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Μια παρουσία στην οποία θα εκχωρηθεί το αναλυμένο αντικείμενο. |

### Τιμή Επιστροφής

Επιστρέφει το μήκος ενός αναλυμένου υποσυμβολοσειράς, διαφορετικά 0.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Class [String](../../../system/string/)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)