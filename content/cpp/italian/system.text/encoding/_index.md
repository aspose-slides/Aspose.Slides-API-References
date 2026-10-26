---
title: Encoding
second_title: Riferimento API di Aspose.Slides per C++
description: Servizi di codifica.
type: docs
weight: 222
url: /it/system.text/encoding/
---
## Encoding classe

[Encoding](./) servizi.

```cpp
class Encoding : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | Clona l'oggetto encoding. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Converte byte tra due codifiche. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Converte byte tra due codifiche. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Confronta le codifiche. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | Ottiene la codifica ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | Ottiene l'oggetto di codifica Unicode standard big-endian. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | Ottiene l'oggetto di codifica UTF-32 standard big-endian. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | Ottiene il nome di codifica compatibile con il corpo dell'agente di posta. |
| virtual int [get_CodePage](./get_codepage/)() | Ottiene l'ID della codepage [Windows](../../system.windows/). |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | Ottiene il fallback del decodificatore. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | Ottiene la codifica predefinita. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | Ottiene il fallback del codificatore. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | Ottiene il nome di codifica leggibile dall'uomo. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | Ottiene il nome di codifica compatibile con l'intestazione dell'agente di posta. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Verifica se la codifica può essere usata nel browser per visualizzare il contenuto. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | Verifica se la codifica può essere usata nel browser per salvare il contenuto. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Verifica se la codifica può essere usata nel client di posta per visualizzare il contenuto. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | Verifica se la codifica può essere usata nel client di posta per salvare il contenuto. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Verifica se la codifica è di sola lettura. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | Verifica se la codifica è a byte singolo. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Ottiene la codifica Latin1. FOR INTERNAL USE. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | Ottiene l'oggetto di codifica Unicode standard. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | Ottiene l'oggetto di codifica UTF-7 standard. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | Ottiene l'oggetto di codifica UTF-8 standard. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | Solo interno, da usare dalle librerie di classe: non contrassegnato e senza validazione di input. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | Ottiene il nome di codifica compatibile IANA. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | Ottiene l'ID della codepage [Windows](../../system.windows/). |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Ottiene il numero di caratteri necessari per codificare un buffer di caratteri. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Ottiene il numero di caratteri necessari per codificare un buffer di caratteri. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Ottiene il numero di caratteri necessari per codificare un buffer di caratteri. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Ottiene il numero di caratteri necessari per codificare una stringa. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Ottiene il numero di caratteri necessari per codificare un buffer di caratteri. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Ottiene il numero di caratteri necessari per codificare un buffer di caratteri. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Ottiene i byte risultanti dalla codifica di un buffer di caratteri. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Ottiene i byte risultanti dalla codifica di un buffer di caratteri. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Ottiene i byte risultanti dalla codifica di un buffer di caratteri. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Ottiene i byte risultanti dalla codifica di un buffer di caratteri. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Ottiene i byte risultanti dalla codifica di un buffer di caratteri. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Ottiene i byte risultati dalla codifica di un buffer di caratteri. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Ottiene i byte risultati dalla codifica di un buffer di caratteri. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Ottiene i byte risultati dalla codifica di un buffer di caratteri. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Ottiene i byte risultati dalla codifica di un buffer di caratteri. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Ottiene i byte risultati dalla codifica di un buffer di caratteri. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Ottiene il numero di caratteri necessari per decodificare un buffer di byte. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ottiene il numero di caratteri necessari per decodificare un buffer di byte. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Ottiene il numero di caratteri necessari per decodificare un buffer di byte. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Ottiene i caratteri risultati dalla decodifica di un buffer di byte. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Ottiene i caratteri risultati dalla decodifica di un buffer di byte. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ottiene i caratteri risultati dalla decodifica di un buffer di byte. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Ottiene i caratteri risultati dalla decodifica di un buffer di byte. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | Ottiene un decoder che inoltra le richieste a questo oggetto. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | Ottiene un encoder che inoltra le richieste a questo oggetto. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | Ottiene la codifica per nome. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | Ottiene la codifica per codepage. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Ottiene la codifica per codepage. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Ottiene la codifica per nome. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | Ottiene l'elenco delle codifiche note. |
| int [GetHashCode](./gethashcode/)() const override | Genera hash della codifica. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | Ottiene il numero massimo di byte necessari per codificare un numero specificato di caratteri. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | Ottiene il numero massimo di caratteri necessari per decodificare un numero specificato di byte. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | Restituisce una sequenza di byte che denota la codifica (ad esempio BOM). |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Decodifica un buffer di byte in una stringa. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Decodifica un buffer di byte in una stringa. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Decodifica un buffer di byte in una stringa. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Decodifica un buffer di byte in una stringa. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Decodifica un buffer di byte in una stringa. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Decodifica un buffer di byte in una stringa. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Decodifica un buffer di byte in una stringa. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Decodifica un buffer di byte in una stringa. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo alla chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo all'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo al metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Imposta il fallback del decodificatore. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Imposta il fallback del codificatore. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (anziché condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo al metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Valore predefinito della codepage. |

## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## Vedi anche

* Classe [Object](../../system/object/)
* Namespace [System::Text](../)
* Libreria [Aspose.Slides](../../)