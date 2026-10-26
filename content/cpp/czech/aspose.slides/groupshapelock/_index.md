---
title: GroupShapeLock
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, které operace jsou na nadřazeném GroupShape zakázány.
type: docs
weight: 1210
url: /cs/aspose.slides/groupshapelock/
---
## GroupShapeLock třída

Určuje, které operace jsou na nadřazeném [GroupShape](../groupshape/) zakázány.

```cpp
class GroupShapeLock : public Aspose::Slides::BaseShapeLock,
                       public Aspose::Slides::IGroupShapeLock
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání čísla s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN-y považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání double ve stylu C#, kde jsou dva NaN-y považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Určuje, zda má tvar zachovat poměr stran při změně velikosti. Čtení **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Určuje, zda je zakázáno přidávat tento tvar do skupiny. Čtení **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Vrátí true, pokud jsou všechna zamykací příznaky zakázána. Pouze pro čtení **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Určuje, zda je zakázáno přesouvat tento tvar. Čtení **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Určuje, zda je zakázáno měnit úhel otočení tohoto tvaru. Čtení **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Určuje, zda je zakázáno vybrat tento tvar. Čtení **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Určuje, zda je zakázáno měnit velikost tohoto tvaru. Čtení **bool**. |
| **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() override | Určuje, zda je zakázáno rozdělit tento skupinový tvar. Čtení **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ověří, zda objekt představuje instanci typu popsaného parametrem targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí výrazu C# lock(). Volat přímo nebo použít objekt hlídky [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Určuje, zda má tvar zachovat poměr stran při změně velikosti. Zápis **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Určuje, zda je zakázáno přidávat tento tvar do skupiny. Zápis **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Určuje, zda je zakázáno přesouvat tento tvar. Zápis **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Určuje, zda je zakázáno měnit úhel otočení tohoto tvaru. Zápis **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Určuje, zda je zakázáno vybrat tento tvar. Zápis **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Určuje, zda je zakázáno měnit velikost tohoto tvaru. Zápis **bool**. |
| void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) override | Určuje, zda je zakázáno rozdělovat tento skupinový tvar. Zápis **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do režimu slabých. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Není vhodné volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Není vhodné volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí výrazu C# lock(). Volat přímo nebo použít objekt hlídky [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Není vhodné volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Není vhodné volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [BaseShapeLock](../baseshapelock/)
* Třída [IGroupShapeLock](../igroupshapelock/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)