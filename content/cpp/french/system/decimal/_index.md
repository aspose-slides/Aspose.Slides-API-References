---
title: Decimal
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente un nombre décimal. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer les objets de ce type."
type: docs
weight: 261
url: /fr/system/decimal/
---
## Classe Decimal

Représente un nombre décimal. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. Ne jamais utiliser la classe [System::SmartPtr](../smartptr/) pour gérer les objets de ce type.

```cpp
class Decimal
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | Ajoute deux valeurs [Decimal](./) spécifiées. |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | Renvoie la plus petite valeur entière qui est supérieure ou égale à la valeur spécifiée. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | Détermine si la valeur représentée par le premier objet [Decimal](./) est inférieure, égale ou supérieure à la valeur représentée par le second objet [Decimal](./). |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | Détermine si la valeur représentée par l'objet actuel est inférieure, égale ou supérieure à la valeur représentée par l'objet spécifié. |
| [Decimal](./decimal/)() | Construit une instance qui représente 0. |
| [Decimal](./decimal/)(std::int8_t) | Construit une instance qui représente la valeur spécifiée. |
| [Decimal](./decimal/)(std::int16_t) | Construit une instance qui représente la valeur spécifiée. |
| [Decimal](./decimal/)(std::int32_t) | Construit une instance qui représente la valeur spécifiée. |
| [Decimal](./decimal/)(std::int64_t) | Construit une instance qui représente la valeur spécifiée. |
| [Decimal](./decimal/)(std::uint8_t) | Construit une instance qui représente la valeur spécifiée. |
| [Decimal](./decimal/)(std::uint16_t) | Construit une instance qui représente la valeur spécifiée. |
| [Decimal](./decimal/)(std::uint32_t) | Construit une instance qui représente la valeur spécifiée. |
| [Decimal](./decimal/)(std::uint64_t) | Construit une instance qui représente la valeur spécifiée. |
| [Decimal](./decimal/)(**float**) | Construit une instance qui représente la valeur spécifiée. |
| [Decimal](./decimal/)(**double**) | Construit une instance qui représente la valeur spécifiée. |
| explicit [Decimal](./decimal/)(const std::string\&) | Construit une instance qui représente une valeur dont la représentation sous forme de chaîne est spécifiée comme une instance de la classe std::string. |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | Construit un objet [Decimal](./) à partir des composants spécifiés. |
| [Decimal](./decimal/)(const [Decimal](./)\&) | Construit une instance de la classe [Decimal](./) qui représente le même nombre que l'objet [Decimal](./) spécifié. |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | Construit une instance de la classe [Decimal](./) à partir d'un tableau d'entiers contenant une représentation binaire. |
| [Decimal](./decimal/)(std::nullptr_t) | Lance toujours ArgumentNullException. |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | Construit une instance de la classe [Decimal](./) représentant la valeur spécifiée. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | Divise deux valeurs [Decimal](./) spécifiées. |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | Détermine si les valeurs représentées par l'objet actuel et l'objet spécifié sont égales. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Détermine si les valeurs représentées par l'objet actuel et l'objet spécifié sont égales. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | Détermine si les valeurs représentées par les objets spécifiés sont égales. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | Renvoie la plus grande valeur entière qui est inférieure ou égale à la valeur spécifiée. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) la valeur de devise OLE spécifiée en la valeur [Decimal](./) équivalente. NOT IMPLEMENTED. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | Convertit l'objet [Decimal](./) spécifié en la représentation binaire de la valeur qu'il représente. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) la valeur [Decimal](./) spécifiée en un tableau d'octets. |
| int [GetHashCode](./gethashcode/)() const | Renvoie un code de hachage pour l'objet actuel. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Obtient le code de type de l'objet. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | Multiplie deux valeurs [Decimal](./) spécifiées. |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | Renvoie une nouvelle instance de la classe [Decimal](./) qui représente une valeur résultant de la négation de la valeur représentée par l'objet spécifié. |
| explicit [operator bool](./operator_bool/)() const | Convertit la valeur représentée par l'objet actuel en une valeur booléenne. |
| explicit [operator double](./operator_double/)() const | Convertit la valeur représentée par l'objet actuel en une valeur à double précision. |
| explicit [operator float](./operator_float/)() const | Convertit la valeur représentée par l'objet actuel en une valeur à simple précision. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | Détermine si les valeurs représentées par l'objet actuel et l'objet spécifié ne sont pas égales. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Détermine si la valeur représentée par l'objet actuel est différente de 0. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | Renvoie une nouvelle instance de la classe [Decimal](./) qui représente une valeur résultant de l'opération modulo avec les valeurs représentées par l'objet actuel et l'objet spécifié. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | Assigne à l'objet actuel une nouvelle valeur résultant de l'opération modulo avec les valeurs représentées par l'objet actuel et l'objet spécifié. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | Renvoie une nouvelle instance de la classe [Decimal](./) qui représente une valeur résultant de la multiplication des valeurs représentées par l'objet actuel et l'objet spécifié. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | Assigne à l'objet actuel une nouvelle valeur résultant de la multiplication des valeurs représentées par l'objet actuel et l'objet spécifié. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | Renvoie une nouvelle instance de la classe [Decimal](./) qui représente une valeur qui est la somme des valeurs représentées par l'objet actuel et l'objet spécifié. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | Incrémente la valeur représentée par l'objet actuel. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | Assigne à l'objet actuel une nouvelle valeur qui est la somme des valeurs représentées par l'objet actuel et l'objet spécifié. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | Renvoie une nouvelle instance de la classe [Decimal](./) qui représente une valeur résultant de la soustraction de la valeur représentée par l'objet spécifié de la valeur représentée par l'objet actuel. |
| [Decimal](./) [operator-](./operator_minus/)() const | Renvoie une nouvelle instance de la classe [Decimal](./) qui représente une valeur résultant de la négation de la valeur représentée par l'objet actuel. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | Décrémente la valeur représentée par l'objet actuel. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | Assigne à l'objet actuel une nouvelle valeur résultant de la soustraction de la valeur représentée par l'objet spécifié de la valeur représentée par l'objet actuel. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | Renvoie une nouvelle instance de la classe [Decimal](./) qui représente une valeur résultant de la division de la valeur représentée par l'objet actuel par la valeur représentée par l'objet spécifié. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | Assigne à l'objet actuel une nouvelle valeur résultant de la division de la valeur représentée par l'objet actuel par la valeur représentée par l'objet spécifié. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | Détermine si la valeur représentée par l'objet actuel est inférieure à la valeur représentée par l'objet spécifié. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | Détermine si la valeur représentée par l'objet actuel est inférieure ou égale à la valeur représentée par l'objet spécifié. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | Assigne la valeur représentée par l'objet spécifié à l'objet actuel. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | Détermine si les valeurs représentées par l'objet actuel et l'objet spécifié sont égales. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Détermine si la valeur représentée par l'objet actuel est 0. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | Détermine si la valeur représentée par l'objet actuel est supérieure à la valeur représentée par l'objet spécifié. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | Détermine si la valeur représentée par l'objet actuel est supérieure ou égale à la valeur représentée par l'objet spécifié. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | Convertit la représentation sous forme de chaîne d'un nombre décimal en une instance équivalente de la classe [Decimal](./). |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | Convertit la représentation sous forme de chaîne d'un nombre décimal en une instance équivalente de la classe [Decimal](./) en utilisant le style spécifié. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la représentation sous forme de chaîne d'un nombre décimal en une instance équivalente de la classe [Decimal](./) en utilisant le fournisseur de format spécifié. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit la représentation sous forme de chaîne d'un nombre décimal en une instance équivalente de la classe [Decimal](./) en utilisant le style et le fournisseur de format spécifiés. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | Calcule le reste après la division de deux valeurs [Decimal](./). |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | Arrondit la valeur spécifiée au nombre entier le plus proche. Un paramètre spécifie le comportement de la fonction si la valeur spécifiée est à égale distance de deux nombres les plus proches. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | Arrondit la valeur spécifiée à la valeur la plus proche avec le nombre de chiffres fractionnaires spécifié. Un paramètre spécifie le comportement de la fonction si la valeur spécifiée est à égale distance de deux nombres les plus proches. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | Soustrait une valeur [Decimal](./) spécifiée d'une autre. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | Convertit la valeur [Decimal](./) en une valeur entière non signée de 8 bits. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | Convertit la valeur [Decimal](./) en nombre à double précision. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | Convertit la valeur [Decimal](./) en une valeur entière signée de 16 bits. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | Convertit la valeur [Decimal](./) en une valeur entière signée de 32 bits. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | Convertit la valeur [Decimal](./) en une valeur entière signée de 64 bits. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) la valeur [Decimal](./) spécifiée en la valeur OLE currency équivalente. NOT IMPLEMENTED. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | Convertit la valeur [Decimal](./) en une valeur entière signée de 8 bits. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | Convertit la valeur [Decimal](./) en nombre à simple précision. |
| std::string [ToStdString](./tostdstring/)() const | Renvoie une instance de std::string contenant la représentation sous forme de chaîne de la valeur représentée par l'objet. |
| [String](../string/) [ToString](./tostring/)() const | Renvoie la représentation sous forme de chaîne de la valeur représentée par l'objet. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Convertit l'objet actuel en chaîne en utilisant les informations de format spécifiques à la culture. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Convertit l'objet actuel en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié et les informations de format spécifiques à la culture fournies par l'objet [IFormatProvider](../iformatprovider/) spécifié. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | Renvoie la représentation sous forme de chaîne de la valeur représentée par l'objet. Pour usage interne. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | Convertit la valeur [Decimal](./) en une valeur entière non signée de 16 bits. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | Convertit la valeur [Decimal](./) en une valeur entière non signée de 32 bits. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | Convertit la valeur [Decimal](./) en une valeur entière non signée de 64 bits. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | Renvoie l'objet [Decimal](./) représentant une valeur dont la partie entière est égale à celle de la valeur représentée par l'objet [Decimal](./) spécifié, tous les chiffres fractionnaires étant supprimés. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en la valeur [Decimal](./) équivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en la valeur [Decimal](./) équivalente en utilisant les informations de formatage et le style de nombre fournis. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Renvoie une référence à l'objet [TypeInfo](../typeinfo/) représentant les informations de type de la classe [Decimal](./). |
| [~Decimal](./~decimal/)() | Destructeur. |

## Champs

| Champ | Description |
| --- | --- |
| static [MaxValue](./maxvalue/) | Représente le plus grand nombre qui peut être représenté par la classe [Decimal](./). |
| static [MinusOne](./minusone/) | Représente le nombre -1. |
| static [MinValue](./minvalue/) | Représente le plus petit nombre qui peut être représenté par la classe [Decimal](./). |
| static [One](./one/) | Représente le nombre 1. |
| static [Zero](./zero/) | Représente le nombre 0. |

## Alias de type

| Alias | Description |
| --- | --- |
| [number_type](./number_type/) | Un alias pour Detail::decimal_number_type. |

## Remarques



```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
Cet exemple de code produit la sortie suivante :
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)