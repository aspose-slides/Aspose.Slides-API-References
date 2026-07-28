---
title: SmartPtr()
second_title: Aspose.Slides for C++ API-referencia
description: Létrehozza a szükséges módú SmartPtr objektumot.
type: docs
weight: 1
url: /hu/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) konstruktor

Létrehozza a szükséges módú [SmartPtr](../) objektumot.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) konstruktor

Létrehozza a szükséges módú null mutató [SmartPtr](../) objektumot.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mode | std::nullptr_t | Pointer mode. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) konstruktor

Létrehozza a megadott objektumra mutató [SmartPtr](../) objektumot, vagy nyers mutatót konvertál [SmartPtr](../)-re.

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | Pointee. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr_\&, SmartPtrMode) konstruktor

Másolás útján létrehozza a [SmartPtr](../) objektumot. Ezután mindkét mutató ugyanarra az objektumra mutat.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Pointer to copy. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) konstruktor

Másolás útján létrehozza a [SmartPtr](../) objektumot. Ezután mindkét mutató ugyanarra az objektumra mutat. Típuskonverziót végez, ha engedélyezett.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Q | Type of object pointed by x. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Pointer to copy. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(SmartPtr_\&&, SmartPtrMode) konstruktor

Áthelyezés útján létrehozza a [SmartPtr](../) objektumot. Gyakorlatban felcseréli a két mutatót, ha ugyanazon módúak. A hívás után x használhatatlanná válhat.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointer to move. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) konstruktor

Átkonvertálja a hivatkozott tömb típusát egy eltérő típusú új tömb létrehozásával. Hasznos, ha C#-ban van egy olyan tömb típuskonverzió, amely C++-ban nem támogatott.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Y | Type of source array. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | Pointer to array to create a copy of, but with different type of elements. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const Y\&) konstruktor

Inicializál egy üres tömböt. Néhány C# kódkonstrukció lefordításához használják.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Y | Placeholder of EmptyArrayInitializer type. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) konstruktor

Létrehozza a [SmartPtr](../)-t, amely megosztja a tulajdonosi információkat a ptr kezdeti értékével, de egy nem kapcsolódó, nem kezelt p mutatót tartalmaz.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | Another smart pointer to share the ownership to the ownership from. |
| p | [Pointee_](../pointee_/) * | Pointer to an object to manage. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. 
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

// Ez az osztály egy mezőt tartalmaz, amely ki lesz nyomtatva.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// Ez az osztály egy Foo osztálypéldányt tartalmaz.
class Bar : public System::Object
{
public:
  Foo data;
};

// A Foo osztálypéldányból származó karakterlánc kiíratására használják.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// Kiírja az objektumra mutató megosztott mutatók számát.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Létrehoz egy SharedPtr-et a Bar osztály egy példányára.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Létrehoz egy SharedPtr-et, amely a Bar osztálypéldány mezőjére mutat.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // A 'bar' mutatót nullptr-re állítja.
  bar.reset();
  PrintSharedCount(bar);
  // a bar->data még létezik, és a 'foo' mutató érvényes.
  PrintMessage(foo);

  return 0;
}
/*
Ez a kódrészlet a következő kimenetet adja:
Megosztott mutatók száma: 1
Megosztott mutatók száma: 2
Megosztott mutatók száma: 0
Helló, világ!
*/
``` |

## Lásd még

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [Array](../../array/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)