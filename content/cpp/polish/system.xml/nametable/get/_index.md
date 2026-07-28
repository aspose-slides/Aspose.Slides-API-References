---
title: Get()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zwraca atomizowany ciąg znaków o podanej wartości.
type: docs
weight: 27
url: /pl/system.xml/nametable/get/
---
## NameTable::Get(const String\&) method

Zwraca atomizowany ciąg znaków o podanej wartości.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Nazwa do znalezienia. |

### Wartość zwracana

Obiekt atomizowanego ciągu znaków lub **nullptr**, jeśli ciąg nie został jeszcze atomizowany.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method

Zwraca atomizowany ciąg znaków zawierający te same znaki, co określony zakres znaków w podanej tablicy.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Tablica znaków zawierająca nazwę do znalezienia. |
| start | **int32_t** | Indeks zerowy w tablicy określający pierwszy znak nazwy. |
| len | **int32_t** | Liczba znaków w nazwie. |

### Wartość zwracana

Atomizowany ciąg znaków lub **nullptr**, jeśli ciąg nie został jeszcze atomizowany. Jeśli **len** jest zero, zwracane jest [String::Empty](../../../system/string/empty/).

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [NameTable](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)