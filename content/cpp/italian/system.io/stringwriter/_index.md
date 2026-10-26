---
title: StringWriter
second_title: Riferimento API di Aspose.Slides per C++
description: "Implementa un TextWriter che scrive informazioni in una stringa. Gli oggetti di questa classe dovrebbero essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o errori di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 417
url: /it/system.io/stringwriter/
---
## StringWriter classe

Implementa un [TextWriter](../textwriter/) che scrive le informazioni in una stringa. Gli oggetti di questa classe dovrebbero essere allocati solo utilizzando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o errori di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Metodi

| Method | Description |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | Chiude lo stream e rilascia le risorse acquisite. |
| void [Dispose](../textwriter/dispose/)() override | Rilascia tutte le risorse utilizzate dall'oggetto corrente e chiude lo stream sottostante. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali sebbene secondo IEC 60559:1989 NaN non sia uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali sebbene secondo IEC 60559:1989 NaN non sia uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual void [Flush](../textwriter/flush/)() | Svuota il contenuto del buffer nello stream sottostante. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Restituisce la codifica attualmente utilizzata. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Restituisce l'oggetto [IFormatProvider](../../system/iformatprovider/) attualmente utilizzato. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Restituisce l'oggetto [IFormatProvider](../../system/iformatprovider/) attualmente utilizzato. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Restituisce una stringa terminatore di linea. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Restituisce una stringa terminatore di linea. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | Restituisce lo StringBuilder attualmente utilizzato. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il conteggio di riferimento condiviso del valore specificato. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Imposta una stringa terminatore di linea. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Costruisce una nuova istanza di [StringWriter](./) usando lo StringBuilder specificato e [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Costruisce una nuova istanza di [StringWriter](./) usando lo StringBuilder specificato e [IFormatProvider](../../system/iformatprovider/) dalla cultura corrente. |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Costruisce una nuova istanza di [StringWriter](./) usando il [IFormatProvider](../../system/iformatprovider/) specificato. |
|  [StringWriter](./stringwriter/)() | Costruisce una nuova istanza di [StringWriter](./) usando [IFormatProvider](../../system/iformatprovider/) dalla cultura corrente. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Restituisce la stringa sottostante. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [Write](./write/)(char_t) override | Scrive il carattere specificato nello stream. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Scrive il sottointervallo specificato di caratteri dall'array di caratteri specificato nello stream. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Scrive la stringa specificata nello stream. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Scrive la rappresentazione stringa dell'oggetto specificato nello stream. |
| virtual void [Write](../textwriter/write/)(**bool**) | Scrive la rappresentazione stringa del valore booleano specificato nello stream. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Scrive la rappresentazione stringa dell'oggetto [Decimal](../../system/decimal/) specificato nello stream. |
| virtual void [Write](../textwriter/write/)(**double**) | Scrive la rappresentazione stringa del valore a doppia precisione specificato nello stream. |
| virtual void [Write](../textwriter/write/)(int) | Scrive la rappresentazione stringa del valore intero a 32 bit specificato nello stream. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Scrive la rappresentazione stringa del valore intero a 64 bit specificato nello stream. |
| virtual void [Write](../textwriter/write/)(**float**) | Scrive la rappresentazione stringa del valore a precisione singola specificato nello stream. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Scrive la rappresentazione stringa del valore intero senza segno a 32 bit specificato nello stream. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Scrive la rappresentazione stringa del valore intero senza segno a 64 bit specificato nello stream. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Scrive tutti i caratteri dall'array specificato nello stream. |
| virtual void [Write](../textwriter/write/)(const char_t *) | Scrive la c-string specificata nello stream. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Scrive la rappresentazione stringa dell'oggetto [TypeInfo](../../system/typeinfo/) specificato nello stream. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Scrive i valori specificati formattati secondo il formato specificato nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)() | Scrive i caratteri terminatore di linea nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Scrive la rappresentazione stringa dell'oggetto specificato seguita dai caratteri terminatore di linea nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Scrive la rappresentazione stringa del valore booleano specificato seguita dai caratteri terminatore di linea nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Scrive il carattere specificato seguito dai caratteri terminatore di linea nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Scrive la rappresentazione stringa dell'oggetto [Decimal](../../system/decimal/) specificato seguita dai caratteri terminatore di linea nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Scrive la rappresentazione stringa del valore a doppia precisione specificato seguita dai caratteri terminatore di linea nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Scrive la rappresentazione stringa del valore intero a 32 bit specificato seguita dai caratteri terminatore di linea nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Scrive la rappresentazione stringa del valore intero a 64 bit specificato seguita dai caratteri terminatore di linea nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Scrive la rappresentazione stringa del valore a precisione singola specificato seguita dai caratteri terminatore di linea nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | Scrive la stringa specificata seguita dai caratteri terminatore di linea nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Scrive la rappresentazione stringa del valore intero senza segno a 32 bit specificato seguita dai caratteri terminatore di linea nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Scrive la rappresentazione stringa del valore intero senza segno a 64 bit specificato seguita dai caratteri terminatore di linea nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Scrive tutti i caratteri dall'array specificato seguiti dai caratteri terminatore di linea nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Scrive il sottointervallo specificato di caratteri UTF-16 dall'array di caratteri specificato seguiti dai caratteri terminatore di linea nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | Scrive la c-string specificata seguita dai caratteri terminatore di linea nello stream. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Scrive la rappresentazione stringa dell'oggetto [TypeInfo](../../system/typeinfo/) specificato seguita dai caratteri terminatore di linea nello stream. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Scrive i valori specificati formattati secondo il formato specificato seguiti dai caratteri nello stream. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Distruttore. |

## Vedi anche

* Classe [TextWriter](../textwriter/)
* Namespace [System::IO](../)
* Libreria [Aspose.Slides](../../)