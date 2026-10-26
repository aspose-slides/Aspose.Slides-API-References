---
title: Add()
second_title: Aspose.Slides dla C++ - referencja API
description: Gdy metoda zostanie przesłonięta w klasie pochodnej, atomizuje podany łańcuch znaków i dodaje go do XmlNameTable.
type: docs
weight: 14
url: /pl/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metoda


Gdy metoda zostanie przesłonięta w klasie pochodnej, atomizuje podany łańcuch znaków i dodaje go do [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Tablica znaków zawierająca nazwę do dodania. |
| offset | **int32_t** | Indeks zerowy w tablicy określający pierwszy znak nazwy. |
| length | **int32_t** | Liczba znaków w nazwie. |

### Return Value

Nowy atomizowany łańcuch znaków lub istniejący, jeśli już istnieje. Jeśli długość wynosi zero, zwracane jest [String::Empty](../../../system/string/empty/).

## XmlNameTable::Add(const String\&) metoda


Gdy metoda zostanie przesłonięta w klasie pochodnej, atomizuje podany łańcuch znaków i dodaje go do [XmlNameTable](../).

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Nazwa do dodania. |

### Return Value

Nowy atomizowany łańcuch znaków lub istniejący, jeśli już istnieje.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [XmlNameTable](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)