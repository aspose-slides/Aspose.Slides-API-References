---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente un pointeur vers une fonction, une méthode ou un objet fonction. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer des objets de ce type."
type: docs
weight: 287
url: /fr/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> classe


Représente un pointeur vers une fonction, une méthode ou un objet fonction. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../smartptr/) pour gérer des objets de ce type.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ReturnType | Le type de retour d'une fonction, d'une méthode ou d'un pointeur d'objet fonction auquel la classe fait référence |
| ArgumentTypes | La liste d'arguments d'une fonction, d'une méthode ou d'un pointeur d'objet fonction auquel la classe fait référence |
## Méthodes

| Méthode | Description |
| --- | --- |
|  [Delegate](./delegate/)() | Constructeur par défaut. Construit l'objet delegate qui ne pointe sur rien. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | Constructeur de copie en déplacement. Prend la possession d'une entité pointée par le delegate spécifié. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | Constructeur. Construit un objet delegate à partir du pointeur spécifié vers une fonction libre ou une méthode statique. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | Constructeur. Construit un delegate à partir du pointeur spécifié vers l'objet fonction généré par std::bind(). |
|  [Delegate](./delegate/)(int, T\&) | Constructeur. Construit un delegate à partir de l'objet fonction spécifié. |
|  [Delegate](./delegate/)(long, T\&&) | Constructeur en déplacement. Construit un delegate à partir de l'objet fonction spécifié. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | Constructeur. Construit un delegate qui pointe vers la méthode non statique spécifiée de l'objet spécifié. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Constructeur. Construit un delegate qui pointe vers la méthode non statique spécifiée de l'objet spécifié. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | Construit un objet delegate qui pointe vers un objet fonction std::function. |
| **bool** [Empty](./empty/)() const | Détermine si l'objet delegate actuel est vide, c.-à-d. ne pointe vers aucune entité. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Invoque une fonction, une méthode ou un objet fonction pointé par l'objet delegate actuel. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | Opérateur d'affectation en déplacement. Prend la possession d'une entité pointée par le delegate spécifié. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | Compare deux objets delegate pour vérifier s'ils pointent vers la même entité. |
## Remarques



```cpp
#include "system/delegate.h"
#include <iostream"

// Déclare le délégué.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // Assigne à la variable l'adresse de la fonction PrintMessage.
  Message mes = Message(&PrintMessage);

  // Appelle la fonction.
  mes();

  return 0;
}
/*
Ce exemple de code produit la sortie suivante :
Hello, world!
*/
```

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)