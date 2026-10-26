---
title: TextFrameFormat
second_title: Aspose.Slides pro C++ API Reference
description: Obsahuje vlastnosti formatTextFrameFormatting objektu TextFrame.
type: docs
weight: 5461
url: /cs/aspose.slides/textframeformat/
---
## TextFrameFormat třída


Contains the [TextFrame](../textframe/)'s formatTextFrameFormatting properties.

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Porovnává se se zadaným objektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | Vrací text vertikálního ukotvení v [TextFrame](../textframe/). Přečtěte si [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | Vrací režim automatického přizpůsobení textu. Přečtěte si [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | Pokud [NullableBool::True](../nullablebool/), text by měl být vodorovně vycentrován v rámečku. Přečtěte si [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Vrací počet sloupců v textové oblasti. Tato hodnota musí být kladné číslo. V opačném případě bude hodnota nastavena na nulu. Hodnota 0 znamená nedefinovanou hodnotu. Přečtěte **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | Vrací mezeru mezi sloupci textu v textové oblasti (v bodech). Toto se má použít pouze, pokud je přítomno více než 1 sloupec. Tato hodnota musí být kladné číslo. V opačném případě bude hodnota nastavena na nulu. Přečtěte **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | Vrací informaci, zda je text zachován plochý i po použití 3-D otočného efektu. Přečtěte **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Vrací spodní okraj (v bodech) v [TextFrame](../textframe/). Přečtěte **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Vrací levý okraj (v bodech) v [TextFrame](../textframe/). Přečtěte **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Vrací pravý okraj (v bodech) v [TextFrame](../textframe/). Přečtěte **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Vrací horní okraj (v bodech) v [TextFrame](../textframe/). Přečtěte **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Vrací objekt Parent_Immediate. Pouze pro čtení [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Vrací nadřazený [IPresentationComponent](../ipresentationcomponent/). Pouze pro čtení [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | Určuje vlastní otočení aplikované na text uvnitř ohraničujícího rámečku. Pokud není zadáno, použije se otočení odpovídajícího tvaru. Pokud je zadáno, použije se nezávisle na tvaru. To znamená, že tvar může mít vlastní otočení a zároveň text může mít své vlastní otočení. Výsledná hodnota vizuálního otočení textu je součtem této vlastnosti a předdefinovaného vertikálního typu v vlastnosti TextVerticalType. Přečtěte **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Určuje orientaci textu. Výsledná hodnota vizuálního otočení textu je součtem této vlastnosti a vlastního úhlu v vlastnosti RotationAngle. Přečtěte [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Vrací objekt [ThreeDFormat](../threedformat/), který představuje vlastnosti 3-D efektu pro text. Pouze pro čtení [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | Vrací tvar zalamování textu. Přečtěte [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True** pokud je text zalamován na okrajích [TextFrame](../textframe/). Přečtěte [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Vrací datovou strukturu počítadla odkazů spojenou s objektem. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | Vrací efektivní data formátování textového rámce s aplikovaným děděním. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Vrací hash kód. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Vrací skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopirovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží počítadlo sdílených odkazů o zadanou hodnotu. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | Nastavuje text vertikálního ukotvení v [TextFrame](../textframe/). Zapište [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | Nastavuje režim automatického přizpůsobení textu. Zapište [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | Pokud [NullableBool::True](../nullablebool/), text by měl být vodorovně vycentrován v rámečku. Zapište [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | Nastavuje počet sloupců v textové oblasti. Tato hodnota musí být kladná. V opačném případě bude nastavena na nulu. Hodnota 0 znamená nedefinovanou hodnotu. Zapište **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | Nastavuje mezeru mezi sloupci textu v textové oblasti (v bodech). Toto se použije jen, pokud je více než 1 sloupec. Tato hodnota musí být kladná. V opačném případě bude nastavena na nulu. Zapište **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | Nastavuje zachování plochého textu i po aplikaci 3-D otočného efektu. Zapište **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Nastavuje spodní okraj (v bodech) v [TextFrame](../textframe/). Zapište **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Nastavuje levý okraj (v bodech) v [TextFrame](../textframe/). Zapište **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Nastavuje pravý okraj (v bodech) v [TextFrame](../textframe/). Zapište **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Nastavuje horní okraj (v bodech) v [TextFrame](../textframe/). Zapište **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | Určuje vlastní otočení aplikované na text uvnitř ohraničujícího rámečku. Pokud není zadáno, použije se otočení odpovídajícího tvaru. Pokud je zadáno, použije se nezávisle na tvaru. To znamená, že tvar může mít vlastní otočení a zároveň text může mít své vlastní otočení. Výsledná hodnota vizuálního otočení textu je součtem této vlastnosti a předdefinovaného vertikálního typu v vlastnosti TextVerticalType. Zapište **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Určuje orientaci textu. Výsledná hodnota vizuálního otočení textu je součtem této vlastnosti a vlastního úhlu v vlastnosti RotationAngle. Zapište [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | Nastavuje tvar zalamování textu. Zapište [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True** pokud je text zalamován na okrajích [TextFrame](../textframe/). Zapište [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Vrací aktuální hodnotu počítadla sdílených odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počítadlo sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počítadlo sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [TextFrameFormat](./textframeformat/)() | Inicializuje novou instanci třídy [TextFrameFormat](./). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počet slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počet slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [PVIObject](../pviobject/)
* Třída [ITextFrameFormat](../itextframeformat/)
* Třída [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)