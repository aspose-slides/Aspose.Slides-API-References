---
title: EndGetRequestStream()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Čeká, dokud nedojde k dokončení určené asynchronní operace získání proudu.
type: docs
weight: 157
url: /cs/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metoda

Čeká, dokud nedojde k dokončení zadané asynchronní operace získání proudu.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Třída [FileWebRequest](../)
* Jmenný prostor [System::Net](../../)
* Knihovna [Aspose.Slides](../../../)