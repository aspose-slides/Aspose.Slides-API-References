---
title: StringFormat
second_title: Riferimento API di Aspose.Slides per C++
description: "Incapsula le informazioni di layout del testo, le manipolazioni di visualizzazione e le funzionalità OpenType. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò causerebbe errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e utilizza questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 313
url: /it/system.drawing/stringformat/
---
## StringFormat classe

Incapsula le informazioni di layout del testo, le manipolazioni di visualizzazione e le funzionalità OpenType. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e utilizza questo puntatore per passarlo alle funzioni come argomento.

```cpp
class StringFormat : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [Clone](./clone/)() | Restituisce una copia esatta dell'oggetto corrente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| [StringAlignment](../stringalignment/) [get_Alignment](./get_alignment/)() const | Restituisce un valore che indica l'allineamento orizzontale della stringa. |
| **int32_t** [get_DigitSubstitutionLanguage](./get_digitsubstitutionlanguage/)() const | Restituisce un valore che indica la lingua usata quando le cifre locali sono sostituite con cifre occidentali. |
| [StringDigitSubstitute](../stringdigitsubstitute/) [get_DigitSubstitutionMethod](./get_digitsubstitutionmethod/)() const | Restituisce il metodo di sostituzione delle cifre. |
| [StringFormatFlags](../stringformatflags/) [get_FormatFlags](./get_formatflags/)() const | Restituisce una combinazione bitwise di StringFormatFlags che specifica il formato della stringa rappresentato dall'oggetto corrente. |
| static [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [get_GenericDefault](./get_genericdefault/)() | Restituisce un oggetto [StringFormat](./) che rappresenta un formato predefinito generico. |
| static [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\> [get_GenericTypographic](./get_generictypographic/)() | Restituisce un oggetto [StringFormat](./) che rappresenta un formato tipografico generico. |
| [Text::HotkeyPrefix](../../system.drawing.text/hotkeyprefix/) [get_HotkeyPrefix](./get_hotkeyprefix/)() const | Restituisce il valore che indica come viene mostrato il prefisso della scorciatoia. |
| [StringAlignment](../stringalignment/) [get_LineAlignment](./get_linealignment/)() const | Restituisce un valore che indica l'allineamento verticale della stringa. |
| [StringTrimming](../stringtrimming/) [get_Trimming](./get_trimming/)() const | Restituisce un valore che indica come la stringa viene troncata. |
| int [GetCharacterRangesCount](./getcharacterrangescount/)() const | Ottiene la dimensione dell'array [CharacterRange](../characterrange/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| [ArrayPtr](../../system/arrayptr/)\<**float**\> [GetTabStops](./gettabstops/)(**float**\&) const | Restituisce le tabulazioni per l'oggetto [StringFormat](./) corrente. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() statement di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [set_Alignment](./set_alignment/)([StringAlignment](../stringalignment/)) | Imposta l'allineamento orizzontale della stringa. |
| void [set_FormatFlags](./set_formatflags/)([StringFormatFlags](../stringformatflags/)) | Imposta i flag del formato della stringa. |
| void [set_HotkeyPrefix](./set_hotkeyprefix/)([Text::HotkeyPrefix](../../system.drawing.text/hotkeyprefix/)) | Imposta il valore che specifica come il prefisso della scorciatoia dovrebbe essere mostrato. |
| void [set_LineAlignment](./set_linealignment/)([StringAlignment](../stringalignment/)) | Imposta l'allineamento verticale della stringa. |
| void [set_Trimming](./set_trimming/)([StringTrimming](../stringtrimming/)) | Imposta un valore che specifica come la stringa viene troncata. |
| void [SetDigitSubstitution](./setdigitsubstitution/)(**int32_t**, [StringDigitSubstitute](../stringdigitsubstitute/)) | Imposta la lingua e il metodo di sostituzione delle cifre. |
| void [SetMeasurableCharacterRanges](./setmeasurablecharacterranges/)(const [ArrayPtr](../../system/arrayptr/)\<[CharacterRange](../characterrange/)\>\&) | Imposta un array di oggetti [CharacterRange](../characterrange/) che rappresentano gli intervalli di caratteri misurati da una chiamata al metodo MeasureCharacterRanges(). |
| void [SetTabStops](./settabstops/)(**float**, const [ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | Imposta le tabulazioni per l'oggetto [StringFormat](./) corrente. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento modello come un puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
|  [StringFormat](./stringformat/)() | Crea una nuova istanza della classe [StringFormat](./). |
|  [StringFormat](./stringformat/)([StringFormatFlags](../stringformatflags/), **int32_t**) | Crea una nuova istanza della classe [StringFormat](./) con i flag di formato e la lingua specificati. |
|  [StringFormat](./stringformat/)(const [SharedPtr](../../system/sharedptr/)\<[StringFormat](./)\>\&) | Costruttore di copia. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco (unlock) dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Libreria [Aspose.Slides](../../)