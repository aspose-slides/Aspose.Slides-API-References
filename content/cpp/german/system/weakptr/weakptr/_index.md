---
title: WeakPtr()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt Nullzeiger.
type: docs
weight: 1
url: /de/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) Konstruktor


Erstellt Nullzeiger.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) Konstruktor


Erstellt einen schwachen Zeiger auf das angegebene Objekt.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) um einen schwachen Zeiger zu erstellen. |

## WeakPtr::WeakPtr(const SmartPtr_&) Konstruktor


Erstellt einen schwachen Zeiger, der denselben Zeiger referenziert, auf den ptr zeigt.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | Zeiger, von dem der Zeigerwert kopiert wird. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) Konstruktor


Erstellt einen schwachen Zeiger, der denselben Zeiger referenziert, auf den x zeigt.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Q | Pointee-Typ des Quellzeigers. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Zeiger, von dem der Zeigerwert kopiert wird. |

## WeakPtr::WeakPtr(const WeakPtr_&) Konstruktor


Kopiert den schwachen Zeiger.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | Zeiger, von dem der Zeigerwert kopiert wird. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) Konstruktor


Kopiert den schwachen Zeiger.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Q | Quell-Pointee-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | Zeiger, von dem der Zeigerwert kopiert wird. |

## WeakPtr::WeakPtr(SmartPtr_&&) Konstruktor


Erzeugt einen schwachen Zeiger durch Verschieben.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | Zeiger, von dem der Zeigerwert verschoben wird. |

## Siehe auch

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Klasse [WeakPtr](../)
* Klasse [SmartPtr](../../smartptr/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)