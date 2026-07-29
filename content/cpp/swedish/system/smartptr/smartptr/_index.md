---
title: SmartPtr()
second_title: Aspose.Slides för C++ API-referens
description: Skapar SmartPtr-objekt av önskat läge.
type: docs
weight: 1
url: /sv/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) konstruktor


Skapar [SmartPtr](../) objekt av önskat läge.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) konstruktor


Skapar nullpekare [SmartPtr](../) objekt av önskat läge.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | std::nullptr_t | Pointer mode. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) konstruktor


Skapar [SmartPtr](../) som pekar på specificerat objekt, eller konverterar råpekare till [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | Pointee. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) konstruktor


Kopieringskonstruktor för [SmartPtr](../) objekt. Båda pekarna pekar på samma objekt efteråt.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Pointer to copy. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) konstruktor


Kopieringskonstruktor för [SmartPtr](../) objekt. Båda pekarna pekar på samma objekt efteråt. Utför typkonvertering om det är tillåtet.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Q | Type of object pointed by x. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Pointer to copy. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) konstruktor


Flyttkonstruktor för [SmartPtr](../) objekt. Effektivt, byter två pekare om de båda har samma läge. x kan bli oanvändbar efter anropet.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointer to move. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) konstruktor


Konverterar typ på refererad array genom att skapa en ny array av annan typ. Användbart om det i C# finns en array-typkonvertering som inte stöds i C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Y | Type of source array. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | Pointer to array to create a copy of, but with different type of elements. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const Y\&) konstruktor


Initierar tom array. Används för att översätta vissa C#-kods konstruktioner.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Y | Placeholder of EmptyArrayInitializer type. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) konstruktor


Skapar en [SmartPtr](../) som delar ägarskapsinformation med det ursprungliga värdet av ptr, men innehåller en orelaterad och ohanterad pekare p.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | Another smart pointer to share the ownership to the ownership from. |
| p | [Pointee_](../pointee_/) * | Pointer to an object to manage. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. 
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream"

// Denna klass innehåller ett fält som kommer att skrivas ut.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// Denna klass innehåller en instans av Foo-klassen.
class Bar : public System::Object
{
public:
  Foo data;
};

// Används för att skriva ut en sträng från Foo-klassen.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// Skriver ut antalet delade pekare som pekar på objektet.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Skapa SharedPtr till en instans av Bar-klassen.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Skapa SharedPtr som pekar på fältet i Bar-instansen.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // Gör 'bar'-pekaren pekande på nullptr.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data existerar fortfarande och 'foo'-pekaren är giltig.
  PrintMessage(foo);

  return 0;
}
/*
Den här kodexemplet ger följande utdata:
Number of shared pointers: 1
Number of shared pointers: 2
Number of shared pointers: 0
Hello, world!
*/
``` |

## Se även

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [Array](../../array/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)