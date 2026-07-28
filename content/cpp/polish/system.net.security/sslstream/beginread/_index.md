---
title: BeginRead()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Inicjuje asynchroniczną operację odczytu.
type: docs
weight: 417
url: /pl/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metoda

Inicjuje asynchroniczną operację odczytu.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów, z której odczytywane są dane. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| count | **int32_t** | Liczba bajtów do odczytania. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne, które zostanie wywołane po zakończeniu operacji. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika, używane do jednoznacznego identyfikowania każdej asynchronicznej operacji odczytu. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący zainicjowaną asynchroniczną operację odczytu.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [Object](../../../system/object/)
* Klasa [SslStream](../)
* Przestrzeń nazw [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)