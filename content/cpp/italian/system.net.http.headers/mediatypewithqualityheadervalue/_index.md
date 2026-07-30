---
title: MediaTypeWithQualityHeaderValue
second_title: Riferimento API Aspose.Slides per C++
description: "Rappresenta un tipo MIME con un fattore di qualità aggiuntivo in un valore dell'intestazione 'Content-Type'. Gli oggetti di questa classe devono essere allocati solo tramite la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherebbe errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e utilizza tale puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 157
url: /it/system.net.http.headers/mediatypewithqualityheadervalue/
---
## MediaTypeWithQualityHeaderValue classe


Rappresenta un tipo MIME con un fattore di qualità aggiuntivo in un valore dell'intestazione 'Content-Type'. Gli oggetti di questa classe devono essere allocati solo tramite la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherebbe errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa tale puntatore per passarla alle funzioni come argomento.

```cpp
class MediaTypeWithQualityHeaderValue : public System::Net::Http::Headers::MediaTypeHeaderValue
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| **bool** [Equals](../mediatypeheadervalue/equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Esegue un'emulazione del confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Esegue un'emulazione del confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per usi interni. |
| [String](../../system/string/) [get_CharSet](../mediatypeheadervalue/get_charset/)() | Restituisce un set di caratteri. |
| [String](../../system/string/) [get_MediaType](../mediatypeheadervalue/get_mediatype/)() | Restituisce il valore dell'intestazione media-type. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](../mediatypeheadervalue/get_parameters/)() | Restituisce i parametri di valore dell'intestazione media-type. |
| [Nullable](../../system/nullable/)\<**double**\> [get_Quality](./get_quality/)() | Restituisce un valore di qualità. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Restituisce la struttura dati del contatore di riferimenti associato all'oggetto. |
| **int32_t** [GetHashCode](../mediatypeheadervalue/gethashcode/)() const override | Analogo al metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| static **int32_t** [GetMediaTypeLength](../mediatypeheadervalue/getmediatypelength/)([String](../../system/string/), **int32_t**, [HeaderFunc](../headerfunc/)\<[System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\>\>, [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\>\&) | Converte una stringa fornita dall'indice specificato in un'istanza della classe [MediaTypeHeaderValue](../mediatypeheadervalue/). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Restituisce il tipo effettivo dell'oggetto. Analogo alla chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo all'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() C# per il blocco. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| [MediaTypeHeaderValue](../mediatypeheadervalue/mediatypeheadervalue/)() | Costruisce una nuova istanza. |
| [MediaTypeHeaderValue](../mediatypeheadervalue/mediatypeheadervalue/)([String](../../system/string/)) | Costruisce una nuova istanza. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)() | Costruisce una nuova istanza. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)([String](../../system/string/)) | Costruisce una nuova istanza. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)([String](../../system/string/), **double**) | Costruisce una nuova istanza. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo al metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, realmente, inizializza un nuovo oggetto e consente la costruzione di copie per le subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, realmente, inizializza solo un nuovo oggetto e consente la costruzione di copie per le subclass. |
| static [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeWithQualityHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Converte una stringa fornita in un'istanza della classe [MediaTypeWithQualityHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [set_CharSet](../mediatypeheadervalue/set_charset/)([String](../../system/string/)) | Imposta un set di caratteri. |
| void [set_MediaType](../mediatypeheadervalue/set_mediatype/)([String](../../system/string/)) | Imposta il valore dell'intestazione media-type. |
| void [set_Quality](./set_quality/)([Nullable](../../system/nullable/)\<**double**\>) | Imposta un valore di qualità. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (anziché condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Restituisce il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| [String](../../system/string/) [ToString](../mediatypeheadervalue/tostring/)() const override | Analogo al metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeWithQualityHeaderValue](./)\>\&) | Tenta di convertire una stringa fornita in un'istanza della classe [MediaTypeWithQualityHeaderValue](./). |
| static **bool** [TryParse](../mediatypeheadervalue/tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\>\&) | Tenta di convertire una stringa fornita in un'istanza della classe [MediaTypeHeaderValue](../mediatypeheadervalue/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [MediaTypeHeaderValue](../mediatypeheadervalue/)
* Namespace [System::Net::Http::Headers](../)
* Libreria [Aspose.Slides](../../)