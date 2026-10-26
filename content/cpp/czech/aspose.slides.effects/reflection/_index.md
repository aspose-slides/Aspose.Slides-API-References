---
title: Reflection
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Představuje efekt odrazu.
type: docs
weight: 1067
url: /cs/aspose.slides.effects/reflection/
---
## Reflection třída

Represents a [Reflection](./) effect.

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## Metody

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Určuje, zda zadaný [Reflection](./) je roven aktuálnímu [Reflection](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovnocenné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání čísl s dvojitou přesností ve stylu C#, kde jsou dva NaN považovány za rovnocenné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) poloměr. Čte **double**. |
| **float** [get_Direction](./get_direction/)() override | Směr odrazu. Čte **float**. |
| **double** [get_Distance](./get_distance/)() override | Vzdálenost odrazu. Čte **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | Určuje koncovou pozici (podél alfa gradientu) koncové alfa hodnoty (procent). Čte **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | Koncová neprůhlednost odrazu. (procent). Čte **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | Určuje směr posunu odrazu. (úhel). Čte **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Vrací nadřazený [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Pouze pro čtení [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Zarovnání obdélníku. Čte [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Určuje, zda se odraz má otáčet spolu s tvarem, pokud je tvar otočen. Čte **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Určuje horizontální měřítko, záporné měřítko způsobí převrácení. (procent) Čte **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Určuje vertikální měřítko, záporné měřítko způsobí převrácení. (procent) Čte **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Určuje horizontální úhel sklonu. Čte **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Určuje vertikální úhel sklonu. Čte **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | Určuje počáteční pozici (podél alfa gradientu) počáteční alfa hodnoty (procent). Čte **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | Počáteční neprůhlednost odrazu. (procent). Čte **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Verze. Pouze pro čtení **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače referencí spojenou s objektem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | Získá efektivní data efektu [Reflection](./) s použitým děděním. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Slouží jako hashovací funkce pro daný typ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží počet sdílených referencí o zadanou hodnotu. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) poloměr. Zápis **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Směr odrazu. Zápis **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Vzdálenost odrazu. Zápis **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | Určuje koncovou pozici (podél alfa gradientu) koncové alfa hodnoty (procent). Zápis **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | Koncová neprůhlednost odrazu. (procent). Zápis **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | Určuje směr posunu odrazu. (úhel). Zápis **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Zarovnání obdélníku. Zápis [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Určuje, zda se odraz má otáčet spolu s tvarem, pokud je tvar otočen. Zápis **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Určuje horizontální měřítko, záporné měřítko způsobí převrácení. (procent) Zápis **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Určuje vertikální měřítko, záporné měřítko způsobí převrácení. (procent) Zápis **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Určuje horizontální úhel sklonu. Zápis **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Určuje vertikální úhel sklonu. Zápis **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | Určuje počáteční pozici (podél alfa gradientu) počáteční alfa hodnoty (procent). Zápis **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | Počáteční neprůhlednost odrazu. (procent). Zápis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje čítač slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje čítač slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [IReflection](../ireflection/)
* Třída [IVisualEffect](../ivisualeffect/)
* Třída [IPVIObject](../../aspose.slides/ipviobject/)
* Jmenný prostor [Aspose::Slides::Effects](../)
* Knihovna [Aspose.Slides](../../)