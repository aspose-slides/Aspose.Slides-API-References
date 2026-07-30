---
title: IOuterShadow
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta un effetto Ombra Esterna.
type: docs
weight: 885
url: /it/aspose.slides.effects/ioutershadow/
---
## IOuterShadow classe


Rappresenta un effetto Ombra Esterna.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## Methods

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) raggio, in punti. Valore predefinito \u2013 0 pt. Legge **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Direzione dell'ombra, in gradi. Valore predefinito \u2013 0 \u00B0 (da sinistra a destra). Legge **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Distanza dell'ombra dall'oggetto, in punti. Valore predefinito \u2013 0 pt. Legge **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Allineamento del rettangolo. Valore predefinito \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Legge [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Indica se l'ombra ruota insieme alla forma. Valore predefinito \u2013 true. Legge **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Fattore di scala orizzontale, in percentuale della dimensione originale. Una scala negativa provoca un ribaltamento. Valore predefinito \u2013 100 %. Legge **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Fattore di scala verticale, in percentuale della dimensione originale. Una scala negativa provoca un ribaltamento. Valore predefinito \u2013 100 %. Legge **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | Colore dell'ombra. Valore predefinito \u2013 nero automatico (dipendente dal tema). Solo lettura [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Angolo di inclinazione orizzontale, in gradi. Valore predefinito \u2013 0 \u00B0. Legge **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Angolo di inclinazione verticale, in gradi. Valore predefinito \u2013 0 \u00B0. Legge **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Ottiene i dati effettivi con l'ereditarietà applicata. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie di sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie di sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) raggio, in punti. Valore predefinito \u2013 0 pt. Scrive **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Direzione dell'ombra, in gradi. Valore predefinito \u2013 0 \u00B0 (da sinistra a destra). Scrive **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Distanza dell'ombra dall'oggetto, in punti. Valore predefinito \u2013 0 pt. Scrive **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Allineamento del rettangolo. Valore predefinito \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Scrive [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Indica se l'ombra ruota insieme alla forma. Valore predefinito \u2013 true. Scrive **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Fattore di scala orizzontale, in percentuale della dimensione originale. Una scala negativa provoca un ribaltamento. Valore predefinito \u2013 100 %. Scrive **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Fattore di scala verticale, in percentuale della dimensione originale. Una scala negativa provoca un ribaltamento. Valore predefinito \u2013 100 %. Scrive **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Angolo di inclinazione orizzontale, in gradi. Valore predefinito \u2013 0 \u00B0. Scrive **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Angolo di inclinazione verticale, in gradi. Valore predefinito \u2013 0 \u00B0. Scrive **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n'th argomento del template a un puntatore debole (invece di condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
## Vedi anche

* Classe [IImageTransformOperation](../iimagetransformoperation/)
* Classe [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Spazio dei nomi [Aspose::Slides::Effects](../)
* Libreria [Aspose.Slides](../../)