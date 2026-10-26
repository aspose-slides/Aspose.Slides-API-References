---
title: Legend
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje vlastnosti legendy grafu.
type: docs
weight: 1262
url: /cs/aspose.slides.charts/legend/
---
## Legend třída

Reprezentuje vlastnosti legendy grafu.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) semantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Určuje skutečnou výšku prvku grafu. Před získáním skutečných hodnot zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/). Čte se **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Určuje skutečnou šířku prvku grafu. Před získáním skutečných hodnot zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/). Čte se **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Určuje skutečnou souřadnici x (levý) prvku grafu relativně k levému hornímu rohu grafu. Před získáním skutečných hodnot zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/). Čte se **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Určuje skutečnou horní polohu prvku grafu relativně k levému hornímu rohu grafu. Před získáním skutečných hodnot zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/). Čte se **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Spodní část. Pouze pro čtení **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Vrací graf. Pouze pro čtení [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | Získává položky legendy. Pouze pro čtení [ILegendEntryCollection](../ilegendentrycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | Získá vlastnosti položky legendy odpovídající datovému bodu v grafu na zadaném indexu. V případě typů grafů: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, je datový bod převzat z první řady. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Vrací formát legendy. Pouze pro čtení [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Vrací výšku legendy jako podíl výšky grafu. Čte se **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Určuje, zda mají být ostatní prvky grafu povoleny překrývat legendu. Čte se **bool**. |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | Určuje umístění legendy v grafu. Hodnoty X, Y, Width, Heigt, které nejsou NaN, přepíší efekt této vlastnosti. Čte [LegendPositionType](../legendpositiontype/). |
| **float** [get_Right](./get_right/)() override | Pravá. Pouze pro čtení **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Formát textu. Pouze pro čtení [IChartTextFormat](../icharttextformat/). |
| **float** [get_Width](./get_width/)() override | Vrací šířku legendy jako podíl šířky grafu. Čte se **float**. |
| **float** [get_X](./get_x/)() override | Vrací souřadnici x legendy jako podíl šířky grafu. Čte se **float**. |
| **float** [get_Y](./get_y/)() override | Vrací souřadnici y legendy jako podíl výšky grafu. Čte se **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování uživatelských objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování uživatelských typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený počitadlo referencí o zadanou hodnotu. |
| void [set_Height](./set_height/)(**float**) override | Nastavuje výšku legendy jako podíl výšky grafu. Zapíše **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Určuje, zda mají být ostatní prvky grafu povoleny překrývat legendu. Zapíše **bool**. |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | Určuje umístění legendy v grafu. Hodnoty X, Y, Width, Heigt, které nejsou NaN, přepíší efekt této vlastnosti. Zapíše [LegendPositionType](../legendpositiontype/). |
| void [set_Width](./set_width/)(**float**) override | Nastavuje šířku legendy jako podíl šířky grafu. Zapíše **float**. |
| void [set_X](./set_x/)(**float**) override | Nastavuje souřadnici x legendy jako podíl šířky grafu. Zapíše **float**. |
| void [set_Y](./set_y/)(**float**) override | Nastavuje souřadnici y legendy jako podíl výšky grafu. Zapíše **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Nastaví n-tý typový argument na weak pointer (namísto shared). Umožňuje přepínání ukazatelů v kontejnerech do režimu weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počitadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílené počitadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílené počitadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod uživatelských objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počitadlo weak referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počitadlo weak referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niští objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [DomObject](../../aspose.slides/domobject/)
* Třída [ILegend](../ilegend/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)