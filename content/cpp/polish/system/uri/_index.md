---
title: Uri
second_title: Odwołanie API Aspose.Slides dla C++
description: "Zunifikowany identyfikator zasobu. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject() . Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go do funkcji jako argument."
type: docs
weight: 1392
url: /pl/system/uri/
---
## Klasa Uri

Ujednolicony identyfikator zasobu. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub błędy asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument.

```cpp
class Uri : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | Określa typ określonej nazwy hosta. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | Określa, czy określony schemat jest prawidłowy. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | Porównuje określone [Uri](./) obiekty przy użyciu określonych reguł porównywania. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | Określa, czy URI reprezentowane przez bieżący i określony obiekt są równe. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | Konwertuje ciąg znaków na jego reprezentację z escapowaniem. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | Konwertuje ciąg znaków URI na jego reprezentację z escapowaniem. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | Zwraca wartość dziesiętną cyfry szesnastkowej. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | Zwraca bezwzględną ścieżkę URI. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | Zwraca bezwzględny URI. |
| [String](../string/) [get_Authority](./get_authority/)() const | Zwraca nazwę hosta i numer portu serwera. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | Zwraca nieescapowaną nazwę hosta. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | Zwraca escapowany fragment URI. |
| [String](../string/) [get_Host](./get_host/)() const | Zwraca nazwę hosta. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | Zwraca typ nazwy hosta. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | Zwraca międzynarodową nazwę domeny hosta. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Określa, czy URI reprezentowany przez bieżący obiekt jest bezwzględny. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | Określa, czy URI reprezentowany przez bieżący obiekt ma domyślny port dla schematu URI. |
| **bool** [get_IsFile](./get_isfile/)() const | Określa, czy URI reprezentowany przez bieżący obiekt jest plikiem. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | Określa, czy URI reprezentowany przez bieżący obiekt odwołuje się do lokalnego hosta. |
| **bool** [get_IsUnc](./get_isunc/)() const | Określa, czy URI reprezentowany przez bieżący obiekt jest ścieżką UNC. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | Zwraca reprezentację systemu operacyjnego nazwy pliku odwoływanego przez URI reprezentowany przez bieżący obiekt. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | Zwraca ciąg URI przekazany do konstruktora przy tworzeniu bieżącego obiektu. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | Zwraca bezwzględną ścieżkę i komponenty zapytania URI reprezentowanego przez bieżący obiekt, oddzielone znakiem zapytania (?). |
| **int32_t** [get_Port](./get_port/)() const | Zwraca numer portu URI reprezentowanego przez bieżący obiekt. |
| [String](../string/) [get_Query](./get_query/)() const | Zwraca informacje o zapytaniu zawarte w URI reprezentowanym przez bieżący obiekt. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | Zwraca schemat URI reprezentowanego przez bieżący obiekt. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | Zwraca tablicę ciągów zawierających segmenty ścieżki URI reprezentowanego przez bieżący obiekt. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | Określa, czy ciąg URI przekazany do konstruktora bieżącego obiektu został w pełni escapowany. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | Zwraca nazwę użytkownika, hasło i inne informacje użytkownika powiązane z URI reprezentowanym przez bieżący obiekt. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | Zwraca określone komponenty URI reprezentowanego przez bieżący obiekt przy użyciu określonego escapowania. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Zwraca strukturę danych licznika referencji powiązaną z obiektem. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Zwraca kod hash dla URI. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | Zwraca określoną część URI reprezentowanego przez bieżący obiekt. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../object/gettype/). |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | Zwraca szesnastkowy odpowiednik określonego znaku. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | Konwertuje określoną szesnastkową reprezentację znaku na znak. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | Określa, czy URI reprezentowane przez bieżący obiekt [Uri](./) jest podstawą URI reprezentowanego przez określony obiekt [Uri](./). |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | Określa, czy określony znak jest prawidłową cyfrą szesnastkową. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | Określa, czy znak w określonym ciągu na określonej pozycji jest zakodowany szesnastkowo. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Wskazuje, czy ciąg użyty do konstrukcji tego [Uri](./) był poprawny i nie wymaga dalszego escapowania. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | Określa, czy określony ciąg jest poprawnym URI. |
| void [Lock](../object/lock/)() | Implementuje blokadę wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../lockcontext/). |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Określa różnicę między dwiema instancjami [Uri](./). |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Określa różnicę między URI reprezentowanymi przez bieżący i określony obiekt [Uri](./). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku ciągu i nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku ciągów. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o określoną wartość. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala zmienić wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../object/sharedcount/)() const | Zwraca bieżącą wartość współdzielonego licznika referencji. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Inkrementuje współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Dekrementuje i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Zwraca ciąg znaków reprezentujący URI reprezentowane przez bieżący obiekt. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Tworzy obiekt [Uri](./) reprezentujący określony URI; argument określa rodzaj URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Tworzy obiekt [Uri](./) z określonego obiektu [Uri](./) reprezentującego bazowy URI oraz ciągu reprezentującego względny URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Tworzy obiekt [Uri](./) z określonych bazowych i względnych URI. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../object/)). |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | Od-escapowuje określony escapowany ciąg. |
| void [Unlock](../object/unlock/)() | Implementuje odblokowanie wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../lockcontext/). |
|  [Uri](./uri/)(const [String](../string/)\&) | Tworzy obiekt [Uri](./) reprezentujący określony URI. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | Tworzy obiekt [Uri](./) reprezentujący określony URI; argument określa, czy URI powinien być escapowany. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | Tworzy obiekt [Uri](./) z określonego obiektu [Uri](./) reprezentującego bazowy URI oraz ciągu reprezentującego względny URI; argument określa, czy URI powinien być escapowany. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | Tworzy obiekt [Uri](./) reprezentujący określony URI; argument określa rodzaj URI. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | Tworzy obiekt [Uri](./) z określonych bazowych i względnych URI. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Tworzy obiekt [Uri](./) z określonych bazowych i względnych URI. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Inkrementuje licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Dekrementuje licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Pola

| Pole | Opis |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Określa znaki oddzielające schemat protokołu komunikacji od części adresowej [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | Określa, że [Uri](./) jest wskaźnikiem do pliku. |
| static [UriSchemeFtp](./urischemeftp/) | Określa, że [Uri](./) jest dostępny przez protokół FTP. |
| static [UriSchemeGopher](./urischemegopher/) | Określa, że [Uri](./) jest dostępny przez protokół Gopher. |
| static [UriSchemeHttp](./urischemehttp/) | Określa, że [Uri](./) jest dostępny przez protokół HTTP. |
| static [UriSchemeHttps](./urischemehttps/) | Określa, że [Uri](./) jest dostępny przez protokół HTTPS. |
| static [UriSchemeMailto](./urischememailto/) | Określa, że [Uri](./) jest adresem e-mail i jest dostępny przez protokół SMTP. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Określa, że [Uri](./) jest dostępny przez schemat NetPipe używany przez [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Określa, że [Uri](./) jest dostępny przez schemat NetTcp używany przez [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNews](./urischemenews/) | Określa, że [Uri](./) jest grupą wiadomości internetowych i jest dostępny przez protokół NNTP. |
| static [UriSchemeNntp](./urischemenntp/) | Określa, że [Uri](./) jest grupą wiadomości internetowych i jest dostępny przez protokół NNTP. |

## Uwagi

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
Ten przykład kodu generuje następujące wyjście:
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

## Zobacz także

* Klasa [Object](../object/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)