---
title: BeginWrite()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Spouští asynchronní operaci zápisu.
type: docs
weight: 170
url: /cs/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) metoda

Spouští asynchronní operaci zápisu.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Vyrovnávací paměť obsahující data k zápisu |
| offset | int | Posun založený na nule v **buffer**, který určuje pozici, odkud začínají data k zápisu |
| count | int | Počet bajtů k zápisu |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Zpětné volání, které se zavolá po dokončení operace |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Uživatelem poskytnutá data používaná k jednoznačné identifikaci každé asynchronní zápisové operace |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující zahájenou asynchronní operaci zápisu

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Object](../../../system/object/)
* Třída [Stream](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)