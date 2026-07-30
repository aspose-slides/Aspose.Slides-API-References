---
title: ILegend
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje vlastnosti legendy grafu.
type: docs
weight: 1080
url: /cs/aspose.slides.charts/ilegend/
---
## ILegend třída

Reprezentuje vlastnosti legendy grafu.

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) semantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Určuje skutečnou výšku prvku grafu. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/), abyste získali skutečné hodnoty. Čte **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Určuje skutečnou šířku prvku grafu. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/), abyste získali skutečné hodnoty. Čte **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Určuje skutečnou x polohu (levý okraj) prvku grafu vzhledem k levému hornímu rohu grafu. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/), abyste získali skutečné hodnoty. Čte **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Určuje skutečný horní okraj prvku grafu vzhledem k levému hornímu rohu grafu. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/), abyste získali skutečné hodnoty. Čte **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Získává horní okraj prvku grafu jako část výšky grafu. Pouze pro čtení **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Vrací graf. Pouze pro čtení [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | Získává položky legendy. Pouze pro čtení [ILegendEntryCollection](../ilegendentrycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | Získá vlastnosti položky legendy odpovídající datovému bodu v grafu na zadaném indexu. Pro typy grafů: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, je datový bod převzat z první řady. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Vrací formát legendy. Pouze pro čtení [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Určuje výšku prvku grafu jako část výšky grafu. Čte **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Určuje, zda mají být ostatním prvkům grafu povoleny překrývat legendu. Čte **bool**. |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | Určuje polohu legendy v grafu. Hodnoty X, Y, Width, Heigt, které nejsou NaN, přebijí účinek této vlastnosti. Čte [LegendPositionType](../legendpositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Vrací prezentaci. Pouze pro čtení [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Získává pravý okraj prvku grafu jako část šířky grafu. Pouze pro čtení **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Vrací základní snímek. Pouze pro čtení [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Vrací formát textu grafu. Pouze pro čtení [IChartTextFormat](../icharttextformat/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Určuje šířku prvku grafu jako část šířky grafu. Čte **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Určuje x polohu (levý okraj) prvku grafu jako část šířky grafu. Čte **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Určuje horní okraj prvku grafu jako část výšky grafu. Čte **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Určuje výšku prvku grafu jako část výšky grafu. Zapíše **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Určuje, zda mají být ostatním prvkům grafu povoleny překrývat legendu. Zapíše **bool**. |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | Určuje polohu legendy v grafu. Hodnoty X, Y, Width, Heigt, které nejsou NaN, přebijí účinek této vlastnosti. Zapíše [LegendPositionType](../legendpositiontype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Určuje šířku prvku grafu jako část šířky grafu. Zapíše **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Určuje x polohu (levý okraj) prvku grafu jako část šířky grafu. Zapíše **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Určuje horní okraj prvku grafu jako část výšky grafu. Zapíše **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (místo sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [ILayoutable](../ilayoutable/)
* Třída [IFormattedTextContainer](../iformattedtextcontainer/)
* Třída [IActualLayout](../iactuallayout/)
* Prostor názvů [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)