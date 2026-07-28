---
title: BeginRead()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Inicjuje asynchroniczną operację odczytu.
type: docs
weight: 248
url: /pl/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metoda

Inicjuje asynchroniczną operację odczytu.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów, w której zostaną zapisane odczytane bajty. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów do odczytu. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne, które zostanie wywołane po zakończeniu operacji. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika używane do jednoznacznej identyfikacji każdej asynchronicznej operacji odczytu. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący zainicjowaną asynchroniczną operację odczytu.

## Zobacz również

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [Object](../../../system/object/)
* Klasa [NetworkStream](../)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Biblioteka [Aspose.Slides](../../../)