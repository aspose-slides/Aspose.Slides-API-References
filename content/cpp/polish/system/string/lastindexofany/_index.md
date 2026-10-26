---
title: LastIndexOfAny()
second_title: Aspose.Slides dla C++ referencja API
description: Wyszukuje dowolny z przekazanych znaków w całym łańcuchu wstecz. Porównuje ostatni znak łańcucha ze wszystkimi znakami w anyOf, następnie porównuje poprzedni i tak dalej. Zwraca indeks pierwszego znalezionego dopasowania.
type: docs
weight: 664
url: /pl/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const metoda


Wyszukuje dowolny z podanych znaków w całym łańcuchu wstecz. Porównuje ostatni znak łańcucha ze wszystkimi znakami w anyOf, następnie porównuje poprzedni i tak dalej. Zwraca indeks pierwszego znalezionego dopasowania.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaków do wyszukania. Kolejność nie ma znaczenia. |

### Wartość zwracana

[Index](../../index/) ostatniego pasującego znaku lub -1, jeśli nie znaleziono.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const metoda


Wyszukuje dowolny z podanych znaków w podciągu wstecz. Porównuje ostatni znak łańcucha ze wszystkimi znakami w anyOf, następnie porównuje poprzedni i tak dalej. Zwraca indeks pierwszego znalezionego dopasowania.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaków do wyszukania. Kolejność nie ma znaczenia. |
| startindex | **int32_t** | [Index](../../index/) do rozpoczęcia wyszukiwania od. |

### Wartość zwracana

[Index](../../index/) ostatniego pasującego znaku lub -1, jeśli nie znaleziono.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const metoda


Wyszukuje dowolny z podanych znaków w podciągu wstecz. Porównuje ostatni znak łańcucha ze wszystkimi znakami w anyOf, następnie porównuje poprzedni i tak dalej. Zwraca indeks pierwszego znalezionego dopasowania.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) znaków do wyszukania. Kolejność nie ma znaczenia. |
| startindex | **int32_t** | [Index](../../index/) do rozpoczęcia wyszukiwania od. |
| count | **int32_t** | Liczba znaków do przeszukania. |

### Wartość zwracana

[Index](../../index/) ostatniego pasującego znaku lub -1, jeśli nie znaleziono.

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [String](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)