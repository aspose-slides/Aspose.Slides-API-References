---
title: DateTimeOffset
second_title: Référence de l'API Aspose.Slides pour C++
description: "Contient la date et l'heure du jour relatives au Temps Universel Coordonné. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Encapsulez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 235
url: /fr/system/datetimeoffset/
---
## DateTimeOffset classe

Contient la date et l'heure du jour relatives au Temps Universel Coordonné. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Encapsulez toujours cette classe dans un pointeur [System::SmartPtr](../smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument.

```cpp
class DateTimeOffset
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | Ajoute un intervalle de temps spécifié à l'objet [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | Ajoute un nombre spécifié de jours à l'objet [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | Ajoute un nombre spécifié d'heures à l'objet [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Ajoute un nombre spécifié de millisecondes à l'objet [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | Ajoute un nombre spécifié de minutes à l'objet [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | Ajoute un nombre spécifié de mois à l'objet [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | Ajoute un nombre spécifié de secondes à l'objet [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | Ajoute un nombre spécifié de ticks à l'objet [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | Ajoute un nombre spécifié d'années à l'objet [DateTimeOffset](./). |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Compare deux objets [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | Compare deux objets [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Compare deux objets [DateTimeOffset](./). |
| constexpr [DateTimeOffset](./datetimeoffset/)() | Constructeur par défaut. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | Constructeur. |
| [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | Constructeur. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | Constructeur. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | Constructeur. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | Constructeur. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | Constructeur. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Vérifie si deux objets [DateTimeOffset](./) représentent le même point dans le temps. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | Vérifie si deux objets [DateTimeOffset](./) représentent le même point dans le temps. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Vérifie si deux objets [DateTimeOffset](./) représentent le même point dans le temps. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | Vérifie si deux objets [DateTimeOffset](./) représentent le même point dans le temps et ont le même décalage. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Vérifie si deux objets [DateTimeOffset](./) représentent le même point dans le temps et ont le même décalage. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) temps de fichier en date et heure avec le décalage horaire local. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix-time en objet [DateTimeOffset](./). |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix-time en objet [DateTimeOffset](./). |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | Obtient le composant date de l'objet actuel. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | Obtient la valeur [DateTime](../datetime/). |
| int [get_Day](./get_day/)() const | Obtient le jour du mois de l'objet actuel. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Obtient le jour de la semaine de l'objet actuel. |
| int [get_DayOfYear](./get_dayofyear/)() const | Obtient le jour de l'année de l'objet actuel. |
| int [get_Hour](./get_hour/)() const | Obtient le composant heure de l'objet actuel. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | Obtient la valeur [DateTime](../datetime/) qui représente la date et l'heure locales. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Obtient le composant milliseconde de l'objet actuel. |
| int [get_Minute](./get_minute/)() const | Obtient le composant minute de l'objet actuel. |
| int [get_Month](./get_month/)() const | Obtient le composant mois de l'objet actuel. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | Obtient [DateTimeOffset](./) dont la date et l'heure sont réglées à l'heure locale actuelle et dont le décalage est celui de l'heure locale. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | Obtient le décalage par rapport à l'UTC. |
| constexpr int [get_Second](./get_second/)() const | Obtient le composant seconde de l'objet actuel. |
| **int64_t** [get_Ticks](./get_ticks/)() const | Obtient le nombre de ticks de l'objet actuel. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Obtient l'heure du jour de l'objet actuel. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | Obtient la valeur [DateTime](../datetime/) qui représente la date et l'heure UTC. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | Obtient [DateTimeOffset](./) dont la date et l'heure sont réglées à l'heure UTC actuelle et dont le décalage est [TimeSpan::Zero](../timespan/zero/). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | Obtient le nombre de ticks de l'objet actuel en temps UTC. |
| int [get_Year](./get_year/)() const | Obtient le composant année de l'objet actuel. |
| int [GetHashCode](./gethashcode/)() const | Obtient le code de hachage de l'objet [DateTimeOffset](./) actuel. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | Détermine si l'objet actuel et l'objet [DateTimeOffset](./) spécifié représentent des valeurs de date et d'heure distinctes. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Retourne une nouvelle instance de la classe [DateTimeOffset](./) qui représente la valeur de date et d'heure correspondant à la somme de la valeur représentée par l'objet actuel et de l'intervalle de temps spécifié. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Retourne une nouvelle instance de la classe [DateTimeOffset](./) représentant la valeur de date et d'heure résultant de la soustraction de l'intervalle de temps spécifié de la valeur représentée par l'objet actuel. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Retourne une instance de la classe [TimeSpan](../timespan/) qui représente l'intervalle de temps entre les valeurs de date et d'heure représentées par les objets actuel et spécifié. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | Détermine si l'objet actuel représente la valeur de date et d'heure antérieure à celle de l'objet [DateTimeOffset](./) spécifié. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | Détermine si l'objet actuel représente la valeur de date et d'heure antérieure ou égale à celle de l'objet [DateTimeOffset](./) spécifié. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | Détermine si l'objet actuel et l'objet [DateTimeOffset](./) spécifié représentent la même valeur de date et d'heure. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | Détermine si l'objet actuel représente la valeur de date et d'heure postérieure à celle de l'objet [DateTimeOffset](./) spécifié. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | Détermine si l'objet actuel représente la valeur de date et d'heure postérieure ou égale à celle de l'objet [DateTimeOffset](./) spécifié. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | Convertit la chaîne spécifiée en équivalent [DateTimeOffset](./). |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Convertit la chaîne spécifiée en objet [DateTimeOffset](./) en utilisant le fournisseur de format et le style de formatage spécifiés. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Convertit la chaîne spécifiée en objet [DateTimeOffset](./) en utilisant le format, le fournisseur de format et le style de formatage spécifiés. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Convertit la chaîne spécifiée en objet [DateTimeOffset](./) en utilisant les formats, le fournisseur de format et le style de formatage spécifiés. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Soustrait un intervalle de temps spécifié de l'objet actuel. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | Soustrait une valeur [DateTimeOffset](./) spécifiée de l'objet actuel. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Convertit l'objet actuel en temps de fichier [Windows](../../system.windows/). |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | Convertit l'objet actuel en un objet qui représente l'heure locale. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | Remplace le décalage de l'objet actuel par le décalage spécifié. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Convertit l'objet actuel en chaîne en utilisant le format et le fournisseur de format spécifiés. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Convertit l'objet actuel en chaîne en utilisant le fournisseur de format spécifié. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Convertit l'objet actuel en chaîne en utilisant le format spécifié. |
| [String](../string/) [ToString](./tostring/)() const | Convertit l'objet actuel en chaîne. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | Convertit l'objet actuel en un objet qui représente l'heure UTC. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Obtient les millisecondes écoulées depuis le début de l'époque Unix. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Obtient les secondes écoulées depuis le début de l'époque Unix. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | Tente de convertir la chaîne spécifiée en objet [DateTimeOffset](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Tente de convertir la chaîne spécifiée en objet [DateTimeOffset](./) en utilisant le fournisseur de format et le style de formatage spécifiés. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Tente de convertir la chaîne spécifiée en objet [DateTimeOffset](./) en utilisant les formats, le fournisseur de format et le style de formatage spécifiés. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Tente de convertir la chaîne spécifiée en objet [DateTimeOffset](./) en utilisant le format, le fournisseur de format et le style de formatage spécifiés. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Retourne un objet [TypeInfo](../typeinfo/) qui représente la structure [TimeSpan](../timespan/). |

## Champs

| Champ | Description |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Obtient le décalage maximal en ticks. |
| static [MaxValue](./maxvalue/) | Obtient la plus grande valeur [DateTimeOffset](./). |
| static constexpr [MinOffset](./minoffset/) | Obtient le décalage minimal en ticks. |
| static [MinValue](./minvalue/) | Obtient la valeur [DateTimeOffset](./) la plus ancienne. |
| static [UnixEpoch](./unixepoch/) | Obtient le début de l'époque Unix. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)