---
title: EndRead()
second_title: Aspose.Slides pro C++ API Reference
description: Čeká, dokud nedokončí zadaná asynchronní operace čtení.
type: docs
weight: 261
url: /cs/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) metoda

Čeká, dokud nedokončí zadaná asynchronní operace čtení.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) objekt, který představuje asynchronní operaci čtení |

### Návratová hodnota

Počet bajtů přečtených během operace čtení reprezentované **asyncResult**

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [NetworkStream](../)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)