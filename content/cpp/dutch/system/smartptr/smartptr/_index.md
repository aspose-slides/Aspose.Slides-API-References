---
title: SmartPtr()
second_title: Aspose.Slides voor C++ API Referentie
description: Maakt SmartPtr-object van de vereiste modus.
type: docs
weight: 1
url: /nl/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) constructor


Maakt [SmartPtr](../) object van de vereiste modus.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer-modus. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) constructor


Maakt null-pointer [SmartPtr](../) object van de vereiste modus.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mode | std::nullptr_t | Pointer-modus. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) constructor


Maakt [SmartPtr](../) die wijst naar het opgegeven object, of converteert ruwe pointer naar [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | Pointee. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer-modus. |

## SmartPtr::SmartPtr(const SmartPtr_\&, SmartPtrMode) constructor


Kopieert [SmartPtr](../) object. Beide pointers wijzen daarna naar hetzelfde object.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Pointer om te kopiëren. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer-modus. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) constructor


Kopieert [SmartPtr](../) object. Beide pointers wijzen daarna naar hetzelfde object. Voert typeconversie uit indien toegestaan.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Q | Type van het object waarnaar x wijst. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Pointer om te kopiëren. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer-modus. |

## SmartPtr::SmartPtr(SmartPtr_\&&, SmartPtrMode) constructor


Verplaatst [SmartPtr](../) object. Effectief wisselt het twee pointers van plaats, als ze beide dezelfde modus hebben. x kan na de aanroep onbruikbaar zijn.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointer om te verplaatsen. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer-modus. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) constructor


Converteert het type van de gerefereerde array door een nieuwe array van een ander type te maken. Handig als er in C# een array-type-cast bestaat die niet wordt ondersteund in C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Y | Type van de bronarray. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | Pointer naar de array waarvan een kopie moet worden gemaakt, maar met een ander type elementen. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer-modus. |

## SmartPtr::SmartPtr(const Y\&) constructor


Initialiseert een lege array. Wordt gebruikt om enkele C#-code-constructies te vertalen.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Y | Plaatsaanduiding voor het type EmptyArrayInitializer. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) constructor


Construeert een [SmartPtr](../) die eigendomsinformatie deelt met de initiële waarde van ptr, maar een niet-gerelateerde en onbeheerde pointer p bevat.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | Een andere slimme pointer om de eigendom mee te delen. |
| p | [Pointee_](../pointee_/) * | Pointer naar een object om te beheren. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer-modus. 
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream"

// Deze klasse bevat een veld dat afgedrukt zal worden.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// Deze klasse bevat een instantie van de Foo-klasse.
class Bar : public System::Object
{
public:
  Foo data;
};

// Wordt gebruikt om een string van de Foo-klasse instantie af te drukken.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// Print het aantal gedeelde pointers die naar het object wijzen.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Maak een SharedPtr naar een instantie van de Bar-klasse.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Maak een SharedPtr die naar het veld van de Bar-klasse instantie zal wijzen.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // Laat de 'bar' pointer naar nullptr wijzen.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data bestaat nog steeds en de 'foo' pointer is geldig.
  PrintMessage(foo);

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende uitvoer:
Number of shared pointers: 1
Number of shared pointers: 2
Number of shared pointers: 0
Hello, world!
*/
``` |

## Zie ook

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [Array](../../array/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)