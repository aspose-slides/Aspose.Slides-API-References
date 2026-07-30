---
title: FontFamily
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un gruppo di caratteri tipografici che condividono un design di base simile. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò genererà errori di runtime e/o violazioni di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e utilizza questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 105
url: /it/system.drawing/fontfamily/
---
## classe FontFamily

Rappresenta un gruppo di caratteri tipografici che condividono un design di base simile. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o violazioni di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e utilizza questo puntatore per passarlo alle funzioni come argomento.

```cpp
class FontFamily : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [Clone](./clone/)() | Restituisce una copia dell'oggetto [FontFamily](./) corrente. |
| void [Dispose](./dispose/)() | Rilascia tutte le risorse del sistema operativo acquisite dall'oggetto corrente. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Determina se l'oggetto corrente e quello specificato sono identici. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
|  [FontFamily](./fontfamily/)(const [String](../../system/string/)\&) | Costruisce una nuova istanza della classe [FontFamily](./) che rappresenta una famiglia di font con il nome specificato. |
|  [FontFamily](./fontfamily/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::FontCollection](../../system.drawing.text/fontcollection/)\>\&) | Costruisce una nuova istanza di [FontFamily](./) nella FontCollection specificata con il nome specificato. |
|  [FontFamily](./fontfamily/)([Text::GenericFontFamilies](../../system.drawing.text/genericfontfamilies/)) | Costruisce una nuova istanza di [FontFamily](./) dalla famiglia di font generica specificata. |
| static [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\>\> [get_Families](./get_families/)() | Restituisce un array contenente tutti gli oggetti [FontFamily](./) associati al contesto grafico corrente. |
| static [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [get_GenericMonospace](./get_genericmonospace/)() | Restituisce un oggetto [FontFamily](./) che rappresenta una famiglia di font Monospace generica. |
| static [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [get_GenericSansSerif](./get_genericsansserif/)() | Restituisce un oggetto [FontFamily](./) che rappresenta una famiglia di font Sans Serif generica. |
| static [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [get_GenericSerif](./get_genericserif/)() | Restituisce un oggetto [FontFamily](./) che rappresenta una famiglia di font Serif generica. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Restituisce il nome della famiglia di font rappresentata dall'oggetto corrente. |
| int [GetCellAscent](./getcellascent/)([FontStyle](../fontstyle/)) | Restituisce l'ascesa della cella della famiglia di font rappresentata dall'oggetto corrente per lo stile di font specificato. |
| int [GetCellDescent](./getcelldescent/)([FontStyle](../fontstyle/)) | Restituisce la discesa della cella della famiglia di font rappresentata dall'oggetto corrente per lo stile di font specificato. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| int [GetEmHeight](./getemheight/)([FontStyle](../fontstyle/)) | Restituisce l'altezza della quadratura em in unità di progettazione del font per lo stile specificato. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| int [GetLineSpacing](./getlinespacing/)([FontStyle](../fontstyle/)) | Restituisce l'interlinea della famiglia di font rappresentata dall'oggetto corrente per lo stile di font specificato. |
| [String](../../system/string/) [GetName](./getname/)(int) const | Restituisce il nome della famiglia di font rappresentata dall'oggetto corrente. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| **bool** [IsStyleAvailable](./isstyleavailable/)([FontStyle](../fontstyle/)) | Determina se lo stile di font specificato è disponibile. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() della dichiarazione C#. Chiamalo direttamente o usa l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, ma inizializza un nuovo oggetto e consente la costruzione di copie delle subclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, ma inizializza un nuovo oggetto e consente la costruzione di copie delle subclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (invece di condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamalo direttamente o usa l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~FontFamily](./~fontfamily/)() | Distruttore. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../../system/object/)
* Spazio dei nomi [System::Drawing](../)
* Libreria [Aspose.Slides](../../)