---
title: ParagraphFormat
second_title: Riferimento API di Aspose.Slides per C++
description: Questa classe contiene le proprietà di formattazione del paragrafo. A differenza di IParagraphFormatEffectiveData, tutte le proprietà di questa classe sono scrivibili.
type: docs
weight: 4668
url: /it/aspose.slides/paragraphformat/
---
## ParagraphFormat classe

Questa classe contiene le proprietà di formattazione del paragrafo. A differenza di [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), tutte le proprietà di questa classe sono scrivibili.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## Metodi

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Confronta con l'oggetto specificato. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti utilizzando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, compreso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, compreso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | Restituisce l'allineamento del testo in un paragrafo senza ereditarietà. Leggi [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | Restituisce la dimensione di tabulazione predefinita senza ereditarietà. Leggi **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | Determina se è utilizzata l'interruzione di riga East Asian in un paragrafo. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | Restituisce un allineamento del carattere in un paragrafo senza ereditarietà. Leggi [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | Determina se è utilizzata la punteggiatura sospesa in un paragrafo. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | Restituisce l'Indentazione della prima riga/Indentazione sospesa del paragrafo senza ereditarietà. L'Indentazione sospesa può essere definita con valori negativi. Leggi **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | Determina se è utilizzata l'interruzione di riga Latin in un paragrafo. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | Restituisce il margine sinistro in un paragrafo senza ereditarietà. Leggi **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | Restituisce il margine destro in un paragrafo senza ereditarietà. Leggi **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Restituisce l'oggetto Parent_Immediate. Solo lettura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Restituisce il genitore [IPresentationComponent](../ipresentationcomponent/). Solo lettura [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | Determina se è utilizzata la scrittura da destra a sinistra in un paragrafo. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | Restituisce la quantità di spazio dopo l'ultima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe avere. Un valore negativo specifica la dimensione dello spazio bianco in punti. Leggi **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | Restituisce la quantità di spazio prima della prima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe avere. Un valore negativo specifica la dimensione dello spazio bianco in punti. Leggi **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | Restituisce la quantità di spazio tra le linee di base in un paragrafo. Un valore positivo indica la percentuale, un valore negativo la dimensione in punti. Nessuna ereditarietà applicata. Leggi **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | Restituisce la tabulazione di un paragrafo all'indice specificato. Nessuna ereditarietà applicata. Solo lettura [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | Restituisce le tabulazioni di un paragrafo. Nessuna ereditarietà applicata. Solo lettura [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | Ottiene i dati di formattazione del paragrafo effettivi con l'ereditarietà applicata. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Restituisce il codice hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, si limita a inizializzare un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, si limita a inizializzare un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [ParagraphFormat](./paragraphformat/)() | Inizializza una nuova istanza della classe [ParagraphFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | Imposta l'allineamento del testo in un paragrafo senza ereditarietà. Scrivi [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | Imposta la dimensione di tabulazione predefinita senza ereditarietà. Scrivi **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | Determina se è utilizzata l'interruzione di riga East Asian in un paragrafo. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | Imposta un allineamento del carattere in un paragrafo senza ereditarietà. Scrivi [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | Determina se è utilizzata la punteggiatura sospesa in un paragrafo. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | Imposta l'Indentazione della prima riga/Indentazione sospesa del paragrafo senza ereditarietà. L'Indentazione sospesa può essere definita con valori negativi. Scrivi **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | Determina se è utilizzata l'interruzione di riga Latin in un paragrafo. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | Imposta il margine sinistro in un paragrafo senza ereditarietà. Scrivi **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | Imposta il margine destro in un paragrafo senza ereditarietà. Scrivi **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | Determina se è utilizzata la scrittura da destra a sinistra in un paragrafo. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | Imposta la quantità di spazio dopo l'ultima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe avere. Un valore negativo specifica la dimensione dello spazio bianco in punti. Scrivi **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | Imposta la quantità di spazio prima della prima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe avere. Un valore negativo specifica la dimensione dello spazio bianco in punti. Scrivi **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | Imposta la quantità di spazio tra le linee di base in un paragrafo. Un valore positivo indica la percentuale, un valore negativo la dimensione in punti. Nessuna ereditarietà applicata. Scrivi **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento di modello a un puntatore debole (anziché condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Note

Questa classe è usata per restituire e manipolare le proprietà di formattazione del paragrafo definite per il paragrafo specifico. Ciò significa che nessuna ereditarietà è applicata quando si ottengono i valori, quindi nella maggior parte dei casi otterrete valori che significano "non definito".

Per ottenere i valori effettivi dei parametri di formattazione, inclusi quelli ereditati, è necessario utilizzare il metodo [ParagraphFormat::GetEffective](./geteffective/) che restituisce un'istanza di [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## Vedi anche

* Classe [PVIObject](../pviobject/)
* Classe [IParagraphFormat](../iparagraphformat/)
* Classe [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* Namespace [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)