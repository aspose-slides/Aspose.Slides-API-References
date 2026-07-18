---
title: GetCacheControlLength()
second_title: Aspose.Slides για την Αναφορά API C++
description: Μετατρέπει μια δοθείσα συμβολοσειρά από τον καθορισμένο δείκτη σε μια παρουσία της κλάσης CacheControlHeaderValue.
type: docs
weight: 456
url: /el/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) method

Μετατρέπει μια δοθείσα συμβολοσειρά από το καθορισμένο δείκτη σε μια παρουσία της κλάσης [CacheControlHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Μια συμβολοσειρά για ανάλυση. |
| startIndex | **int32_t** | Μια αρχική θέση για την ανάλυση. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | Μια τιμή που πρέπει να προστεθεί στο αναλυμένο αντικείμενο. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | Μια παρουσία στην οποία θα αντιστοιχιστεί ένα αναλυμένο αντικείμενο. |

### Τιμή Επιστροφής

Το μήκος ενός αναλυμένου υποσυμβολοσειράς, διαφορετικά 0.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [CacheControlHeaderValue](../)
* Χώρος ονομάτων [System::Net::Http::Headers](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)