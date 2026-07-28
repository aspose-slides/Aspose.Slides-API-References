---
title: IndexOfAny()
second_title: Aspose.Slides dla C++ – referencja API
description: Wyszukiwanie znaków do przodu.
type: docs
weight: 638
url: /pl/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const metoda

Wyszukiwanie znaków w przód.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| c | char_t | Znak do wyszukania. |
| startIndex | int | [Index](../../index/) do rozpoczęcia przeszukiwania. |

### Wartość zwracana

[Index](../../index/) pierwszej pozycji znaku od startIndex lub -1, jeśli nie znaleziono.

## String::IndexOfAny(const String\&, int) const metoda

W związku z tym przeszukuje wszystkie znaki ciągu str w tym obiekcie. Jeśli pierwszy znak zostanie znaleziony, zwracana jest jego pozycja, w przeciwnym razie szuka drugiego i tak dalej.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) znaków do wyszukania. Kolejność znaków ma znaczenie. |
| startIndex | int | Pozycja, od której rozpocząć wyszukiwanie. |

### Wartość zwracana

[Index](../../index/) pierwszego znalezionego znaku lub -1, jeśli nie znaleziono.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const metoda

Wyszukuje dowolny z podanych znaków w całym łańcuchu. Porównuje pierwszy znak łańcucha ze wszystkimi znakami w anyOf, potem drugi i tak dalej. Zwraca indeks pierwszego pasującego do któregokolwiek ze znaków docelowych.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaków do wyszukania. Kolejność nie ma znaczenia. |

### Wartość zwracana

[Index](../../index/) pierwszego pasującego znaku lub -1, jeśli nie znaleziono.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const metoda

Wyszukuje dowolny z podanych znaków w całym łańcuchu. Porównuje pierwszy znak łańcucha ze wszystkimi znakami w anyOf, potem drugi i tak dalej. Zwraca indeks pierwszego pasującego do któregokolwiek ze znaków docelowych.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaków do wyszukania. Kolejność nie ma znaczenia. |
| startindex | **int32_t** | [Index](../../index/) do rozpoczęcia przeszukiwania. |

### Wartość zwracana

[Index](../../index/) pierwszego pasującego znaku lub -1, jeśli nie znaleziono.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const metoda

Wyszukuje dowolny z podanych znaków w całym łańcuchu. Porównuje pierwszy znak łańcucha ze wszystkimi znakami w anyOf, potem drugi i tak dalej. Zwraca indeks pierwszego pasującego do któregokolwiek ze znaków docelowych.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaków do wyszukania. Kolejność nie ma znaczenia. |
| startindex | **int32_t** | [Index](../../index/) do rozpoczęcia przeszukiwania. |
| count | **int32_t** | Liczba znaków do przeszukania. |

### Wartość zwracana

[Index](../../index/) pierwszego pasującego znaku lub -1, jeśli nie znaleziono.

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [String](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)