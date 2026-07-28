---
title: Write()
second_title: Aspose.Slides dla C++ Referencja API
description: Jeśli tryb opakowywania jest binary, zapisuje do strumienia określony podzakres bajtów z podanej tablicy bajtów, w przeciwnym razie konwertuje określony podzakres bajtów z podanej tablicy bajtów na typ char_type, a następnie zapisuje wynik do strumienia. Nieobsługiwane!
type: docs
weight: 79
url: /pl/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Jeśli tryb opakowywania jest binary, zapisuje do strumienia określony podzakres bajtów z podanej tablicy bajtów, w przeciwnym razie konwertuje określony podzakres bajtów z podanej tablicy bajtów na typ char_type, a następnie zapisuje wynik do strumienia. Nieobsługiwane!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica zawierająca bajty do zapisania. |
| offset | **int32_t** | Indeks oparty na zerze w **buffer**, w którym zaczyna się podzakres do zapisu. |
| count | **int32_t** | Liczba elementów w podzakresie do zapisu. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Zapisuje określony podzakres bajtów z podanej tablicy bajtów do strumienia.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Widok tablicy zawierający bajty do zapisania |
| offset | **int32_t** | Indeks oparty na zerze w **buffer**, w którym zaczyna się podzakres do zapisu |
| count | **int32_t** | Liczba elementów w podzakresie do zapisu |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [BasicSTDIStreamWrapper](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)