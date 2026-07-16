---
title: WeakPtr()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un pointeur nul.
type: docs
weight: 1
url: /fr/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) constructeur


Crée un pointeur nul.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) constructeur


Crée un pointeur faible vers l'objet donné.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) pour créer un pointeur faible vers. |

## WeakPtr::WeakPtr(const SmartPtr_\&) constructeur


Crée un pointeur faible référant le même pointeur que ptr pointe.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | Pointeur pour copier la valeur du pointee depuis. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) constructeur


Crée un pointeur faible référant le même pointeur que x pointe.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Q | type pointee du pointeur source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Pointeur pour copier la valeur du pointee depuis. |

## WeakPtr::WeakPtr(const WeakPtr_\&) constructeur


Construit un pointeur faible par copie.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | Pointeur pour copier la valeur du pointee depuis. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) constructeur


Construit un pointeur faible par copie.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Q | type pointee du pointeur source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | Pointeur pour copier la valeur du pointee depuis. |

## WeakPtr::WeakPtr(SmartPtr_\&&) constructeur


Construit un pointeur faible par déplacement.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | Pointeur pour déplacer la valeur du pointee depuis. |

## Voir également

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Classe [WeakPtr](../)
* Classe [SmartPtr](../../smartptr/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)