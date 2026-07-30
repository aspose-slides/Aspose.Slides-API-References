---
title: IHyperlink
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un collegamento ipertestuale.
type: docs
weight: 2523
url: /it/aspose.slides/ihyperlink/
---
## IHyperlink classe

Rappresenta un collegamento ipertestuale.

```cpp
class IHyperlink : public virtual System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() | Restituisce il tipo dell'azione di HyperLinkEx. Solo lettura [HyperlinkActionType](../hyperlinkactiontype/). |
| virtual [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() | Rappresenta la sorgente del colore del collegamento ipertestuale - stili o formato della porzione. Lettura [HyperlinkColorSource](../hyperlinkcolorsource/). |
| virtual [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() | Specifica l'URL esterno. Se questa proprietà diventa non nulla, allora la proprietà TargetSlide diventa nulla. Solo lettura [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() | Rappresenta un collegamento ipertestuale impostato per questa porzione senza considerare il contenuto effettivo della porzione. |
| virtual **bool** [get_HighlightClick](./get_highlightclick/)() | Determina se il collegamento ipertestuale deve essere evidenziato al clic. Solo lettura **bool**. |
| virtual **bool** [get_History](./get_history/)() | Determina se il target del collegamento ipertestuale padre deve essere aggiunto a un elenco di collegamenti ipertestuali visualizzati quando viene invocato. Solo lettura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | Rappresenta il suono in riproduzione del collegamento ipertestuale. Solo lettura [IAudio](../iaudio/). |
| virtual **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() | Determina se il suono deve essere interrotto al clic sul collegamento ipertestuale. Solo lettura **bool**. |
| virtual [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() | Restituisce il frame all'interno del frameset HTML padre per il target del collegamento ipertestuale padre quando esiste. Solo lettura [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() | Se il HyperlinkEx punta a una slide specifica restituisce questa slide. Se la proprietà diventa non nulla, allora la proprietà ExternalUrl diventa nulla. Solo lettura [ISlide](../islide/). |
| virtual [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() | Restituisce la stringa che può essere mostrata in un'interfaccia utente associata al collegamento ipertestuale padre. Solo lettura [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa l'istruzione lock() di C# per il blocco. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e abilita la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e abilita la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| virtual void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) | Rappresenta la sorgente del colore del collegamento ipertestuale - stili o formato della porzione. Scrivi [HyperlinkColorSource](../hyperlinkcolorsource/). |
| virtual void [set_HighlightClick](./set_highlightclick/)(**bool**) | Determina se il collegamento ipertestuale deve essere evidenziato al clic. Scrivi **bool**. |
| virtual void [set_History](./set_history/)(**bool**) | Determina se il target del collegamento ipertestuale padre deve essere aggiunto a un elenco di collegamenti ipertestuali visualizzati quando viene invocato. Scrivi **bool**. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Rappresenta il suono in riproduzione del collegamento ipertestuale. Scrivi [IAudio](../iaudio/). |
| virtual void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) | Determina se il suono deve essere interrotto al clic sul collegamento ipertestuale. Scrivi **bool**. |
| virtual void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) | Restituisce il frame all'interno del frameset HTML padre per il target del collegamento ipertestuale padre quando esiste. Scrivi [System::String](../../system/string/). |
| virtual void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) | Restituisce la stringa che può essere mostrata in un'interfaccia utente associata al collegamento ipertestuale padre. Scrivi [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento modello come puntatore debole (piuttosto che condiviso). Consente di cambiare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointers o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointers o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione lock() di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointers o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointers o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../../system/object/)
* Spazio dei nomi [Aspose::Slides](../)
* Library [Aspose.Slides](../../)