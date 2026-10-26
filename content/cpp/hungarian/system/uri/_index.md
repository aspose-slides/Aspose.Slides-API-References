---
title: Uri
second_title: Aspose.Slides C++ API referencia
description: "Egységes erőforrás-azonosító. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az objektum függvények argumentumaként történő átadásához."
type: docs
weight: 1392
url: /hu/system/uri/
---
## Uri osztály

Unified resource identifier. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Uri : public System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | Meghatározza a megadott gépnév típusát. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | Meghatározza, hogy a megadott séma érvényes-e. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | Összehasonlítja a megadott [Uri](./) objektumokat a megadott összehasonlítási szabályok alapján. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | Meghatározza, hogy a jelenlegi és a megadott objektumok által reprezentált URI-k egyenlőek-e. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../object/equals/) szemantika alapján. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | Átalakít egy karakterláncot a megfelelő escape-reprezentációvá. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | Átalakít egy URI karakterláncot a megfelelő escape-reprezentációvá. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | Megkapja egy hexadecimális számjegy decimális értékét. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | Visszaadja az URI abszolút útvonalát. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | Visszaadja az abszolút URI-t. |
| [String](../string/) [get_Authority](./get_authority/)() const | Visszaadja a kiszolgáló gépnevet és a portszámot. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | Visszaadja egy escape-eltlen gépnevet. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | Visszaadja a escape-elt URI-fragmentumot. |
| [String](../string/) [get_Host](./get_host/)() const | Visszaadja a gépnevet. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | Visszaadja a gépnév típusát. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | Visszaadja a kiszolgáló International Domain Name-jét. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Meghatározza, hogy a jelenlegi objektum által reprezentált URI abszolút-e. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | Meghatározza, hogy a jelenlegi objektum által reprezentált URI rendelkezik-e alapértelmezett portra a URI sémájához. |
| **bool** [get_IsFile](./get_isfile/)() const | Meghatározza, hogy a jelenlegi objektum által reprezentált URI fájl-e. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | Meghatározza, hogy a jelenlegi objektum által reprezentált URI helyi gépre hivatkozik-e. |
| **bool** [get_IsUnc](./get_isunc/)() const | Meghatározza, hogy a jelenlegi objektum által reprezentált URI UNC útvonal-e. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | Visszaadja a fájlnév operációs rendszer általi reprezentációját, amelyet a jelenlegi objektum által reprezentált URI hivatkozik. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | Visszaadja azt az URI karakterláncot, amelyet a konstruktorhoz adtak a jelenlegi objektum létrehozásakor. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | Visszaadja az abszolút útvonal és lekérdezés komponenseket, amelyek ? kérdőjellel vannak elválasztva. |
| **int32_t** [get_Port](./get_port/)() const | Visszaadja a jelenlegi objektum által reprezentált URI portszámát. |
| [String](../string/) [get_Query](./get_query/)() const | Visszaadja a jelenlegi objektum által reprezentált URI-ban szereplő lekérdezési információkat. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | Visszaadja a jelenlegi objektum által reprezentált URI sémáját. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | Visszaad egy karakterlánc tömböt, amely a jelenlegi objektum által reprezentált URI útvonal szegmenseit tartalmazza. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | Megállapítja, hogy a jelenlegi objektum konstruktorába átadott URI karakterlánc teljesen escape-elt volt-e. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | Visszaadja a felhasználónevet, jelszót és egyéb felhasználói információkat, amelyek a jelenlegi objektum által reprezentált URI-hez kapcsolódnak. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | Visszaadja a jelenlegi objektum által reprezentált URI megadott komponenseit a megadott escape használatával. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Megkapja az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Megkapja az URI hash kódját. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | Visszaadja a jelenlegi objektum által reprezentált URI megadott részét. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../object/gettype/) hívás analógiája. |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | Visszaadja a megadott karakter hexadecimális ekvivalensét. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | Átalakítja a megadott hexadecimális karakter-reprezentációt egy karakterré. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Ellenőrzi, hogy az objektum egy példányt képvisel-e a cél típussal. A C# 'is' operátor analógiája. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | Megállapítja, hogy a jelenlegi [Uri](./) objektum által reprezentált URI egy alap-e a megadott [Uri](./) objektum által reprezentált URI-hoz képest. |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | Megállapítja, hogy a megadott karakter egy érvényes hexadecimális számjegy-e. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | Megállapítja, hogy a megadott karakterlánc megadott pozícióján lévő karakter hexadecimálisan kódolt-e. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Jelzi, hogy a [Uri](./) létrehozásához használt karakterlánc jól formált volt-e, és nem szükséges további escape. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | Megállapítja, hogy a megadott karakterlánc jól formált URI-e. |
| void [Lock](../object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) vakoló objektumot. |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Megállapítja a különbséget két [Uri](./) példány között. |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Megállapítja a különbséget a jelenlegi és a megadott [Uri](./) objektumok által reprezentált URI-k között. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../object/memberwiseclone/) metódus analógiája. Engedélyezi egyedi típusok klónozását. |
|  [Object](../object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../object/object/)([Object](../object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak inicializál egy új objektumot és engedélyezi az alosztályok másolásos konstrukcióját. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak inicializál egy új objektumot és engedélyezi az alosztályok másolásos konstrukcióját. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával összehasonlítja az értéktípusú objektumot a nullptr-al. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | A [Object::ReferenceEquals](../object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-dik sablonargumentumot gyenge (weak) mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerben való weak módra váltását. |
| int [SharedCount](../object/sharedcount/)() const | Megkapja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../string/) [ToString](./tostring/)() const override | Visszaadja a jelenlegi objektum által reprezentált URI karakterlánc reprezentációját. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Létrehozza a megadott URI-t reprezentáló [Uri](./) objektumot; egy argumentum határozza meg az URI típusát. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Létrehozza az [Uri](./) objektumot a megadott [Uri](./) objektum alapján, amely a base URI-t reprezentálja, és a relatív URI karakterlánc reprezentációját. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Létrehozza az [Uri](./) objektumot a megadott base és relatív URI-k alapján. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Megvalósítja a C# typeof([System.Object](../object/)) konstrukciót. |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | Kibontja a megadott escape-elt karakterláncot. |
| void [Unlock](../object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) vakoló objektumot. |
|  [Uri](./uri/)(const [String](../string/)\&) | Létrehozza a megadott URI-t reprezentáló [Uri](./) objektumot. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | Létrehozza a megadott URI-t reprezentáló [Uri](./) objektumot; egy argumentum határozza meg, hogy a URI escape-elt legyen-e. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | Létrehozza az [Uri](./) objektumot a megadott [Uri](./) objektum alapján, amely a base URI-t reprezentálja, és a relatív URI karakterláncot; egy argumentum határozza meg, hogy a URI escape-elt legyen-e. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | Létrehozza a megadott URI-t reprezentáló [Uri](./) objektumot; egy argumentum határozza meg az URI típusát. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | Létrehozza az [Uri](./) objektumot a megadott base és relatív URI-k alapján. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Létrehozza az [Uri](./) objektumot a megadott base és relatív URI-k alapján. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Megadja azokat a karaktereket, amelyek elválasztják a kommunikációs protokoll sémáját a [Uri](./) címrészétől. |
| static [UriSchemeFile](./urischemefile/) | Megadja, hogy a [Uri](./) egy fájlra mutató pointer. |
| static [UriSchemeFtp](./urischemeftp/) | Megadja, hogy a [Uri](./) a File Transfer Protocol segítségével érhető el. |
| static [UriSchemeGopher](./urischemegopher/) | Megadja, hogy a [Uri](./) a Gopher protokollon keresztül érhető el. |
| static [UriSchemeHttp](./urischemehttp/) | Megadja, hogy a [Uri](./) a Hypertext Transfer Protocol (HTTP) segítségével érhető el. |
| static [UriSchemeHttps](./urischemehttps/) | Megadja, hogy a [Uri](./) a Secure Hypertext Transfer Protocol (HTTPS) használatával érhető el. |
| static [UriSchemeMailto](./urischememailto/) | Megadja, hogy a [Uri](./) egy e-mail cím, és a Simple Mail Transport Protocol (SMTP) segítségével érhető el. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Megadja, hogy a [Uri](./) a [Windows](../../system.windows/) Communication Foundation által használt NetPipe sémán keresztül érhető el. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Megadja, hogy a [Uri](./) a [Windows](../../system.windows/) Communication Foundation által használt NetTcp sémán keresztül érhető el. |
| static [UriSchemeNews](./urischemenews/) | Megadja, hogy a [Uri](./) egy Internet hírcsoport, és a Network News Transport Protocol (NNTP) használatával érhető el. |
| static [UriSchemeNntp](./urischemenntp/) | Megadja, hogy a [Uri](./) egy Internet hírcsoport, és a Network News Transport Protocol (NNTP) használatával érhető el. |

## Megjegyzések

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
Ez a kódrészlet a következő kimenetet állítja elő:
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

## Lásd még

* Osztály [Object](../object/)
* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)