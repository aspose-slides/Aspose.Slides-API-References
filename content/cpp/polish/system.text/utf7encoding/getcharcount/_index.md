---
title: GetCharCount()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów.
type: docs
weight: 79
url: /pl/system.text/utf7encoding/getcharcount/
---
## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metoda

Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów.

```cpp
int System::Text::UTF7Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do dekodowania. |
| index | int | Początek fragmentu. |
| count | int | Rozmiar fragmentu. |

### Wartość zwracana

Liczba znaków.

## UTF7Encoding::GetCharCount(const uint8_t *, int) metoda

Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów.

```cpp
int System::Text::UTF7Encoding::GetCharCount(const uint8_t *bytes, int count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty do dekodowania. |
| count | int | Liczba bajtów. |

### Wartość zwracana

Liczba znaków.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metoda

Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do dekodowania. |
| index | int | Początek fragmentu. |
| count | int | Rozmiar fragmentu. |

### Wartość zwracana

Liczba znaków.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>) metoda

Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bajty do dekodowania. |

### Wartość zwracana

Liczba znaków.

## UTF7Encoding::GetCharCount(const uint8_t *, int) metoda

Pobiera liczbę znaków potrzebnych do dekodowania bufora bajtów.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bajty do dekodowania. |
| count | int | Liczba bajtów. |

### Wartość zwracana

Liczba znaków.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [UTF7Encoding](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)