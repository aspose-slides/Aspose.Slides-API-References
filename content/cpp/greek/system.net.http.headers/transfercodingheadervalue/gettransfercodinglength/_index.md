---
title: GetTransferCodingLength()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει μια δοσμένη συμβολοσειρά από τον καθορισμένο δείκτη σε μια παρουσία της κλάσης TransferCodingHeaderValue.
type: docs
weight: 105
url: /el/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) μέθοδος


Μετατρέπει μια δοσμένη συμβολοσειρά από το καθορισμένο δείκτη σε ένα αντικείμενο της κλάσης [TransferCodingHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | [String](../../../system/string/) | Μία συμβολοσειρά προς ανάλυση. |
| startIndex | **int32_t** | Μια θέση εκκίνησης για ανάλυση. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | Μια εμφάνιση στην οποία θα εκχωρηθεί ένα αναλυμένο αντικείμενο. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | Ο delegate που χρησιμοποιείται για τη δημιουργία εμφανίσεων της κλάσης [TransferCodingHeaderValue](../). |

### Τιμή Επιστροφής

Επιστρέφει το μήκος ενός αναλυμένου υποσυμβολοσειράς, διαφορετικά 0.

## Δείτε επίσης

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [TransferCodingHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)