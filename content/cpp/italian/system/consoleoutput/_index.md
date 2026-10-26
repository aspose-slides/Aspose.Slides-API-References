---
title: ConsoleOutput
second_title: "Aspose.Slides per C++ Riferimento API"
description: "Rappresenta il flusso di output standard. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò causerà errori di runtime e/o violazioni di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e usare questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 209
url: /it/system/consoleoutput/
---
## ConsoleOutput classe

Rappresenta il flusso di output standard. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o violazioni di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | Chiude il flusso e rilascia le risorse acquisite. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | Rilascia tutte le risorse usate dall'oggetto corrente e chiude il flusso sottostante. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | Svuota il contenuto del buffer nel flusso sottostante. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Restituisce sempre la codifica ASCII. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | Restituisce l'oggetto [IFormatProvider](../iformatprovider/) attualmente usato. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | Restituisce l'oggetto [IFormatProvider](../iformatprovider/) attualmente usato. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | Restituisce una stringa delimitatore di riga. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | Restituisce una stringa delimitatore di riga. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../object/object/)([Object](../object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie nelle sottoclassi. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie nelle sottoclassi. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | Imposta una stringa delimitatore di riga. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa la costruzione C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [Write](./write/)(**bool**) override | Emette la rappresentazione testuale del valore bool specificato sul flusso di output rappresentato dall'oggetto corrente. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Emette la rappresentazione testuale dell'oggetto specificato sul flusso di output rappresentato dall'oggetto corrente. |
| void [Write](./write/)(char_t) override | Emette il valore carattere specificato sul flusso di output rappresentato dall'oggetto corrente. |
| void [Write](./write/)([Decimal](../decimal/)) override | Emette la rappresentazione testuale del valore [Decimal](../decimal/) sul flusso di output rappresentato dall'oggetto corrente. |
| void [Write](./write/)(**double**) override | Emette la rappresentazione testuale del valore double-precision sul flusso di output rappresentato dall'oggetto corrente. |
| void [Write](./write/)(**int32_t**) override | Emette la rappresentazione testuale del valore intero a 32 bit sul flusso di output rappresentato dall'oggetto corrente. |
| void [Write](./write/)(**int64_t**) override | Emette la rappresentazione testuale del valore intero a 64 bit sul flusso di output rappresentato dall'oggetto corrente. |
| void [Write](./write/)(**float**) override | Emette la rappresentazione testuale del valore a virgola mobile a precisione singola sul flusso di output rappresentato dall'oggetto corrente. |
| void [Write](./write/)(const [String](../string/)\&) override | Emette l'oggetto stringa specificato sul flusso di output rappresentato dall'oggetto corrente. |
| void [Write](./write/)(**uint32_t**) override | Emette la rappresentazione testuale del valore intero senza segno a 32 bit sul flusso di output rappresentato dall'oggetto corrente. |
| void [Write](./write/)(**uint64_t**) override | Emette la rappresentazione testuale del valore intero senza segno a 64 bit sul flusso di output rappresentato dall'oggetto corrente. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Emette la rappresentazione testuale dell'array di caratteri specificato sul flusso di output rappresentato dall'oggetto corrente. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Emette la rappresentazione testuale di un intervallo di valori dell'array di caratteri specificato sul flusso di output rappresentato dall'oggetto corrente. |
| void [Write](./write/)(const char_t *) override | Emette la c-string specificata sul flusso di output rappresentato dall'oggetto corrente. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | Emette la rappresentazione testuale dell'oggetto [TypeInfo](../typeinfo/) specificato sul flusso di output rappresentato dall'oggetto corrente. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | Scrive la rappresentazione testuale del valore intero a 32 bit specificato sul flusso. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | Scrive i valori specificati formattati secondo il formato specificato sul flusso. |
| void [WriteLine](./writeline/)() override | Emette il delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Emette la rappresentazione testuale dell'oggetto specificato seguita dal delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)(**bool**) override | Emette la rappresentazione testuale del valore bool specificato seguita dal delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)(char_t) override | Emette il valore carattere specificato seguito dal delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | Emette la rappresentazione testuale del valore [Decimal](../decimal/) seguito dal delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)(**double**) override | Emette la rappresentazione testuale del valore double-precision seguito dal delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)(int) override | Emette la rappresentazione testuale del valore intero a 32 bit seguito dal delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)(**int64_t**) override | Emette la rappresentazione testuale del valore intero a 64 bit seguito dal delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)(**float**) override | Emette la rappresentazione testuale del valore a precisione singola seguito dal delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | Emette l'oggetto stringa specificato seguito dal delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)(**uint32_t**) override | Emette la rappresentazione testuale del valore intero senza segno a 32 bit seguito dal delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)(**uint64_t**) override | Emette la rappresentazione testuale del valore intero senza segno a 64 bit seguito dal delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Emette la rappresentazione testuale dell'array di caratteri specificato seguito dal delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Emette la rappresentazione testuale di un intervallo di valori dell'array di caratteri specificato seguito dal delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)(const char_t *) override | Emette la c-string specificata seguita dal delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | Emette la rappresentazione testuale dell'oggetto [TypeInfo](../typeinfo/) specificato seguito dal delimitatore di riga corrente sul flusso di output rappresentato dall'oggetto corrente. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | Scrive i valori specificati formattati secondo il formato specificato seguiti dai caratteri di terminazione di riga sul flusso. |
| virtual  [~Object](../object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | Distruttore. |

## Vedi anche

* Classe [TextWriter](../../system.io/textwriter/)
* Namespace [System](../)
* Libreria [Aspose.Slides](../../)