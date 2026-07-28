---
title: MemoryStream()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy nową instancję klasy MemoryStream z początkową pojemnością równą 0.
type: docs
weight: 1
url: /pl/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() konstruktor


Tworzy nową instancję klasy [MemoryStream](../) z początkową pojemnością równą 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) konstruktor


Tworzy nową instancję klasy [MemoryStream](../) reprezentującej strumień oparty na buforze pamięci o podanym rozmiarze.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| capacity_ | int | Rozmiar w bajtach bufora pamięci powiązanego ze strumieniem reprezentowanym przez tworzony obiekt |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) konstruktor


Tworzy nową instancję klasy [MemoryStream](../) reprezentującej strumień pamięci podłączony do określonego bufora pamięci. Parametr określa, czy strumień jest zapisywalny.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów używana jako bufor pamięci, na którym oparty będzie strumień reprezentowany przez tworzony obiekt |
| writable | **bool** | Określa, czy strumień powinien być zapisywalny |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) konstruktor


Tworzy nową instancję klasy [MemoryStream](../) reprezentującej strumień pamięci podłączony do segmentu określonego bufora pamięci rozpoczynającego się w podanym indeksie i obejmującego podaną liczbę elementów. Parametry określają, czy strumień jest zapisywalny oraz czy metoda GetBytes() może być wywołana.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów, z której segment ma być użyty jako bufor pamięci, na którym oparty będzie strumień reprezentowany przez tworzony obiekt |
| index | int | Indeks (liczony od zera) elementu w **content**, od którego zaczyna się segment |
| count | int | Liczba elementów **content** włączonych do segmentu |
| writable | **bool** | Określa, czy strumień powinien być zapisywalny |
| publiclyVisible | **bool** | Określa, czy podstawowy bufor pamięci powinien być udostępniony wywołującemu metodę GetByte() |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [MemoryStream](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)