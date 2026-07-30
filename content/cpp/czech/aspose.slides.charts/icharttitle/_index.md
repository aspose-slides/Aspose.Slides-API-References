---
title: IChartTitle
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Reprezentuje vlastnosti názvu grafu.
type: docs
weight: 911
url: /cs/aspose.slides.charts/icharttitle/
---
## IChartTitle třída


Represents chart title properties.

```cpp
class IChartTitle : public Aspose::Slides::Charts::ILayoutable,
                    public Aspose::Slides::Charts::IOverridableText,
                    public Aspose::Slides::Charts::IActualLayout
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Inicializuje TextFrameForOverriding textem v parametru "text". Pokud je TextFrameForOverriding již inicializován, pak jednoduše změní jeho text. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Určuje skutečnou výšku prvku grafu. Před voláním zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/), abyste získali skutečné hodnoty. Čte **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Určuje skutečnou šířku prvku grafu. Před voláním zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/), abyste získali skutečné hodnoty. Čte **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Určuje skutečnou polohu x (vlevo) prvku grafu relativně k levému hornímu rohu grafu. Před voláním zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/), abyste získali skutečné hodnoty. Čte **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Určuje skutečnou horní pozici prvku grafu relativně k levému hornímu rohu grafu. Před voláním zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/), abyste získali skutečné hodnoty. Čte **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Získá horní část prvku grafu jako zlomek výšky grafu. Pouze pro čtení **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Vrací graf. Pouze pro čtení [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Vrací výplň, čáru, efektní styly názvu. Pouze pro čtení [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Určuje výšku prvku grafu jako zlomek výšky grafu. Čte **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Určuje, zda jiné prvky grafu mohou překrývat název. Čte **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Vrací prezentaci. Pouze pro čtení [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Získá pravou část prvku grafu jako zlomek šířky grafu. Pouze pro čtení **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Vrací základní snímek. Pouze pro čtení [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Vrací formát textu grafu. Pouze pro čtení [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Může obsahovat bohatě formátovaný text. Pokud není tato vlastnost null, pak tato hodnota formátovaného textu přepíše automaticky generovaný text. Automaticky generovaný text je implicitní vlastností datového popisku, popisku jednotky zobrazení osy hodnot, názvu osy, názvu grafu, popisku trendové čáry. Automaticky generovaný text je formátován pomocí vlastnosti [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Pouze pro čtení [ITextFrame](../../aspose.slides/itextframe/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Určuje šířku prvku grafu jako zlomek šířky grafu. Čte **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Určuje polohu x (vlevo) prvku grafu jako zlomek šířky grafu. Čte **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Určuje horní část prvku grafu jako zlomek výšky grafu. Čte **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie k metodě C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie k volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie k operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání podle C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie k metodě C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje konstrukci kopií podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Přiřazovací operátor. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje konstrukci kopií podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží počítadlo sdílených odkazů o zadanou hodnotu. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Určuje výšku prvku grafu jako zlomek výšky grafu. Zapíše **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Určuje, zda jiné prvky grafu mohou překrývat název. Zapíše **bool**. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Určuje šířku prvku grafu jako zlomek šířky grafu. Zapíše **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Určuje polohu x (vlevo) prvku grafu jako zlomek šířky grafu. Zapíše **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Určuje horní část prvku grafu jako zlomek výšky grafu. Zapíše **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu počítadla sdílených odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší počítadlo sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí počítadlo sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie k metodě C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání podle C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší počítadlo slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží počítadlo slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [ILayoutable](../ilayoutable/)
* Třída [IOverridableText](../ioverridabletext/)
* Třída [IActualLayout](../iactuallayout/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)