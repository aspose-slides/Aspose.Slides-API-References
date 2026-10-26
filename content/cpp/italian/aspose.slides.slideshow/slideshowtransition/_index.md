---
title: SlideShowTransition
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta la transizione della presentazione.
type: docs
weight: 404
url: /it/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition classe

Rappresenta la transizione della presentazione.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Determina se le due istanze [SlideShowTransition](./) sono uguali. Lettura/scrittura **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | Questo attributo specifica se la presentazione avanzare alla diapositiva successiva dopo un certo tempo. Lettura **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | Specifica il tempo, in millisecondi, dopo il quale la transizione dovrebbe iniziare. Questa impostazione può essere usata in combinazione con l'attributo advClick. Se questo attributo non è specificato, si presume che non avvenga alcun avanzamento automatico. Lettura **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | Specifica se un clic del mouse farà avanzare la diapositiva o meno. Se questo attributo non è specificato, si assume il valore true. Lettura **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | Ottiene la durata dell'effetto di transizione della diapositiva in millisecondi. Lettura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | Restituisce i dati audio incorporati. Lettura [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | Specifica se questo suono è o meno un suono integrato. Se questo attributo è impostato su true, l'applicazione generatrice viene avvisata di controllare l'attributo name specificato per questo suono nella sua lista di suoni integrati e può quindi mostrare un nome o un'interfaccia personalizzata secondo necessità. Lettura **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | Questo attributo specifica se il suono verrà ripetuto fino al verificarsi del prossimo evento sonoro nella presentazione. Lettura **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | Imposta o restituisce la modalità suono per la transizione della diapositiva. Lettura [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | Specifica un nome leggibile dall'uomo per il suono della transizione. Il [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) deve essere assegnato per ottenere o impostare il nome del suono. Lettura [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | Specifica la velocità di transizione da usare quando si passa dalla diapositiva corrente a quella successiva. Lettura [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | Tipo di transizione. Lettura [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) mostra valore di transizione. Solo lettura [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Funziona come funzione hash per un tipo particolare, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia praticamente nulla, ma inizializza un nuovo oggetto e consente la copia dei sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia praticamente nulla, ma inizializza un nuovo oggetto e consente la copia dei sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | Questo attributo specifica se la presentazione avanzare alla diapositiva successiva dopo un certo tempo. Scrittura **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | Specifica il tempo, in millisecondi, dopo il quale la transizione dovrebbe iniziare. Questa impostazione può essere usata in combinazione con l'attributo advClick. Se questo attributo non è specificato, si presume che non avvenga alcun avanzamento automatico. Scrittura **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | Specifica se un clic del mouse farà avanzare la diapositiva o meno. Se questo attributo non è specificato, si assume il valore true. Scrittura **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | Imposta la durata dell'effetto di transizione della diapositiva in millisecondi. Scrittura **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | Imposta i dati audio incorporati. Scrittura [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | Specifica se questo suono è integrato. Se questo attributo è impostato su true, l'applicazione generatrice viene avvisata di controllare l'attributo name specificato per questo suono nella sua lista di suoni integrati e può quindi mostrare un nome o un'interfaccia personalizzata secondo necessità. Scrittura **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | Questo attributo specifica se il suono sarà ripetuto fino al verificarsi del prossimo evento sonoro nella presentazione. Scrittura **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | Imposta o restituisce la modalità suono per la transizione della diapositiva. Scrittura [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | Specifica un nome leggibile dall'uomo per il suono della transizione. Il [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) deve essere assegnato per ottenere o impostare il nome del suono. Scrittura [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | Specifica la velocità di transizione da usare quando si passa dalla diapositiva corrente a quella successiva. Scrittura [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | Tipo di transizione. Scrittura [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Imposta il n-esimo argomento template a un puntatore weak (anziché shared). Consente di passare i puntatori nei contenitori alla modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [DomObject](../../aspose.slides/domobject/)
* Classe [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* Spazio dei nomi [Aspose::Slides::SlideShow](../)
* Libreria [Aspose.Slides](../../)