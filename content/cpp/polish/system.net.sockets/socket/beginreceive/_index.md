---
title: BeginReceive()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Inicjuje asynchroniczną operację zapisu.
type: docs
weight: 521
url: /pl/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) metoda


Inicjuje operację zapisu asynchronicznego.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufor, w którym zostaną zapisane odebrane dane. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| size | **int32_t** | Liczba bajtów w określonej tablicy zaczynająca się od parametru 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Zachowanie odbioru. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne, które zostanie wywołane po zakończeniu operacji. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika używane do jednoznacznej identyfikacji każdej asynchronicznej operacji odbioru. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący rozpoczętą asynchroniczną operację odbioru.

## Zobacz także

* Wyliczenie [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [Object](../../../system/object/)
* Klasa [Socket](../)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Biblioteka [Aspose.Slides](../../../)