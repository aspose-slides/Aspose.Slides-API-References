---
title: Timing
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta il timing dell'animazione.
type: docs
weight: 625
url: /it/aspose.slides.animation/timing/
---
## Classe Timing


Rappresenta il timing dell'animazione.

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## Metodi

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti utilizzando la semantica [Object.Equals](../../system/object/equals/) di C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| **float** [get_Accelerate](./get_accelerate/)() override | Descrive la percentuale della durata dell'effetto di accelerazione. Leggi **float**. |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | Descrive se riprodurre automaticamente l'animazione al contrario dopo averla riprodotta nella direzione avanti. Leggi **bool**. |
| **float** [get_Decelerate](./get_decelerate/)() override | Descrive la percentuale della durata dell'effetto di decelerazione. Leggi **float**. |
| **float** [get_Duration](./get_duration/)() override | Descrive la durata dell'effetto di animazione. Leggi **float**. |
| **float** [get_RepeatCount](./get_repeatcount/)() override | Descrive il numero di volte in cui l'effetto dovrebbe ripetersi. Leggi **float**. |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | Descrive il numero di volte in cui l'effetto dovrebbe ripetersi. Leggi **float**. |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | Questo attributo specifica se l'effetto si ripeterà fino alla fine della diapositiva. Leggi **bool**. |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | Questo attributo specifica se l'effetto si ripeterà fino al prossimo clic. Leggi **bool**. |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | Specifica se un effetto deve ricominciare dopo il completamento. Leggi [EffectRestartType](../effectrestarttype/). |
| **bool** [get_Rewind](./get_rewind/)() override | Questo attributo specifica se l'effetto verrà riavvolto al termine della riproduzione. Leggi **bool**. |
| **float** [get_Speed](./get_speed/)() override | Specifica la percentuale di cui velocizzare (o rallentare) il timing. Leggi **float**. |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | Descrive il tempo di ritardo dopo il trigger. Leggi **float**. |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | Descrive il tipo di trigger. Leggi [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() di C# per il blocco. Chiama direttamente o usa l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento l'oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [set_Accelerate](./set_accelerate/)(**float**) override | Descrive la percentuale della durata dell'effetto di accelerazione. Scrivi **float**. |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | Descrive se riprodurre automaticamente l'animazione al contrario dopo averla riprodotta nella direzione avanti. Scrivi **bool**. |
| void [set_Decelerate](./set_decelerate/)(**float**) override | Descrive la percentuale della durata dell'effetto di decelerazione. Scrivi **float**. |
| void [set_Duration](./set_duration/)(**float**) override | Descrive la durata dell'effetto di animazione. Scrivi **float**. |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | Descrive il numero di volte in cui l'effetto dovrebbe ripetersi. Scrivi **float**. |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | Descrive il numero di volte in cui l'effetto dovrebbe ripetersi. Scrivi **float**. |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | Questo attributo specifica se l'effetto si ripeterà fino alla fine della diapositiva. Scrivi **bool**. |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | Questo attributo specifica se l'effetto si ripeterà fino al prossimo clic. Scrivi **bool**. |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | Specifica se un effetto deve ricominciare dopo il completamento. Scrivi [EffectRestartType](../effectrestarttype/). |
| void [set_Rewind](./set_rewind/)(**bool**) override | Questo attributo specifica se l'effetto verrà riavvolto al termine della riproduzione. Scrivi **bool**. |
| void [set_Speed](./set_speed/)(**float**) override | Specifica la percentuale di cui velocizzare (o rallentare) il timing. Scrivi **float**. |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | Descrive il tempo di ritardo dopo il trigger. Scrivi **float**. |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | Descrive il tipo di trigger. Scrivi [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta l'argomento template n-esimo come puntatore debole (piuttosto che condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore attuale del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiama direttamente o usa l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [ITiming](../itiming/)
* Classe [IDOMObject](../../aspose.slides/idomobject/)
* Spazio dei nomi [Aspose::Slides::Animation](../)
* Libreria [Aspose.Slides](../../)