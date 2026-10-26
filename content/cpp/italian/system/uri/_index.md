---
title: Uri
second_title: Riferimento API Aspose.Slides per C++
description: "Identificatore di risorsa unificato. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o violazioni di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 1392
url: /it/system/uri/
---
## Classe Uri

Identificatore di risorsa unificato. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché causerebbe errori di runtime e/o violazioni di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class Uri : public System::Object
```

## Metodi

| Method | Description |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | Determina il tipo del nome host specificato. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | Determina se lo schema specificato è valido. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | Confronta gli oggetti [Uri](./) specificati usando le regole di confronto specificate. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | Determina se gli URI rappresentati dall'oggetto corrente e da quello specificato sono uguali. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | Converte una stringa nella sua rappresentazione escaped. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | Converte una stringa URI nella sua rappresentazione escaped. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | Ottiene il valore decimale di una cifra esadecimale. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | Restituisce il percorso assoluto dell'URI. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | Restituisce l'URI assoluto. |
| [String](../string/) [get_Authority](./get_authority/)() const | Restituisce il nome host e il numero di porta per un server. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | Restituisce un nome host non escaped. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | Restituisce il frammento URI escaped. |
| [String](../string/) [get_Host](./get_host/)() const | Restituisce il nome host. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | Restituisce il tipo del nome host. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | Restituisce un Nome di Dominio Internazionale dell'host. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Determina se l'URI rappresentato dall'oggetto corrente è assoluto. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | Determina se l'URI rappresentato dall'oggetto corrente ha la porta predefinita per lo schema dell'URI. |
| **bool** [get_IsFile](./get_isfile/)() const | Determina se l'URI rappresentato dall'oggetto corrente è un file. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | Determina se l'URI rappresentato dall'oggetto corrente fa riferimento a un host locale. |
| **bool** [get_IsUnc](./get_isunc/)() const | Determina se l'URI rappresentato dall'oggetto corrente è un percorso UNC. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | Restituisce la rappresentazione del sistema operativo del nome file a cui fa riferimento l'URI rappresentato dall'oggetto corrente. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | Restituisce la stringa URI che è stata passata al costruttore quando l'oggetto corrente è stato costruito. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | Restituisce il percorso assoluto e le componenti di query dell'URI rappresentato dall'oggetto corrente, separate da un punto interrogativo (?). |
| **int32_t** [get_Port](./get_port/)() const | Restituisce il numero di porta dell'URI rappresentato dall'oggetto corrente. |
| [String](../string/) [get_Query](./get_query/)() const | Restituisce le informazioni di query incluse nell'URI rappresentato dall'oggetto corrente. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | Restituisce lo schema dell'URI rappresentato dall'oggetto corrente. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | Restituisce un array di stringhe contenente i segmenti di percorso dell'URI rappresentato dall'oggetto corrente. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | Determina se la stringa URI passata al costruttore dell'oggetto corrente era completamente escaped. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | Restituisce un nome utente, password e altre informazioni utente associate all'URI rappresentato dall'oggetto corrente. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | Restituisce i componenti specificati dell'URI rappresentato dall'oggetto corrente usando l'escaping specificato. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Ottiene il codice hash per l'URI. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | Restituisce la porzione specificata dell'URI rappresentato dall'oggetto corrente. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../object/gettype/). |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | Restituisce l'equivalente esadecimale del carattere specificato. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | Converte la rappresentazione esadecimale specificata di un carattere in un carattere. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | Determina se l'URI rappresentato dall'oggetto [Uri](./) corrente è una base dell'URI rappresentato dall'oggetto [Uri](./) specificato. |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | Determina se il carattere specificato rappresenta una cifra esadecimale valida. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | Determina se un carattere nella stringa specificata nella posizione specificata è codificato esadecimale. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Indica se la stringa usata per costruire questo [Uri](./) era ben formata e non necessita di ulteriore escaping. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | Determina se la stringa specificata è un URI ben formato. |
| void [Lock](../object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente oppure usare l'oggetto sentinella [LockContext](../lockcontext/). |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Determina la differenza tra due istanze [Uri](./). |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Determina la differenza tra gli URI rappresentati dall'oggetto corrente e da quello specificato [Uri](./). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../object/memberwiseclone/). Abilita il cloning di tipi personalizzati. |
|  [Object](../object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../object/object/)([Object](../object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e abilita la costruzione di copie nelle sottoclassi. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e abilita la costruzione di copie nelle sottoclassi. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso stringa e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso delle stringhe. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi di un valore specificato. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore weak (piuttosto che shared). Consente di passare i puntatori nei contenitori alla modalità weak. |
| int [SharedCount](../object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Restituisce la rappresentazione stringa dell'URI rappresentato dall'oggetto corrente. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Crea un oggetto [Uri](./) che rappresenta l'URI specificato; un argomento specifica il tipo di URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Costruisce un oggetto [Uri](./) a partire dall'oggetto [Uri](./) specificato che rappresenta l'URI base e dalla rappresentazione stringa dell'URI relativo. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Costruisce un oggetto [Uri](./) a partire dagli URI base e relativo specificati. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa il costrutto C# typeof([System.Object](../object/)). |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | Rimuove l'escaping dalla stringa escaped specificata. |
| void [Unlock](../object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente oppure usare l'oggetto sentinella [LockContext](../lockcontext/). |
|  [Uri](./uri/)(const [String](../string/)\&) | Crea un oggetto [Uri](./) che rappresenta l'URI specificato. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | Crea un oggetto [Uri](./) che rappresenta l'URI specificato; un argomento indica se l'URI deve essere escaped. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | Crea un oggetto [Uri](./) a partire dall'oggetto [Uri](./) specificato che rappresenta l'URI base e dalla rappresentazione stringa dell'URI relativo; un argomento indica se l'URI deve essere escaped. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | Crea un oggetto [Uri](./) che rappresenta l'URI specificato; un argomento specifica il tipo di URI. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | Crea un oggetto [Uri](./) a partire dagli URI base e relativo specificati. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Crea un oggetto [Uri](./) a partire dagli URI base e relativo specificati. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa il contatore di riferimenti weak. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa il contatore di riferimenti weak. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| virtual  [~Object](../object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Campi

| Field | Description |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Specifica i caratteri che separano lo schema del protocollo di comunicazione dalla parte dell'indirizzo del [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | Specifica che [Uri](./) è un puntatore a un file. |
| static [UriSchemeFtp](./urischemeftp/) | Specifica che [Uri](./) è accessibile tramite il File Transfer Protocol. |
| static [UriSchemeGopher](./urischemegopher/) | Specifica che [Uri](./) è accessibile tramite il protocollo Gopher. |
| static [UriSchemeHttp](./urischemehttp/) | Specifica che [Uri](./) è accessibile tramite l'Hypertext Transfer Protocol. |
| static [UriSchemeHttps](./urischemehttps/) | Specifica che [Uri](./) è accessibile tramite il Secure Hypertext Transfer Protocol. |
| static [UriSchemeMailto](./urischememailto/) | Specifica che [Uri](./) è un indirizzo email ed è accessibile tramite il Simple Mail Transport Protocol. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Specifica che [Uri](./) è accessibile tramite lo schema NetPipe usato da [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Specifica che [Uri](./) è accessibile tramite lo schema NetTcp usato da [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNews](./urischemenews/) | Specifica che [Uri](./) è un newsgroup Internet ed è accessibile tramite il Network News Transport Protocol. |
| static [UriSchemeNntp](./urischemenntp/) | Specifica che [Uri](./) è un newsgroup Internet ed è accessibile tramite il Network News Transport Protocol. |

## Osservazioni

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
Questo esempio di codice produce il seguente output:
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

## Vedi anche

* Classe [Object](../object/)
* Namespace [System](../)
* Libreria [Aspose.Slides](../../)