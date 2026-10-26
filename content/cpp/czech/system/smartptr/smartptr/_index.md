---
title: SmartPtr()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vytvoří objekt SmartPtr požadovaného režimu.
type: docs
weight: 1
url: /cs/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) konstruktor


Vytvoří [SmartPtr](../) objekt požadovaného režimu.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Režim ukazatele. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) konstruktor


Vytvoří null-pointer [SmartPtr](../) objekt požadovaného režimu.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mode | std::nullptr_t | Režim ukazatele. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) konstruktor


Vytvoří [SmartPtr](../) ukazující na zadaný objekt nebo převede syrový ukazatel na [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | Pointee. |
| mode | [SmartPtrMode](../../smartptrmode/) | Režim ukazatele. |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) konstruktor


Kopírově vytvoří [SmartPtr](../) objekt. Oba ukazatele po operaci ukazují na stejný objekt.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Ukazatel k záloze. |
| mode | [SmartPtrMode](../../smartptrmode/) | Režim ukazatele. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) konstruktor


Kopírově vytvoří [SmartPtr](../) objekt. Oba ukazatele po operaci ukazují na stejný objekt. Provede konverzi typu, pokud je povolena.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Q | Typ objektu, na který ukazuje x. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Ukazatel k záloze. |
| mode | [SmartPtrMode](../../smartptrmode/) | Režim ukazatele. |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) konstruktor


Přesunovým vytvoří [SmartPtr](../) objekt. Efektivně prohodí dva ukazatele, pokud jsou oba ve stejném režimu. x může být po volání nepoužitelný.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Ukazatel k přesunu. |
| mode | [SmartPtrMode](../../smartptrmode/) | Režim ukazatele. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) konstruktor


Převede typ odkazovaného pole vytvořením nového pole jiného typu. Užitočné, pokud v C# existuje přetypování pole, které není podporováno v C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Y | Typ zdrojového pole. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | Ukazatel na pole, jehož kopii vytvořit, ale s jiným typem prvků. |
| mode | [SmartPtrMode](../../smartptrmode/) | Režim ukazatele. |

## SmartPtr::SmartPtr(const Y\&) konstruktor


Inicializuje prázdné pole. Používá se k překladu některých konstrukcí kódu v C#.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Y | Zástupný typ pro EmptyArrayInitializer. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) konstruktor


Vytvoří [SmartPtr](../), který sdílí informaci o vlastnictví s počáteční hodnotou ptr, ale obsahuje nesouvisející a neřízený ukazatel p.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | Další chytrý ukazatel, jehož vlastnictví má být sdíleno. |
| p | [Pointee_](../pointee_/) * | Ukazatel na objekt, který má být spravován. |
| mode | [SmartPtrMode](../../smartptrmode/) | Režim ukazatele. 
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

// Tato třída obsahuje pole, které bude vytištěno.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// Tato třída obsahuje instanci třídy Foo.
class Bar : public System::Object
{
public:
  Foo data;
};

// Použito k vytištění řetězce z instance třídy Foo.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// Vytiskne počet sdílených ukazatelů ukazujících na objekt.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Vytvořte SharedPtr na instanci třídy Bar.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Vytvořte SharedPtr, který bude ukazovat na pole instance třídy Bar.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // Nastavte ukazatel 'bar' na nullptr.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data stále existuje a ukazatel 'foo' je platný.
  PrintMessage(foo);

  return 0;
}
/*
Tento ukázkový kód produkuje následující výstup:
Number of shared pointers: 1
Number of shared pointers: 2
Number of shared pointers: 0
Hello, world!
*/
``` |

## Viz také

* Výčet [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Třída [SmartPtr](../)
* Třída [Array](../../array/)
* Obor názvů [System](../../)
* Knihovna [Aspose.Slides](../../../)