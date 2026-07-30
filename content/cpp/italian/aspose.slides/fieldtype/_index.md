---
title: FieldType
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta un tipo di campo. Questo valore determina quale testo verrà impostato nella parte del campo quando verrà aggiornato.
type: docs
weight: 872
url: /it/aspose.slides/fieldtype/
---
## FieldType classe

Rappresenta un tipo di campo. Questo valore determina quale testo sarà impostato nella parte del campo quando verrà aggiornato.

```cpp
class FieldType : public Aspose::Slides::IFieldType
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Verifica se questo campo è uguale a un altro. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
|  [FieldType](./fieldtype/)([System::String](../../system/string/)) | Inizializza una nuova istanza della classe [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime](./get_datetime/)() | Data e ora correnti nel formato predefinito data/ora per l'applicazione di rendering. Sola lettura [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime1](./get_datetime1/)() | Data e ora correnti in un primo formato predefinito (MM/DD/YYYY per inglese). Sola lettura [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime10](./get_datetime10/)() | Data e ora correnti in un decimo formato predefinito (hh:mm per inglese). Sola lettura [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime11](./get_datetime11/)() | Data e ora correnti in un undicesimo formato predefinito (hh:mm:ss per inglese). Sola lettura [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime12](./get_datetime12/)() | Data e ora correnti in un dodicesimo formato predefinito (hh:mm AM/PM per inglese). Sola lettura [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime13](./get_datetime13/)() | Data e ora correnti in un tredicesimo formato predefinito (hh:mm:ss AM/PM per inglese). Sola lettura [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime2](./get_datetime2/)() | Data e ora correnti in un secondo formato predefinito (Day, Month DD, YYYY per inglese). Sola lettura [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime3](./get_datetime3/)() | Data e ora correnti in un terzo formato predefinito (DD Month YYYY per inglese). Sola lettura [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime4](./get_datetime4/)() | Data e ora correnti in un quarto formato predefinito (Month DD, YYYY per inglese). Sola lettura [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime5](./get_datetime5/)() | Data e ora correnti in un quinto formato predefinito (DD-Mon-YY per inglese). Sola lettura [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime6](./get_datetime6/)() | Data e ora correnti in un sesto formato predefinito (Month YY per inglese). Sola lettura [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime7](./get_datetime7/)() | Data e ora correnti in un settimo formato predefinito (Mon-YY per inglese). Sola lettura [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime8](./get_datetime8/)() | Data e ora correnti in un ottavo formato predefinito (MM/DD/YYYY hh:mm AM/PM per inglese). Sola lettura [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime9](./get_datetime9/)() | Data e ora correnti in un nono formato predefinito (MM/DD/YYYY hh:mm:ss AM/PM per inglese). Sola lettura [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_Footer](./get_footer/)() | Footer di [Slide](../slide/). Sola lettura [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_Header](./get_header/)() | Header di [Slide](../slide/). Sola lettura [FieldType](./). |
| [System::String](../../system/string/) [get_InternalString](./get_internalstring/)() override | Restituisce il nome interno di questo oggetto [FieldType](./). Leggi [System::String](../../system/string/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_SlideNumber](./get_slidenumber/)() | Numero della diapositiva corrente. Sola lettura [FieldType](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Restituisce l'hashcode per questo oggetto. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiama direttamente o usa l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, si limita a inizializzare un nuovo oggetto e consente la copia di costruttori per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, si limita a inizializzare un nuovo oggetto e consente la copia di costruttori per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [set_InternalString](./set_internalstring/)([System::String](../../system/string/)) override | Restituisce il nome interno di questo oggetto [FieldType](./). Scrivi [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointers o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointers o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiama direttamente o usa l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointers o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointers o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Class [IFieldType](../ifieldtype/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)