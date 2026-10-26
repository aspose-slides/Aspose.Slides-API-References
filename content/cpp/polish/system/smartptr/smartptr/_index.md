---
title: SmartPtr()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy obiekt SmartPtr w wymaganym trybie.
type: docs
weight: 1
url: /pl/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) konstruktor


Tworzy obiekt [SmartPtr](../) w wymaganym trybie.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Tryb wskaźnika. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) konstruktor


Tworzy obiekt [SmartPtr](../) o wskaźniku null w wymaganym trybie.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mode | std::nullptr_t | Tryb wskaźnika. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) konstruktor


Tworzy [SmartPtr](../) wskazujący na określony obiekt lub konwertuje surowy wskaźnik na [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | Obiekt wskazywany. |
| mode | [SmartPtrMode](../../smartptrmode/) | Tryb wskaźnika. |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) konstruktor


Kopiowa konstrukcja obiektu [SmartPtr](../). Oba wskaźniki wskazują na ten sam obiekt po wykonaniu.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)& | Wskaźnik do skopiowania. |
| mode | [SmartPtrMode](../../smartptrmode/) | Tryb wskaźnika. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>&, SmartPtrMode) konstruktor


Kopiowa konstrukcja obiektu [SmartPtr](../). Oba wskaźniki wskazują na ten sam obiekt po wykonaniu. Wykonuje konwersję typu, jeśli jest dozwolona.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Q | Typ obiektu wskazywanego przez x. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>& | Wskaźnik do skopiowania. |
| mode | [SmartPtrMode](../../smartptrmode/) | Tryb wskaźnika. |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) konstruktor


Konstrukcja przenosząca obiektu [SmartPtr](../). W praktyce zamienia dwa wskaźniki, jeśli oba są tego samego trybu. x może być nieużywalny po wywołaniu.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)&& | Wskaźnik do przeniesienia. |
| mode | [SmartPtrMode](../../smartptrmode/) | Tryb wskaźnika. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>&, SmartPtrMode) konstruktor


Konwertuje typ referencjonowanej tablicy poprzez utworzenie nowej tablicy innego typu. Przydatne, gdy w C# istnieje rzutowanie typu tablicy, które nie jest obsługiwane w C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Y | Typ oryginalnej tablicy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>& | Wskaźnik do tablicy, z której ma być utworzona kopia, ale z elementami innego typu. |
| mode | [SmartPtrMode](../../smartptrmode/) | Tryb wskaźnika. |

## SmartPtr::SmartPtr(const Y&) konstruktor


Inicjalizuje pustą tablicę. Używane do translacji niektórych konstrukcji kodu C#.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Y | Symbol zastępczy typu EmptyArrayInitializer. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>&, Pointee_ *, SmartPtrMode) konstruktor


Tworzy [SmartPtr](../), który współdzieli własność z początkową wartością ptr, ale przechowuje niepowiązany i niezarządzany wskaźnik p.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>& | Inny inteligentny wskaźnik, aby współdzielić własność z ptr. |
| p | [Pointee_](../pointee_/) * | Wskaźnik do obiektu do zarządzania. |
| mode | [SmartPtrMode](../../smartptrmode/) | Tryb wskaźnika. |
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

// Ta klasa zawiera pole, które zostanie wydrukowane.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// Ta klasa zawiera instancję klasy Foo.
class Bar : public System::Object
{
public:
  Foo data;
};

// Używane do wydrukowania łańcucha znaków z instancji klasy Foo.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// Drukuje liczbę współdzielonych wskaźników wskazujących na obiekt.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Utwórz SharedPtr do instancji klasy Bar.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Utwórz SharedPtr, który będzie wskazywał na pole instancji klasy Bar.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // Ustaw wskaźnik 'bar' na nullptr.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data wciąż istnieje i wskaźnik 'foo' jest ważny.
  PrintMessage(foo);

  return 0;
}
/*
Ten przykład kodu generuje następujące wyjście:
Liczba współdzielonych wskaźników: 1
Liczba współdzielonych wskaźników: 2
Liczba współdzielonych wskaźników: 0
Witaj, świecie!
*/
``` |

## Zobacz także

* Wyliczenie [SmartPtrMode](../../smartptrmode/)
* Definicja typu [Pointee_](../pointee_/)
* Definicja typu [SmartPtr_](../smartptr_/)
* Klasa [SmartPtr](../)
* Klasa [Array](../../array/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)