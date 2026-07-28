---
title: BeginWrite()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Inicjuje asynchroniczną operację zapisu.
type: docs
weight: 274
url: /pl/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metoda

Inicjuje asynchroniczną operację zapisu.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufor zawierający dane do zapisania. |
| offset | **int32_t** | Offset w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów do zapisu. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Callback do wywołania po zakończeniu operacji. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika używane do jednoznacznego identyfikowania każdej asynchronicznej operacji zapisu. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący zainicjowaną asynchroniczną operację zapisu.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [Object](../../../system/object/)
* Klasa [NetworkStream](../)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)