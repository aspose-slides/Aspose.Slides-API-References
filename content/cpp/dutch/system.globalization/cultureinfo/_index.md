---
title: CultureInfo
second_title: Aspose.Slides voor C++ API-referentie
description: "Collectie van cultuurspecifieke waarden en algoritmen. Setter-bewerkingen zijn alleen ingeschakeld op objecten die niet alleen-lezen zijn. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten oplevert. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 53
url: /nl/system.globalization/cultureinfo/
---
## CultureInfo klasse

Collectie van cultuurspecifieke waarden en algoritmen. Setter-bewerkingen zijn alleen ingeschakeld op objecten die niet alleen-lezen zijn. Objecten van deze klasse moeten alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [ClearCachedData](./clearcacheddata/)() | Vernieuwt gecachte cultuurinformatie. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Kloont cultuurinfo. |
| static [CultureInfoPtr](../cultureinfoptr/) [CreateSpecificCulture](./createspecificculture/)(const [String](../../system/string/)\&) | Creëert een cultuur op naam. |
| explicit  [CultureInfo](./cultureinfo/)(int) | RTTI-informatie. |
|  [CultureInfo](./cultureinfo/)(int, **bool**) | Constructor. |
| explicit  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&) | Constructor. |
|  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&, **bool**) | Constructor. |
|  [CultureInfo](./cultureinfo/)(std::nullptr_t) | Gooit altijd ArgumentNullException. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergelijkt objecten. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-achtige zwevend-kommagetallenvergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-achtige zwevend-kommagetallenvergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [CalendarPtr](../calendarptr/) [get_Calendar](./get_calendar/)() const | Haalt de kalender op die door de cultuur wordt gebruikt. |
| virtual [CompareInfoPtr](../compareinfoptr/) [get_CompareInfo](./get_compareinfo/)() const | Haalt de stringvergelijker op die voldoet aan de cultuurrichtlijnen. |
| [CultureTypes](../culturetypes/) [get_CultureTypes](./get_culturetypes/)() const | Haalt de bitwise-samenvoeging op van cultuurtypen die de huidige cultuur beschrijven. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentCulture](./get_currentculture/)() | Haalt de cultuur op die voor de huidige thread is ingesteld. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentUICulture](./get_currentuiculture/)() | Haalt de UI-cultuur van de huidige thread op. |
| virtual [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_DateTimeFormat](./get_datetimeformat/)() const | Haalt datumopmaak-informatie op. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | Haalt de standaardcultuur op in het huidige toepassingsdomein. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | Haalt de standaard UI-cultuur op in het huidige toepassingsdomein. |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | Haalt de weergavenaam van de cultuur op. |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | Haalt de Engelse naam van de cultuur op. |
| [String](../../system/string/) [get_IetfLanguageTag](./get_ietflanguagetag/)() const | Haalt de RFC-4646-naam voor een taal op. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InstalledUICulture](./get_installeduiculture/)() | Haalt de cultuur op die met het besturingssysteem is geïnstalleerd. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InvariantCulture](./get_invariantculture/)() | Haalt de invariante cultuur op. |
| virtual **bool** [get_IsNeutralCulture](./get_isneutralculture/)() const | Controleert of de cultuur neutraal is. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Controleert of het cultuurobject alleen-lezen is. |
| virtual int [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | Haalt de actieve invoer-locale-identificator op. |
| virtual int [get_LCID](./get_lcid/)() const | Haalt de cultuur-identificator op. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Haalt de cultuurnaam op. |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | Haalt de oorspronkelijke cultuurnaam op. |
| virtual [NumberFormatInfoPtr](../numberformatinfoptr/) [get_NumberFormat](./get_numberformat/)() const | Haalt getalopmaak-informatie op. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[CalendarPtr](../calendarptr/)\> [get_OptionalCalendars](./get_optionalcalendars/)() const | Lijst van kalenders die met de cultuur kunnen worden gebruikt. |
| virtual [CultureInfoPtr](../cultureinfoptr/) [get_Parent](./get_parent/)() const | Haalt de bovenliggende cultuur op. |
| virtual [TextInfoPtr](../textinfoptr/) [get_TextInfo](./get_textinfo/)() const | Haalt tekstparameters op die door de cultuur worden gebruikt. |
| virtual [String](../../system/string/) [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | Haalt de drieletterige ISO 639-2-taalcode op. |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | Haalt de drieletterige code voor de taal op zoals gedefinieerd in de [Windows](../../system.windows/) API. |
| virtual [String](../../system/string/) [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | Haalt de tweeletterige ISO-taalnaam op die bij de cultuur hoort. |
| **bool** [get_UseUserOverride](./get_useuseroverride/)() const | Haalt een vlag op die aangeeft of de [CultureInfo](./) gebruikers-geselecteerde cultuurinstellingen gebruikt. |
| [CultureInfoPtr](../cultureinfoptr/) [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | Haalt een alternatieve cultuur op die geschikt is voor console-applicaties. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&) | Haalt de cultuur op op basis van de naam. Hetzelfde als CreateSpecificCulture. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Haalt de cultuur op op basis van de naam. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(**int32_t**) | Haalt de cultuur op op basis van id. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const [String](../../system/string/)\&) | Verouderd. Haalt een alleen-lezen [CultureInfo](./) object op via de opgegeven RFC-4646-taaltag. |
| static [ArrayPtr](../../system/arrayptr/)\<[CultureInfoPtr](../cultureinfoptr/)\> [GetCultures](./getcultures/)([CultureTypes](../culturetypes/)) | Haalt culturen op die tot de gespecificeerde typen behoren. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Haalt formatteringsobject op voor een specifiek type. |
| int [GetHashCode](./gethashcode/)() const override | Geeft de hash-code van het object terug. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge aan C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat door targetType wordt beschreven. Analoge aan C# ‘is’-operator. |
| **bool** [IsInherited](./isinherited/)() const | Haalt de geërfde-vlag op. VOOR INTERNE GEBRUIK. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge aan C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieer-constructor. Kopieert niets, initialiseert slechts een nieuw object en maakt kopiëren door subklassen mogelijk. |
| [CultureInfo](./)\& [operator=](./operator_equal/)(const [CultureInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzings-operator. Kopieert niets, initialiseert slechts een nieuw object en maakt kopiëren door subklassen mogelijk. |
| **bool** [operator==](./operator_equal_equal/)(const [CultureInfo](./)\&) const | Vergelijkt cultuurparameters. |
| static [CultureInfoPtr](../cultureinfoptr/) [ReadOnly](./readonly/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Haalt een alleen-lezen versie van de cultuur op. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr per referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| static void [set_CurrentCulture](./set_currentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Stelt de cultuur in voor de huidige thread. |
| static void [set_CurrentUICulture](./set_currentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Stelt de UI-cultuur van de huidige thread in. |
| virtual void [set_DateTimeFormat](./set_datetimeformat/)([DateTimeFormatInfoPtr](../datetimeformatinfoptr/)) | Stelt datumopmaak-informatie in. |
| static void [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Stelt de standaardcultuur in het huidige toepassingsdomein in. |
| static void [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Stelt de standaard UI-cultuur in het huidige toepassingsdomein in. |
| virtual void [set_NumberFormat](./set_numberformat/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Haalt getalopmaak-informatie op. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in op een zwakke pointer (in plaats van gedeelde). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt de gedeelde referentieteller en geeft deze terug. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Converteert cultuur naar string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Klasse [IFormatProvider](../../system/iformatprovider/)
* Klasse [ICloneable](../../system/icloneable/)
* Naamruimte [System::Globalization](../)
* Bibliotheek [Aspose.Slides](../../)