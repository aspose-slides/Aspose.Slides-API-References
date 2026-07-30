---
title: AdjustableArrowCap
second_title: Aspose.Slides per C++ Riferimento API
description: "Rappresenta un cappuccio di linea a forma di freccia regolabile. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o violazioni di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e utilizza questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 1
url: /it/system.drawing.drawing2d/adjustablearrowcap/
---
## AdjustableArrowCap classe

Rappresenta un cappuccio di linea a forma di freccia regolabile. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o violazioni di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class AdjustableArrowCap : public System::Drawing::Drawing2D::CustomLineCap
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [AdjustableArrowCap](./adjustablearrowcap/)(**float**, **float**, **bool**) | Costruisce una nuova istanza di [AdjustableArrowCap](./) con la larghezza e l'altezza specificate. |
| virtual [SharedPtr](../../system/sharedptr/)\<[CustomLineCap](../customlinecap/)\> [Clone](../customlinecap/clone/)() | Restituisce una copia dell'oggetto corrente. |
|  [CustomLineCap](../customlinecap/customlinecap/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, [LineCap](../linecap/), **float**) | Costruisce una nuova istanza della classe [CustomLineCap](../customlinecap/) che rappresenta un cappuccio di linea definito dall'utente con le proprietà specificate. |
| void [Dispose](../customlinecap/dispose/)() | Rilascia tutte le risorse del sistema operativo acquisite dall'oggetto corrente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [LineCap](../linecap/) [get_BaseCap](../customlinecap/get_basecap/)() const | Restituisce il cappuccio di linea base da cui è stato creato questo cappuccio personalizzato. |
| **float** [get_BaseInset](../customlinecap/get_baseinset/)() const | Restituisce la distanza tra la linea e il cappuccio. |
| **bool** [get_Filled](./get_filled/)() const | Restituisce un valore che indica se la freccia rappresentata dall'oggetto corrente è piena. |
| **float** [get_Height](./get_height/)() const | Restituisce l'altezza della freccia rappresentata dall'oggetto corrente. |
| **float** [get_MiddleInset](./get_middleinset/)() const | Imposta la distanza tra la linea e il cappuccio rappresentato dall'oggetto corrente. |
| [LineJoin](../linejoin/) [get_StrokeJoin](../customlinecap/get_strokejoin/)() const | Restituisce il valore LineJoin che determina come le linee di questo cappuccio personalizzato sono unite. |
| **float** [get_Width](./get_width/)() const | Restituisce la larghezza della freccia rappresentata dall'oggetto corrente. |
| **float** [get_WidthScale](../customlinecap/get_widthscale/)() const | Restituisce la scala di questo cappuccio personalizzato. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| void [GetStrokeCaps](../customlinecap/getstrokecaps/)([LineCap](../linecap/)\&, [LineCap](../linecap/)\&) | Ottiene i cappucci di linea iniziale e finale del cappuccio personalizzato rappresentato dall'oggetto corrente. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, realmente, ma inizializza un nuovo oggetto e abilita la costruzione per copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, realmente, ma inizializza un nuovo oggetto e abilita la costruzione per copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [set_BaseCap](../customlinecap/set_basecap/)([LineCap](../linecap/)) | Imposta il valore del cappuccio di linea base per questo cappuccio personalizzato. |
| void [set_BaseInset](../customlinecap/set_baseinset/)(**float**) | Imposta la distanza tra la linea e il cappuccio. |
| void [set_Filled](./set_filled/)(**bool**) | Imposta un valore che specifica se la freccia rappresentata dall'oggetto corrente è piena. |
| void [set_Height](./set_height/)(**float**) | Imposta l'altezza della freccia rappresentata dall'oggetto corrente. |
| void [set_MiddleInset](./set_middleinset/)(**float**) | Imposta la distanza tra la linea e il cappuccio rappresentato dall'oggetto corrente. |
| void [set_StrokeJoin](../customlinecap/set_strokejoin/)([LineJoin](../linejoin/)) | Imposta il valore LineJoin che determina come le linee di questo cappuccio personalizzato sono unite. |
| void [set_Width](./set_width/)(**float**) | Imposta la larghezza della freccia rappresentata dall'oggetto corrente. |
| void [set_WidthScale](../customlinecap/set_widthscale/)(**float**) | Imposta il valore di scala di questo cappuccio personalizzato. |
| void [SetStrokeCaps](../customlinecap/setstrokecaps/)([LineCap](../linecap/), [LineCap](../linecap/)) | Imposta i cappucci di linea iniziale e finale del cappuccio personalizzato rappresentato dall'oggetto corrente. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (invece di condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [CustomLineCap](../customlinecap/)
* Spazio dei nomi [System::Drawing::Drawing2D](../)
* Libreria [Aspose.Slides](../../)