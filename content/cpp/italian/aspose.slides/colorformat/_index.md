---
title: ColorFormat
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un colore utilizzato in una presentazione.
type: docs
weight: 339
url: /it/aspose.slides/colorformat/
---
## ColorFormat classe

Rappresenta un colore utilizzato in una presentazione.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | Copia il formato colore da \"color\". |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Verifica l'uguaglianza con l'oggetto specificato. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| **uint8_t** [get_B](./get_b/)() override | Restituisce il componente blu di un colore. Tutte le trasformazioni colore sono ignorate. Lettura **uint8_t**. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | Restituisce il colore risultante (con tutte le trasformazioni colore applicate). Imposta i colori RGB e cancella tutte le trasformazioni colore. Lettura [System::Drawing::Color](../../system.drawing/color/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | Restituisce l'operazione di trasformazione colore applicata al colore all'indice specificato. Lettura/scrittura [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | Restituisce la collezione di trasformazioni colore applicate a un colore. Sola lettura [IColorOperationCollection](../icoloroperationcollection/). |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | Restituisce il metodo di definizione colore. Lettura [Slides::ColorType](../colortype/). |
| **float** [get_FloatB](./get_floatb/)() override | Restituisce il componente blu di un colore. Tutte le trasformazioni colore sono ignorate. Lettura **float**. |
| **float** [get_FloatG](./get_floatg/)() override | Restituisce il componente verde di un colore. Tutte le trasformazioni colore sono ignorate. Lettura **float**. |
| **float** [get_FloatR](./get_floatr/)() override | Restituisce il componente rosso di un colore. Tutte le trasformazioni colore sono ignorate. Lettura **float**. |
| **uint8_t** [get_G](./get_g/)() override | Restituisce il componente verde di un colore. Tutte le trasformazioni colore sono ignorate. |
| **float** [get_Hue](./get_hue/)() override | Restituisce il componente tonalità di un colore in rappresentazione HSL. Tutte le trasformazioni colore sono ignorate. Lettura **float**. |
| **float** [get_Luminance](./get_luminance/)() override | Restituisce il componente luminanza di un colore in rappresentazione HSL. Tutte le trasformazioni colore sono ignorate. Lettura **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Restituisce l'oggetto Parent_Immediate. Sola lettura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Restituisce il genitore [IPresentationComponent](../ipresentationcomponent/). Sola lettura [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | Restituisce il preset colore. Lettura [Slides::PresetColor](../presetcolor/). |
| **uint8_t** [get_R](./get_r/)() override | Restituisce il componente rosso di un colore. Tutte le trasformazioni colore sono ignorate. Lettura **uint8_t**. |
| **float** [get_Saturation](./get_saturation/)() override | Restituisce il componente saturazione di un colore in rappresentazione HSL. Tutte le trasformazioni colore sono ignorate. Lettura **float**. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | Restituisce il colore identificato da uno schema colore. Lettura [Slides::SchemeColor](../schemecolor/). |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | Restituisce il colore identificato dalla tabella colori di sistema. Lettura [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e consente la copia dei sottotipi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, solo inizializza un nuovo oggetto e consente la copia dei sottotipi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [set_B](./set_b/)(**uint8_t**) override | Imposta il componente blu di un colore. Tutte le trasformazioni colore sono ignorate. Scrittura **uint8_t**. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | Imposta il colore risultante (con tutte le trasformazioni colore applicate). Imposta i colori RGB e cancella tutte le trasformazioni colore. Scrittura [System::Drawing::Color](../../system.drawing/color/). |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | Imposta l'operazione di trasformazione colore applicata al colore all'indice specificato. Lettura/scrittura [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | Imposta il metodo di definizione colore. Scrittura [Slides::ColorType](../colortype/). |
| void [set_FloatB](./set_floatb/)(**float**) override | Imposta il componente blu di un colore. Tutte le trasformazioni colore sono ignorate. Scrittura **float**. |
| void [set_FloatG](./set_floatg/)(**float**) override | Imposta il componente verde di un colore. Tutte le trasformazioni colore sono ignorate. Scrittura **float**. |
| void [set_FloatR](./set_floatr/)(**float**) override | Imposta il componente rosso di un colore. Tutte le trasformazioni colore sono ignorate. Scrittura **float**. |
| void [set_G](./set_g/)(**uint8_t**) override | Imposta il componente verde di un colore. Tutte le trasformazioni colore sono ignorate. |
| void [set_Hue](./set_hue/)(**float**) override | Imposta il componente tonalità di un colore in rappresentazione HSL. Tutte le trasformazioni colore sono ignorate. Scrittura **float**. |
| void [set_Luminance](./set_luminance/)(**float**) override | Imposta il componente luminanza di un colore in rappresentazione HSL. Tutte le trasformazioni colore sono ignorate. Scrittura **float**. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | Imposta il preset colore. Scrittura [Slides::PresetColor](../presetcolor/). |
| void [set_R](./set_r/)(**uint8_t**) override | Imposta il componente rosso di un colore. Tutte le trasformazioni colore sono ignorate. Scrittura **uint8_t**. |
| void [set_Saturation](./set_saturation/)(**float**) override | Imposta il componente saturazione di un colore in rappresentazione HSL. Tutte le trasformazioni colore sono ignorate. Scrittura **float**. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | Imposta il colore identificato da uno schema colore. Scrittura [Slides::SchemeColor](../schemecolor/). |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | Imposta il colore identificato dalla tabella colori di sistema. Scrittura [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un weak pointer (piuttosto che shared). Consente di passare i puntatori nei contenitori a modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | Restituisce un [System::String](../../system/string/) che rappresenta il formato colore corrente. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente di convertire oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa il blocco lock() di C# sbloccando. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [PVIObject](../pviobject/)
* Classe [IColorFormat](../icolorformat/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)