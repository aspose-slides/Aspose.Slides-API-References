---
title: PictureFrameLock
second_title: Aspose.Slides pro C++ referenční příručka API
description: Určuje, které operace jsou na nadřazeném PictureFrame zakázány.
type: docs
weight: 4746
url: /cs/aspose.slides/pictureframelock/
---
## PictureFrameLock třída


Určuje, které operace jsou na nadřazeném [PictureFrame](../pictureframe/) zakázány.

```cpp
class PictureFrameLock : public Aspose::Slides::BaseShapeLock,
                         public Aspose::Slides::IPictureFrameLock
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnoty ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Určuje, zda je změna hodnot nastavení zakázána. Čte **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Určuje, zda je změna šipek zakázána. Čte **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Určuje, zda má tvar zachovat poměr stran při změně velikosti. Čte **bool**. |
| **bool** [get_CropLocked](./get_croplocked/)() override | Určuje, zda je oříznutí obrázku zakázáno. Čte **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Určuje, zda je přímá změna obrysu tohoto tvaru zakázána. Čte **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Určuje, zda je přidání tohoto tvaru do skupiny zakázáno. Čte **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Vrací true, pokud jsou všechny zamykací příznaky zakázány. Pouze pro čtení **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Určuje, zda je přesunutí tohoto tvaru zakázáno. Čte **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Určuje, zda je změna úhlu otáčení tohoto tvaru zakázána. Čte **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Určuje, zda je výběr tohoto tvaru zakázán. Čte **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Určuje, zda je změna typu tvaru zakázána. Čte **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Určuje, zda je změna velikosti tohoto tvaru zakázána. Čte **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu čítače odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# metody [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zámek výrazu C# lock(). Volat přímo nebo použít objekt hlídky [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle odkazu. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle odkazu. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač odkazů o zadanou hodnotu. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Určuje, zda je změna hodnot nastavení zakázána. Zapíše **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Určuje, zda je změna šipek zakázána. Zapíše **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Určuje, zda má tvar zachovat poměr stran při změně velikosti. Zapíše **bool**. |
| void [set_CropLocked](./set_croplocked/)(**bool**) override | Určuje, zda je oříznutí obrázku zakázáno. Zapíše **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Určuje, zda je přímá změna obrysu tohoto tvaru zakázána. Zapíše **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Určuje, zda je přidání tohoto tvaru do skupiny zakázáno. Zapíše **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Určuje, zda je přesunutí tohoto tvaru zakázáno. Zapíše **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Určuje, zda je změna úhlu otáčení tohoto tvaru zakázána. Zapíše **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Určuje, zda je výběr tohoto tvaru zakázán. Zapíše **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Určuje, zda je změna typu tvaru zakázána. Zapíše **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Určuje, zda je změna velikosti tohoto tvaru zakázána. Zapíše **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (místo sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# metody [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení výrazu C# lock(). Volat přímo nebo použít objekt hlídky [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niči objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [BaseShapeLock](../baseshapelock/)
* Třída [IPictureFrameLock](../ipictureframelock/)
* Namespace [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)