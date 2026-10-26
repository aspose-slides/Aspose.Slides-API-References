---
title: Write()
second_title: Odwołanie API Aspose.Slides dla C++
description: Jeśli tryb opakowywania jest binarny, zapisuje do strumienia określony podzakres bajtów z podanej tablicy bajtów, w przeciwnym razie konwertuje określony podzakres bajtów z podanej tablicy bajtów do typu char_type i zapisuje wynik do strumienia.
type: docs
weight: 79
url: /pl/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Jeśli tryb opakowywania jest binarny, zapisuje do strumienia określony podzakres bajtów z podanej tablicy bajtów, w przeciwnym razie konwertuje określony podzakres bajtów z podanej tablicy bajtów do typu char_type i zapisuje wynik do strumienia.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica zawierająca bajty do zapisania |
| offset | **int32_t** | Indeks zerowy elementu w **buffer**, od którego rozpoczyna się podzakres do zapisania |
| count | **int32_t** | Liczba elementów w podzakresie do zapisania |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Zapisuje określony podzakres bajtów z podanej tablicy bajtów do strumienia.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Widok tablicy zawierający bajty do zapisania |
| offset | **int32_t** | Indeks zerowy elementu w **buffer**, od którego rozpoczyna się podzakres do zapisania |
| count | **int32_t** | Liczba elementów w podzakresie do zapisania |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)