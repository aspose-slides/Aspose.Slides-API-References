---
title: IReflection
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta un effetto di riflessione.
type: docs
weight: 937
url: /it/aspose.slides.effects/ireflection/
---
## IReflection classe

Rappresenta un effetto di riflessione.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) raggio. Leggi **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Direzione della riflessione. Leggi **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Distanza della riflessione. Leggi **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | Specifica la posizione finale (lungo la rampa del gradiente alpha) del valore alpha finale (percentuali). Leggi **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | Opacità finale della riflessione. (percentuali). Leggi **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | Specifica la direzione per traslare la riflessione. (angolo). Leggi **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Allineamento del rettangolo. Leggi [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Specifica se la riflessione deve ruotare con la forma quando la forma è ruotata. Leggi **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Specifica il fattore di scala orizzontale, una scala negativa provoca una inversione. (percentuali) Leggi **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Specifica il fattore di scala verticale, una scala negativa provoca una inversione. (percentuali) Leggi **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Specifica l'angolo di inclinazione orizzontale. Leggi **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Specifica l'angolo di inclinazione verticale. Leggi **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | Specifica la posizione iniziale (lungo la rampa del gradiente alpha) del valore alpha iniziale (percentuali). Leggi **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | Opacità iniziale della riflessione. (percentuali). Leggi **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Ottiene i dati effettivi con l'ereditarietà applicata. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione copia delle subclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione copia delle subclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi di un valore specificato. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) raggio. Scrivi **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Direzione della riflessione. Scrivi **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Distanza della riflessione. Scrivi **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | Specifica la posizione finale (lungo la rampa del gradiente alpha) del valore alpha finale (percentuali). Scrivi **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | Opacità finale della riflessione. (percentuali). Scrivi **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | Specifica la direzione per traslare la riflessione. (angolo). Scrivi **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Allineamento del rettangolo. Scrivi [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Specifica se la riflessione deve ruotare con la forma quando la forma è ruotata. Scrivi **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Specifica il fattore di scala orizzontale, una scala negativa provoca una inversione. (percentuali) Scrivi **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Specifica il fattore di scala verticale, una scala negativa provoca una inversione. (percentuali) Scrivi **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Specifica l'angolo di inclinazione orizzontale. Scrivi **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Specifica l'angolo di inclinazione verticale. Scrivi **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | Specifica la posizione iniziale (lungo la rampa del gradiente alpha) del valore alpha iniziale (percentuali). Scrivi **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | Opacità iniziale della riflessione. (percentuali). Scrivi **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
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

* Classe [IImageTransformOperation](../iimagetransformoperation/)
* Classe [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Namespace [Aspose::Slides::Effects](../)
* Libreria [Aspose.Slides](../../)