---
title: Uri
second_title: Aspose.Slides für C++ API-Referenz
description: "Einheitlicher Ressourcenbezeichner. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() erzeugt werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führen kann. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen weiterzugeben."
type: docs
weight: 1392
url: /de/system/uri/
---
## Uri-Klasse

Einheitlicher Ressourcenbezeichner. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../makeobject/) erzeugt werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führen kann. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Uri : public System::Object
```

## Methoden

| Method | Description |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | Bestimmt den Typ des angegebenen Hostnamens. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | Bestimmt, ob das angegebene Schema gültig ist. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | Vergleicht die angegebenen [Uri](./)-Objekte mit den angegebenen Vergleichsregeln. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | Bestimmt, ob die von dem aktuellen und dem angegebenen Objekt dargestellten URIs gleich sind. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | Konvertiert einen String in seine escaped Darstellung. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | Konvertiert einen URI-String in seine escaped Darstellung. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | Ermittelt den Dezimalwert einer Hexadezimalziffer. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | Gibt den absoluten Pfad der URI zurück. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | Gibt die absolute URI zurück. |
| [String](../string/) [get_Authority](./get_authority/)() const | Gibt den Hostnamen und die Portnummer eines Servers zurück. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | Gibt einen nicht escaped Hostnamen zurück. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | Gibt das escaped URI-Fragment zurück. |
| [String](../string/) [get_Host](./get_host/)() const | Gibt den Hostnamen zurück. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | Gibt den Hostnamen-Typ zurück. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | Gibt einen Internationalen Domainnamen des Hosts zurück. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Bestimmt, ob die von dem aktuellen Objekt dargestellte URI absolut ist. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | Bestimmt, ob die von dem aktuellen Objekt dargestellte URI den Standardport für das Schema der URI hat. |
| **bool** [get_IsFile](./get_isfile/)() const | Bestimmt, ob die von dem aktuellen Objekt dargestellte URI eine Datei ist. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | Bestimmt, ob die von dem aktuellen Objekt dargestellte URI einen lokalen Host referenziert. |
| **bool** [get_IsUnc](./get_isunc/)() const | Bestimmt, ob die von dem aktuellen Objekt dargestellte URI ein UNC-Pfad ist. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | Gibt die Betriebssystemdarstellung des Dateinamens zurück, auf die von der URI des aktuellen Objekts verwiesen wird. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | Gibt den URI-String zurück, der dem Konstruktor beim Erzeugen des aktuellen Objekts übergeben wurde. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | Gibt den absoluten Pfad und die Abfragekomponenten der von dem aktuellen Objekt dargestellten URI zurück, getrennt durch ein Fragezeichen (?). |
| **int32_t** [get_Port](./get_port/)() const | Gibt die Portnummer der von dem aktuellen Objekt dargestellten URI zurück. |
| [String](../string/) [get_Query](./get_query/)() const | Gibt die in der von dem aktuellen Objekt dargestellten URI enthaltenen Abfrageinformationen zurück. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | Gibt das Schema der von dem aktuellen Objekt dargestellten URI zurück. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | Gibt ein Array von Strings zurück, das die Pfadsegmente der von dem aktuellen Objekt dargestellten URI enthält. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | Bestimmt, ob der dem Konstruktor des aktuellen Objekts übergebene URI-String vollständig escaped war. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | Gibt einen Benutzernamen, ein Passwort und andere Benutzerinformationen zurück, die mit der von dem aktuellen Objekt dargestellten URI verknüpft sind. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | Gibt die angegebenen Komponenten der von dem aktuellen Objekt dargestellten URI zurück, wobei die angegebene Escapierung verwendet wird. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Ermittelt den Hashcode für die URI. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | Gibt den angegebenen Teil der von dem aktuellen Objekt dargestellten URI zurück. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../object/gettype/)-Aufruf. |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | Gibt das hexadezimale Äquivalent des angegebenen Zeichens zurück. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | Konvertiert die angegebene hexadezimale Darstellung eines Zeichens in ein Zeichen. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C# 'is'-Operator. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | Bestimmt, ob die von dem aktuellen [Uri](./)-Objekt dargestellte URI die Basis der von dem angegebenen [Uri](./)-Objekt dargestellten URI ist. |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | Bestimmt, ob das angegebene Zeichen eine gültige hexadezimale Ziffer darstellt. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | Bestimmt, ob ein Zeichen im angegebenen String an der angegebenen Position hexadezimal codiert ist. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Gibt an, ob der zum Erzeugen dieses [Uri](./) verwendete String wohlgeformt ist und nicht weiter escaped werden muss. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | Bestimmt, ob der angegebene String eine wohlgeformte URI ist. |
| void [Lock](../object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../lockcontext/)-Wächterobjekt verwenden. |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Bestimmt die Differenz zwischen zwei [Uri](./)-Instanzen. |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Bestimmt die Differenz zwischen den von dem aktuellen und dem angegebenen [Uri](./)-Objekt dargestellten URIs. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| [String](../string/) [ToString](./tostring/)() const override | Gibt die String-Darstellung der von dem aktuellen Objekt dargestellten URI zurück. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Konstruiert ein [Uri](./)-Objekt, das die angegebene URI darstellt; ein Argument gibt die Art der URI an. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Konstruiert ein [Uri](./)-Objekt aus dem angegebenen [Uri](./)-Objekt, das die Basis-URI darstellt, und der String-Darstellung der relativen URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Konstruiert ein [Uri](./)-Objekt aus den angegebenen Basis- und relativen URIs. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementiert das C# typeof([System.Object](../object/))-Konstrukt. |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | Entescaped den angegebenen escaped String. |
| void [Unlock](../object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../lockcontext/)-Wächterobjekt verwenden. |
|  [Uri](./uri/)(const [String](../string/)\&) | Konstruiert ein [Uri](./)-Objekt, das die angegebene URI darstellt. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | Konstruiert ein [Uri](./)-Objekt, das die angegebene URI darstellt; ein Argument gibt an, ob die URI escaped werden soll. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | Konstruiert ein [Uri](./)-Objekt aus dem angegebenen [Uri](./)-Objekt, das die Basis-URI darstellt, und der String-Darstellung der relativen URI; ein Argument gibt an, ob die URI escaped werden soll. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | Konstruiert ein [Uri](./)-Objekt, das die angegebene URI darstellt; ein Argument gibt die Art der URI an. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | Konstruiert ein [Uri](./)-Objekt aus den angegebenen Basis- und relativen URIs. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Konstruiert ein [Uri](./)-Objekt aus den angegebenen Basis- und relativen URIs. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Felder

| Field | Description |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Gibt die Zeichen an, die das Kommunikationsprotokoll-Schema vom Adressteil der [Uri](./) trennen. |
| static [UriSchemeFile](./urischemefile/) | Gibt an, dass [Uri](./) ein Zeiger auf eine Datei ist. |
| static [UriSchemeFtp](./urischemeftp/) | Gibt an, dass [Uri](./) über das File Transfer Protocol zugegriffen wird. |
| static [UriSchemeGopher](./urischemegopher/) | Gibt an, dass [Uri](./) über das Gopher-Protokoll zugegriffen wird. |
| static [UriSchemeHttp](./urischemehttp/) | Gibt an, dass [Uri](./) über das Hypertext Transfer Protocol zugegriffen wird. |
| static [UriSchemeHttps](./urischemehttps/) | Gibt an, dass [Uri](./) über das Secure Hypertext Transfer Protocol zugegriffen wird. |
| static [UriSchemeMailto](./urischememailto/) | Gibt an, dass [Uri](./) eine E-Mail-Adresse ist und über das Simple Mail Transport Protocol zugegriffen wird. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Gibt an, dass [Uri](./) über das NetPipe-Schema der [Windows](../../system.windows/) Communication Foundation zugegriffen wird. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Gibt an, dass [Uri](./) über das NetTcp-Schema der [Windows](../../system.windows/) Communication Foundation zugegriffen wird. |
| static [UriSchemeNews](./urischemenews/) | Gibt an, dass [Uri](./) eine Internet-Newsgroup ist und über das Network News Transport Protocol zugegriffen wird. |
| static [UriSchemeNntp](./urischemenntp/) | Gibt an, dass [Uri](./) eine Internet-Newsgroup ist und über das Network News Transport Protocol zugegriffen wird. |

## Anmerkungen

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
Dieses Codebeispiel erzeugt die folgende Ausgabe:
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

## Siehe auch

* Klasse [Object](../object/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)