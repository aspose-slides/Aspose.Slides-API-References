---
title: IRotation3D
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Reprezentuje 3D rotaci grafu.
type: docs
weight: 1171
url: /cs/aspose.slides.charts/irotation3d/
---
## IRotation3D třída

Reprezentuje 3D rotaci grafu.

```cpp
class IRotation3D : public virtual System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | Vrací hloubku 3D grafu jako procento šířky grafu (mezi 20 a 2000 procenty). Čte **uint16_t**. |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | Určuje výšku 3-D grafu jako procento šířky grafu (mezi 5 a 500 procenty). Čte **uint16_t**. |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | Vrací hodnotu perspektivy (úhlová hodnota zorného pole) pro 3D grafy (mezi 0 a 100). Ignorováno, pokud je hodnota vlastnosti RightAngleAxes true. Čte **uint8_t**. |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | Určuje, zda jsou osy grafu pravé úhly, místo aby byly kresleny v perspektivě. Jinými slovy určuje, zda jsou úhly os grafu nezávislé na rotaci nebo náklonu grafu. Čte **bool**. |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | Vrací úhel rotace kolem osy X, tj. ve směru Y pro 3D grafy (mezi –90 a 90 stupni). Vlastnost odpovídá položce 21.2.2.157 rotX (X Rotation) v ECMA-376 a volbě „Y Rotation“ v PowerPoint 2007+. Čte **int8_t**. |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | Vrací úhel rotace kolem osy Y, tj. ve směru X pro 3D grafy (mezi 0 a 360 stupni). Vlastnost odpovídá položce 21.2.2.158 rotY (Y Rotation) v ECMA-376 a volbě „X Rotation“ v PowerPoint 2007+. Čte **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu čítače referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného cílovým typem. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() výrazu. Zavolejte přímo nebo použijte sentinelní objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování při konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování při konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje počet sdílených referencí o zadanou hodnotu. |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | Nastavuje hloubku 3D grafu jako procento šířky grafu (mezi 20 a 2000 procenty). Zapíše **uint16_t**. |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | Určuje výšku 3-D grafu jako procento šířky grafu (mezi 5 a 500 procenty). Zapíše **uint16_t**. |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | Nastavuje hodnotu perspektivy (úhlová hodnota zorného pole) pro 3D grafy (mezi 0 a 100). Ignorováno, pokud je hodnota vlastnosti RightAngleAxes true. Zapíše **uint8_t**. |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | Určuje, zda jsou osy grafu pravé úhly, místo aby byly kresleny v perspektivě. Jinými slovy určuje, zda jsou úhly os grafu nezávislé na rotaci nebo náklonu grafu. Zapíše **bool**. |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | Nastavuje úhel rotace kolem osy X, tj. ve směru Y pro 3D grafy (mezi –90 a 90 stupni). Vlastnost odpovídá položce 21.2.2.157 rotX (X Rotation) v ECMA-376 a volbě „Y Rotation“ v PowerPoint 2007+. Zapíše **int8_t**. |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | Nastavuje úhel rotace kolem osy Y, tj. ve směru X pro 3D grafy (mezi 0 a 360 stupni). Vlastnost odpovídá položce 21.2.2.158 rotY (Y Rotation) v ECMA-376 a volbě „X Rotation“ v PowerPoint 2007+. Zapíše **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu počitadla sdílených referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počet sdílených referencí. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počet sdílených referencí. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení C# lock() výrazu. Zavolejte přímo nebo použijte sentinelní objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počet slabých referencí. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počet slabých referencí. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)