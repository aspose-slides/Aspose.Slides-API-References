---
title: Reflection
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un effetto Reflection.
type: docs
weight: 1067
url: /it/aspose.slides.effects/reflection/
---
## Reflection classe

Rappresenta un effetto [Reflection](./).

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## Metodi

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Determina se il [Reflection](./) specificato è uguale al [Reflection](./) corrente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) raggio. Leggi **double**. |
| **float** [get_Direction](./get_direction/)() override | Direzione del riflesso. Leggi **float**. |
| **double** [get_Distance](./get_distance/)() override | Distanza del riflesso. Leggi **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | Specifica la posizione finale (lungo la rampa del gradiente alfa) del valore alfa finale (percentuali). Leggi **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | Opacità finale del riflesso. (percentuali). Leggi **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | Specifica la direzione per spostare il riflesso. (angolo). Leggi **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Restituisce il [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) genitore. Solo lettura [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Allineamento rettangolo. Leggi [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Specifica se il riflesso deve ruotare con la forma se la forma è ruotata. Leggi **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Specificano il fattore di scala orizzontale, una scala negativa causa un ribaltamento. (percentuali) Leggi **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Specifica il fattore di scala verticale, una scala negativa causa un ribaltamento. (percentuali) Leggi **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Specifica l'angolo di inclinazione orizzontale. Leggi **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Specifica l'angolo di inclinazione verticale. Leggi **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | Specifica la posizione iniziale (lungo la rampa del gradiente alfa) del valore alfa iniziale (percentuali). Leggi **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | Opacità iniziale del riflesso. (percentuali). Leggi **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Versione. Solo lettura **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | Ottiene i dati effetto [Reflection](./) efficaci con l'ereditarietà applicata. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Funziona come funzione hash per un tipo specifico. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiama direttamente o usa l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente di clonare tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie di sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie di sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) raggio. Scrivi **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Direzione del riflesso. Scrivi **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Distanza del riflesso. Scrivi **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | Specifica la posizione finale (lungo la rampa del gradiente alfa) del valore alfa finale (percentuali). Scrivi **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | Opacità finale del riflesso. (percentuali). Scrivi **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | Specifica la direzione per spostare il riflesso. (angolo). Scrivi **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Allineamento rettangolo. Scrivi [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Specifica se il riflesso deve ruotare con la forma se la forma è ruotata. Scrivi **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Specifica il fattore di scala orizzontale, una scala negativa causa un ribaltamento. (percentuali) Scrivi **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Specifica il fattore di scala verticale, una scala negativa causa un ribaltamento. (percentuali) Scrivi **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Specifica l'angolo di inclinazione orizzontale. Scrivi **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Specifica l'angolo di inclinazione verticale. Scrivi **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | Specifica la posizione iniziale (lungo la rampa del gradiente alfa) del valore alfa iniziale (percentuali). Scrivi **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | Opacità iniziale del riflesso. (percentuali). Scrivi **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (invece di condiviso). Consente di passare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente di convertire oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiama direttamente o usa l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IReflection](../ireflection/)
* Classe [IVisualEffect](../ivisualeffect/)
* Classe [IPVIObject](../../aspose.slides/ipviobject/)
* Spazio dei nomi [Aspose::Slides::Effects](../)
* Libreria [Aspose.Slides](../../)