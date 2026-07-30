---
title: TextWriter
second_title: Riferimento API di Aspose.Slides per C++
description: "Una classe base per le classi che rappresentano scrittori che scrivono sequenze di caratteri verso destinazioni diverse. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o errori di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e usare questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 443
url: /it/system.io/textwriter/
---
## TextWriter classe


Una classe base per le classi che rappresentano scrittori che scrivono sequenze di caratteri verso destinazioni diverse. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un’istanza di questo tipo sullo stack o usando l’operatore new, poiché ciò provocherà errori di runtime e/o errori di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usare questo puntatore per passarlo alle funzioni come argomento.

```cpp
class TextWriter : public System::IDisposable
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual void [Close](./close/)() | Chiude lo stream e rilascia le risorse acquisite. |
| void [Dispose](./dispose/)() override | Rilascia tutte le risorse utilizzate dall'oggetto corrente e chiude lo stream sottostante. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual void [Flush](./flush/)() | Svuota il contenuto del buffer verso lo stream sottostante. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Restituisce la codifica attualmente utilizzata. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | Restituisce l'oggetto [IFormatProvider](../../system/iformatprovider/) attualmente utilizzato. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | Restituisce l'oggetto [IFormatProvider](../../system/iformatprovider/) attualmente utilizzato. |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | Restituisce una stringa terminatore di riga. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | Restituisce una stringa terminatore di riga. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la copia dei sottotipi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la copia dei sottotipi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | Imposta una stringa terminatore di riga. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta l'argomento template n-esimo a un puntatore debole (invece che condiviso). Consente di passare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Scrive la rappresentazione stringa dell'oggetto specificato sullo stream. |
| virtual void [Write](./write/)(**bool**) | Scrive la rappresentazione stringa del valore booleano specificato sullo stream. |
| virtual void [Write](./write/)(char_t) | Scrive il carattere specificato sullo stream. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | Scrive la rappresentazione stringa dell'oggetto [Decimal](../../system/decimal/) specificato sullo stream. |
| virtual void [Write](./write/)(**double**) | Scrive la rappresentazione stringa del valore a doppia precisione specificato sullo stream. |
| virtual void [Write](./write/)(int) | Scrive la rappresentazione stringa del valore intero a 32 bit specificato sullo stream. |
| virtual void [Write](./write/)(**int64_t**) | Scrive la rappresentazione stringa del valore intero a 64 bit specificato sullo stream. |
| virtual void [Write](./write/)(**float**) | Scrive la rappresentazione stringa del valore a precisione singola specificato sullo stream. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Scrive la stringa specificata sullo stream. |
| virtual void [Write](./write/)(**uint32_t**) | Scrive la rappresentazione stringa del valore intero non firmato a 32 bit specificato sullo stream. |
| virtual void [Write](./write/)(**uint64_t**) | Scrive la rappresentazione stringa del valore intero non firmato a 64 bit specificato sullo stream. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Scrive tutti i caratteri dall'array specificato sullo stream. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Scrive il sottointervallo specificato di caratteri UTF-16 dall'array di caratteri specificato sullo stream. |
| virtual void [Write](./write/)(const char_t *) | Scrive la c-string specificata sullo stream. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | Scrive la rappresentazione stringa dell'oggetto [TypeInfo](../../system/typeinfo/) specificato sullo stream. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | Scrive i valori specificati formattati secondo il formato specificato sullo stream. |
| virtual void [WriteLine](./writeline/)() | Scrive i caratteri terminatori di riga sullo stream. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Scrive la rappresentazione stringa dell'oggetto specificato seguita dai caratteri terminatori di riga sullo stream. |
| virtual void [WriteLine](./writeline/)(**bool**) | Scrive la rappresentazione stringa del valore booleano specificato seguita dai caratteri terminatori di riga sullo stream. |
| virtual void [WriteLine](./writeline/)(char_t) | Scrive il carattere specificato seguito dai caratteri terminatori di riga sullo stream. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | Scrive la rappresentazione stringa dell'oggetto [Decimal](../../system/decimal/) specificato seguita dai caratteri terminatori di riga sullo stream. |
| virtual void [WriteLine](./writeline/)(**double**) | Scrive la rappresentazione stringa del valore a doppia precisione specificato seguita dai caratteri terminatori di riga sullo stream. |
| virtual void [WriteLine](./writeline/)(int) | Scrive la rappresentazione stringa del valore intero a 32 bit specificato seguita dai caratteri terminatori di riga sullo stream. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | Scrive la rappresentazione stringa del valore intero a 64 bit specificato seguita dai caratteri terminatori di riga sullo stream. |
| virtual void [WriteLine](./writeline/)(**float**) | Scrive la rappresentazione stringa del valore a precisione singola specificato seguita dai caratteri terminatori di riga sullo stream. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Scrive la stringa specificata seguita dai caratteri terminatori di riga sullo stream. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | Scrive la rappresentazione stringa del valore intero non firmato a 32 bit specificato seguita dai caratteri terminatori di riga sullo stream. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | Scrive la rappresentazione stringa del valore intero non firmato a 64 bit specificato seguita dai caratteri terminatori di riga sullo stream. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Scrive tutti i caratteri dall'array specificato seguiti dai caratteri terminatori di riga sullo stream. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Scrive il sottointervallo specificato di caratteri UTF-16 dall'array di caratteri specificato seguito dai caratteri terminatori di riga sullo stream. |
| virtual void [WriteLine](./writeline/)(const char_t *) | Scrive la c-string specificata seguita dai caratteri terminatori di riga sullo stream. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Scrive la rappresentazione stringa dell'oggetto [TypeInfo](../../system/typeinfo/) specificato seguita dai caratteri terminatori di riga sullo stream. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Scrive i valori specificati formattati secondo il formato specificato seguiti dai caratteri di riga sullo stream. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
| virtual  [~TextWriter](./~textwriter/)() | Distruttore. |

## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [Ptr](./ptr/) | Un alias per un puntatore condiviso a questa classe. |

## Vedi anche

* Classe [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)