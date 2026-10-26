---
title: BeginWrite()
second_title: Aspose.Slides C++ API referenciája
description: Elindít egy aszinkron írási műveletet.
type: docs
weight: 443
url: /hu/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metódus


Elindít egy aszinkron írási műveletet.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A bájt tömb, amelybe az adatokat írja. |
| offset | **int32_t** | Az eltolás bájtokban a megadott tömbben. |
| count | **int32_t** | Az írandó bájtok száma. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Visszahívás, amelyet a művelet befejezésekor hívnak meg. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | A felhasználó által megadott adatok, amelyek egyedi azonosítást biztosítanak minden aszinkron írási művelethez. |

### Visszatérési érték

[IAsyncResult](../../../system/iasyncresult/) objektum, amely az elindított aszinkron írási műveletet képviseli.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Object](../../../system/object/)
* Osztály [SslStream](../)
* Névtér [System::Net::Security](../../)
* Könyvtár [Aspose.Slides](../../../)