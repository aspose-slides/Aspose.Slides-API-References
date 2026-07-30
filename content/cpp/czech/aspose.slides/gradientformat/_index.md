---
title: GradientFormat
second_title: Aspose.Slides pro referenci API C++
description: Reprezentuje formát gradientu.
type: docs
weight: 1106
url: /cs/aspose.slides/gradientformat/
---
## GradientFormat třída

Represent a gradient format.

```cpp
class GradientFormat : public Aspose::Slides::PVIObject,
                       public Aspose::Slides::IGradientFormat
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Porovnává se se zadaným objektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí řádovou čárkou (double) ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [Aspose::Slides::GradientDirection](../gradientdirection/) [get_GradientDirection](./get_gradientdirection/)() override | Vrací styl gradientu. Číst [Slides::GradientDirection](../gradientdirection/). |
| [Aspose::Slides::GradientShape](../gradientshape/) [get_GradientShape](./get_gradientshape/)() override | Vrací tvar gradientu. Číst [Slides::GradientShape](../gradientshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGradientStop](../igradientstop/)\> [get_GradientStop](./get_gradientstop/)(**int32_t**) override | Vrací zastavení gradientu na zadaném indexu. |
| [System::SharedPtr](../../system/sharedptr/)\<[IGradientStopCollection](../igradientstopcollection/)\> [get_GradientStops](./get_gradientstops/)() override | Vrací kolekci zastavení gradientu. Pouze pro čtení [IGradientStopCollection](../igradientstopcollection/). |
| **float** [get_LinearGradientAngle](./get_lineargradientangle/)() override | Vrací úhel gradientu. Číst **float**. |
| [NullableBool](../nullablebool/) [get_LinearGradientScaled](./get_lineargradientscaled/)() override | Určuje, zda je gradient škálován. Číst [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Vrací objekt Parent_Immediate. Pouze pro čtení [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Vrací rodiče [IPresentationComponent](../ipresentationcomponent/). Pouze pro čtení [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | Vrací režim otáčení pro gradient. Číst [Slides::TileFlip](../tileflip/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu referenčního čítače spojenou s objektem. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Vrací hash kód. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí příkazu C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| void [set_GradientDirection](./set_gradientdirection/)([Aspose::Slides::GradientDirection](../gradientdirection/)) override | Nastavuje styl gradientu. Zapsat [Slides::GradientDirection](../gradientdirection/). |
| void [set_GradientShape](./set_gradientshape/)([Aspose::Slides::GradientShape](../gradientshape/)) override | Nastavuje tvar gradientu. Zapsat [Slides::GradientShape](../gradientshape/). |
| void [set_LinearGradientAngle](./set_lineargradientangle/)(**float**) override | Nastavuje úhel gradientu. Zapsat **float**. |
| void [set_LinearGradientScaled](./set_lineargradientscaled/)([NullableBool](../nullablebool/)) override | Určuje, zda je gradient škálován. Zapsat [NullableBool](../nullablebool/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | Nastavuje režim otáčení gradientu. Zapsat [Slides::TileFlip](../tileflip/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení dle C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [PVIObject](../pviobject/)
* Třída [IGradientFormat](../igradientformat/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)