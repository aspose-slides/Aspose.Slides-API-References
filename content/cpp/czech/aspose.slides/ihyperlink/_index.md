---
title: IHyperlink
second_title: Aspose.Slides pro C++ – reference API
description: Reprezentuje hypertextový odkaz.
type: docs
weight: 2523
url: /cs/aspose.slides/ihyperlink/
---
## IHyperlink třída

Reprezentuje hypertextový odkaz.

```cpp
class IHyperlink : public virtual System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) semantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnoty ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání čísel s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání čísel s dvojitou přesností ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() | Vrací typ akce HyperLinkEx. Pouze pro čtení [HyperlinkActionType](../hyperlinkactiontype/). |
| virtual [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() | Zastupuje zdroj barvy hypertextového odkazu – buď styly nebo formátování úseku. Pouze pro čtení [HyperlinkColorSource](../hyperlinkcolorsource/). |
| virtual [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() | Určuje externí URL. Pokud se tato vlastnost stane nenulovou, pak se vlastnost TargetSlide stane nulovou. Pouze pro čtení [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() | Zastupuje hypertextový odkaz, který je nastaven pro tento úsek bez ohledu na skutečný obsah úseku. |
| virtual **bool** [get_HighlightClick](./get_highlightclick/)() | Určuje, zda by měl být hypertextový odkaz zvýrazněn po kliknutí. Pouze pro čtení **bool**. |
| virtual **bool** [get_History](./get_history/)() | Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán na seznam zobrazených odkazů při jeho vyvolání. Pouze pro čtení **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | Zastupuje přehrávaný zvuk hypertextového odkazu. Pouze pro čtení [IAudio](../iaudio/). |
| virtual **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() | Určuje, zda by měl být zvuk zastaven při kliknutí na hypertextový odkaz. Pouze pro čtení **bool**. |
| virtual [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() | Vrací rámec v nadřazeném HTML framesetu pro cíl nadřazeného hypertextového odkazu, pokud existuje. Pouze pro čtení [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() | Pokud HyperlinkEx cílí na konkrétní snímek, vrátí tento snímek. Pokud se vlastnost stane nenulovou, pak se vlastnost ExternalUrl stane nulovou. Pouze pro čtení [ISlide](../islide/). |
| virtual [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() | Vrací řetězec, který může být zobrazen v uživatelském rozhraní jako související s nadřazeným hypertextovým odkazem. Pouze pro čtení [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu referenčního čítače spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného cílovým typem. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Volat přímo nebo použít hlídkový objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Neprovádí žádné kopírování, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Neprovádí žádné kopírování, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený referenční čítač o zadanou hodnotu. |
| virtual void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) | Zastupuje zdroj barvy hypertextového odkazu – buď styly nebo formát úseku. Zapisovat [HyperlinkColorSource](../hyperlinkcolorsource/). |
| virtual void [set_HighlightClick](./set_highlightclick/)(**bool**) | Určuje, zda by měl být hypertextový odkaz zvýrazněn po kliknutí. Zapisovat **bool**. |
| virtual void [set_History](./set_history/)(**bool**) | Určuje, zda má být cíl nadřazeného hypertextového odkazu přidán na seznam zobrazených odkazů při jeho vyvolání. Zapisovat **bool**. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Zastupuje přehrávaný zvuk hypertextového odkazu. Zapisovat [IAudio](../iaudio/). |
| virtual void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) | Určuje, zda by měl být zvuk zastaven při kliknutí na hypertextový odkaz. Zapisovat **bool**. |
| virtual void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) | Vrací rámec v nadřazeném HTML framesetu pro cíl nadřazeného hypertextového odkazu, pokud existuje. Zapisovat [System::String](../../system/string/). |
| virtual void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) | Vrací řetězec, který může být zobrazen v uživatelském rozhraní jako související s nadřazeným hypertextovým odkazem. Zapisovat [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (místo sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Volat přímo nebo použít hlídkový objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)