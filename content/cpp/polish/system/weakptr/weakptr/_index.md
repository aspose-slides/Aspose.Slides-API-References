---
title: WeakPtr()
second_title: Aspose.Slides dla C++ – referencja API
description: Tworzy pusty wskaźnik.
type: docs
weight: 1
url: /pl/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) konstruktor

Tworzy pusty wskaźnik.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) konstruktor

Tworzy słaby wskaźnik do podanego obiektu.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) do utworzenia słabego wskaźnika do. |

## WeakPtr::WeakPtr(const SmartPtr_&) konstruktor

Tworzy słaby wskaźnik odwołujący się do tego samego wskaźnika, na który wskazuje ptr.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | Wskaźnik do skopiowania wartości wskazywanego obiektu. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) konstruktor

Tworzy słaby wskaźnik odwołujący się do tego samego wskaźnika, na który wskazuje x.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Q | Typ obiektu wskazywanego przez wskaźnik źródłowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Wskaźnik do skopiowania wartości wskazywanego obiektu. |

## WeakPtr::WeakPtr(const WeakPtr_&) konstruktor

Konstruktor kopiujący słaby wskaźnik.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | Wskaźnik do skopiowania wartości wskazywanego obiektu. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) konstruktor

Konstruktor kopiujący słaby wskaźnik.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Q | Typ obiektu wskazywanego w źródle. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | Wskaźnik do skopiowania wartości wskazywanego obiektu. |

## WeakPtr::WeakPtr(SmartPtr_&&) konstruktor

Konstruktor przenoszący słaby wskaźnik.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | Wskaźnik do przeniesienia wartości wskazywanego obiektu. |

## Zobacz także

* Definicja typu [Pointee_](../../smartptr/pointee_/)
* Definicja typu [SmartPtr_](../../smartptr/smartptr_/)
* Definicja typu [WeakPtr_](../weakptr_/)
* Klasa [WeakPtr](../)
* Klasa [SmartPtr](../../smartptr/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)