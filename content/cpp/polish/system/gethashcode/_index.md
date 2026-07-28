---
title: GetHashCode()
second_title: Aspose.Slides dla referencji API C++
description: Zwraca kod skrótu dla określonej wartości skalarnej.
type: docs
weight: 2484
url: /pl/system/gethashcode/
---
## System::GetHashCode(const T\&) funkcja

Zwraca kod skrótu dla określonej wartości skalarnej.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wartości, dla której funkcja generuje kod skrótu |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const T\& | Wartość, dla której ma zostać wygenerowany kod skrótu |

### Wartość zwracana

Kod skrótu wygenerowany dla określonej wartości

## System::GetHashCode(const T\&) funkcja

Zwraca kod skrótu dla określonego obiektu.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektu, dla którego funkcja generuje kod skrótu |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../smartptr/) wskazujący na obiekt, dla którego ma zostać wygenerowany kod skrótu |

### Wartość zwracana

Kod skrótu wygenerowany dla określonego obiektu

## System::GetHashCode(const T\&) funkcja

Zwraca kod skrótu dla określonego obiektu będącego wyjątkiem.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektu, dla którego funkcja generuje kod skrótu |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const T\& | Exception Wrapper zawierający obiekt, dla którego ma zostać wygenerowany kod skrótu |

### Wartość zwracana

Kod skrótu wygenerowany dla określonego obiektu

## System::GetHashCode(const T\&) funkcja

Zwraca kod skrótu dla określonego obiektu, który nie jest inteligentnym wskaźnikiem ani wyjątkiem.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektu, dla którego funkcja generuje kod skrótu |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const T\& | Stała referencja do obiektu, dla którego ma zostać wygenerowany kod skrótu |

### Wartość zwracana

Kod skrótu wygenerowany dla określonego obiektu

## System::GetHashCode(const std::thread::id\&) funkcja

Specjalizacja dla std::thread::id; Zwraca kod skrótu dla określonego obiektu wątku.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## Zobacz także

* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Przestrzeń nazw [System](../)
* Library [Aspose.Slides](../../)