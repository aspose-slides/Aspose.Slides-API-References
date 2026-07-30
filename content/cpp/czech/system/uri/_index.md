---
title: Uri
second_title: Aspose.Slides pro C++ API Reference
description: "Jednotný identifikátor zdroje. Objektům této třídy by mělo být alokováno pouze pomocí funkce System::MakeObject() . Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 1392
url: /cs/system/uri/
---
## Uri třída

Unified resource identifier. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Uri : public System::Object
```

## Metody

| Method | Description |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | Určuje typ zadaného názvu hostitele. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | Určuje, zda je zadané schéma platné. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | Porovnává zadané objekty [Uri](./) pomocí specifikovaných pravidel porovnání. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | Určuje, zda jsou URI reprezentované aktuálním a zadaným objektem stejné. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | Převádí řetězec na jeho escapovanou reprezentaci. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | Převádí řetězec URI na jeho escapovanou reprezentaci. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | Získává desetinnou hodnotu hexadecimální číslice. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | Vrací absolutní cestu URI. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | Vrací absolutní URI. |
| [String](../string/) [get_Authority](./get_authority/)() const | Vrací název hostitele a číslo portu pro server. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | Vrací neescapovaný název hostitele. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | Vrací escapovaný fragment URI. |
| [String](../string/) [get_Host](./get_host/)() const | Vrací název hostitele. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | Vrací typ názvu hostitele. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | Vrací mezinárodní doménové jméno hostitele. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Určuje, zda je URI reprezentované aktuálním objektem absolutní. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | Určuje, zda má URI reprezentované aktuálním objektem výchozí port pro schéma URI. |
| **bool** [get_IsFile](./get_isfile/)() const | Určuje, zda je URI reprezentované aktuálním objektem soubor. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | Určuje, zda URI reprezentované aktuálním objektem odkazuje na lokální hostitele. |
| **bool** [get_IsUnc](./get_isunc/)() const | Určuje, zda je URI reprezentované aktuálním objektem UNC cestou. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | Vrací operační systémovou reprezentaci názvu souboru odkazovaného URI reprezentovaným aktuálním objektem. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | Vrací řetězec URI, který byl předán konstruktoru při vytvoření aktuálního objektu. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | Vrací absolutní cestu a komponenty dotazu URI reprezentovaného aktuálním objektem, oddělené otazníkem (?). |
| **int32_t** [get_Port](./get_port/)() const | Vrací číslo portu URI reprezentovaného aktuálním objektem. |
| [String](../string/) [get_Query](./get_query/)() const | Vrací informace o dotazu obsažené v URI reprezentovaném aktuálním objektem. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | Vrací schéma URI reprezentovaného aktuálním objektem. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | Vrací pole řetězců obsahujících segmenty cesty URI reprezentovaného aktuálním objektem. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | Určuje, zda řetězec URI předaný konstruktoru aktuálního objektu byl plně escapován. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | Vrací uživatelské jméno, heslo a další uživatelské informace spojené s URI reprezentovaným aktuálním objektem. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | Vrací zadané komponenty URI reprezentovaného aktuálním objektem pomocí specifikovaného escapování. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Získává hash kód pro URI. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | Vrací zadanou část URI reprezentovaného aktuálním objektem. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../object/gettype/). |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | Vrací hexadecimální ekvivalent zadaného znaku. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | Převádí zadanou hexadecimální reprezentaci znaku na znak. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | Určuje, zda je URI reprezentované aktuálním objektem [Uri](./) základem URI reprezentovaného zadaným objektem [Uri](./). |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | Určuje, zda zadaný znak představuje platnou hexadecimální číslici. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | Určuje, zda je znak v zadaném řetězci na určené pozici hexadecimálně kódován. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Indikuje, zda řetězec použitý k vytvoření tohoto [Uri](./) byl správně vytvořený a není nutné jej dále escapovat. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | Určuje, zda je zadaný řetězec dobře formovaný URI. |
| void [Lock](../object/lock/)() | Implementuje zamykání pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../lockcontext/). |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Určuje rozdíl mezi dvěma instancemi [Uri](./). |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Určuje rozdíl mezi URI reprezentovanými aktuálním a zadaným objektem [Uri](./). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| [Object](../object/object/)() | Vytváří objekt. Inicializuje všechny interní datové struktury. |
| [Object](../object/object/)([Object](../object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Vrací řetězcovou reprezentaci URI reprezentovaného aktuálním objektem. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Vytváří objekt [Uri](./), který reprezentuje zadané URI; argument určuje druh URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Vytváří objekt [Uri](./) z uvedeného objektu [Uri](./) představujícího základní URI a řetězcové reprezentace relativního URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Vytváří objekt [Uri](./) ze specifikovaných základního a relativního URI. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukci C# typeof([System.Object](../object/)). |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | Odkrývá (unescapes) zadaný escapovaný řetězec. |
| void [Unlock](../object/unlock/)() | Implementuje odemknutí pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../lockcontext/). |
| [Uri](./uri/)(const [String](../string/)\&) | Vytváří objekt [Uri](./), který reprezentuje zadané URI. |
| [Uri](./uri/)(const [String](../string/)&, **bool**) | Vytváří objekt [Uri](./) reprezentující zadané URI; argument určuje, zda má být URI escapováno. |
| [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | Vytváří objekt [Uri](./) ze zadaného objektu [Uri](./) představujícího základní URI a řetězcové reprezentace relativního URI; argument určuje, zda má být URI escapováno. |
| [Uri](./uri/)(const [String](../string/)&, [UriKind](../urikind/)) | Vytváří objekt [Uri](./), který reprezentuje zadané URI; argument určuje druh URI. |
| [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | Vytváří objekt [Uri](./) ze zadaných základního a relativního URI. |
| [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Vytváří objekt [Uri](./) ze zadaných základního a relativního URI. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../object/~object/)() | Niči objekt. Uvolňuje všechny interní datové struktury. |

## Pole

| Field | Description |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Určuje znaky, které oddělují schéma komunikačního protokolu od adresní části [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | Určuje, že [Uri](./) je ukazatel na soubor. |
| static [UriSchemeFtp](./urischemeftp/) | Určuje, že [Uri](./) je přístupné přes protokol FTP. |
| static [UriSchemeGopher](./urischemegopher/) | Určuje, že [Uri](./) je přístupné přes protokol Gopher. |
| static [UriSchemeHttp](./urischemehttp/) | Určuje, že [Uri](./) je přístupné přes protokol HTTP. |
| static [UriSchemeHttps](./urischemehttps/) | Určuje, že [Uri](./) je přístupné přes protokol HTTPS. |
| static [UriSchemeMailto](./urischememailto/) | Určuje, že [Uri](./) je e-mailová adresa a je přístupná přes protokol SMTP. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Určuje, že [Uri](./) je přístupné přes schéma NetPipe používané [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Určuje, že [Uri](./) je přístupné přes schéma NetTcp používané [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNews](./urischemenews/) | Určuje, že [Uri](./) je internetová novinová skupina a je přístupná přes protokol NNTP. |
| static [UriSchemeNntp](./urischemenntp/) | Určuje, že [Uri](./) je internetová novinová skupina a je přístupná přes protokol NNTP. |

## Poznámky

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
Tento ukázkový kód produkuje následující výstup:
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

## Viz také

* Třída [Object](../object/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)