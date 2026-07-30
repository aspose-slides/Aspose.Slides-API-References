---
title: IsBypassed()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací hodnotu, která určuje, zda proxy nesmí být použita pro zadaného hostitele.
type: docs
weight: 40
url: /cs/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) metoda

Vrací hodnotu, která určuje, zda proxy nesmí být použita pro zadaný hostitel.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI hostitele k ověření. |

### Návratová hodnota

True, když proxy server nesmí být použit, jinak false.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Uri](../../../system/uri/)
* Třída [IWebProxy](../)
* Jmenný prostor [System::Net](../../)
* Knihovna [Aspose.Slides](../../../)