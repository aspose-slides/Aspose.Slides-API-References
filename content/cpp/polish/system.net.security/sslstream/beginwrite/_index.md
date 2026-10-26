---
title: BeginWrite()
second_title: Referencja API Aspose.Slides dla C++
description: Inicjuje asynchroniczną operację zapisu.
type: docs
weight: 443
url: /pl/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metoda

Inicjuje asynchroniczną operację zapisu.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica bajtów, do której zapisywane są dane. |
| offset | **int32_t** | Przesunięcie w bajtach w określonej tablicy. |
| count | **int32_t** | Liczba bajtów do zapisania. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne, które zostanie wywołane po zakończeniu operacji. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika, używane do jednoznacznej identyfikacji każdej asynchronicznej operacji zapisu. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący zainicjowaną asynchroniczną operację zapisu.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Definicja typu [AsyncCallback](../../../system/asynccallback/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [Object](../../../system/object/)
* Klasa [SslStream](../)
* Przestrzeń nazw [System::Net::Security](../../)
* Biblioteka [Aspose.Slides](../../../)