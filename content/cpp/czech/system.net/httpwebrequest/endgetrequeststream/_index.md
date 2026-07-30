---
title: EndGetRequestStream()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Čeká, dokud se nedokončí zadaná asynchronní operace získání proudu.
type: docs
weight: 482
url: /cs/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metoda

Čeká, dokud se nedokončí zadaná asynchronní operace získání proudu.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Objekt [IAsyncResult](../../../system/iasyncresult/) představující asynchronní operaci získání proudu. |

### Návratová hodnota

Proud pro zápis dat do zdroje.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Stream](../../../system.io/stream/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [HttpWebRequest](../)
* Jmenný prostor [System::Net](../../)
* Library [Aspose.Slides](../../../)