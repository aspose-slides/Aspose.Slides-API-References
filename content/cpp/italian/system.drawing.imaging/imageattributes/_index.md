---
title: ImageAttributes
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta informazioni su come i colori dell'immagine vengono manipolati durante il rendering. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 105
url: /it/system.drawing.imaging/imageattributes/
---
## ImageAttributes classe

Rappresenta informazioni su come i colori dell'immagine vengono manipolati durante il rendering. Gli oggetti di questa classe dovrebbero essere allocati solo utilizzando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class ImageAttributes : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [ClearBrushRemapTable](./clearbrushremaptable/)() | NON IMPLEMENTATO. |
| void [ClearColorKey](./clearcolorkey/)([ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| void [ClearColorMatrix](./clearcolormatrix/)([ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| void [ClearGamma](./cleargamma/)([ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| void [ClearNoOp](./clearnoop/)([ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| void [ClearOutputChannel](./clearoutputchannel/)([ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| void [ClearOutputChannelColorProfile](./clearoutputchannelcolorprofile/)([ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| void [ClearRemapTable](./clearremaptable/)([ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| void [ClearThreshold](./clearthreshold/)([ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| [SharedPtr](../../system/sharedptr/)\<[ImageAttributes](./)\> [Clone](./clone/)() | Crea una copia dell'oggetto corrente. |
| void [Dispose](./dispose/)() | Rilascia tutte le risorse del sistema operativo acquisite dall'oggetto corrente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo reference in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per usi interni. |
| void [GetAdjustedPalette](./getadjustedpalette/)(const [SharedPtr](../../system/sharedptr/)\<[ColorPalette](../colorpalette/)\>\&, [ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ImageAttributes](./imageattributes/)() | Costruttore predefinito. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la copia dei sottoclasse. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la copia dei sottoclasse. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso di un valore specificato. |
| void [SetBrushRemapTable](./setbrushremaptable/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[ColorMap](../colormap/)\>\>\&) | NON IMPLEMENTATO. |
| void [SetColorKey](./setcolorkey/)([Color](../../system.drawing/color/), [Color](../../system.drawing/color/), [ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| void [SetColorMatrices](./setcolormatrices/)(const [SharedPtr](../../system/sharedptr/)\<[ColorMatrix](../colormatrix/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[ColorMatrix](../colormatrix/)\>\&, [ColorMatrixFlag](../colormatrixflag/), [ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| void [SetColorMatrix](./setcolormatrix/)(const [SharedPtr](../../system/sharedptr/)\<[ColorMatrix](../colormatrix/)\>\&, [ColorMatrixFlag](../colormatrixflag/), [ColorAdjustType](../coloradjusttype/)) | Imposta la matrice di correzione del colore. |
| void [SetGamma](./setgamma/)(**float**, [ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| void [SetNoOp](./setnoop/)([ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| void [SetOutputChannel](./setoutputchannel/)([ColorChannelFlag](../colorchannelflag/), [ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| void [SetOutputChannelColorProfile](./setoutputchannelcolorprofile/)(const [String](../../system/string/)\&, [ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| void [SetRemapTable](./setremaptable/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[ColorMap](../colormap/)\>\>\&, [ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (invece che condiviso). Consente di passare i puntatori nei contenitori in modalità debole. |
| void [SetThreshold](./setthreshold/)(**float**, [ColorAdjustType](../coloradjusttype/)) | NON IMPLEMENTATO. |
| void [SetWrapMode](./setwrapmode/)([Drawing2D::WrapMode](../../system.drawing.drawing2d/wrapmode/), [Color](../../system.drawing/color/), **bool**) | Imposta la modalità di avvolgimento e il colore usati per decidere come ripetere una texture su una forma, o ai bordi della forma. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Libreria [Aspose.Slides](../../)