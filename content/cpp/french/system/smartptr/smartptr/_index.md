---
title: SmartPtr()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Crée un objet SmartPtr du mode requis.
type: docs
weight: 1
url: /fr/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) constructeur


Crée un objet [SmartPtr](../) du mode requis.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Mode du pointeur. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) constructeur


Crée un objet [SmartPtr](../) pointeur nul du mode requis.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| mode | std::nullptr_t | Mode du pointeur. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) constructeur


Crée [SmartPtr](../) pointant vers l'objet spécifié, ou convertit le pointeur brut en [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | Objet pointé. |
| mode | [SmartPtrMode](../../smartptrmode/) | Mode du pointeur. |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) constructeur


Construit une copie de l'objet [SmartPtr](../). Les deux pointeurs pointent vers le même objet par la suite.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Pointeur à copier. |
| mode | [SmartPtrMode](../../smartptrmode/) | Mode du pointeur. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) constructeur


Construit une copie de l'objet [SmartPtr](../). Les deux pointeurs pointent vers le même objet par la suite. Effectue la conversion de type si autorisée.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Q | Type de l'objet pointé par x. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Pointeur à copier. |
| mode | [SmartPtrMode](../../smartptrmode/) | Mode du pointeur. |

## SmartPtr::SmartPtr(SmartPtr_\&&, SmartPtrMode) constructeur


Construit un déplacement de l'objet [SmartPtr](../). En pratique, échange deux pointeurs s'ils sont du même mode. x peut être inutilisable après l'appel.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointeur à déplacer. |
| mode | [SmartPtrMode](../../smartptrmode/) | Mode du pointeur. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) constructeur


Convertit le type du tableau référencé en créant un nouveau tableau d'un type différent. Utile si en C# il existe une conversion de type de tableau qui n'est pas prise en charge en C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Y | Type du tableau source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | Pointeur vers le tableau dont on crée une copie, mais avec un type d'éléments différent. |
| mode | [SmartPtrMode](../../smartptrmode/) | Mode du pointeur. |

## SmartPtr::SmartPtr(const Y\&) constructeur


Initialise un tableau vide. Utilisé pour traduire certaines constructions de code C#.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Y | Espace réservé du type EmptyArrayInitializer. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) constructeur


Construit un [SmartPtr](../) qui partage les informations de propriété avec la valeur initiale de ptr, mais détient un pointeur p non lié et non géré.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | Un autre smart pointer pour partager la propriété du ptr. |
| p | [Pointee_](../pointee_/) * | Pointeur vers un objet à gérer. |
| mode | [SmartPtrMode](../../smartptrmode/) | Mode du pointeur. |
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream"

// Cette classe contient un champ qui sera imprimé.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// Cette classe contient une instance de la classe Foo.
class Bar : public System::Object
{
public:
  Foo data;
};

// Utilisée pour imprimer une chaîne depuis l'instance de la classe Foo.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// Imprime le nombre de pointeurs partagés pointant vers l'objet.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Crée un SharedPtr vers une instance de la classe Bar.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Crée un SharedPtr qui pointera vers le champ de l'instance de la classe Bar.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // Rend le pointeur 'bar' nul.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data existe toujours et le pointeur 'foo' est valide.
  PrintMessage(foo);

  return 0;
}
/*
Cet exemple de code produit la sortie suivante :
Nombre de pointeurs partagés : 1
Nombre de pointeurs partagés : 2
Nombre de pointeurs partagés : 0
Bonjour, le monde !
*/
```

## Voir aussi

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [Array](../../array/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)