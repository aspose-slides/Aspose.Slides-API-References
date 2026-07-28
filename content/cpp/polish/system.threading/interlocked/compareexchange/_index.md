---
title: CompareExchange()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Wymienia wartość zmiennej: sprawdza, czy zmienna jest równa określonej wartości i zapisuje nową wartość tylko wtedy, gdy przechowywana wartość odpowiada oczekiwanej."
type: docs
weight: 79
url: /pl/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T\&, T, T) metoda


Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ zmiennej. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| location1 | T\& | Referencja do zmiennej, którą należy zmienić. |
| value | T | Wartość do zapisania. |
| comparand | T | Wartość, z którą porównywana jest wartość zmiennej przed wymianą. |

### Wartość zwracana

Wartość zmiennej na początku operacji, niezależnie od tego, czy została zmieniona.

## Interlocked::CompareExchange(T\&, T, T) metoda


Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected. Not implemented.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ zmiennej. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| location1 | T\& | Referencja do zmiennej, którą należy zmienić. |
| value | T | Wartość do zapisania. |
| comparand | T | Wartość, z którą porównywana jest wartość zmiennej przed wymianą. |

### Wartość zwracana

Wartość zmiennej na początku operacji, niezależnie od tego, czy została zmieniona.

## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) metoda


Compare-exchanges value on variable: checks if variable is equal to specific value and stores the new value only if stored value matches expected.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| location1 | **int32_t**\& | Referencja do zmiennej, którą należy zmienić. |
| value | **int32_t** | Wartość do zapisania. |
| comparand | **int32_t** | Wartość, z którą porównywana jest wartość zmiennej przed wymianą. |
| succeeded | **bool**\& | Referencja do zmiennej, która jest ustawiana na true, jeśli wymiana nastąpiła, i na false w przeciwnym razie. |

### Wartość zwracana

Wartość zmiennej na początku operacji, niezależnie od tego, czy została zmieniona.

## Zobacz także

* Class [Interlocked](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)