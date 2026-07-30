---
title: OuterShadow
second_title: Aspose.Slides pro C++ API reference
description: Reprezentuje efekt vnějšího stínu.
type: docs
weight: 1041
url: /cs/aspose.slides.effects/outershadow/
---
## OuterShadow třída


Reprezentuje efekt vnějšího stínu.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Určuje, zda zadaný [OuterShadow](./) je roven aktuálnímu [OuterShadow](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Napodobuje porovnávání desetinných čísel ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Napodobuje porovnávání desetinných čísel ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) radius, in points. Default value \u2013 0 pt. Čtení **double**. |
| **float** [get_Direction](./get_direction/)() override | Direction of the shadow, in degrees. Default value \u2013 0 \u00B0 (left-to-right). Čtení **float**. |
| **double** [get_Distance](./get_distance/)() override | Distance of the shadow from the object, in points. Default value \u2013 0 pt. Čtení **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Returns parent [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Pouze pro čtení [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Rectangle alignment. Default value \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Čtení [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Indicates whether the shadow rotates together with the shape. Default value \u2013 true. Čtení **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Horizontal scaling factor, in percent of the original size. Negative scaling causes a flip. Default value \u2013 100 %. Čtení **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Vertical scaling factor, in percent of the original size. Negative scaling causes a flip. Default value \u2013 100 %. Čtení **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | Color of the shadow. Default value \u2013 automatic black (theme-dependent). Pouze pro čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Horizontal skew angle, in degrees. Default value \u2013 0 \u00B0. Čtení **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Vertical skew angle, in degrees. Default value \u2013 0 \u00B0. Čtení **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Verze. Pouze pro čtení **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | Získá efektivní data efektu Outer Shadow s aplikovaným děděním. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Slouží jako hashovací funkce pro konkrétní typ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání C# lock(). Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) radius, in points. Default value \u2013 0 pt. Zápis **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Direction of the shadow, in degrees. Default value \u2013 0 \u00B0 (left-to-right). Zápis **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Distance of the shadow from the object, in points. Default value \u2013 0 pt. Zápis **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Rectangle alignment. Default value \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Zápis [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Indicates whether the shadow rotates together with the shape. Default value \u2013 true. Zápis **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Horizontal scaling factor, in percent of the original size. Negative scaling causes a flip. Default value \u2013 100 %. Zápis **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Vertical scaling factor, in percent of the original size. Negative scaling causes a flip. Default value \u2013 100 %. Zápis **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Horizontal skew angle, in degrees. Default value \u2013 0 \u00B0. Zápis **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Vertical skew angle, in degrees. Default value \u2013 0 \u00B0. Zápis **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí C# lock(). Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počítadlo slabých referencí. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počítadlo slabých referencí. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Viz také

* Třída [IOuterShadow](../ioutershadow/)
* Třída [IVisualEffect](../ivisualeffect/)
* Třída [IPVIObject](../../aspose.slides/ipviobject/)
* Jmenný prostor [Aspose::Slides::Effects](../)
* Knihovna [Aspose.Slides](../../)