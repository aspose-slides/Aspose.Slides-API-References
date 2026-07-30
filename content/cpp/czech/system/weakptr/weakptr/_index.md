---
title: WeakPtr()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří nulový ukazatel.
type: docs
weight: 1
url: /cs/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) konstruktor

Vytvoří ukazatel null.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) konstruktor

Vytvoří slabý ukazatel na zadaný objekt.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) k vytvoření slabého ukazatele na. |

## WeakPtr::WeakPtr(const SmartPtr_\&) konstruktor

Vytvoří slabý ukazatel odkazující na stejný ukazatel, na který ukazuje ptr.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | Ukazatel, ze kterého se kopíruje hodnota ukazovaného objektu. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) konstruktor

Vytvoří slabý ukazatel odkazující na stejný ukazatel, na který ukazuje x.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Q | Typ ukazovaného objektu zdrojového ukazatele. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Ukazatel, ze kterého se kopíruje hodnota ukazovaného objektu. |

## WeakPtr::WeakPtr(const WeakPtr_\&) konstruktor

Vytvoří kopii slabého ukazatele.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | Ukazatel, ze kterého se kopíruje hodnota ukazovaného objektu. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) konstruktor

Vytvoří kopii slabého ukazatele.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Q | Typ ukazovaného objektu zdroje. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | Ukazatel, ze kterého se kopíruje hodnota ukazovaného objektu. |

## WeakPtr::WeakPtr(SmartPtr_\&&) konstruktor

Vytvoří slabý ukazatel přesunutím.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | Ukazatel, ze kterého se přesunuje hodnota ukazovaného objektu. |

## Viz také

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Třída [WeakPtr](../)
* Třída [SmartPtr](../../smartptr/)
* jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)