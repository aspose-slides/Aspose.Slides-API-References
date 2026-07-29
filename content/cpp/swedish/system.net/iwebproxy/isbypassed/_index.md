---
title: IsBypassed()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett värde som indikerar om proxyservern inte får användas för den angivna värden.
type: docs
weight: 40
url: /sv/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) metod

Returnerar ett värde som anger om proxyn inte får användas för den angivna värden.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Värdens URI att kontrollera. |

### Returvärde

Sant när proxyservern inte får användas, annars falskt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Uri](../../../system/uri/)
* Klass [IWebProxy](../)
* Namnrymd [System::Net](../../)
* Library [Aspose.Slides](../../../)