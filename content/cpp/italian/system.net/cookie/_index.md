---
title: Cookie
second_title: Riferimento API Aspose.Slides per C++
description: "Rappresenta un cookie HTTP. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o violazioni di asserzioni. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarla alle funzioni come argomento."
type: docs
weight: 1
url: /it/system.net/cookie/
---
## Classe Cookie

Rappresenta un cookie HTTP. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o violazioni di asserzioni. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarla alle funzioni come argomento.

```cpp
class Cookie : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | Crea una copia dell'istanza corrente. |
| [Cookie](./cookie/)() | Costruisce una nuova istanza. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | Costruisce una nuova istanza. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Costruisce una nuova istanza. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Costruisce una nuova istanza. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | Restituisce il valore dell'attributo 'Comment'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | Restituisce il valore dell'attributo 'CommentURL'. |
| **bool** [get_Discard](./get_discard/)() const | Restituisce il valore dell'attributo 'Discard'. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | Restituisce il valore dell'attributo 'Domain'. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | Restituisce un valore che indica se il dominio è implicito. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | Restituisce la chiave del dominio. |
| **bool** [get_Expired](./get_expired/)() | Restituisce un valore che indica se il cookie è scaduto. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | Restituisce il valore dell'attributo 'Expires'. |
| **bool** [get_HttpOnly](./get_httponly/)() const | Restituisce il valore dell'attributo 'HttpOnly'. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Restituisce il nome del cookie. |
| [String](../../system/string/) [get_Path](./get_path/)() const | Restituisce il valore dell'attributo 'Path'. |
| **bool** [get_Plain](./get_plain/)() const | Restituisce un valore che indica se la specifica del cookie è 'Plain'. |
| [String](../../system/string/) [get_Port](./get_port/)() const | Restituisce il valore dell'attributo 'Port'. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | Restituisce la collezione dei valori dell'attributo 'Port'. |
| **bool** [get_Secure](./get_secure/)() const | Restituisce il valore dell'attributo 'Secure'. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | Restituisce l'ora in cui il cookie è stato creato. |
| [String](../../system/string/) [get_Value](./get_value/)() const | Restituisce il valore del cookie. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | Restituisce la specifica del cookie. |
| **int32_t** [get_Version](./get_version/)() const | Restituisce il valore dell'attributo '[Version](../../system/version/)'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Restituisce la struttura dati del contatore di riferimento associata all'oggetto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Restituisce il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | Questo metodo è chiamato da altri metodi per impostare il nome di un metodo. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | Imposta il valore dell'attributo 'Comment'. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Imposta il valore dell'attributo 'CommentURL'. |
| void [set_Discard](./set_discard/)(**bool**) | Imposta il valore dell'attributo 'Discard'. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | Imposta il valore dell'attributo 'Domain'. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | Imposta un valore che indica se il dominio è implicito. |
| void [set_Expired](./set_expired/)(**bool**) | Imposta un valore che indica se il cookie è scaduto. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | Imposta il valore dell'attributo 'Expires'. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | Imposta il valore dell'attributo 'HttpOnly'. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Imposta il nome del cookie. |
| void [set_Path](./set_path/)([String](../../system/string/)) | Imposta il valore dell'attributo 'Path'. |
| void [set_Port](./set_port/)([String](../../system/string/)) | Imposta il valore dell'attributo 'Port'. |
| void [set_Secure](./set_secure/)(**bool**) | Imposta il valore dell'attributo 'Secure'. |
| void [set_Value](./set_value/)([String](../../system/string/)) | Imposta il valore del cookie. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | Imposta la specifica del cookie. |
| void [set_Version](./set_version/)(**int32_t**) | Imposta il valore dell'attributo '[Version](../../system/version/)'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n'th argomento template a un puntatore debole (invece che condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Restituisce il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | Serializza l'istanza corrente nella rappresentazione stringa. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruttura C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | Verifica e imposta i valori predefiniti degli attributi. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | Il nome dell'attributo 'Comment'. |
| static [CommentUrlAttributeName](./commenturlattributename/) | Il nome dell'attributo 'CommentURL'. |
| static [DiscardAttributeName](./discardattributename/) | Il nome dell'attributo 'Discard'. |
| static [DomainAttributeName](./domainattributename/) | Il nome dell'attributo 'Domain'. |
| static [EqualsLiteral](./equalsliteral/) | Il separatore usato per separare il nome e il valore di un attributo. |
| static [ExpiresAttributeName](./expiresattributename/) | Il nome dell'attributo 'Expires'. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | Il nome dell'attributo 'HttpOnly'. |
| static [MaxAgeAttributeName](./maxageattributename/) | Il nome dell'attributo 'Max-Age'. |
| static [MaxSupportedVersion](./maxsupportedversion/) | La versione massima supportata. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | La rappresentazione stringa della versione massima supportata. |
| static [PathAttributeName](./pathattributename/) | Il nome dell'attributo 'Path'. |
| static [PortAttributeName](./portattributename/) | Il nome dell'attributo 'Port'. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | L'array che contiene i delimitatori per i valori dell'attributo 'Port'. |
| static [QuotesLiteral](./quotesliteral/) | Il simbolo usato per avvolgere le parti dell'attributo. |
| static [ReservedToName](./reservedtoname/) | Un valore riservato per il nome del cookie. |
| static [ReservedToValue](./reservedtovalue/) | Un valore riservato per il valore del cookie. |
| static [SecureAttributeName](./secureattributename/) | Il nome dell'attributo 'Secure'. |
| static [SeparatorLiteral](./separatorliteral/) | Il separatore degli attributi. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | Il prefisso dei nomi degli attributi speciali. |
| static [VersionAttributeName](./versionattributename/) | Il nome dell'attributo '[Version](../../system/version/)'. |

## Vedi anche

* Classe [Object](../../system/object/)
* Spazio dei nomi [System::Net](../)
* Libreria [Aspose.Slides](../../)