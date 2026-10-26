---
title: Get()
second_title: Aspose.Slides for C++ - odwołanie do API
description: Gdy zostanie przesłonięta w klasie pochodnej, zwraca atomizowany łańcuch zawierający te same znaki, co określony zakres znaków w podanej tablicy.
type: docs
weight: 1
url: /pl/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


Gdy zostanie przesłonięta w klasie pochodnej, zwraca atomizowany łańcuch zawierający te same znaki co określony zakres znaków w podanej tablicy.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Tablica znaków zawierająca nazwę do wyszukania. |
| offset | **int32_t** | Indeks zerowy w tablicy określający pierwszy znak nazwy. |
| length | **int32_t** | Liczba znaków w nazwie. |

### Wartość zwracana

Atomizowany łańcuch lub **nullptr**, jeśli łańcuch nie został jeszcze atomizowany. Jeśli **length** jest równy zero, [String::Empty](../../../system/string/empty/) jest zwracany.

## XmlNameTable::Get(const String\&) method


Gdy zostanie przesłonięta w klasie pochodnej, zwraca atomizowany łańcuch zawierający tę samą wartość co podany łańcuch.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Nazwa do wyszukania. |

### Wartość zwracana

Atomizowany łańcuch lub **nullptr**, jeśli łańcuch nie został jeszcze atomizowany.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)