---
title: IGroupShapeLock
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, které operace jsou na nadřazeném GroupShape zakázány.
type: docs
weight: 2497
url: /cs/aspose.slides/igroupshapelock/
---
## Třída IGroupShapeLock


Určuje, které operace jsou na nadřazeném [GroupShape](../groupshape/) zakázány.

```cpp
class IGroupShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty podle sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Určuje, zda má tvar zachovat poměr stran při změně velikosti. Čte **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Určuje, zda je zakázáno přidat tento tvar do skupiny. Čte **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Vrací true, pokud jsou všechna zamykací vlajky zakázána. Pouze pro čtení **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Určuje, zda je zakázáno přesouvat tento tvar. Čte **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | Určuje, zda je zakázáno měnit úhel otáčení tohoto tvaru. Čte **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Určuje, zda je zakázáno vybírat tento tvar. Čte **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Určuje, zda je zakázáno měnit velikost tohoto tvaru. Čte **bool**. |
| virtual **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() | Určuje, zda je zakázáno rozdělit tento skupinový tvar. Čte **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ověří, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání C# lock() příkazu. Volat přímo nebo použít objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje konstrukci podtříd kopií. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje konstrukci podtříd kopií. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Určuje, zda má tvar zachovat poměr stran při změně velikosti. Zapíše **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Určuje, zda je zakázáno přidat tento tvar do skupiny. Zapíše **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Určuje, zda je zakázáno přesouvat tento tvar. Zapíše **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | Určuje, zda je zakázáno měnit úhel otáčení tohoto tvaru. Zapíše **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Určuje, zda je zakázáno vybírat tento tvar. Zapíše **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Určuje, zda je zakázáno měnit velikost tohoto tvaru. Zapíše **bool**. |
| virtual void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) | Určuje, zda je zakázáno rozdělit tento skupinový tvar. Zapíše **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-ty argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač referencí. Neměl by být volán přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Neměl by být volán přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání C# lock() příkazu. Volat přímo nebo použít objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý čítač referencí. Neměl by být volán přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Neměl by být volán přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
## Viz také

* Třída [IBaseShapeLock](../ibaseshapelock/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)