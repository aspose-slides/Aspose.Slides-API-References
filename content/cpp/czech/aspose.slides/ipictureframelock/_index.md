---
title: IPictureFrameLock
second_title: Aspose.Slides pro C++ – reference API
description: Určuje, které operace jsou na nadřazeném PictureFrameEx zakázány.
type: docs
weight: 3264
url: /cs/aspose.slides/ipictureframelock/
---
## IPictureFrameLock třída

Určuje, které operace jsou na nadřazeném PictureFrameEx zakázány.

```cpp
class IPictureFrameLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dva NaN považovány za rovny, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dva NaN považovány za rovny, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Určuje, zda je změna hodnot upravení zakázána. Čtení **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Určuje, zda je změna šipek zakázána. Čtení **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Určuje, zda musí tvar při změně velikosti zachovat poměr stran. Čtení **bool**. |
| virtual **bool** [get_CropLocked](./get_croplocked/)() | Určuje, zda je ořezávání obrázku zakázáno. Čtení **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Určuje, zda je přímá změna obrysu tohoto tvaru zakázána. Čtení **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Určuje, zda je přidání tohoto tvaru do skupiny zakázáno. Čtení **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Vrátí true, pokud jsou všechny zámky zakázány. Pouze pro čtení **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Určuje, zda je přesunutí tohoto tvaru zakázáno. Čtení **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | Určuje, zda je změna úhlu otáčení tohoto tvaru zakázána. Čtení **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Určuje, zda je výběr tohoto tvaru zakázán. Čtení **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Určuje, zda je změna typu tvaru zakázána. Čtení **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Určuje, zda je změna velikosti tohoto tvaru zakázána. Čtení **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počitadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenci typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač odkazů o zadanou hodnotu. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Určuje, zda je změna hodnot upravení zakázána. Zápis **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Určuje, zda je změna šipek zakázána. Zápis **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Určuje, zda má tvar při změně velikosti zachovat poměr stran. Zápis **bool**. |
| virtual void [set_CropLocked](./set_croplocked/)(**bool**) | Určuje, zda je ořezávání obrázku zakázáno. Zápis **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Určuje, zda je přímá změna obrysu tohoto tvaru zakázána. Zápis **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Určuje, zda je přidání tohoto tvaru do skupiny zakázáno. Zápis **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Určuje, zda je přesunutí tohoto tvaru zakázáno. Zápis **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | Určuje, zda je změna úhlu otáčení tohoto tvaru zakázána. Zápis **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Určuje, zda je výběr tohoto tvaru zakázán. Zápis **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Určuje, zda je změna typu tvaru zakázána. Zápis **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Určuje, zda je změna velikosti tohoto tvaru zakázána. Zápis **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání pomocí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Viz také

* Třída [IBaseShapeLock](../ibaseshapelock/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)