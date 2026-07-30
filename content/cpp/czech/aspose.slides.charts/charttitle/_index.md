---
title: ChartTitle
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Reprezentuje vlastnosti titulku grafu.
type: docs
weight: 326
url: /cs/aspose.slides.charts/charttitle/
---
## ChartTitle třída


Reprezentuje vlastnosti titulku grafu.

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## Metody

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inicializuje TextFrameForOverriding pomocí textu v parametru "text". Pokud je TextFrameForOverriding již inicializováno, jednoduše změní jeho text. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Určuje skutečnou výšku prvku grafu. Před získáním skutečných hodnot zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/). Čte se **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Určuje skutečnou šířku prvku grafu. Před získáním skutečných hodnot zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/). Čte se **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Určuje skutečnou horizontální polohu (vlevo) prvku grafu relativně k levému hornímu rohu grafu. Před získáním skutečných hodnot zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/). Čte se **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Určuje skutečný horní okraj prvku grafu relativně k levému hornímu rohu grafu. Před získáním skutečných hodnot zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/). Čte se **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Spodní okraj. Pouze pro čtení **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Vrací nadřazený graf. Pouze pro čtení [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Vrací styly výplně, čáry a efektu titulku. Pouze pro čtení [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Vrací výšku titulku jako podíl výšky grafu. Čte se **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Určuje, zda jiné prvky grafu smí překrývat titulek. Čte se **bool**. |
| **float** [get_Right](./get_right/)() override | Vpravo. Pouze pro čtení **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Vrací formát textu. Pouze pro čtení [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Může obsahovat bohatě formátovaný text. Pokud není tato vlastnost null, hodnota tohoto formátovaného textu přepíše automaticky generovaný text. Automaticky generovaný text je implicitní vlastností popisku dat, popisku jednotek osy hodnot, názvu osy, titulku grafu, popisku trendové čáry. Automaticky generovaný text je formátován pomocí vlastnosti [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Pouze pro čtení [ITextFrame](../../aspose.slides/itextframe/). |
| **float** [get_Width](./get_width/)() override | Vrací šířku titulku jako podíl šířky grafu. Čte se **float**. |
| **float** [get_X](./get_x/)() override | Vrací souřadnici x titulku jako podíl šířky grafu. Čte se **float**. |
| **float** [get_Y](./get_y/)() override | Vrací souřadnici y titulku jako podíl výšky grafu. Čte se **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu čítače odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání dle C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Skutečně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Skutečně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač odkazů o zadanou hodnotu. |
| void [set_Height](./set_height/)(**float**) override | Nastavuje výšku titulku jako podíl výšky grafu. Zapisuje **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Určuje, zda jiné prvky grafu smí překrývat titulek. Zapisuje **bool**. |
| void [set_Width](./set_width/)(**float**) override | Nastavuje šířku titulku jako podíl šířky grafu. Zapisuje **float**. |
| void [set_X](./set_x/)(**float**) override | Nastavuje souřadnici x titulku jako podíl šířky grafu. Zapisuje **float**. |
| void [set_Y](./set_y/)(**float**) override | Nastavuje souřadnici y titulku jako podíl výšky grafu. Zapisuje **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí dle C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niči objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [IChartTitle](../icharttitle/)
* Třída [IDOMObject](../../aspose.slides/idomobject/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)