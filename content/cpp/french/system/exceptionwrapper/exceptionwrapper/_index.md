---
title: ExceptionWrapper()
second_title: Référence API Aspose.Slides pour C++
description: Construit une instance nulle de la classe ExceptionWrapper qui ne représente aucune exception.
type: docs
weight: 14
url: /fr/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) constructeur


Construit une instance nulle de la classe [ExceptionWrapper](../) qui ne représente aucune exception.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) constructeur


Construit une instance de la classe [ExceptionWrapper](../) qui contient le pointeur passé.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Pointeur intelligent vers l'instance de la classe Exception. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) constructeur


Constructeur de copie.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Autre instance de la classe wrapper qui doit être copiée. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) constructeur


Constructeur de déplacement.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Autre instance de la classe wrapper qui doit être déplacée. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) constructeur


Constructeur qui transmet les paramètres aux constructeurs de la classe Exception et crée un pointeur intelligent qui détient une nouvelle instance de la classe Exception.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## Voir aussi

* Typedef [ExceptionPtr](../../exceptionptr/)
* Classe [ExceptionWrapper](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)