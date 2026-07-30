---
title: BulletFormat
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta le proprietà di formattazione dei punti elenco del paragrafo.
type: docs
weight: 248
url: /it/aspose.slides/bulletformat/
---
## BulletFormat classe

Rappresenta le proprietà di formattazione dei punti elenco del paragrafo.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## Metodi

| Method | Description |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | Imposta gli spostamenti predefiniti non zero per Indent e MarginLeft effettivi del paragrafo quando i bullet sono abilitati (come fa PowerPoint se si attivano i bullet/numero di paragrafo). Se i bullet sono disabilitati, ripristina semplicemente Indent e MarginLeft del paragrafo (come fa PowerPoint se si disabilitano i bullet/numero di paragrafo). Gli spostamenti di indentazione sono applicati in relazione al contesto bullet corrente - IBulletFormat::get(set)_Type, .NumberedBulletStyle e FontHeight della prima porzione. Gli spostamenti di indentazione non zero sono applicati a Indent e MarginLeft effettivi del paragrafo corrente (rendendo i valori risultanti valori locali). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Confronta con l'oggetto specificato. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| char16_t [get_Char](./get_char/)() override | Restituisce il carattere bullet di un paragrafo senza ereditarietà. Leggi **wchar_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | Restituisce il formato colore di un bullet di un paragrafo senza ereditarietà. Solo lettura [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | Restituisce il font del bullet di un paragrafo senza ereditarietà. Leggi [IFontData](../ifontdata/). |
| **float** [get_Height](./get_height/)() override | Restituisce l'altezza del bullet di un paragrafo senza ereditarietà. Il valore std::numeric_limits<float>::quiet_NaN() determina che il bullet eredita l'altezza dalla prima porzione del paragrafo. Leggi **float**. |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | Determina se il bullet ha un colore proprio o lo eredita dalla prima porzione del paragrafo. **[NullableBool::True](../nullablebool/)** se il bullet ha un colore proprio e **[NullableBool::False](../nullablebool/)** se il bullet eredita il colore dalla prima porzione del paragrafo. Leggi [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | Determina se il bullet ha un font proprio o lo eredita dalla prima porzione del paragrafo. **[NullableBool::True](../nullablebool/)** se il bullet ha un font proprio e **[NullableBool::False](../nullablebool/)** se il bullet eredita il font dalla prima porzione del paragrafo. Leggi [NullableBool](../nullablebool/). |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | Restituisce il primo numero usato per il gruppo di bullet numerati senza ereditarietà. Leggi **int16_t**. |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | Restituisce lo stile di un bullet numerato senza ereditarietà. Leggi [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Restituisce l'oggetto Parent_Immediate. Solo lettura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Restituisce il genitore [IPresentationComponent](../ipresentationcomponent/). Solo lettura [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Restituisce l'immagine usata come bullet in un paragrafo senza ereditarietà. Solo lettura [ISlidesPicture](../islidespicture/). |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | Restituisce il tipo di bullet di un paragrafo senza ereditarietà. Leggi [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | Ottiene i dati di formattazione del bullet effettivi con l'ereditarietà applicata. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Restituisce il codice hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e abilita la costruzione per copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e abilita la costruzione per copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [set_Char](./set_char/)(char16_t) override | Imposta il carattere bullet di un paragrafo senza ereditarietà. Scrivi **wchar_t**. |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Imposta il font del bullet di un paragrafo senza ereditarietà. Scrivi [IFontData](../ifontdata/). |
| void [set_Height](./set_height/)(**float**) override | Imposta l'altezza del bullet di un paragrafo senza ereditarietà. Il valore std::numeric_limits<float>::quiet_NaN() determina che il bullet eredita l'altezza dalla prima porzione del paragrafo. Scrivi **float**. |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | Determina se il bullet ha un colore proprio o lo eredita dalla prima porzione del paragrafo. **[NullableBool::True](../nullablebool/)** se il bullet ha un colore proprio e **[NullableBool::False](../nullablebool/)** se il bullet eredita il colore dalla prima porzione del paragrafo. Scrivi [NullableBool](../nullablebool/). |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | Determina se il bullet ha un font proprio o lo eredita dalla prima porzione del paragrafo. **[NullableBool::True](../nullablebool/)** se il bullet ha un font proprio e **[NullableBool::False](../nullablebool/)** se il bullet eredita il font dalla prima porzione del paragrafo. Scrivi [NullableBool](../nullablebool/). |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | Imposta il primo numero usato per il gruppo di bullet numerati senza ereditarietà. Scrivi **int16_t**. |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | Imposta lo stile di un bullet numerato senza ereditarietà. Scrivi [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | Imposta il tipo di bullet di un paragrafo senza ereditarietà. Scrivi [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (invece che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [PVIObject](../pviobject/)
* Classe [IBulletFormat](../ibulletformat/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)