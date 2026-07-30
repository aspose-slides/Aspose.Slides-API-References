---
title: BeginRead()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Iniciuje asynchronní operaci čtení.
type: docs
weight: 157
url: /cs/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) metoda


Iniciuje asynchronní operaci čtení.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer, do kterého se čte |
| offset | int | Posun založený na nule v **buffer**, který určuje pozici, odkud začít zapisovat načtená data |
| count | int | Počet bajtů, které se mají přečíst |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Callback, který se zavolá po dokončení operace |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Uživatelem poskytnutá data používaná k jednoznačnému identifikování každé asynchronní operace čtení |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující iniciovanou asynchronní operaci čtení

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Object](../../../system/object/)
* Třída [Stream](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)