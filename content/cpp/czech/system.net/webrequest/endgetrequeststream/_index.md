---
title: EndGetRequestStream()
second_title: Aspose.Slides pro C++ API Reference
description: Čeká, dokud nedojde k dokončení zadané asynchronní operace získání proudu.
type: docs
weight: 313
url: /cs/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metoda


Čeká, dokud nedojde k dokončení zadané asynchronní operace získání proudu.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Objekt [IAsyncResult](../../../system/iasyncresult/), který představuje asynchronní operaci pro získání proudu. |

### Návratová hodnota

Proud pro zápis dat do zdroje.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Stream](../../../system.io/stream/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [WebRequest](../)
* Jmenný prostor [System::Net](../../)
* Library [Aspose.Slides](../../../)