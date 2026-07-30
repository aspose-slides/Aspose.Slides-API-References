---
title: ITiming
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta la tempistica dell'animazione.
type: docs
weight: 443
url: /it/aspose.slides.animation/itiming/
---
## classe ITiming

Rappresenta la tempistica dell'animazione.

```cpp
class ITiming : public virtual System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | Descrive la percentuale della durata dell'effetto di accelerazione. Leggi **float**. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | Descrive se riprodurre automaticamente l'animazione al contrario dopo averla riprodotta nella direzione in avanti. Leggi **bool**. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | Descrive la percentuale della durata dell'effetto di decelerazione. Leggi **float**. |
| virtual **float** [get_Duration](./get_duration/)() | Descrive la durata dell'effetto di animazione. Leggi **float**. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | Descrive il numero di volte in cui l'effetto deve essere ripetuto. Leggi **float**. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | Descrive il numero di volte in cui l'effetto deve essere ripetuto. Leggi **float**. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | Questo attributo specifica se l'effetto verrà ripetuto fino alla fine della diapositiva. Leggi **bool**. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | Questo attributo specifica se l'effetto verrà ripetuto fino al prossimo clic. Leggi **bool**. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | Specifica se un effetto deve ripartire dopo il completamento. Leggi [EffectRestartType](../effectrestarttype/). |
| virtual **bool** [get_Rewind](./get_rewind/)() | Questo attributo specifica se l'effetto verrà riportato all'inizio al termine della riproduzione. Leggi **bool**. |
| virtual **float** [get_Speed](./get_speed/)() | Specifica la percentuale con cui accelerare (o rallentare) la tempistica. Leggi **float**. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | Descrive il tempo di ritardo dopo il trigger. Leggi **float**. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | Descrive il tipo di trigger. Leggi [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo al metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo alla chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo all'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o utilizzare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo al metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia realmente nulla, ma inizializza un nuovo oggetto e consente la copia dei sottoclasse. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnamento. Non copia realmente nulla, ma inizializza un nuovo oggetto e consente la copia dei sottoclasse. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento l'oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi di un valore specificato. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | Descrive la percentuale della durata dell'effetto di accelerazione. Scrivi **float**. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | Descrive se riprodurre automaticamente l'animazione al contrario dopo averla riprodotta nella direzione in avanti. Scrivi **bool**. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | Descrive la percentuale della durata dell'effetto di decelerazione. Scrivi **float**. |
| virtual void [set_Duration](./set_duration/)(**float**) | Descrive la durata dell'effetto di animazione. Scrivi **float**. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | Descrive il numero di volte in cui l'effetto deve essere ripetuto. Scrivi **float**. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | Descrive il numero di volte in cui l'effetto deve essere ripetuto. Scrivi **float**. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | Questo attributo specifica se l'effetto verrà ripetuto fino alla fine della diapositiva. Scrivi **bool**. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | Questo attributo specifica se l'effetto verrà ripetuto fino al prossimo clic. Scrivi **bool**. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | Specifica se un effetto deve ripartire dopo il completamento. Scrivi [EffectRestartType](../effectrestarttype/). |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | Questo attributo specifica se l'effetto verrà riportato all'inizio al termine della riproduzione. Scrivi **bool**. |
| virtual void [set_Speed](./set_speed/)(**float**) | Specifica la percentuale con cui accelerare (o rallentare) la tempistica. Scrivi **float**. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | Descrive il tempo di ritardo dopo il trigger. Scrivi **float**. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | Descrive il tipo di trigger. Scrivi [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a puntatore weak (piuttosto che shared). Consente il cambio dei puntatori nei contenitori a modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; in alternativa, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; in alternativa, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo al metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco del lock() di C#. Chiamare direttamente o utilizzare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti weak. Non dovrebbe essere chiamato direttamente; in alternativa, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti weak. Non dovrebbe essere chiamato direttamente; in alternativa, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../../system/object/)
* Namespace [Aspose::Slides::Animation](../)
* Libreria [Aspose.Slides](../../)