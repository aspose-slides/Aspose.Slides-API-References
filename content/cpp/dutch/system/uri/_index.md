---
title: Uri
second_title: "Aspose.Slides voor C++ API-referentie"
description: "Uniforme resource identifier. Objecten van deze klasse mogen alleen worden toegewezen met de functie System::MakeObject(). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik die pointer om deze als argument aan functies door te geven."
type: docs
weight: 1392
url: /nl/system/uri/
---
## Uri klasse

Unified resource identifier. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../smartptr/) pointer en gebruik die pointer om deze als argument aan functies door te geven.

```cpp
class Uri : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | Bepaalt het type van de opgegeven hostnaam. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | Bepaalt of het opgegeven schema geldig is. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | Vergelijkt de opgegeven [Uri](./) objecten met behulp van de opgegeven vergelijkingsregels. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | Bepaalt of de URI's die worden vertegenwoordigd door het huidige en het opgegeven object gelijk zijn. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergelijkt objecten met behulp van de C# [Object.Equals](../object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | Converteert een string naar zijn escaped weergave. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | Converteert een URI-string naar zijn escaped weergave. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | Haalt de decimale waarde op van een hexadecimale cijfer. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | Retourneert het absolute pad van de URI. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | Retourneert de absolute URI. |
| [String](../string/) [get_Authority](./get_authority/)() const | Retourneert de hostnaam en het poortnummer voor een server. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | Retourneert een niet-escaped hostnaam. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | Retourneert het escaped URI-fragment. |
| [String](../string/) [get_Host](./get_host/)() const | Retourneert de hostnaam. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | Retourneert het hostnaamtype. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | Retourneert een International Domain Name van de host. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Bepaalt of de URI die wordt vertegenwoordigd door het huidige object absoluut is. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | Bepaalt of de URI die wordt vertegenwoordigd door het huidige object de standaardpoort heeft voor het schema van de URI. |
| **bool** [get_IsFile](./get_isfile/)() const | Bepaalt of de URI die wordt weergegeven door het huidige object een bestand is. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | Bepaalt of de URI die wordt vertegenwoordigd door het huidige object een lokale host refereert. |
| **bool** [get_IsUnc](./get_isunc/)() const | Bepaalt of de URI die wordt vertegenwoordigd door het huidige object een UNC-pad is. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | Retourneert de besturingssysteemrepresentatie van de bestandsnaam waarnaar verwezen wordt door de URI die wordt weergegeven door het huidige object. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | Retourneert de URI-string die werd doorgegeven aan de constructor toen het huidige object werd geconstrueerd. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | Retourneert het absolute pad en de query-componenten van de URI die wordt weergegeven door het huidige object, gescheiden door een vraagteken (?). |
| **int32_t** [get_Port](./get_port/)() const | Retourneert het poortnummer van de URI die wordt vertegenwoordigd door het huidige object. |
| [String](../string/) [get_Query](./get_query/)() const | Retourneert de query-informatie die is opgenomen in de URI die wordt vertegenwoordigd door het huidige object. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | Retourneert het schema van de URI die wordt vertegenwoordigd door het huidige object. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | Retourneert een array van strings die de padsegmenten van de URI bevatten die wordt vertegenwoordigd door het huidige object. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | Bepaalt of de URI-string die aan de constructor van het huidige object werd doorgegeven volledig escaped was. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | Retourneert een gebruikersnaam, wachtwoord en andere gebruikersinformatie die gerelateerd is aan de URI die wordt vertegenwoordigd door het huidige object. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | Retourneert de opgegeven componenten van de URI die wordt weergegeven door het huidige object met behulp van de opgegeven escaping. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Haalt de hashcode op voor de URI. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | Retourneert het opgegeven deel van de URI die wordt vertegenwoordigd door het huidige object. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../object/gettype/) aanroep. |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | Retourneert een hexadecimale equivalent van het opgegeven teken. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | Converteert de opgegeven hexadecimale weergave van een teken naar een teken. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analoge van C# 'is' operator. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | Bepaalt of de URI die wordt vertegenwoordigd door het huidige [Uri](./) object een basis is van de URI die wordt vertegenwoordigd door het opgegeven [Uri](./) object. |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | Bepaalt of het opgegeven teken een geldig hexadecimaal cijfer is. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | Bepaalt of een teken in de opgegeven string op de opgegeven positie hexadecimaal gecodeerd is. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Geeft aan of de string die werd gebruikt om dit [Uri](./) te construeren goed gevormd was en niet verder escaped hoeft te worden. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | Bepaalt of de opgegeven string een goed gevormde URI is. |
| void [Lock](../object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../lockcontext/) bewaakobject. |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Bepaalt het verschil tussen twee [Uri](./) instanties. |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Bepaalt het verschil tussen URI's die worden vertegenwoordigd door het huidige en het opgegeven [Uri](./) object. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieerconstructor. Kopieert in feite niets, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Toewijzingsoperator. Kopieert in feite niets, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisatie van [Object::ReferenceEquals](../object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th template-argument in op een zwakke pointer (in plaats van gedeeld). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mocht niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mocht niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Retourneert de stringrepresentatie van de URI die wordt vertegenwoordigd door het huidige object. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Construeert een [Uri](./) object dat de opgegeven URI vertegenwoordigt; een argument specificeert het type URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Construeert een [Uri](./) object van het opgegeven [Uri](./) object dat de basis-URI vertegenwoordigt en de stringrepresentatie van de relatieve URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Construeert een [Uri](./) object van de opgegeven basis- en relatieve URI's. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementeert C# typeof([System.Object](../object/)) constructie. |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | De-escaped de opgegeven escaped string. |
| void [Unlock](../object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../lockcontext/) bewaakobject. |
|  [Uri](./uri/)(const [String](../string/)\&) | Construeert een [Uri](./) object dat de opgegeven URI vertegenwoordigt. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | Construeert een [Uri](./) object dat de opgegeven URI vertegenwoordigt; een argument geeft aan of de URI escaped moet worden. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | Construeert een [Uri](./) object van het opgegeven [Uri](./) object dat de basis-URI vertegenwoordigt en de stringrepresentatie van de relatieve URI; een argument geeft aan of de URI escaped moet worden. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | Construeert een [Uri](./) object dat de opgegeven URI vertegenwoordigt; een argument specificeert het type URI. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | Construeert een [Uri](./) object van de opgegeven basis- en relatieve URI's. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Construeert een [Uri](./) object van de opgegeven basis- en relatieve URI's. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mocht niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Vermindert de zwakke referentieteller. Mocht niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Specificeert de tekens die het communicatieprotocolschema scheiden van het adresgedeelte van de [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | Geeft aan dat de [Uri](./) een pointer naar een bestand is. |
| static [UriSchemeFtp](./urischemeftp/) | Geeft aan dat de [Uri](./) wordt benaderd via het File Transfer Protocol. |
| static [UriSchemeGopher](./urischemegopher/) | Geeft aan dat de [Uri](./) wordt benaderd via het Gopher-protocol. |
| static [UriSchemeHttp](./urischemehttp/) | Geeft aan dat de [Uri](./) wordt benaderd via het Hypertext Transfer Protocol. |
| static [UriSchemeHttps](./urischemehttps/) | Geeft aan dat de [Uri](./) wordt benaderd via het Secure Hypertext Transfer Protocol. |
| static [UriSchemeMailto](./urischememailto/) | Geeft aan dat de [Uri](./) een e-mailadres is en wordt benaderd via het Simple Mail Transport Protocol. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Geeft aan dat de [Uri](./) wordt benaderd via het NetPipe-schema dat wordt gebruikt door [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Geeft aan dat de [Uri](./) wordt benaderd via het NetTcp-schema dat wordt gebruikt door [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNews](./urischemenews/) | Geeft aan dat de [Uri](./) een internet-nieuwsgroep is en wordt benaderd via het Network News Transport Protocol. |
| static [UriSchemeNntp](./urischemenntp/) | Geeft aan dat de [Uri](./) een internet-nieuwsgroep is en wordt benaderd via het Network News Transport Protocol. |

## Opmerkingen

```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende output:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## Zie ook

* Klasse [Object](../object/)
* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)