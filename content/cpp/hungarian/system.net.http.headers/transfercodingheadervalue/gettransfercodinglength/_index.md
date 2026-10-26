---
title: GetTransferCodingLength()
second_title: Aspose.Slides C++ API hivatkozás
description: Átalakítja a megadott karakterláncot a megadott indexről a TransferCodingHeaderValue osztály egy példányává.
type: docs
weight: 105
url: /hu/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) method


Átalakítja a megadott karakterláncot a meghatározott indexről a [TransferCodingHeaderValue](../) osztály egy példányává.

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | [String](../../../system/string/) | Feldolgozandó karakterlánc. |
| startIndex | **int32_t** | A feldolgozás kezdőpozíciója. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | Egy példány, amelybe a feldolgozott objektum lesz hozzárendelve. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | Az a delegált, amely a [TransferCodingHeaderValue](../) osztály példányainak létrehozására szolgál. |

### Visszatérési érték

A feldolgozott részkarakterlánc hosszát adja vissza, egyébként 0.

## Lásd még

* typedef [HeaderFunc](../../headerfunc/)
* typedef [SharedPtr](../../../system/sharedptr/)
* osztály [String](../../../system/string/)
* osztály [TransferCodingHeaderValue](../)
* névtér [System::Net::Http::Headers](../../)
* könyvtár [Aspose.Slides](../../../)