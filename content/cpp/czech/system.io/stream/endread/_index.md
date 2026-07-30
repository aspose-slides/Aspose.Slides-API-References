---
title: EndRead()
second_title: Aspose.Slides pro C++ referenci API
description: Čeká, dokud nedokončí zadaná asynchronní operace čtení.
type: docs
weight: 183
url: /cs/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) metoda


Čeká, dokud nedokončí zadaná asynchronní operace čtení.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | Objekt [IAsyncResult](../../../system/iasyncresult/), který představuje asynchronní operaci čtení |

### Návratová hodnota

Počet bajtů přečtených během operace čtení reprezentované **asyncResult**

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Stream](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)