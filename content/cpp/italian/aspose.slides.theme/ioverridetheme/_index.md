---
title: IOverrideTheme
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un tema di sovrascrittura.
type: docs
weight: 391
url: /it/aspose.slides.theme/ioverridetheme/
---
## IOverrideTheme classe


Rappresenta un tema di sovrascrittura.

```cpp
class IOverrideTheme : public virtual Aspose::Slides::Theme::ITheme
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual void [Clear](./clear/)() | Imposta [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/) a null per disabilitare qualsiasi sovrascrittura con questo oggetto tema. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ColorFormat](../itheme/get_colorformat/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\> [get_ColorScheme](../itheme/get_colorscheme/)() | Restituisce lo schema dei colori. Solo lettura [IColorScheme](../icolorscheme/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\> [get_FontScheme](../itheme/get_fontscheme/)() | Restituisce lo schema dei caratteri. Solo lettura [IFontScheme](../ifontscheme/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\> [get_FormatScheme](../itheme/get_formatscheme/)() | Restituisce lo schema di formattazione delle forme. Solo lettura [IFormatScheme](../iformatscheme/). |
| virtual **bool** [get_IsEmpty](./get_isempty/)() | Un valore vero indica che [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/) sono null e qualsiasi sovrascrittura con questo oggetto tema è disabilitata. Solo lettura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Restituisce la presentazione. Solo lettura [IPresentation](../../aspose.slides/ipresentation/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../ithemeeffectivedata/)\> [GetEffective](../itheme/geteffective/)() | Ottiene i dati del tema effettivo con l'ereditarietà applicata. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [InitColorScheme](./initcolorscheme/)() | Inizializza [ColorScheme](../colorscheme/) con un nuovo oggetto per sovrascrivere [ColorScheme](../colorscheme/) di InheritedTheme. |
| virtual void [InitColorSchemeFrom](./initcolorschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\>) | Inizializza [ColorScheme](../colorscheme/) con un nuovo oggetto per sovrascrivere [ColorScheme](../colorscheme/) di InheritedTheme. |
| virtual void [InitColorSchemeFromInherited](./initcolorschemefrominherited/)() | Inizializza [ColorScheme](../colorscheme/) con un nuovo oggetto per sovrascrivere [ColorScheme](../colorscheme/) di InheritedTheme. E inizializza i dati di questo nuovo oggetto con i dati del [ColorScheme](../colorscheme/) di InheritedTheme. |
| virtual void [InitFontScheme](./initfontscheme/)() | Inizializza [FontScheme](../fontscheme/) con un nuovo oggetto per sovrascrivere [FontScheme](../fontscheme/) di InheritedTheme. |
| virtual void [InitFontSchemeFrom](./initfontschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\>) | Inizializza [FontScheme](../fontscheme/) con un nuovo oggetto per sovrascrivere [FontScheme](../fontscheme/) di InheritedTheme. |
| virtual void [InitFontSchemeFromInherited](./initfontschemefrominherited/)() | Inizializza [FontScheme](../fontscheme/) con un nuovo oggetto per sovrascrivere [FontScheme](../fontscheme/) di InheritedTheme. E inizializza i dati di questo nuovo oggetto con i dati del [FontScheme](../fontscheme/) di InheritedTheme. |
| virtual void [InitFormatScheme](./initformatscheme/)() | Inizializza [FormatScheme](../formatscheme/) con un nuovo oggetto per sovrascrivere [FormatScheme](../formatscheme/) di InheritedTheme. |
| virtual void [InitFormatSchemeFrom](./initformatschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\>) | Inizializza [FormatScheme](../formatscheme/) con un nuovo oggetto per sovrascrivere [FormatScheme](../formatscheme/) di InheritedTheme. |
| virtual void [InitFormatSchemeFromInherited](./initformatschemefrominherited/)() | Inizializza [FormatScheme](../formatscheme/) con un nuovo oggetto per sovrascrivere [FormatScheme](../formatscheme/) di InheritedTheme. E inizializza i dati di questo nuovo oggetto con i dati del [FormatScheme](../formatscheme/) di InheritedTheme. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento oggetti di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento del template come puntatore debole (anziché condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare i puntatori intelligenti o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare i puntatori intelligenti o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare i puntatori intelligenti o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare i puntatori intelligenti o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [ITheme](../itheme/)
* Spazio dei nomi [Aspose::Slides::Theme](../)
* Libreria [Aspose.Slides](../../)