---
title: BeginGetRequestStream()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Spouští asynchronní operaci pro získání proudu pro zápis dat do zdroje.
type: docs
weight: 469
url: /cs/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) metoda


Spouští asynchronní operaci pro získání proudu pro zápis dat do zdroje.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Zpětné volání, které bude voláno po dokončení operace. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data používaná k jedinečné identifikaci každé asynchronní operace. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující zahájenou asynchronní operaci.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Object](../../../system/object/)
* Třída [HttpWebRequest](../)
* Jmenný prostor [System::Net](../../)
* Knihovna [Aspose.Slides](../../../)