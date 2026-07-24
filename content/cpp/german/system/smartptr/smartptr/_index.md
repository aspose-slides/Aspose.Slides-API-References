---
title: SmartPtr()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt SmartPtr-Objekt des erforderlichen Modus.
type: docs
weight: 1
url: /de/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) Konstruktor


Erstellt [SmartPtr](../) Objekt des erforderlichen Modus.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) Konstruktor


Erstellt Nullzeiger [SmartPtr](../) Objekt des erforderlichen Modus.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mode | std::nullptr_t | Pointer mode. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) Konstruktor


Erstellt [SmartPtr](../), das auf das angegebene Objekt zeigt, oder konvertiert den rohen Zeiger zu [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | Pointee. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) Konstruktor


Kopiert [SmartPtr](../) Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Pointer to copy. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) Konstruktor


Kopiert [SmartPtr](../) Objekt. Beide Zeiger zeigen danach auf dasselbe Objekt. Führt eine Typkonvertierung durch, falls zulässig.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Q | Typ des von x referenzierten Objekts. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Pointer to copy. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) Konstruktor


Konstruiert [SmartPtr](../) Objekt per Move. Effektiv tauscht es zwei Zeiger, wenn beide den gleichen Modus haben. x kann nach dem Aufruf unbenutzbar sein.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointer to move. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) Konstruktor


Konvertiert den Typ des referenzierten Arrays, indem ein neues Array eines anderen Typs erstellt wird. Nützlich, wenn es in C# einen Array-Typcast gibt, der in C++ nicht unterstützt wird.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Y | Typ des Quell-Arrays. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | Zeiger auf das zu kopierende Array, jedoch mit anderem Elementtyp. |
| mode | [SmartPtrMode](../../smartptrmode/) | Zeiger-Modus. |

## SmartPtr::SmartPtr(const Y\&) Konstruktor


Initialisiert leeres Array. Wird verwendet, um einige C#-Codekonstrukte zu übersetzen.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Y | Platzhalter des Typs EmptyArrayInitializer. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) Konstruktor


Konstruiert ein [SmartPtr](../), das die Eigentumsinformationen des ursprünglichen Werts von ptr teilt, aber einen nicht zusammenhängenden und nicht verwalteten Zeiger p hält.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | Ein anderer Smart-Pointer, um das Eigentum vom Ausgangs-Pointer zu teilen. |
| p | [Pointee_](../pointee_/) * | Zeiger auf ein zu verwaltendes Objekt. |
| mode | [SmartPtrMode](../../smartptrmode/) | Zeiger-Modus. 
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

// Diese Klasse enthält ein Feld, das ausgegeben wird.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// Diese Klasse enthält eine Instanz der Foo-Klasse.
class Bar : public System::Object
{
public:
  Foo data;
};

// Wird verwendet, um einen String aus der Foo-Klasseninstanz auszugeben.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// Gibt die Anzahl der Shared-Pointer aus, die auf das Objekt zeigen.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Erstelle ein SharedPtr zu einer Instanz der Bar-Klasse.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Erstelle ein SharedPtr, das auf das Feld der Bar-Klasseninstanz zeigt.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // Setze den Zeiger 'bar' auf nullptr.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data existiert noch und der Zeiger 'foo' ist gültig.
  PrintMessage(foo);

  return 0;
}
/*
Dieses Codebeispiel erzeugt die folgende Ausgabe:
Number of shared pointers: 1
Number of shared pointers: 2
Number of shared pointers: 0
Hello, world!
*/
``` |

## Siehe auch

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [Array](../../array/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)