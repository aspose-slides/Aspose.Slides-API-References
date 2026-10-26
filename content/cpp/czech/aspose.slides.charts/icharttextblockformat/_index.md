---
title: IChartTextBlockFormat
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje vlastnosti formátování pro textové prvky grafu.
type: docs
weight: 885
url: /cs/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat třída


Reprezentuje vlastnosti formátování pro textové prvky grafu.

```cpp
class IChartTextBlockFormat : public virtual System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) semantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s dvojitou přesností ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Vrací vertikální kotvící text v [TextFrame](../../aspose.slides/textframe/). Přečtěte si [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | Vrací režim automatického přizpůsobení textu. Změna této vlastnosti může mít určitý vliv pouze na tyto části grafu: [DataLabel](../datalabel/) a [DataLabelFormat](../datalabelformat/) (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Přečtěte si [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | Pokud [NullableBool::True](../../aspose.slides/nullablebool/), pak by text měl být vodorovně vycentrován v rámečku. Přečtěte si [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Vrací spodní okraj (v bodech) v [TextFrame](../../aspose.slides/textframe/). Změna této vlastnosti může mít určitý vliv pouze na tyto části grafu: [DataLabel](../datalabel/) a [DataLabelFormat](../datalabelformat/) (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Přečtěte si **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Vrací levý okraj (v bodech) v [TextFrame](../../aspose.slides/textframe/). Změna této vlastnosti může mít určitý vliv pouze na tyto části grafu: [DataLabel](../datalabel/) a [DataLabelFormat](../datalabelformat/) (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Přečtěte si **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Vrací pravý okraj (v bodech) v [TextFrame](../../aspose.slides/textframe/). Změna této vlastnosti může mít určitý vliv pouze na tyto části grafu: [DataLabel](../datalabel/) a [DataLabelFormat](../datalabelformat/) (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Přečtěte si **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Vrací horní okraj (v bodech) v [TextFrame](../../aspose.slides/textframe/). Změna této vlastnosti může mít určitý vliv pouze na tyto části grafu: [DataLabel](../datalabel/) a [DataLabelFormat](../datalabelformat/) (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Přečtěte si **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Určuje vlastní rotaci, která je aplikována na text uvnitř ohraničujícího rámce. Pokud není zadána, použije se rotace přidruženého tvaru. Pokud je zadána, aplikuje se nezávisle na tvaru. To znamená, že tvar může mít rotaci aplikovanou kromě rotace samotného textu. Výsledná hodnota vizuální rotace textu je souhrnem této vlastnosti a předdefinovaného vertikálního typu v vlastnosti TextVerticalType. Přečtěte si **float**. |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Určuje orientaci textu. Výsledná hodnota vizuální rotace textu je souhrnem této vlastnosti a vlastního úhlu v vlastnosti RotationAngle. Přečtěte si [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | **True** pokud je text zalomený na okrajích [TextFrame](../../aspose.slides/textframe/). Změna této vlastnosti může mít určitý vliv pouze na tyto části grafu: [DataLabel](../datalabel/) a [DataLabelFormat](../datalabelformat/) (plná podpora v PowerPoint 2007/2013). Přečtěte si [NullableBool](../../aspose.slides/nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# příkazu lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | Nastaví vertikální kotvící text v [TextFrame](../../aspose.slides/textframe/). Zapište [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | Nastaví režim automatického přizpůsobení textu. Změna této vlastnosti může mít určitý vliv pouze na tyto části grafu: [DataLabel](../datalabel/) a [DataLabelFormat](../datalabelformat/) (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Zapište [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | Pokud [NullableBool::True](../../aspose.slides/nullablebool/), pak by text měl být vodorovně vycentrován v rámečku. Zapište [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Nastaví spodní okraj (v bodech) v [TextFrame](../../aspose.slides/textframe/). Změna této vlastnosti může mít určitý vliv pouze na tyto části grafu: [DataLabel](../datalabel/) a [DataLabelFormat](../datalabelformat/) (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Zapište **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Nastaví levý okraj (v bodech) v [TextFrame](../../aspose.slides/textframe/). Změna této vlastnosti může mít určitý vliv pouze na tyto části grafu: [DataLabel](../datalabel/) a [DataLabelFormat](../datalabelformat/) (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Zapište **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Nastaví pravý okraj (v bodech) v [TextFrame](../../aspose.slides/textframe/). Změna této vlastnosti může mít určitý vliv pouze na tyto části grafu: [DataLabel](../datalabel/) a [DataLabelFormat](../datalabelformat/) (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Zapište **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Nastaví horní okraj (v bodech) v [TextFrame](../../aspose.slides/textframe/). Změna této vlastnosti může mít určitý vliv pouze na tyto části grafu: [DataLabel](../datalabel/) a [DataLabelFormat](../datalabelformat/) (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Zapište **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Určuje vlastní rotaci, která je aplikována na text uvnitř ohraničujícího rámce. Pokud není zadána, použije se rotace přidruženého tvaru. Pokud je zadána, aplikuje se nezávisle na tvaru. To znamená, že tvar může mít rotaci aplikovanou kromě rotace samotného textu. Výsledná hodnota vizuální rotace textu je souhrnem této vlastnosti a předdefinovaného vertikálního typu v vlastnosti TextVerticalType. Zapište **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | Určuje orientaci textu. Výsledná hodnota vizuální rotace textu je souhrnem této vlastnosti a vlastního úhlu v vlastnosti RotationAngle. Zapište [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | **True** pokud je text zalomený na okrajích [TextFrame](../../aspose.slides/textframe/). Změna této vlastnosti může mít určitý vliv pouze na tyto části grafu: [DataLabel](../datalabel/) a [DataLabelFormat](../datalabelformat/) (plná podpora v PowerPoint 2007/2013). Zapište [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# příkazu lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)