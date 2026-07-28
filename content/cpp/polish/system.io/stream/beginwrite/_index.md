---
title: BeginWrite()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Inicjuje asynchroniczną operację zapisu.
type: docs
weight: 170
url: /pl/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) metoda

Inicjuje asynchroniczną operację zapisu.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufor zawierający dane do zapisania |
| offset | int | Przesunięcie zerobazowe w **buffer**, wskazujące pozycję, od której rozpoczynają się dane do zapisania |
| count | int | Liczba bajtów do zapisania |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne, które zostanie wywołane po zakończeniu operacji |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Dane dostarczone przez użytkownika, używane do jednoznacznej identyfikacji każdej asynchronicznej operacji zapisu |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący zainicjowaną asynchroniczną operację zapisu

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Definicja typu [AsyncCallback](../../../system/asynccallback/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [Object](../../../system/object/)
* Klasa [Stream](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)