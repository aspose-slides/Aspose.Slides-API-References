---
title: OuterShadow
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta un effetto Outer Shadow.
type: docs
weight: 1041
url: /it/aspose.slides.effects/outershadow/
---
## OuterShadow classe


Rappresenta un effetto Outer Shadow.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Determina se il [OuterShadow](./) specificato è uguale all'[OuterShadow](./) corrente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) raggio, in punti. Valore predefinito \\u2013 0 pt. Lettura **double**. |
| **float** [get_Direction](./get_direction/)() override | Direzione dell'ombra, in gradi. Valore predefinito \\u2013 0 \\u00B0 (da sinistra a destra). Lettura **float**. |
| **double** [get_Distance](./get_distance/)() override | Distanza dell'ombra dall'oggetto, in punti. Valore predefinito \\u2013 0 pt. Lettura **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Restituisce il [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) genitore. Solo lettura [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Allineamento del rettangolo. Valore predefinito \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Lettura [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Indica se l'ombra ruota insieme alla forma. Valore predefinito \\u2013 true. Lettura **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Fattore di scala orizzontale, in percentuale della dimensione originale. Una scala negativa provoca un ribaltamento. Valore predefinito \\u2013 100 %. Lettura **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Fattore di scala verticale, in percentuale della dimensione originale. Una scala negativa provoca un ribaltamento. Valore predefinito \\u2013 100 %. Lettura **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | Colore dell'ombra. Valore predefinito \\u2013 nero automatico (dipendente dal tema). Solo lettura [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Angolo di inclinazione orizzontale, in gradi. Valore predefinito \\u2013 0 \\u00B0. Lettura **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Angolo di inclinazione verticale, in gradi. Valore predefinito \\u2013 0 \\u00B0. Lettura **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Versione. Solo lettura **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | Ottiene i dati effettivi dell'effetto Outer Shadow con l'ereditarietà applicata. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Funziona come funzione hash per un tipo specifico. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) raggio, in punti. Valore predefinito \\u2013 0 pt. Scrittura **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Direzione dell'ombra, in gradi. Valore predefinito \\u2013 0 \\u00B0 (da sinistra a destra). Scrittura **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Distanza dell'ombra dall'oggetto, in punti. Valore predefinito \\u2013 0 pt. Scrittura **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Allineamento del rettangolo. Valore predefinito \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Scrittura [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Indica se l'ombra ruota insieme alla forma. Valore predefinito \\u2013 true. Scrittura **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Fattore di scala orizzontale, in percentuale della dimensione originale. Una scala negativa provoca un ribaltamento. Valore predefinito \\u2013 100 %. Scrittura **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Fattore di scala verticale, in percentuale della dimensione originale. Una scala negativa provoca un ribaltamento. Valore predefinito \\u2013 100 %. Scrittura **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Angolo di inclinazione orizzontale, in gradi. Valore predefinito \\u2013 0 \\u00B0. Scrittura **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Angolo di inclinazione verticale, in gradi. Valore predefinito \\u2013 0 \\u00B0. Scrittura **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento modello come puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IOuterShadow](../ioutershadow/)
* Classe [IVisualEffect](../ivisualeffect/)
* Classe [IPVIObject](../../aspose.slides/ipviobject/)
* Spazio dei nomi [Aspose::Slides::Effects](../)
* Libreria [Aspose.Slides](../../)