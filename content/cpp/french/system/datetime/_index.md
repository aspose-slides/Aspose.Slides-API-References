---
title: DateTime
second_title: Référence API Aspose.Slides pour C++
description: "Représente une valeur de date et d'heure spécifique sur le continuum du temps. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer les objets de ce type."
type: docs
weight: 222
url: /fr/system/datetime/
---
## Classe DateTime

Représente une valeur de date et d’heure spécifique sur le continuum du temps. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N’utilisez jamais la classe [System::SmartPtr](../smartptr/) pour gérer les objets de ce type.

```cpp
class DateTime
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | Retourne une nouvelle instance de la classe [DateTime](./) qui représente une valeur de date et d’heure résultant de l’addition de l’intervalle de temps spécifié à la valeur de date et d’heure représentée par l’objet actuel. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | Retourne une nouvelle instance de la classe [DateTime](./) représentant la valeur de date et d’heure qui est la somme de la valeur représentée par l’objet actuel et du nombre spécifié de jours. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | Retourne une nouvelle instance de la classe [DateTime](./) représentant la valeur de date et d’heure qui est la somme de la valeur représentée par l’objet actuel et du nombre spécifié d’heures. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Retourne une nouvelle instance de la classe [DateTime](./) représentant la valeur de date et d’heure qui est la somme de la valeur représentée par l’objet actuel et du nombre spécifié de millisecondes. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | Retourne une nouvelle instance de la classe [DateTime](./) représentant la valeur de date et d’heure qui est la somme de la valeur représentée par l’objet actuel et du nombre spécifié de minutes. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | Retourne une nouvelle instance de la classe [DateTime](./) représentant la valeur de date et d’heure qui est la somme de la valeur représentée par l’objet actuel et du nombre spécifié de mois. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | Retourne une nouvelle instance de la classe [DateTime](./) représentant la valeur de date et d’heure qui est la somme de la valeur représentée par l’objet actuel et du nombre spécifié de secondes. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | Retourne une nouvelle instance de la classe [DateTime](./) représentant la valeur de date et d’heure qui est la somme de la valeur représentée par l’objet actuel et du nombre spécifié d’intervalles de 100 nanosecondes. |
| [DateTime](./) [AddYears](./addyears/)(int) const | Retourne une nouvelle instance de la classe [DateTime](./) représentant la valeur de date et d’heure dont le composant année est augmenté du nombre spécifié. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | Compare deux valeurs représentées par les instances spécifiées de la classe [DateTime](./) et retourne la valeur indiquant la position relative des valeurs sur la ligne du temps. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | Compare deux valeurs de date et d’heure représentées par l’objet actuel et l’instance spécifiée de la classe [DateTime](./) et retourne la valeur indiquant la position relative des valeurs sur la ligne du temps. |
| constexpr [DateTime](./datetime/)() | Construit une instance qui représente la plus petite valeur possible de date et d’heure égale à MinValue. |
|  [DateTime](./datetime/)(int, int, int) | Construit une instance qui représente une valeur de date et d’heure spécifiée par une année, un mois et un jour particuliers. |
|  [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Construit une instance qui représente une valeur de date et d’heure spécifiée par une année, un mois et un jour particuliers dans le calendrier indiqué. |
|  [DateTime](./datetime/)(int, int, int, int, int, int) | Construit une instance qui représente une valeur de date et d’heure spécifiée par une année, un mois, un jour, une heure, une minute et une seconde particuliers. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Construit une instance qui représente une valeur de date et d’heure spécifiée par une année, un mois, un jour, une heure, une minute et une seconde particuliers. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Construit une instance qui représente une valeur de date et d’heure spécifiée par une année, un mois, un jour, une heure, une minute et une seconde particuliers dans le calendrier indiqué. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Construit une instance qui représente une valeur de date et d’heure spécifiée par une année, un mois, un jour, une heure, une minute, une seconde et une milliseconde particuliers. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | Construit une instance qui représente une valeur de date et d’heure spécifiée par une année, un mois, un jour, une heure, une minute, une seconde et une milliseconde particuliers dans le calendrier indiqué. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | Construit une instance qui représente une valeur de date et d’heure spécifiée par un nombre de ticks. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | Construit une instance qui représente une valeur de date et d’heure spécifiée par un nombre de ticks. POUR USAGE INTERNE. |
|  [DateTime](./datetime/)(const [DateTime](./)\&) | Copie-construit une instance. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | Retourne le nombre de jours dans le mois spécifié de l’année spécifiée. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | Détermine si les instances spécifiées de la classe [DateTime](./) représentent la même valeur de date et d’heure. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | Détermine si l’instance spécifiée de la classe [DateTime](./) représente la même valeur de date et d’heure que l’objet actuel. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | Désérialise la valeur de date-heure à partir de l’entier non signé 64 bits indiqué et affecte la nouvelle instance de la classe [DateTime](./) à cette valeur. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | Convertit le File time indiqué en une instance de la classe [DateTime](./) représentant la même valeur de date et d’heure que l’heure locale. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | Convertit le File time indiqué en une instance de la classe [DateTime](./) représentant la même valeur de date et d’heure que l’heure UTC. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | Retourne une instance de la classe [DateTime](./) représentant la valeur de date et d’heure équivalente à la date d’automatisation OLE spécifiée. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | Convertit la valeur Unix time indiquée en une instance de la classe [DateTime](./). POUR USAGE INTERNE. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | Retourne une nouvelle instance de la classe [DateTime](./) qui représente la partie date de la date-heure représentée par l’objet actuel, avec chaque composant de la partie temps mis à 0. |
| int [get_Day](./get_day/)() const | Retourne le numéro ordinal du jour du mois représenté par l’objet actuel. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Retourne une valeur représentant le jour de la semaine représenté par l’objet actuel. |
| int [get_DayOfYear](./get_dayofyear/)() const | Retourne le numéro ordinal du jour de l’année représenté par l’objet actuel. |
| constexpr int [get_Hour](./get_hour/)() const | Retourne le composant heure de la valeur de date et d’heure représentée par l’objet actuel. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | Retourne la valeur indiquant si la date et l’heure représentées par l’objet actuel sont locales, UTC ou aucune des deux. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Retourne le composant milliseconde de la valeur de date et d’heure représentée par l’objet actuel. |
| constexpr int [get_Minute](./get_minute/)() const | Retourne le composant minute de la valeur de date et d’heure représentée par l’objet actuel. |
| int [get_Month](./get_month/)() const | Retourne le numéro ordinal du mois de l’année représenté par l’objet actuel. |
| static [DateTime](./) [get_Now](./get_now/)() | Retourne une instance de la classe [DateTime](./) qui représente l’heure actuelle en heure locale. |
| constexpr int [get_Second](./get_second/)() const | Retourne le composant seconde de la valeur de date et d’heure représentée par l’objet actuel. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Retourne le nombre d’intervalles de 100 nanosecondes écoulés depuis 00 :00 :00 UTC, 1 janvier 0001 du calendrier grégorien jusqu’à la date-heure représentée par l’objet actuel. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Retourne la valeur qui représente l’intervalle de temps entre le début du jour représenté par l’objet actuel et la valeur de date et d’heure représentée par l’objet actuel. |
| static [DateTime](./) [get_Today](./get_today/)() | Retourne une instance de la classe [DateTime](./) qui représente la date actuelle avec chaque composant de la partie temps mis à 0. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | Retourne une instance de la classe [DateTime](./) qui représente l’heure actuelle en UTC. |
| int [get_Year](./get_year/)() const | Retourne l’année représentée par l’objet actuel. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Obtient les parties de la date. POUR USAGE INTERNE. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | Retourne un tableau de chaînes où chaque élément est la représentation sous forme de chaîne de l’objet actuel formatée avec l’un des spécificateurs de format de date et d’heure standards. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Retourne un tableau de chaînes où chaque élément est la représentation sous forme de chaîne de l’objet actuel formatée avec le spécificateur de format de date et d’heure standard indiqué. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Retourne un tableau de chaînes où chaque élément est la représentation sous forme de chaîne de l’objet actuel formatée avec l’un des spécificateurs de format de date et d’heure standards et le fournisseur de format indiqué. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Retourne un tableau de chaînes où chaque élément est la représentation sous forme de chaîne de l’objet actuel formatée avec le spécificateur de format de date et d’heure standard indiqué et le fournisseur de format. |
| int [GetHashCode](./gethashcode/)() const | Retourne un code de hachage pour l’objet actuel. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Détermine si la valeur de date et d’heure représentée par l’objet actuel se situe dans la période d’heure d’été pour le fuseau horaire actuel. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Détermine si l’année spécifiée est une année bissextile. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | Détermine si l’objet actuel et l’objet [DateTime](./) spécifié représentent des valeurs de date et d’heure distinctes. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Retourne une nouvelle instance de la classe [DateTime](./) qui représente la valeur de date et d’heure qui est la somme de la valeur représentée par l’objet actuel et de l’intervalle de temps spécifié. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | Affecte à l’objet actuel la valeur de date et d’heure qui est la somme de la valeur représentée par l’objet actuel et de l’intervalle de temps spécifié. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Retourne une nouvelle instance de la classe [DateTime](./) représentant la valeur de date et d’heure qui résulte de la soustraction de l’intervalle de temps spécifié à la valeur représentée par l’objet actuel. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | Retourne une instance de la classe [TimeSpan](../timespan/) qui représente l’intervalle de temps entre les valeurs de date et d’heure représentées par les objets actuel et spécifié. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | Affecte à l’objet actuel la valeur de date et d’heure qui résulte de la soustraction de l’intervalle de temps spécifié à la valeur de date et d’heure représentée par l’objet actuel. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | Détermine si l’objet actuel représente la valeur de date et d’heure antérieure à celle représentée par l’objet [DateTime](./) spécifié. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | Détermine si l’objet actuel représente la valeur de date et d’heure antérieure ou égale à celle représentée par l’objet [DateTime](./) spécifié. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | Assigne la valeur représentée par l’instance [DateTime](./) spécifiée à l’objet actuel. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | Détermine si l’objet actuel et l’objet [DateTime](./) spécifié représentent la même valeur de date et d’heure. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | Détermine si l’objet actuel représente la valeur de date et d’heure postérieure à celle représentée par l’objet [DateTime](./) spécifié. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | Détermine si l’objet actuel représente la valeur de date et d’heure postérieure ou égale à celle représentée par l’objet [DateTime](./) spécifié. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | Convertit la représentation sous forme de chaîne d’une valeur de date et d’heure en l’équivalent de l’objet [DateTime](./). |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Convertit la représentation sous forme de chaîne d’une valeur de date et d’heure en l’équivalent de l’objet [DateTime](./) en utilisant les informations de format spécifiques à la culture. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Convertit la représentation sous forme de chaîne d’une valeur de date et d’heure en l’équivalent de l’objet [DateTime](./) en utilisant le format indiqué et les informations de format spécifiques à la culture. Le format de la chaîne doit correspondre exactement au format indiqué. Lève une exception si la conversion échoue. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Convertit la représentation sous forme de chaîne d’une valeur de date et d’heure en l’équivalent de l’objet [DateTime](./) en utilisant les formats, les informations de format spécifiques à la culture et le style indiqués. Le format de la chaîne doit correspondre exactement à un ou plusieurs des formats indiqués. Lève une exception si la conversion échoue. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | Construit un nouvel objet [DateTime](./) qui représente le même nombre de ticks que l’objet [DateTime](./) indiqué et représente l’heure locale, l’heure UTC ou aucune des deux selon le paramètre **kind**. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Retourne une nouvelle instance de la classe [DateTime](./) représentant la valeur de date et d’heure qui résulte de la soustraction de l’intervalle de temps spécifié à la valeur représentée par l’objet actuel. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | Retourne une instance de la classe [TimeSpan](../timespan/) représentant l’intervalle de temps entre les valeurs de date et d’heure représentées par les objets actuel et spécifié. |
| **int64_t** [ToBinary](./tobinary/)() const | Sérialise l’objet actuel. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Retourne une valeur qui représente la date et l’heure de l’objet actuel sous forme de File time. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | Convertit la valeur de date et d’heure de l’objet actuel en File time UTC. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | Retourne une nouvelle instance de la classe [DateTime](./) qui représente la valeur de date et d’heure de l’objet actuel en heure locale. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | Retourne une chaîne contenant la représentation longue de la date de l’objet actuel. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | Retourne une chaîne contenant la représentation longue de l’heure de l’objet actuel. |
| **double** [ToOADate](./tooadate/)() const | Retourne la valeur de date et d’heure de l’objet actuel sous forme de date d’automatisation OLE. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | Retourne une chaîne contenant la représentation courte de la date de l’objet actuel. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | Retourne une chaîne contenant la représentation courte de l’heure de l’objet actuel. |
| [String](../string/) [ToString](./tostring/)() const | Retourne la représentation sous forme de chaîne de la valeur de date et d’heure de l’objet actuel en utilisant les conventions de formatage définies par la culture actuelle. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Retourne la représentation sous forme de chaîne de la valeur de date et d’heure de l’objet actuel en utilisant le format indiqué et les conventions de formatage définies par la culture actuelle. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Retourne la représentation sous forme de chaîne de la valeur de date et d’heure de l’objet actuel en utilisant les informations de format spécifiées. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Retourne la représentation sous forme de chaîne de la valeur de date et d’heure de l’objet actuel en utilisant les informations de format spécifiées. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | Retourne une nouvelle instance de la classe [DateTime](./) qui représente la valeur de date et d’heure de l’objet actuel en UTC. |
| time_t [ToUnixTime](./tounixtime/)() const | Retourne une valeur qui représente la date et l’heure de l’objet actuel sous forme de temps Unix. POUR USAGE INTERNE. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | Convertit la représentation sous forme de chaîne d’une valeur de date et d’heure en l’équivalent de l’objet [DateTime](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Convertit la représentation sous forme de chaîne d’une valeur de date et d’heure en l’équivalent de l’objet [DateTime](./) en utilisant les informations de format spécifiques à la culture et le style indiqués. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Convertit la représentation sous forme de chaîne d’une valeur de date et d’heure en l’équivalent de l’objet [DateTime](./) en utilisant le format, les informations de format spécifiques à la culture et le style indiqués. Le format de la chaîne doit correspondre exactement au format indiqué. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Convertit la représentation sous forme de chaîne d’une valeur de date et d’heure en l’équivalent de l’objet [DateTime](./) en utilisant les formats, les informations de format spécifiques à la culture et le style indiqués. Le format de la chaîne doit correspondre exactement à un ou plusieurs des formats indiqués. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Retourne un objet [TypeInfo](../typeinfo/) qui contient des informations sur cette classe. |
## Champs

| Champ | Description |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | Le nombre d’intervalles de 100 nanosecondes dans l’intervalle de temps entre la valeur [DateTime](./) minimale possible et la valeur maximale possible. |
| static [MaxValue](./maxvalue/) | Une instance de la classe [DateTime](./) qui représente la valeur de date et d’heure maximale possible. |
| static constexpr [MinTicks](./minticks/) | Le nombre minimal de ticks qu’une instance de la classe [DateTime](./) peut représenter. |
| static [MinValue](./minvalue/) | Une instance de la classe [DateTime](./) qui représente la valeur de date et d’heure minimale possible. |
| static constexpr [TicksPerDay](./ticksperday/) | Le nombre de ticks dans une journée. |
| static constexpr [TicksPerHour](./ticksperhour/) | Le nombre de ticks dans une heure. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | Le nombre de ticks dans une microseconde. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Le nombre de ticks dans une milliseconde. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Le nombre de ticks dans une minute. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Le nombre de ticks dans une seconde. |
| static [UnixEpoch](./unixepoch/) | Une instance de la classe [DateTime](./) qui représente le début de l’époque Unix (01 janv 1970 00 :00 :00). |
## Remarques



```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Créez l'instance de la classe 'DateTime'.
  DateTime dateTime{1990, 10, 30};

  // Imprimez l'instance dans plusieurs formats.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
Cet exemple de code produit la sortie suivante:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)