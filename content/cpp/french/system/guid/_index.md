---
title: Guid
second_title: Aspose.Slides pour C++ Référence de l'API
description: "Représente un identifiant global unique. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer des objets de ce type."
type: docs
weight: 885
url: /fr/system/guid/
---
## Guid classe

Représente un identifiant global unique. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../smartptr/) pour gérer des objets de ce type.

```cpp
class Guid
```

## Méthodes

| Méthode | Description |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | Effectue une comparaison arithmétique des GUID représentés par les objets actuel et spécifié. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | Détermine si les GUID représentés par les objets actuel et spécifié sont égaux. |
| int [GetHashCode](./gethashcode/)() const | Renvoie un code de hachage pour l'objet actuel. |
|  [Guid](./guid/)() | Construit un objet qui représente un GUID composé de tous les zéros. |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Construit un objet qui représente un GUID spécifié comme un tableau de valeurs entières non signées de 8 bits. |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Construit un objet qui représente un GUID spécifié comme une vue de tableau de valeurs entières non signées de 8 bits. |
|  [Guid](./guid/)(const [String](../string/)\&) | Construit un objet qui représente un GUID spécifié sous forme de chaîne. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Construit une instance de la classe [Guid](./) à partir des composants GUID spécifiés. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | Construit une instance de la classe [Guid](./) à partir des composants GUID spécifiés. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Construit une instance de la classe [Guid](./) à partir des entiers non signés et des octets spécifiés. |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Construit une instance de la classe [Guid](./) à partir des entiers non signés et des octets spécifiés. |
|  [Guid](./guid/)(const [Guid](./)\&) | Construit un objet qui représente le même GUID que l'objet spécifié. |
| static [Guid](./) [NewGuid](./newguid/)() | Génére un nouveau GUID et renvoie un objet [Guid](./) qui le représente. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | Détermine si les GUID représentés par les objets actuel et spécifié ne sont pas égaux. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | Assigne à l'objet actuel la valeur GUID représentée par l'objet [Guid](./) spécifié. |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | Détermine si les GUID représentés par les objets actuel et spécifié sont égaux. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | Convertit la représentation sous forme de chaîne d'un GUID spécifié en un objet [Guid](./) équivalent. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | Convertit le GUID représenté par l'objet actuel en un tableau d'octets. |
| [String](../string/) [ToString](./tostring/)() const | Convertit le GUID représenté par l'objet actuel en sa représentation sous forme de chaîne. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Convertit le GUID représenté par l'objet actuel en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Convertit le GUID représenté par l'objet actuel en sa représentation sous forme de chaîne en utilisant le format de chaîne et la culture spécifiés. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | Tente de convertir la chaîne spécifiée en un objet [Guid](./). |
|  [~Guid](./~guid/)() | Destructeur. |
## Champs

| Champ | Description |
| --- | --- |
| static [Empty](./empty/) | Représente un GUID dont la valeur est 0. |
## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)