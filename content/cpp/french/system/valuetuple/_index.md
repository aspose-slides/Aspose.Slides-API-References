---
title: ValueTuple
second_title: Référence API Aspose.Slides pour C++
description: Classe qui représente une structure de données ValueTuple.
type: docs
weight: 1418
url: /fr/system/valuetuple/
---
## ValueTuple classe

Classe qui représente une structure de données [ValueTuple](./).

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## Methods

| Méthode | Description |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | Détermine si les objets actuels et spécifiés sont identiques. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<Index, tuple_t\>\& [Item](./item/)() | Obtient la référence à la valeur du composant de l'objet [ValueTuple](./). |
| const std::tuple_element_t\<Index, tuple_t\>\& [Item](./item/)() const | Obtient la valeur du composant de l'objet [ValueTuple](./). |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Déconstruit l'objet en ce tuple de valeurs. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Renvoie une référence à l'objet [TypeInfo](../typeinfo/) représentant les informations de type de la classe [ValueTuple](./). |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | Construit un objet tuple. |
## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)