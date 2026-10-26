---
title: Cast()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Rzutuje wskaźnik na jego własny typ.
type: docs
weight: 287
url: /pl/system/smartptr/cast/
---
## SmartPtr::Cast() const metoda


Rzutuje wskaźnik na jego własny typ.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Y | Docelowy typ wskazywanego obiektu. |
| Check | Flagi powodujące rzucenie wyjątku, jeśli rzutowanie nie jest dostępne. |

### Wartość zwracana

Wskaźnik zmienionego typu, który zawsze jest w trybie współdzielonym.

## SmartPtr::Cast() const metoda


Rzutuje wskaźnik na typ bazowy przy użyciu static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Y | Docelowy typ wskazywanego obiektu. |
| Check | Flagi powodujące rzucenie wyjątku, jeśli rzutowanie nie jest dostępne. |

### Wartość zwracana

Wskaźnik zmienionego typu, który zawsze jest w trybie współdzielonym.

## SmartPtr::Cast() const metoda


Rzutuje wskaźnik na typ pochodny przy użyciu dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Y | Docelowy typ wskazywanego obiektu. |
| Check | Flagi powodujące rzucenie wyjątku, jeśli rzutowanie nie jest dostępne. |

### Wartość zwracana

Wskaźnik zmienionego typu, który zawsze jest w trybie współdzielonym. Rzuca InvalidCastException, jeśli konwersja nie jest dostępna.

## SmartPtr::Cast() const metoda


Rzutuje wskaźnik na typ pochodny przy użyciu dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Y | Docelowy typ wskazywanego obiektu. |
| Check | Flagi powodujące rzucenie wyjątku, jeśli rzutowanie nie jest dostępne. |

### Wartość zwracana

Wskaźnik zmienionego typu, który zawsze jest w trybie współdzielonym. Zwraca nullptr, jeśli konwersja nie jest dostępna.

## Zobacz również

* Klasa [SmartPtr](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)