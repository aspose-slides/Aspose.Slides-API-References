---
title: IParagraphFormat
second_title: Riferimento API di Aspose.Slides per C++
description: Questa classe contiene le proprietà di formattazione del paragrafo. A differenza di IParagraphFormatEffectiveData, tutte le proprietà di questa classe sono scrivibili.
type: docs
weight: 3147
url: /it/aspose.slides/iparagraphformat/
---
## IParagraphFormat classe


Questa classe contiene le proprietà di formattazione del paragrafo. A differenza di [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), tutte le proprietà di questa classe sono scrivibili.

```cpp
class IParagraphFormat : public virtual System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Restituisce l'allineamento del testo in un paragrafo senza ereditarietà. Leggi [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | Restituisce il formato elenco puntato del paragrafo. Solo lettura [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Restituisce il formato di porzione predefinito di un paragrafo. Nessuna ereditarietà applicata. Solo lettura [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Restituisce la dimensione di tabulazione predefinita senza ereditarietà. Leggi **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Restituisce la profondità del paragrafo. Il valore 0 indica valore non definito. Leggi **int16_t**. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Determina se è utilizzato l'interruzione di riga East Asian in un paragrafo. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Restituisce l'allineamento del carattere in un paragrafo senza ereditarietà. Leggi [Slides::FontAlignment](../fontalignment/). |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Determina se è utilizzata la punteggiatura sospesa in un paragrafo. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | Restituisce l'indentazione della prima riga/pendente del paragrafo senza ereditarietà. L'indentazione pendente può essere definita con valori negativi. Leggi **float**. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Determina se è utilizzata l'interruzione di riga Latina in un paragrafo. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Restituisce il margine sinistro in un paragrafo senza ereditarietà. Leggi **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Restituisce il margine destro in un paragrafo senza ereditarietà. Leggi **float**. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Determina se è utilizzata la scrittura da destra a sinistra in un paragrafo. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Restituisce la quantità di spazio dopo l'ultima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Leggi **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Restituisce la quantità di spazio prima della prima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Leggi **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Restituisce la quantità di spazio tra le linee di base in un paragrafo. Un valore positivo indica percentuale, negativo indica dimensione in punti. Nessuna ereditarietà applicata. Leggi **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Restituisce la tabulazione di un paragrafo all'indice specificato. Nessuna ereditarietà applicata. Solo lettura [Aspose::Slides::ITab](../itab/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | Restituisce le tabulazioni di un paragrafo. Nessuna ereditarietà applicata. Solo lettura [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | Ottiene i dati di formattazione del paragrafo effettivi con l'ereditarietà applicata. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, davvero, solo inizializza un nuovo oggetto e abilita la costruzione copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, davvero, solo inizializza un nuovo oggetto e abilita la costruzione copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | Imposta l'allineamento del testo in un paragrafo senza ereditarietà. Scrivi [TextAlignment](../textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Imposta la dimensione di tabulazione predefinita senza ereditarietà. Scrivi **float**. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | Imposta la profondità del paragrafo. Il valore 0 indica valore non definito. Scrivi **int16_t**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | Determina se è utilizzata l'interruzione di riga East Asian in un paragrafo. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | Imposta l'allineamento del carattere in un paragrafo senza ereditarietà. Scrivi [Slides::FontAlignment](../fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | Determina se è usata la punteggiatura sospesa in un paragrafo. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | Imposta l'indentazione della prima riga/pendente del paragrafo senza ereditarietà. L'indentazione pendente può essere definita con valori negativi. Scrivi **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | Determina se è utilizzata l'interruzione di riga Latina in un paragrafo. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Imposta il margine sinistro in un paragrafo senza ereditarietà. Scrivi **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Imposta il margine destro in un paragrafo senza ereditarietà. Scrivi **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | Determina se è usata la scrittura da destra a sinistra in un paragrafo. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Imposta la quantità di spazio dopo l'ultima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Scrivi **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Imposta la quantità di spazio prima della prima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Scrivi **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Imposta la quantità di spazio tra le linee di base in un paragrafo. Un valore positivo indica percentuale, negativo indica dimensione in punti. Nessuna ereditarietà applicata. Scrivi **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Osservazioni

Questa classe è usata per restituire e manipolare le proprietà di formattazione del paragrafo definite per il paragrafo specifico. Questo significa che nessuna ereditarietà è applicata quando si ottengono i valori, quindi nella maggior parte dei casi otterrai valori che significano "non definito".

Per ottenere i valori effettivi dei parametri di formattazione includendo quelli ereditati è necessario usare il metodo [IParagraphFormat::GetEffective](./geteffective/) che restituisce un'istanza [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## Vedi anche

* Classe [Object](../../system/object/)
* Namespace [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)