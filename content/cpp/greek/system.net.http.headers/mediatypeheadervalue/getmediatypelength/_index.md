---
title: GetMediaTypeLength()
second_title: Aspose.Slides για C++ API Reference
description: Μετατρέπει μια δοθείσα συμβολοσειρά από το συγκεκριμένο ευρετήριο σε ένα στιγμιότυπο της κλάσης MediaTypeHeaderValue.
type: docs
weight: 144
url: /el/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) μέθοδος

Μετατρέπει μια δοθείσα συμβολοσειρά από το συγκεκριμένο ευρετήριο σε ένα στιγμιότυπο της κλάσης [MediaTypeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Μια συμβολοσειρά προς ανάλυση. |
| startIndex | **int32_t** | Θέση έναρξης για την ανάλυση. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | Ο delegate που χρησιμοποιείται για τη δημιουργία εμφανίσεων της κλάσης [MediaTypeHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | Μια εμφάνιση όπου θα ανατεθεί το παρασυθέν αντικείμενο. |

### Return Value

Επιστρέφει το μήκος ενός παρασυθέντος υποσυμβολοσειρά, διαφορετικά 0.

## Δείτε επίσης

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [MediaTypeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)