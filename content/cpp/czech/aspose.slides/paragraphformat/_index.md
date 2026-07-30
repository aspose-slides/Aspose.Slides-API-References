---
title: ParagraphFormat
second_title: Aspose.Slides pro C++ API referenci
description: Tato třída obsahuje vlastnosti formátování odstavců. Na rozdíl od IParagraphFormatEffectiveData jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 4668
url: /cs/aspose.slides/paragraphformat/
---
## ParagraphFormat třída


Tato třída obsahuje vlastnosti formátování odstavců. Na rozdíl od [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) jsou všechny vlastnosti této třídy zapisovatelné.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Porovnává s určeným objektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovny, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovny, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | Vrací zarovnání textu v odstavci bez dědičnosti. Přečtěte [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | Vrací výchozí velikost tabulátoru bez dědičnosti. Přečtěte **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | Určuje, zda se v odstavci používá východoasijské zalomení řádku. Není aplikována dědičnost. Přečtěte [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | Vrací zarovnání písma v odstavci bez dědičnosti. Přečtěte [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | Určuje, zda se v odstavci používá závěsová interpunkce. Není aplikována dědičnost. Přečtěte [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | Vrací odsazení první řádky / závěsové odsazení odstavce bez dědičnosti. Závěsové odsazení může být definováno zápornými hodnotami. Přečtěte **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | Určuje, zda se v odstavci používá latinské zalomení řádku. Není aplikována dědičnost. Přečtěte [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | Vrací levý okraj v odstavci bez dědičnosti. Přečtěte **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | Vrací pravý okraj v odstavci bez dědičnosti. Přečtěte **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Vrací objekt Parent_Immediate. Pouze pro čtení [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Vrací rodičovský [IPresentationComponent](../ipresentationcomponent/). Pouze pro čtení [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | Určuje, zda se v odstavci používá psaní zprava doleva. Není aplikována dědičnost. Přečtěte [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | Vrací množství prostoru po poslední řádce v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, které by měl bílý prostor mít. Záporná hodnota udává velikost bílého prostoru v bodech. Přečtěte **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | Vrací množství prostoru před první řádkou v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, které by měl bílý prostor mít. Záporná hodnota udává velikost bílého prostoru v bodech. Přečtěte **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | Vrací množství prostoru mezi základními řádky v odstavci. Kladná hodnota znamená procento, záporná - velikost v bodech. Není aplikována dědičnost. Přečtěte **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | Vrací tabulátor odstavce na zadaném indexu. Není aplikována dědičnost. Pouze pro čtení [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | Vrací tabulátory odstavce. Není aplikována dědičnost. Pouze pro čtení [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | Získá efektivní data formátování odstavce s aplikovanou dědičností. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Vrací hash kód. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
|  [ParagraphFormat](./paragraphformat/)() | Inicializuje novou instanci třídy [ParagraphFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává objekt hodnotového typu s nullptr podle reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač odkazů o zadanou hodnotu. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | Nastavuje zarovnání textu v odstavci bez dědičnosti. Zapište [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | Nastavuje výchozí velikost tabulátoru bez dědičnosti. Zapište **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | Určuje, zda se v odstavci používá východoasijské zalomení řádku. Není aplikována dědičnost. Zapište [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | Nastavuje zarovnání písma v odstavci bez dědičnosti. Zapište [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | Určuje, zda se v odstavci používá závěsová interpunkce. Není aplikována dědičnost. Zapište [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | Nastavuje odsazení první řádky / závěsové odsazení odstavce bez dědičnosti. Závěsové odsazení může být definováno zápornými hodnotami. Zapište **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | Určuje, zda se v odstavci používá latinské zalomení řádku. Není aplikována dědičnost. Zapište [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | Nastavuje levý okraj v odstavci bez dědičnosti. Zapište **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | Nastavuje pravý okraj v odstavci bez dědičnosti. Zapište **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | Určuje, zda se v odstavci používá psaní zprava doleva. Není aplikována dědičnost. Zapište [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | Nastavuje množství prostoru po poslední řádce v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, které by měl bílý prostor mít. Záporná hodnota udává velikost bílého prostoru v bodech. Zapište **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | Nastavuje množství prostoru před první řádkou v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, které by měl bílý prostor mít. Záporná hodnota udává velikost bílého prostoru v bodech. Zapište **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | Nastavuje množství prostoru mezi základními řádky v odstavci. Kladná hodnota znamená procento, záporná - velikost v bodech. Není aplikována dědičnost. Zapište **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování odstavců definovanými pro konkrétní odstavec. To znamená, že při získávání hodnot není použita žádná dědičnost, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Pro získání efektivních hodnot parametrů formátování včetně dědičných je třeba použít metodu [ParagraphFormat::GetEffective](./geteffective/), která vrací instanci [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## Viz také

* Třída [PVIObject](../pviobject/)
* Třída [IParagraphFormat](../iparagraphformat/)
* Třída [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)