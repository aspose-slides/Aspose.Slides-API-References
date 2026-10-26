---
title: Uri
second_title: Aspose.Slides för C++ API-referens
description: "Enhetlig resursidentifierare. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omge alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 1392
url: /sv/system/uri/
---
## Uri klass


Enhetlig resursidentifierare. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Bunta alltid in denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class Uri : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | Bestämmer typen av det angivna värdnamnet. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | Bestämmer om det angivna schemat är giltigt. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | Jämför de angivna [Uri](./)-objekten med hjälp av de angivna jämförelsereglerna. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | Bestämmer om de URI:er som representeras av det aktuella och det angivna objektet är lika. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Jämför objekt med C# [Object.Equals](../object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | Konverterar en sträng till dess escapade representation. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | Konverterar en URI-sträng till dess escapade representation. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | Hämtar det decimala värdet av en hexadecimal siffra. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | Returnerar URI:ens absoluta sökväg. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | Returnerar den absoluta URI:n. |
| [String](../string/) [get_Authority](./get_authority/)() const | Returnerar värdnamnet och portnumret för en server. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | Returnerar ett icke-escapat värdnamn. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | Returnerar den escapade URI-fragmentet. |
| [String](../string/) [get_Host](./get_host/)() const | Returnerar värdnamnet. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | Returnerar typen av värdnamn. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | Returnerar ett internationellt domännamn för värden. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Bestämmer om URI:n som representeras av det aktuella objektet är absolut. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | Bestämmer om URI:n som representeras av det aktuella objektet har standardport för URI:ns schema. |
| **bool** [get_IsFile](./get_isfile/)() const | Bestämmer om URI:n som representeras av det aktuella objektet är en fil. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | Bestämmer om URI:n som representeras av det aktuella objektet refererar till en lokal värd. |
| **bool** [get_IsUnc](./get_isunc/)() const | Bestämmer om URI:n som representeras av det aktuella objektet är en UNC-sökväg. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | Returnerar operativsystemets representation av filnamnet som refereras av URI:n som representeras av det aktuella objektet. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | Returnerar URI-strängen som skickades till konstruktorn när det aktuella objektet skapades. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | Returnerar den absoluta sökvägen och frågekomponenterna för URI:n som representeras av det aktuella objektet, separerade med ett frågetecken (?). |
| **int32_t** [get_Port](./get_port/)() const | Returnerar portnumret för URI:n som representeras av det aktuella objektet. |
| [String](../string/) [get_Query](./get_query/)() const | Returnerar frågeinformationen som ingår i URI:n som representeras av det aktuella objektet. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | Returnerar schemat för URI:n som representeras av det aktuella objektet. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | Returnerar en array av strängar som innehåller sökvägssegmenten för URI:n som representeras av det aktuella objektet. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | Bestämmer om URI-strängen som skickades till konstruktorn för det aktuella objektet var fullständigt escapad. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | Returnerar ett användarnamn, lösenord och annan användarinformation som är associerad med URI:n som representeras av det aktuella objektet. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | Returnerar de angivna komponenterna av URI:n som representeras av det aktuella objektet med den angivna escapingen. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Hämtar hashkoden för URI:n. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | Returnerar den angivna delen av URI:n som representeras av det aktuella objektet. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Hämtar det faktiska typen av objektet. Analog till C# [System.Object.GetType()](../object/gettype/)-anrop. |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | Returnerar en hexadecimal motsvarighet till det angivna tecknet. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | Konverterar den angivna hexadecimala representationen av ett tecken till ett tecken. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen beskriven av targetType. Analog till C#-operatorn 'is'. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | Bestämmer om URI:n som representeras av det aktuella [Uri](./)-objektet är en bas för URI:n som representeras av det angivna [Uri](./)-objektet. |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | Bestämmer om det angivna tecknet representerar en giltig hexadecimal siffra. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | Bestämmer om ett tecken i den angivna strängen på den angivna positionen är hexadecimalt kodad. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Indikerar huruvida strängen som användes för att konstruera detta [Uri](./) var välformad och inte kräver ytterligare escaping. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | Bestämmer om den angivna strängen är en välformad URI. |
| void [Lock](../object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjekt. |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Bestämmer skillnaden mellan två [Uri](./)-instanser. |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Bestämmer skillnaden mellan URI:er representerade av det aktuella och det angivna [Uri](./)-objektet. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../object/memberwiseclone/)-metoden. Gör det möjligt att klona anpassade typer. |
|  [Object](../object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt ett värdetypsobjekt med nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specialisering av [Object::ReferenceEquals](../object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Sätter den n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../object/sharedcount/)() const | Hämtar nuvarande värde för delad referensräknare. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| [String](../string/) [ToString](./tostring/)() const override | Returnerar den strängrepresentation av URI:n som representeras av det aktuella objektet. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Skapar ett [Uri](./)-objekt som representerar den angivna URI:n; ett argument specificerar URI-typen. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Skapar ett [Uri](./)-objekt från det angivna [Uri](./)-objektet som representerar bas-URI:n och den strängrepresentation av relativ URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Skapar ett [Uri](./)-objekt från de angivna bas- och relativa URI:erna. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementerar C# typeof([System.Object](../object/))-konstruktion. |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | Avkodar den angivna escapade strängen. |
| void [Unlock](../object/unlock/)() | Implementerar avlåsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../lockcontext/)-vaktobjekt. |
|  [Uri](./uri/)(const [String](../string/)\&) | Skapar ett [Uri](./)-objekt som representerar den angivna URI:n. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | Skapar ett [Uri](./)-objekt som representerar den angivna URI:n; ett argument specificerar om URI:n ska escapade. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | Skapar ett [Uri](./)-objekt från det angivna [Uri](./)-objektet som representerar bas-URI:n och den strängrepresentation av relativ URI; ett argument specificerar om URI:n ska escapade. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | Skapar ett [Uri](./)-objekt som representerar den angivna URI:n; ett argument specificerar URI-typen. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | Skapar ett [Uri](./)-objekt från de angivna bas- och relativa URI:erna. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Skapar ett [Uri](./)-objekt från de angivna bas- och relativa URI:erna. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Anger tecknen som separerar kommunikationsprotokollets schema från adressdelen av [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | Anger att [Uri](./) är en pekare till en fil. |
| static [UriSchemeFtp](./urischemeftp/) | Anger att [Uri](./) nås via File Transfer Protocol. |
| static [UriSchemeGopher](./urischemegopher/) | Anger att [Uri](./) nås via Gopher-protokollet. |
| static [UriSchemeHttp](./urischemehttp/) | Anger att [Uri](./) nås via Hypertext Transfer Protocol. |
| static [UriSchemeHttps](./urischemehttps/) | Anger att [Uri](./) nås via Secure Hypertext Transfer Protocol. |
| static [UriSchemeMailto](./urischememailto/) | Anger att [Uri](./) är en e-postadress och nås via Simple Mail Transport Protocol. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Anger att [Uri](./) nås via NetPipe-schemat som används av [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Anger att [Uri](./) nås via NetTcp-schemat som används av [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNews](./urischemenews/) | Anger att [Uri](./) är en Internet-nyhetsgrupp och nås via Network News Transport Protocol. |
| static [UriSchemeNntp](./urischemenntp/) | Anger att [Uri](./) är en Internet-nyhetsgrupp och nås via Network News Transport Protocol. |

## Anmärkningar



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
Det här kodexemplet producerar följande utskrift:
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

## Se också

* Klass [Object](../object/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)