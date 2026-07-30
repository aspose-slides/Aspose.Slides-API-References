---
title: Rotation3D
second_title: Aspose.Slides pro C++ API reference
description: Reprezentuje 3D rotaci grafu.
type: docs
weight: 1327
url: /cs/aspose.slides.charts/rotation3d/
---
## Rotation3D třída

Reprezentuje 3D rotaci grafu.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | Vrací hloubku 3D grafu jako procento šířky grafu (mezi 20 a 2000 procenty). Čte se **uint16_t**. |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | Udává výšku 3-D grafu jako procento šířky grafu (mezi 5 a 500 procenty). Čte se **uint16_t**. |
| **uint8_t** [get_Perspective](./get_perspective/)() override | Vrací hodnotu perspektivy (úhel zorného pole) pro 3D grafy (mezi 0 a 240). Ignorováno, pokud je hodnota vlastnosti RightAngleAxes true. Čte se **uint8_t**. |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | Určuje, zda jsou osy grafu v pravých úhlech, místo aby byly vykresleny v perspektivě. Jinými slovy určuje, zda úhly os grafu jsou nezávislé na rotaci nebo elevaci grafu. Čte se **bool**. |
| **int8_t** [get_RotationX](./get_rotationx/)() override | Vrací úhel rotace kolem osy X, tj. ve směru Y pro 3D grafy (mezi –90 a 90 stupni). Vlastnost odpovídá položce 21.2.2.157 rotX (X Rotation) v ECMA-376 a volbě „Y Rotation“ v PowerPoint 2007+. Čte se **int8_t**. |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | Vrací úhel rotace kolem osy Y, tj. ve směru X pro 3D grafy (mezi 0 a 360 stupni). Vlastnost odpovídá položce 21.2.2.158 rotY (Y Rotation) v ECMA-376 a volbě „X Rotation“ v PowerPoint 2007+. Čte se **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počitadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie k metodě C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie k volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie k operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() deklarace. Zavolejte přímo nebo použijte sentinel objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie k metodě C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nekopíruje nic, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nekopíruje nic, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává hodnotový typ objektu s nullptr referencí. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | Nastaví hloubku 3D grafu jako procento šířky grafu (mezi 20 a 2000 procenty). Zapíše **uint16_t**. |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | Udává výšku 3-D grafu jako procento šířky grafu (mezi 5 a 500 procenty). Zapíše **uint16_t**. |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | Nastaví hodnotu perspektivy (úhel zorného pole) pro 3D grafy (mezi 0 a 240). Ignorováno, pokud je hodnota vlastnosti RightAngleAxes true. Zapíše **uint8_t**. |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | Určuje, zda jsou osy grafu v pravých úhlech, místo aby byly vykresleny v perspektivě. Jinými slovy určuje, zda úhly os grafu jsou nezávislé na rotaci nebo elevaci grafu. Zapíše **bool**. |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | Nastaví úhel rotace kolem osy X, tj. ve směru Y pro 3D grafy (mezi –90 a 90 stupni). Vlastnost odpovídá položce 21.2.2.157 rotX (X Rotation) v ECMA-376 a volbě „Y Rotation“ v PowerPoint 2007+. Zapíše **int8_t**. |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | Nastaví úhel rotace kolem osy Y, tj. ve směru X pro 3D grafy (mezi 0 a 360 stupni). Vlastnost odpovídá položce 21.2.2.158 rotY (Y Rotation) v ECMA-376 a volbě „X Rotation“ v PowerPoint 2007+. Zapíše **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počitadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie k metodě C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock() deklarace. Zavolejte přímo nebo použijte sentinel objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [IRotation3D](../irotation3d/)
* Třída [IDOMObject](../../aspose.slides/idomobject/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)