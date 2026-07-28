---
title: operator=()
second_title: Referencja API Aspose.Slides dla C++
description: Przypisuje null do bieżącego obiektu.
type: docs
weight: 14
url: /pl/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) metoda

Przypisuje null do bieżącego obiektu.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```

### Wartość zwracana

Obiekt [Nullable](../) reprezentujący wartość null.

## Nullable::operator=(const T1\&) metoda

Zastępuje aktualnie reprezentowaną wartość obiektu podaną wartością.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| The | typ nowej wartości, którą ma reprezentować bieżący obiekt |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const T1\& | Nowa wartość, którą ma reprezentować bieżący obiekt |

### Wartość zwracana

Referencja do bieżącego obiektu

## Nullable::operator=(const Nullable\<T1\>\&) metoda

Zastępuje aktualnie reprezentowaną wartość obiektu podaną wartością.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| The | typ nowej wartości, którą ma reprezentować bieżący obiekt |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | Nowa wartość, którą ma reprezentować bieżący obiekt |

### Wartość zwracana

Referencja do bieżącego obiektu

## Zobacz także

* Klasa [Nullable](../)
* Struktura [IsNullable](../../isnullable/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)