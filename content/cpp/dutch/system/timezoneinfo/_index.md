---
title: TimeZoneInfo
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een informatie voor die een specifieke tijdzone beschrijft. Objecten van deze klasse mogen alleen worden toegewezen met de functie System::MakeObject(). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Omhul deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om hem als argument aan functies door te geven."
type: docs
weight: 1340
url: /nl/system/timezoneinfo/
---
## TimeZoneInfo klasse


Stelt een informatie voor die een specifieke tijdzone beschrijft. Objecten van deze klasse mogen alleen worden toegewezen met de functie [System::MakeObject()](../makeobject/). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Omhul deze klasse altijd in een [System::SmartPtr](../smartptr/)-pointer en gebruik deze pointer om hem als argument aan functies door te geven.

```cpp
class TimeZoneInfo : public System::IEquatable<TimeZoneInfoPtr>
```

## Methoden

| Method | Description |
| --- | --- |
| static void [ClearCachedData](./clearcacheddata/)() | Wis de in cache opgeslagen tijdzone-gegevens. |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) tijd van één tijdzone naar een andere. |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTime](./converttime/)(const [DateTimeOffset](../datetimeoffset/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) tijd naar de tijd in een gespecificeerde tijdzone. |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) tijd naar de tijd in een gespecificeerde tijdzone. |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&) | [Convert](../convert/) tijd naar de tijd in een gespecificeerde tijdzone. |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(const [DateTimeOffset](../datetimeoffset/)\&, const [String](../string/)\&) | [Convert](../convert/) tijd naar de tijd in een gespecificeerde tijdzone. |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&, const [String](../string/)\&) | [Convert](../convert/) tijd naar de tijd in een gespecificeerde tijdzone. |
| static [DateTime](../datetime/) [ConvertTimeFromUtc](./converttimefromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | Converteert UTC-tijd naar de tijd in een gespecificeerde tijdzone. |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | Converteert tijd naar UTC-tijd. |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/)) | Converteert tijd naar UTC-tijd. |
| static [DateTime](../datetime/) [ConvertTimeToUtcNoThrow](./converttimetoutcnothrow/)([DateTime](../datetime/)) | Converteert tijd naar UTC-tijd. VOOR INTERNE GEBRUIK. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&, **bool**) | Maakt een aangepaste tijdzone. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&) | Maakt een aangepaste tijdzone. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&) | Maakt een aangepaste tijdzone. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override |  |
| **bool** [Equals](./equals/)([TimeZoneInfoPtr](../timezoneinfoptr/)) override | Bepaalt of het huidige en opgegeven object gelijk zijn. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-achtige zwevende-komma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-achtige zwevende-komma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [FindSystemTimeZoneById](./findsystemtimezonebyid/)(const [String](../string/)\&) | Haalt tijdzone met opgegeven identifier. |
| [TimeSpan](../timespan/) [get_BaseUtcOffset](./get_baseutcoffset/)() const | Retourneert een instantie van [TimeSpan](../timespan/) die een tijdsinterval tussen de standaardtijd van de huidige tijdzone en UTC-tijd weergeeft. |
| [String](../string/) [get_DaylightName](./get_daylightname/)() const | Haalt naam op voor de zomertijd van de huidige tijdzone. |
| [String](../string/) [get_DisplayName](./get_displayname/)() const | Haalt naam op voor de huidige tijdzone. |
| [String](../string/) [get_Id](./get_id/)() const | Retourneert de identifier van de tijdzone die wordt vertegenwoordigd door het huidige object. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Local](./get_local/)() | Retourneert een instantie van [TimeZoneInfo](./) die een lokale tijdzone weergeeft. |
| [String](../string/) [get_StandardName](./get_standardname/)() const | Haalt naam op voor de standaardtijd van de huidige tijdzone. |
| **bool** [get_SupportsDaylightSavingTime](./get_supportsdaylightsavingtime/)() const | Haalt vlag op die aangeeft of de tijdzone regels voor zomertijd heeft. |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Utc](./get_utc/)() | Retourneert een instantie van [TimeZoneInfo](./) die een UTC-tijdzone weergeeft. |
| [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\> [GetAdjustmentRules](./getadjustmentrules/)() const | Retourneert een array bestaande uit **AdjustmentRule**-objecten die aanpassingsregels vertegenwoordigen die van toepassing zijn op het huidige [TimeZoneInfo](./)-object. |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)([DateTime](../datetime/)) const | Haalt UTC-datums en -tijden op waarnaar een opgegeven datum en tijd kan worden gemapt. |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)(const [DateTimeOffset](../datetimeoffset/)\&) const | Haalt UTC-datums en -tijden op waarnaar een opgegeven datum en tijd kan worden gemapt. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Haalt referentieteller-datastructuur op die aan het object is gekoppeld. |
| int [GetHashCode](./gethashcode/)() const override | Analoge van C# [Object.GetHashCode()](../object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| static [SharedPtr](../sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[TimeZoneInfoPtr](../timezoneinfoptr/)\>\> [GetSystemTimeZones](./getsystemtimezones/)() | Haalt gesorteerde verzameling op van alle tijdzones die beschikbaar zijn op het lokale systeem. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Haalt feitelijk type van object op. Analoge van C# [System.Object.GetType()](../object/gettype/)-aanroep. |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) const | Bereken verschil tussen tijd in deze tijdzone en UTC-tijdzone voor een opgegeven datum en tijd. |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)(const [DateTimeOffset](../datetimeoffset/)\&) const | Bereken verschil tussen tijd in deze tijdzone en UTC-tijdzone voor een opgegeven datum en tijd. |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | Interne hulpfunctie die de UTC-offset teruggeeft voor een UTC-datum-tijd in een gespecificeerde tijdzone. VOOR INTERNE GEBRUIK. |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, **bool**\&, **bool**\&) | Interne hulpfunctie die de UTC-offset teruggeeft voor een UTC-datum-tijd in een gespecificeerde tijdzone. VOOR INTERNE GEBRUIK. |
| [TimeSpan](../timespan/) [GetUtcOffsetNoThrow](./getutcoffsetnothrow/)([DateTime](../datetime/)) const | Bereken verschil tussen tijd in deze tijdzone en UTC-tijdzone voor een opgegeven datum en tijd. VOOR INTERNE GEBRUIK. |
| **bool** [HasSameRules](./hassamerules/)(const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) const | Controleert of de huidige en een andere tijdzone dezelfde aanpassingsregels hebben. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Controleert of object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van C# 'is'-operator. |
| **bool** [IsAmbiguousTime](./isambiguoustime/)([DateTime](../datetime/)) const | Controleert of opgegeven datum en tijd ambigu is en naar meerdere UTC-tijden kan worden gemapt. |
| **bool** [IsAmbiguousTime](./isambiguoustime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | Controleert of opgegeven datum en tijd ambigu is en naar meerdere UTC-tijden kan worden gemapt. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) const | Controleert of opgegeven datum en tijd binnen de periode van zomertijd valt. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | Controleert of opgegeven datum en tijd binnen de periode van zomertijd valt. |
| **bool** [IsDaylightSavingTimeNoThrow](./isdaylightsavingtimenothrow/)([DateTime](../datetime/)) const | Controleert of opgegeven datum en tijd binnen de periode van zomertijd valt. |
| **bool** [IsInvalidTime](./isinvalidtime/)([DateTime](../datetime/)) const | Controleert of opgegeven datum en tijd ongeldig is. |
| void [Lock](../object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../lockcontext/)-waarnemingsobject. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../object/object/)([Object](../object/) const\&) | Copy-constructor. Kopieert niets, initialiseert gewoon een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Assignatie-operator. Kopieert niets, initialiseert gewoon een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object per referentie met nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Stelt nth-template-argument in als een zwakke pointer (in plaats van gedeeld). Maakt schakelen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Analoge van C# [Object.ToString()](../object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static [DateTime](../datetime/) [TransitionTimeToDateTime](./transitiontimetodatetime/)(**int32_t**, const **TransitionTime**\&) | Hulpfunctie die een jaar en **TransitionTime** converteert naar een [DateTime](../datetime/). |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementeert C# typeof([System.Object](../object/)) constructie. |
| void [Unlock](../object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../lockcontext/)-waarnemingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [AdjustmentRulePtr](./adjustmentruleptr/) | Een alias voor een gedeelde pointer naar een instantie van de **AdjustmentRule**-klasse. |

## Zie ook

* Klasse [IEquatable](../iequatable/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)