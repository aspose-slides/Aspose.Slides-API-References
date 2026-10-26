---
title: IColorFormat
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un colore utilizzato in una presentazione.
type: docs
weight: 1691
url: /it/aspose.slides/icolorformat/
---
## IColorFormat classe

Rappresenta un colore utilizzato in una presentazione.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | Copia il formato colore da \"color\". |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual **uint8_t** [get_B](./get_b/)() | Restituisce la componente blu di un colore. Tutte le trasformazioni di colore sono ignorate. Lettura **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | Restituisce il colore risultante (con tutte le trasformazioni di colore applicate). Imposta i colori RGB e cancella tutte le trasformazioni di colore. Lettura [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | Restituisce l'operazione di trasformazione colore applicata al colore all'indice specificato. Lettura/scrittura [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | Restituisce la collezione di trasformazioni colore applicate a un colore. Solo lettura [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | Restituisce il metodo di definizione colore. Lettura [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | Restituisce la componente blu di un colore. Tutte le trasformazioni di colore sono ignorate. Lettura **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | Restituisce la componente verde di un colore. Tutte le trasformazioni di colore sono ignorate. Lettura **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | Restituisce la componente rossa di un colore. Tutte le trasformazioni di colore sono ignorate. Lettura **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | Restituisce la componente verde di un colore. Tutte le trasformazioni di colore sono ignorate. Lettura **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | Restituisce la componente tonalità di un colore nella rappresentazione HSL. Tutte le trasformazioni di colore sono ignorate. Lettura **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | Restituisce la componente luminanza di un colore nella rappresentazione HSL. Tutte le trasformazioni di colore sono ignorate. Lettura **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | Restituisce il preset colore. Lettura [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | Restituisce la componente rossa di un colore. Tutte le trasformazioni di colore sono ignorate. Lettura **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | Restituisce la componente saturazione di un colore nella rappresentazione HSL. Tutte le trasformazioni di colore sono ignorate. Lettura **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | Restituisce il colore identificato da uno schema colore. Lettura [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | Restituisce il colore identificato dalla tabella colori di sistema. Lettura [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione per copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione per copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| virtual void [set_B](./set_b/)(**uint8_t**) | Imposta la componente blu di un colore. Tutte le trasformazioni di colore sono ignorate. Scrittura **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | Restituisce il colore risultante (con tutte le trasformazioni di colore applicate). Imposta i colori RGB e cancella tutte le trasformazioni di colore. Scrittura [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | Imposta l'operazione di trasformazione colore applicata al colore all'indice specificato. Lettura/scrittura [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | Imposta il metodo di definizione colore. Scrittura [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | Imposta la componente blu di un colore. Tutte le trasformazioni di colore sono ignorate. Scrittura **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | Imposta la componente verde di un colore. Tutte le trasformazioni di colore sono ignorate. Scrittura **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | Imposta la componente rossa di un colore. Tutte le trasformazioni di colore sono ignorate. Scrittura **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | Imposta la componente verde di un colore. Tutte le trasformazioni di colore sono ignorate. Scrittura **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | Imposta la componente tonalità di un colore nella rappresentazione HSL. Tutte le trasformazioni di colore sono ignorate. Scrittura **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | Imposta la componente luminanza di un colore nella rappresentazione HSL. Tutte le trasformazioni di colore sono ignorate. Scrittura **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | Imposta il preset colore. Scrittura [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | Imposta la componente rossa di un colore. Tutte le trasformazioni di colore sono ignorate. Scrittura **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | Imposta la componente saturazione di un colore nella rappresentazione HSL. Tutte le trasformazioni di colore sono ignorate. Scrittura **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | Imposta il colore identificato da uno schema colore. Scrittura [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | Imposta il colore identificato dalla tabella colori di sistema. Scrittura [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento modello come puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | Restituisce un [System::String](../../system/string/) che rappresenta il formato colore corrente. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruttura C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IFillParamSource](../ifillparamsource/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)