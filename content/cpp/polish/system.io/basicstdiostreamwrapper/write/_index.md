---
title: Write()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Jeśli tryb owinięcia jest binarny, zapisuje do strumienia określony podzakres bajtów z podanej tablicy bajtów, w przeciwnym razie konwertuje określony podzakres bajtów z podanej tablicy bajtów na typ char_type, a następnie zapisuje wynik do strumienia.
type: docs
weight: 79
url: /pl/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Jeśli tryb owinięcia jest binarny, zapisuje do strumienia określony podzakres bajtów z określonej tablicy bajtów, w przeciwnym razie konwertuje określony podzakres bajtów z określonej tablicy bajtów na typ char_type i następnie zapisuje wynik do strumienia.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica zawierająca bajty do zapisania |
| offset | **int32_t** | Indeks 0-bazowy elementu w **buffer**, od którego zaczyna się podzakres do zapisania |
| count | **int32_t** | Liczba elementów w podzakresie do zapisania |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Zapisuje określony podzakres bajtów z określonej tablicy bajtów do strumienia.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Widok tablicy zawierający bajty do zapisania |
| offset | **int32_t** | Indeks 0-bazowy elementu w **buffer**, od którego zaczyna się podzakres do zapisania |
| count | **int32_t** | Liczba elementów w podzakresie do zapisania |

## Zobacz też

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [BasicSTDIOStreamWrapper](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)