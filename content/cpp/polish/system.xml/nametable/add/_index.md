---
title: Add()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Atomizuje podany ciąg znaków i dodaje go do NameTable.
type: docs
weight: 14
url: /pl/system.xml/nametable/add/
---
## NameTable::Add(const String\&) metoda

Atomizuje podany ciąg znaków i dodaje go do [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | Ciąg znaków do dodania. |

### Wartość zwracana

Atomizowany ciąg znaków lub istniejący ciąg, jeśli już znajduje się w [NameTable](../).

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metoda

Atomizuje podany ciąg znaków i dodaje go do [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Tablica znaków zawierająca ciąg znaków do dodania. |
| start | **int32_t** | Indeks zerowy w tablicy określający pierwszy znak ciągu. |
| len | **int32_t** | Liczba znaków w ciągu. |

### Wartość zwracana

Atomizowany ciąg znaków lub istniejący ciąg, jeśli już istnieje w [NameTable](../). Jeśli **len** jest zerowy, zwracany jest [String::Empty](../../../system/string/empty/).

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [NameTable](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)