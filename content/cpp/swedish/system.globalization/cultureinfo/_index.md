---
title: CultureInfo
second_title: Aspose.Slides för C++ API-referens
description: "Samling av kulturspecifika värden och algoritmer. Sättoperationer är endast aktiverade på objekt som inte är skrivskyddade. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller påståendefel. Inslå alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 53
url: /sv/system.globalization/cultureinfo/
---
## CultureInfo klass

Samling av kulturspecifika värden och algoritmer. Sättoperationer är endast aktiverade på objekt som inte är skrivskyddade. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller påståendefel. Inslå alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## Metoder

| Method | Description |
| --- | --- |
| void [ClearCachedData](./clearcacheddata/)() | Uppdaterar cachad kulturinformation. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Klonar kulturinfo. |
| static [CultureInfoPtr](../cultureinfoptr/) [CreateSpecificCulture](./createspecificculture/)(const [String](../../system/string/)\&) | Skapar kultur efter namn. |
| explicit  [CultureInfo](./cultureinfo/)(int) | RTTI-information. |
|  [CultureInfo](./cultureinfo/)(int, **bool**) | Konstruktor. |
| explicit  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&, **bool**) | Konstruktor. |
|  [CultureInfo](./cultureinfo/)(std::nullptr_t) | Kastar alltid ArgumentNullException. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Jämför objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| virtual [CalendarPtr](../calendarptr/) [get_Calendar](./get_calendar/)() const | Hämtar kalender som används av kulturen. |
| virtual [CompareInfoPtr](../compareinfoptr/) [get_CompareInfo](./get_compareinfo/)() const | Hämtar strängjämförare som följer kulturregler. |
| [CultureTypes](../culturetypes/) [get_CultureTypes](./get_culturetypes/)() const | Hämtar bitvis sammanslagning av kulturyper som beskriver den aktuella kulturen. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentCulture](./get_currentculture/)() | Hämtar kulturinställning för den aktuella tråden. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentUICulture](./get_currentuiculture/)() | Hämtar den aktuella trådens UI-kultur. |
| virtual [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_DateTimeFormat](./get_datetimeformat/)() const | Hämtar datumformatinformation. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | Hämtar standardkultur i den aktuella applikationsdomänen. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | Hämtar standard-UI-kultur i den aktuella applikationsdomänen. |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | Hämtar kulturens visningsnamn. |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | Hämtar kulturens engelska namn. |
| [String](../../system/string/) [get_IetfLanguageTag](./get_ietflanguagetag/)() const | Hämtar RFC 4646-namnet för ett språk. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InstalledUICulture](./get_installeduiculture/)() | Hämtar kultur som är installerad med operativsystemet. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InvariantCulture](./get_invariantculture/)() | Hämtar invariant kultur. |
| virtual **bool** [get_IsNeutralCulture](./get_isneutralculture/)() const | Kontrollerar om kulturen är neutral. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Kontrollerar om kulturobjektet är skrivskyddat. |
| virtual int [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | Hämtar aktivt inmatningslokalidentifierare. |
| virtual int [get_LCID](./get_lcid/)() const | Hämtar kulturidentifierare. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Hämtar kulturnamn. |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | Hämtar kulturens inhemska namn. |
| virtual [NumberFormatInfoPtr](../numberformatinfoptr/) [get_NumberFormat](./get_numberformat/)() const | Hämtar talformatinformation. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[CalendarPtr](../calendarptr/)\> [get_OptionalCalendars](./get_optionalcalendars/)() const | Lista över kalendrar som kan användas med kulturen. |
| virtual [CultureInfoPtr](../cultureinfoptr/) [get_Parent](./get_parent/)() const | Hämtar föräldrakultur. |
| virtual [TextInfoPtr](../textinfoptr/) [get_TextInfo](./get_textinfo/)() const | Hämtar textparametrar som används av kulturen. |
| virtual [String](../../system/string/) [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | Hämtar trebokstavskod för ISO 639-2-språk. |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | Hämtar trebokstavskod för språk enligt [Windows](../../system.windows/)-API. |
| virtual [String](../../system/string/) [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | Hämtar tvåbokstavs ISO-språknamn som är associerat med kulturen. |
| **bool** [get_UseUserOverride](./get_useuseroverride/)() const | Hämtar en flagga som indikerar om [CultureInfo](./) använder användarvalda kulturinställningar. |
| [CultureInfoPtr](../cultureinfoptr/) [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | Hämtar alternativ kultur lämplig för konsolapplikationer. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknardatastruktur associerad med objektet. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&) | Hämtar kultur efter namn. Samma som CreateSpecificCulture. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Hämtar kultur efter namn. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(**int32_t**) | Hämtar kultur efter id. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const [String](../../system/string/)\&) | Föråldrad. Hämtar ett skrivskyddat [CultureInfo](./)-objekt med den specificerade RFC 4646-språktaggen. |
| static [ArrayPtr](../../system/arrayptr/)\<[CultureInfoPtr](../cultureinfoptr/)\> [GetCultures](./getcultures/)([CultureTypes](../culturetypes/)) | Hämtar kulturer som faller inom angivna typer. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Hämtar formatobjekt för specifik typ. |
| int [GetHashCode](./gethashcode/)() const override | Returnerar objektets hash-kod. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typ beskrivna av targetType. Analog till C# 'is'-operator. |
| **bool** [IsInherited](./isinherited/)() const | Hämtar är-ärvd-flaggan. ENDAST FÖR INTERNT BRUK. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [CultureInfo](./)\& [operator=](./operator_equal/)(const [CultureInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| **bool** [operator==](./operator_equal_equal/)(const [CultureInfo](./)\&) const | Jämför kulturparametrar. |
| static [CultureInfoPtr](../cultureinfoptr/) [ReadOnly](./readonly/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Hämtar en skrivskyddad version av kultur. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| static void [set_CurrentCulture](./set_currentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Ställer in kultur för den aktuella tråden. |
| static void [set_CurrentUICulture](./set_currentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Ställer in den aktuella trådens UI-kultur. |
| virtual void [set_DateTimeFormat](./set_datetimeformat/)([DateTimeFormatInfoPtr](../datetimeformatinfoptr/)) | Ställer in datumformatinformation. |
| static void [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Ställer in standardkultur i den aktuella applikationsdomänen. |
| static void [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Ställer in standard-UI-kultur i den aktuella applikationsdomänen. |
| virtual void [set_NumberFormat](./set_numberformat/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Hämtar talformatinformation. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n:te mallargument till en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Konverterar kultur till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../../system/object/)
* Klass [IFormatProvider](../../system/iformatprovider/)
* Klass [ICloneable](../../system/icloneable/)
* Namnrymd [System::Globalization](../)
* Bibliotek [Aspose.Slides](../../)