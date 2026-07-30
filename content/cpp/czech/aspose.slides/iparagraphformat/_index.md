---
title: IParagraphFormat
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Tato třída obsahuje vlastnosti formátování odstavců. Na rozdíl od IParagraphFormatEffectiveData jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 3147
url: /cs/aspose.slides/iparagraphformat/
---
## IParagraphFormat třída


Tato třída obsahuje vlastnosti formátování odstavců. Na rozdíl od [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) jsou všechny vlastnosti této třídy zapisovatelné.

```cpp
class IParagraphFormat : public virtual System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Vrací zarovnání textu v odstavci bez dědičnosti. Číst [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | Vrací formát odrážky odstavce. Pouze pro čtení [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Vrací výchozí formát části odstavce. Není použita dědičnost. Pouze pro čtení [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Vrací výchozí velikost tabelace bez dědičnosti. Číst **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Vrací hloubku odstavce. Hodnota 0 znamená nedefinovanou hodnotu. Číst **int16_t**. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Určuje, zda je v odstavci používáno východoasijské zalomení řádku. Není použita dědičnost. Číst [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Vrací zarovnání písma v odstavci bez dědičnosti. Číst [Slides::FontAlignment](../fontalignment/). |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Určuje, zda je v odstavci používána visící interpunkce. Není použita dědičnost. Číst [NullableBool](../nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | Vrací odsazení první řádky/visící odsazení odstavce bez dědičnosti. Visící odsazení může být definováno zápornými hodnotami. Číst **float**. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Určuje, zda je v odstavci používáno latinské zalomení řádku. Není použita dědičnost. Číst [NullableBool](../nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Vrací levý okraj v odstavci bez dědičnosti. Číst **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Vrací pravý okraj v odstavci bez dědičnosti. Číst **float**. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Určuje, zda je v odstavci používán zápis zprava doleva. Není použita dědičnost. Číst [NullableBool](../nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Vrací množství prostoru po poslední řádce v odstavci bez dědičnosti. Kladná hodnota určuje procento velikosti písma, které by měla být bílá mezera. Záporná hodnota určuje velikost bílé mezery v bodech. Číst **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Vrací množství prostoru před první řádkou v odstavci bez dědičnosti. Kladná hodnota určuje procento velikosti písma, které by měla být bílá mezera. Záporná hodnota určuje velikost bílé mezery v bodech. Číst **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Vrací množství prostoru mezi základními řádky v odstavci. Kladná hodnota znamená procento, záporná - velikost v bodech. Není použita dědičnost. Číst **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Vrací tabelaci odstavce na zadaném indexu. Není použita dědičnost. Pouze pro čtení [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | Vrací tabelace odstavce. Není použita dědičnost. Pouze pro čtení [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | Získává efektivní data formátování odstavce s aplikovanou dědičností. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného cílovým typem. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# příkazu lock(). Zavolejte přímo nebo použijte [LockContext](../../system/lockcontext/) objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje počet sdílených referencí o zadanou hodnotu. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | Nastavuje zarovnání textu v odstavci bez dědičnosti. Zapište [TextAlignment](../textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Nastavuje výchozí velikost tabelace bez dědičnosti. Zapište **float**. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | Nastavuje hloubku odstavce. Hodnota 0 znamená nedefinovanou hodnotu. Zapište **int16_t**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | Určuje, zda je v odstavci používáno východoasijské zalomení řádku. Není použita dědičnost. Zapište [NullableBool](../nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | Nastavuje zarovnání písma v odstavci bez dědičnosti. Zapište [Slides::FontAlignment](../fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | Určuje, zda je v odstavci používána visící interpunkce. Není použita dědičnost. Zapište [NullableBool](../nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | Nastavuje odsazení první řádky/visící odsazení odstavce bez dědičnosti. Visící odsazení může být definováno zápornými hodnoty. Zapište **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | Určuje, zda je v odstavci používáno latinské zalomení řádku. Není použita dědičnost. Zapište [NullableBool](../nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Nastavuje levý okraj v odstavci bez dědičnosti. Zapište **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Nastavuje pravý okraj v odstavci bez dědičnosti. Zapište **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | Určuje, zda je v odstavci používán zápis zprava doleva. Není použita dědičnost. Zapište [NullableBool](../nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Nastavuje množství prostoru po poslední řádce v odstavci bez dědičnosti. Kladná hodnota určuje procento velikosti písma, které by měla být bílá mezera. Záporná hodnota určuje velikost bílé mezery v bodech. Zapište **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Nastavuje množství prostoru před první řádkou v odstavci bez dědičnosti. Kladná hodnota určuje procento velikosti písma, které by měla být bílá mezera. Záporná hodnota určuje velikost bílé mezery v bodech. Zapište **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Nastavuje množství prostoru mezi základními řádky v odstavci. Kladná hodnota znamená procento, záporná - velikost v bodech. Není použita dědičnost. Zapište **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (místo sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu počítadla sdílených referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# příkazu lock(). Zavolejte přímo nebo použijte [LockContext](../../system/lockcontext/) objekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolňuje všechny vnitřní datové struktury. |
## Poznámky


Tato třída se používá k vracení a manipulaci s vlastnostmi formátování odstavců definovanými pro konkrétní odstavec. To znamená, že při získávání hodnot se nepoužije žádná dědičnost, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Aby bylo možné získat skutečné hodnoty parametrů formátování včetně zděděných, je nutné použít metodu [IParagraphFormat::GetEffective](./geteffective/), která vrací instanci [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)