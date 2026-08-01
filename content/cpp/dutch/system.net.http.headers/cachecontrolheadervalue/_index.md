---
title: CacheControlHeaderValue
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een waarde van de 'Cache-Control' header voor. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, want dit leidt tot runtime-fouten en/of assertiefouten. Omsluit deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 14
url: /nl/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue klasse

Stelt een waarde van de 'Cache-Control' header voor. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wrap deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Methoden

| Method | Description |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Construeert een nieuwe instantie. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | Retourneert de collectie van de cache-extension tokens. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | Haalt de maximale leeftijdwaarde op in seconden die de tijd bepaalt waarin de client een respons accepteert. |
| **bool** [get_MaxStale](./get_maxstale/)() | Haalt de waarde op die bepaalt of de client verlopen reacties accepteert. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | Haalt de waarde op in seconden die de tijd bepaalt waarin de client verlopen reacties accepteert. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | Haalt de waarde op die de versheidslevensduur bepaalt. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | Haalt de waarde op die bepaalt of de server hervalidatie van een cache-item vereist wanneer het verouderd raakt. |
| **bool** [get_NoCache](./get_nocache/)() | Haalt de waarde op die bepaalt of de client een gecachte respons accepteert. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | Haalt de collectie van veldnamen op in de 'no-cache' directive in de 'Cache-Control' header. |
| **bool** [get_NoStore](./get_nostore/)() | Haalt de waarde op die bepaalt of een cache geen enkel deel van een HTTP-verzoek of -respons mag opslaan. |
| **bool** [get_NoTransform](./get_notransform/)() | Haalt de waarde op die bepaalt of een cache of proxy geen enkel deel van de entiteits-body mag wijzigen. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | Haalt de waarde op die bepaalt of de client alleen gecachete items mag gebruiken. |
| **bool** [get_Private](./get_private/)() | Haalt de waarde op die bepaalt of het HTTP-responsbericht of een deel ervan bedoeld is voor één gebruiker en niet door een gedeelde cache mag worden gecached. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | Haalt de collectie van veldnamen op in de 'private' directive in de 'Cache-Control' header. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | Haalt de waarde op die bepaalt of de server hervalidatie van een cache-item vereist wanneer het verouderd raakt voor de gedeelde user-agent caches. |
| **bool** [get_Public](./get_public/)() | Haalt de waarde op die bepaalt of een HTTP-respons door welke cache dan ook kan worden gecached. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | Haalt de gedeelde maximale leeftijdwaarde op in seconden die de 'max-age' directive in de 'Cache-Control' header of de 'Expires' header voor een gedeelde cache overschrijft. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Converteert een meegegeven string vanaf de gespecificeerde index naar een instantie van de [CacheControlHeaderValue](./) klasse. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Stelt hashen van aangepaste objecten in. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentinel-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Stelt klonen van aangepaste types in. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopie-constructie van subclasses mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopie-constructie van subclasses mogelijk. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Converteert een meegegeven string naar een instantie van de [CacheControlHeaderValue](./) klasse. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object met nullptr via referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Stelt de maximale leeftijdwaarde in seconden in die de tijd bepaalt waarin de client een respons accepteert. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | Stelt de waarde in die bepaalt of de client verlopen reacties accepteert. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Stelt de waarde in seconden in die de tijd bepaalt waarin de client verlopen reacties accepteert. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Stelt de waarde in die de versheidslevensduur bepaalt. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | Stelt de waarde in die bepaalt of de server hervalidatie van een cache-item vereist wanneer het verouderd raakt. |
| void [set_NoCache](./set_nocache/)(**bool**) | Stelt de waarde in die bepaalt of de client een gecachte respons accepteert. |
| void [set_NoStore](./set_nostore/)(**bool**) | Stelt de waarde in die bepaalt of een cache geen enkel deel van een HTTP-verzoek of -respons mag opslaan. |
| void [set_NoTransform](./set_notransform/)(**bool**) | Stelt de waarde in die bepaalt of een cache of proxy geen enkel deel van de entiteits-body mag wijzigen. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | Stelt de waarde in die bepaalt of de client alleen gecachete items mag gebruiken. |
| void [set_Private](./set_private/)(**bool**) | Stelt de waarde in die bepaalt of het HTTP-responsbericht of een deel ervan bedoeld is voor één gebruiker en niet door een gedeelde cache mag worden gecached. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | Stelt de waarde in die bepaalt of de server hervalidatie van een cache-item vereist wanneer het verouderd raakt voor de gedeelde user-agent caches. |
| void [set_Public](./set_public/)(**bool**) | Stelt de waarde in die bepaalt of een HTTP-respons door welke cache dan ook kan worden gecached. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Stelt de gedeelde maximale leeftijdwaarde in seconden in die de 'max-age' directive in de 'Cache-Control' header of de 'Expires' header voor een gedeelde cache overschrijft. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de template-argument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Stelt conversie van aangepaste objecten naar string in. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Probeert een meegegeven string naar een instantie van de [CacheControlHeaderValue](./) klasse te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentinel-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [ICloneable](../../system/icloneable/)
* Naamruimte [System::Net::Http::Headers](../)
* Bibliotheek [Aspose.Slides](../../)