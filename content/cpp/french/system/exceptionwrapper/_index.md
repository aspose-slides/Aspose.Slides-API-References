---
title: ExceptionWrapper
second_title: Référence API Aspose.Slides pour C++
description: Modèle qui représente un wrapper d'exceptions dérivées de la classe Exception.
type: docs
weight: 833
url: /fr/system/exceptionwrapper/
---
## ExceptionWrapper classe


Template that represents wrapper of exceptions that are derived from Exception class.

```cpp
template<typename T>class ExceptionWrapper
```

## Méthodes

| Method | Description |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Construit une instance nulle de la classe [ExceptionWrapper](./) qui ne représente aucune exception. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | Construit une instance de la classe [ExceptionWrapper](./) qui contient le pointeur passé. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | Constructeur de copie. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | Constructeur de déplacement. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Constructeur qui transmet les paramètres aux constructeurs de la classe Exception et crée un pointeur intelligent qui détient une nouvelle instance de la classe Exception. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | Opérateur de conversion implicite vers SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | Permet d'accéder aux membres de l'objet Exception. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | Opérateur d'affectation. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | Opérateur d'affectation par déplacement. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Raccourci pour obtenir l'objet [System::TypeInfo](../typeinfo/) pour le type Exception. |
## Définitions de type

| Typedef | Description |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Utilisé pour les fonctions de conversion. |
## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)