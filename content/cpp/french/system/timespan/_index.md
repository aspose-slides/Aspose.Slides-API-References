---
title: TimeSpan
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente un intervalle de temps. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer des objets de ce type."
type: docs
weight: 1288
url: /fr/system/timespan/
---
## Classe TimeSpan


Represents a time interval. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class TimeSpan
```

## Méthodes

| Method | Description |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | Renvoie une nouvelle instance de la classe [TimeSpan](./) qui représente un intervalle de temps correspondant à la somme des intervalles de temps représentés par l'objet actuel et l'objet spécifié. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | Compare deux objets [TimeSpan](./). |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | Compare l'objet actuel et l'objet spécifié. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Compare l'objet actuel et l'objet spécifié. |
| [TimeSpan](./) [Duration](./duration/)() const | Renvoie une nouvelle instance de l'objet [TimeSpan](./) dont la valeur est la valeur absolue de l'objet actuel. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | Détermine si l'intervalle de temps représenté par l'objet actuel est égal à l'intervalle de temps représenté par l'objet spécifié. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Détermine si l'intervalle de temps représenté par l'objet actuel est égal à l'intervalle de temps représenté par l'objet spécifié. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | Renvoie true si les objets spécifiés représentent le même intervalle de temps, sinon false. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | Renvoie un nouvel objet [TimeSpan](./) qui représente l'intervalle spécifié. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | Renvoie un nouvel objet [TimeSpan](./) qui représente l'intervalle spécifié. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | Renvoie un nouvel objet [TimeSpan](./) qui représente l'intervalle spécifié. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | Renvoie un nouvel objet [TimeSpan](./) qui représente l'intervalle spécifié. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | Renvoie un nouvel objet [TimeSpan](./) qui représente l'intervalle spécifié. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | Renvoie un nouvel objet [TimeSpan](./) qui représente l'intervalle spécifié. |
| constexpr int [get_Days](./get_days/)() const | Renvoie la composante jours de l'intervalle de temps représenté par l'objet actuel [TimeSpan](./). |
| constexpr int [get_Hours](./get_hours/)() const | Renvoie la composante heures de l'intervalle de temps représenté par l'objet actuel [TimeSpan](./). |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | Renvoie la composante millisecondes de l'intervalle de temps représenté par l'objet actuel [TimeSpan](./). |
| constexpr int [get_Minutes](./get_minutes/)() const | Renvoie la composante minutes de l'intervalle de temps représenté par l'objet actuel [TimeSpan](./). |
| constexpr int [get_Seconds](./get_seconds/)() const | Renvoie la composante secondes de l'intervalle de temps représenté par l'objet actuel [TimeSpan](./). |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Renvoie le nombre d'intervalles de 100 nanosecondes qui constituent l'intervalle de temps représenté par l'objet actuel [TimeSpan](./). |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | Renvoie la valeur de l'objet actuel [TimeSpan](./) exprimée en jours entiers et fractions de jour. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | Renvoie la valeur de l'objet actuel [TimeSpan](./) exprimée en heures entières et fractions d'heure. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Renvoie la valeur de l'objet actuel [TimeSpan](./) exprimée en millisecondes entières et fractions de milliseconde. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | Renvoie la valeur de l'objet actuel [TimeSpan](./) exprimée en minutes entières et fractions de minute. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | Renvoie la valeur de l'objet actuel [TimeSpan](./) exprimée en secondes entières et fractions de seconde. |
| int [GetHashCode](./gethashcode/)() const | Renvoie un code de hachage pour l'objet actuel. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | Renvoie une nouvelle instance de l'objet [TimeSpan](./) qui représente la valeur négative de l'objet actuel [TimeSpan](./). |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | Détermine si l'intervalle de temps représenté par l'objet actuel n'est pas égal à l'intervalle de temps représenté par l'objet spécifié. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | Renvoie une nouvelle instance de la classe [TimeSpan](./) qui représente un intervalle de temps correspondant à la somme des intervalles de temps représentés par les objets actuel et spécifié. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | Renvoie l'instance elle-même. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | Attribue à l'objet actuel l'intervalle de temps correspondant à la somme de l'intervalle de temps représenté par l'objet actuel et l'objet spécifié. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | Renvoie une nouvelle instance de la classe [TimeSpan](./) qui représente un intervalle de temps résultant de la soustraction de l'intervalle de temps représenté par l'objet spécifié de l'intervalle de temps représenté par l'objet actuel. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | Renvoie une nouvelle instance de l'objet [TimeSpan](./) qui représente la valeur négative de l'objet actuel [TimeSpan](./). |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | Attribue à l'objet actuel l'intervalle de temps résultant de la soustraction de l'intervalle de temps représenté par l'objet spécifié de l'intervalle de temps représenté par l'objet actuel. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | Détermine si l'intervalle de temps représenté par l'objet actuel est plus court que l'intervalle de temps représenté par l'objet spécifié. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | Détermine si l'intervalle de temps représenté par l'objet actuel est plus court ou égal à l'intervalle de temps représenté par l'objet spécifié. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | Attribue l'intervalle de temps de l'objet [TimeSpan](./) spécifié à l'objet actuel [TimeSpan](./). |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | Détermine si l'intervalle de temps représenté par l'objet actuel est égal à l'intervalle de temps représenté par l'objet spécifié. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | Détermine si l'intervalle de temps représenté par l'objet actuel est plus long que l'intervalle de temps représenté par l'objet spécifié. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | Détermine si l'intervalle de temps représenté par l'objet actuel est plus long ou égal à l'intervalle de temps représenté par l'objet spécifié. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | Convertit une chaîne en objet [TimeSpan](./) équivalent. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convertit une chaîne en objet [TimeSpan](./) équivalent en utilisant le fournisseur de format spécifié. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Convertit une chaîne en objet [TimeSpan](./) équivalent en utilisant les formats spécifiés, le fournisseur de format et les styles. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Convertit une chaîne en objet [TimeSpan](./) équivalent en utilisant le format spécifié, le fournisseur de format et les styles. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | Renvoie une nouvelle instance de la classe [TimeSpan](./) qui représente un intervalle de temps résultant de la soustraction de l'intervalle de temps représenté par l'objet spécifié de l'intervalle de temps représenté par l'objet actuel. |
| constexpr [TimeSpan](./timespan/)() | Construit un objet [TimeSpan](./) qui représente un intervalle de temps nul. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | Construit une instance de la classe [TimeSpan](./) qui représente l'intervalle de temps spécifié. |
|  [TimeSpan](./timespan/)(int, int, int) | Construit une instance de la classe [TimeSpan](./) qui représente l'intervalle de temps égal à la somme du nombre spécifié d'heures, de minutes et de secondes. |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | Construit une instance de la classe [TimeSpan](./) qui représente l'intervalle de temps égal à la somme du nombre spécifié d'heures, de minutes, de secondes et de millisecondes. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | Construit un objet [TimeSpan](./) qui représente l'intervalle de temps égal à l'intervalle de temps représenté par l'objet [TimeSpan](./) spécifié. |
| [String](../string/) [ToString](./tostring/)() const | Renvoie la représentation sous forme de chaîne de caractères de l'intervalle de temps représenté par l'objet actuel. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Convertit la valeur de l'objet actuel en représentation de chaîne équivalente, en utilisant le format spécifié. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Convertit la valeur de l'objet actuel en représentation de chaîne équivalente, en utilisant le format et le fournisseur de format spécifiés. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | Convertit une chaîne en objet [TimeSpan](./) équivalent et renvoie le résultat de la conversion. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Convertit une chaîne en objet [TimeSpan](./) équivalent en utilisant le fournisseur de format spécifié et renvoie le résultat de la conversion. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Convertit une chaîne en objet [TimeSpan](./) équivalent en utilisant les formats spécifiés et le fournisseur de format, et renvoie le résultat de la conversion. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Convertit une chaîne en objet [TimeSpan](./) équivalent en utilisant le format, le fournisseur de format et les styles spécifiés, et renvoie le résultat de la conversion. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Convertit une chaîne en objet [TimeSpan](./) équivalent en utilisant les formats, le fournisseur de format et les styles spécifiés, et renvoie le résultat de la conversion. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Convertit une chaîne en objet [TimeSpan](./) équivalent en utilisant le format et le fournisseur de format, et renvoie le résultat de la conversion. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Renvoie un objet [TypeInfo](../typeinfo/) qui représente la structure [TimeSpan](./). |

## Champs

| Field | Description |
| --- | --- |
| static [MaxValue](./maxvalue/) | L'objet [TimeSpan](./) qui représente l'intervalle le plus long possible. |
| static [MinValue](./minvalue/) | /// L'objet [TimeSpan](./) qui représente l'intervalle le plus court possible. |
| static constexpr [TicksPerDay](./ticksperday/) | Le nombre d'intervalles de 100 nanosecondes dans une journée (intervalle de 24 heures). |
| static constexpr [TicksPerHour](./ticksperhour/) | Le nombre d'intervalles de 100 nanosecondes dans une heure. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Le nombre d'intervalles de 100 nanosecondes dans une milliseconde. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Le nombre d'intervalles de 100 nanosecondes dans une minute. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Le nombre d'intervalles de 100 nanosecondes dans une seconde. |
| static [Zero](./zero/) | L'objet [TimeSpan](./) qui représente un intervalle nul. |

## Remarques



```cpp
#include "system/datetime.h"
#include "system/timespan.h"
#include <iostream>

int main()
{
  const auto date1 = System::DateTime(2021, 01, 01);
  const auto date2 = System::DateTime(2021, 10, 30);

  const auto interval = date2 - date1;

  std::cout << "Number of ticks: " << interval.get_Ticks() << std::endl;
  std::cout << "Number of milliseconds: " << interval.get_Milliseconds() << std::endl;
  std::cout << "Total number of milliseconds: " << interval.get_TotalMilliseconds() << std::endl;
  std::cout << "Number of minutes: " << interval.get_Minutes() << std::endl;
  std::cout << "Total number of minutes: " << interval.get_TotalMinutes() << std::endl;
  std::cout << "Number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Total number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Number of days: " << interval.get_Days() << std::endl;
  std::cout << "Total number of days: " << interval.get_TotalDays() << std::endl;

  return 0;
}
/*
Cet exemple de code produit la sortie suivante :
Number of ticks: 260928000000000
Number of milliseconds: 0
Total number of milliseconds: 2.60928e+10
Number of minutes: 0
Total number of minutes: 434880
Number of hours: 0
Total number of hours: 0
Number of days: 302
Total number of days: 302
*/
```

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)