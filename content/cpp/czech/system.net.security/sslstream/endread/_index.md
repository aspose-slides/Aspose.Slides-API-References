---
title: EndRead()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Čeká, dokud nedokončí zadanou asynchronní operaci čtení.
type: docs
weight: 430
url: /cs/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) metoda

Čeká, dokud nedokončí zadanou asynchronní operaci čtení.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Objekt [IAsyncResult](../../../system/iasyncresult/), který představuje asynchronní operaci čtení |

### Návratová hodnota

Počet bytů přečtených během operace čtení reprezentované **asyncResult**

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [SslStream](../)
* Jmenný prostor [System::Net::Security](../../)
* Knihovna [Aspose.Slides](../../../)