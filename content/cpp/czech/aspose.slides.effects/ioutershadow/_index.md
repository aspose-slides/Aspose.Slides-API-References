---
title: IOuterShadow
second_title: Aspose.Slides pro C++ referenční příručka API
description: Představuje efekt vnějšího stínu.
type: docs
weight: 885
url: /cs/aspose.slides.effects/ioutershadow/
---
## IOuterShadow třída


Představuje efekt vnějšího stínu.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) poloměr v bodech. Výchozí hodnota – 0 pt. Čte **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Směr stínu ve stupních. Výchozí hodnota – 0 ° (zleva doprava). Čte **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Vzdálenost stínu od objektu v bodech. Výchozí hodnota – 0 pt. Čte **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Zarovnání obdélníku. Výchozí hodnota – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Čte [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Určuje, zda se stín otáčí spolu s tvarem. Výchozí hodnota – true. Čte **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Horizontální faktor měřítka v procentech původní velikosti. Záporné měřítko způsobí převrácení. Výchozí hodnota – 100 %. Čte **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Vertikální faktor měřítka v procentech původní velikosti. Záporné měřítko způsobí převrácení. Výchozí hodnota – 100 %. Čte **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | Barva stínu. Výchozí hodnota – automatická černá (závislá na motivu). Pouze pro čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Horizontální úhel zkosení ve stupních. Výchozí hodnota – 0 °. Čte **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Vertikální úhel zkosení ve stupních. Výchozí hodnota – 0 °. Čte **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Získá efektivní data s aplikovaným děděním. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání výrazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený počítadlo referencí o zadanou hodnotu. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) poloměr v bodech. Výchozí hodnota – 0 pt. Zapisuje **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Směr stínu ve stupních. Výchozí hodnota – 0 ° (zleva doprava). Zapisuje **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Vzdálenost stínu od objektu v bodech. Výchozí hodnota – 0 pt. Zapisuje **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Zarovnání obdélníku. Výchozí hodnota – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Zapisuje [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Určuje, zda se stín otáčí spolu s tvarem. Výchozí hodnota – true. Zapisuje **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Horizontální faktor měřítka v procentech původní velikosti. Záporné měřítko způsobí převrácení. Výchozí hodnota – 100 %. Zapisuje **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Vertikální faktor měřítka v procentech původní velikosti. Záporné měřítko způsobí převrácení. Výchozí hodnota – 100 %. Zapisuje **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Horizontální úhel zkosení ve stupních. Výchozí hodnota – 0 °. Zapisuje **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Vertikální úhel zkosení ve stupních. Výchozí hodnota – 0 °. Zapisuje **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n'tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílené počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílené počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení výrazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [IImageTransformOperation](../iimagetransformoperation/)
* Třída [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Jmenný prostor [Aspose::Slides::Effects](../)
* Knihovna [Aspose.Slides](../../)