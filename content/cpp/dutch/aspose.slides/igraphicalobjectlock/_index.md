---
title: IGraphicalObjectLock
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt welke bewerkingen zijn uitgeschakeld op het bovenliggende GraphicalObjectEx.
type: docs
weight: 2471
url: /nl/aspose.slides/igraphicalobjectlock/
---
## IGraphicalObjectLock klasse

Bepaalt welke bewerkingen zijn uitgeschakeld op het bovenliggende GraphicalObjectEx.

```cpp
class IGraphicalObjectLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Bepaalt of de vorm de beeldverhouding moet behouden bij het schalen. Lees **bool**. |
| virtual **bool** [get_DrilldownLocked](./get_drilldownlocked/)() | Bepaalt of het selecteren van subvormen van dit object verboden is. Lees **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Bepaalt of het toevoegen van deze vorm aan een groep verboden is. Lees **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Geeft true terug als alle vergrendelingsvlaggen zijn uitgeschakeld. Alleen-lezen **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Bepaalt of het verplaatsen van deze vorm verboden is. Lees **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Bepaalt of het selecteren van deze vorm verboden is. Lees **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Bepaalt of het wijzigen van de grootte van deze vorm verboden is. Lees **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Schakelt hash-generatie van aangepaste objecten in. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Schakelt klonen van aangepaste types in. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopieconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopieconstructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Bepaalt of de vorm de beeldverhouding moet behouden bij het schalen. Schrijf **bool**. |
| virtual void [set_DrilldownLocked](./set_drilldownlocked/)(**bool**) | Bepaalt of het selecteren van subvormen van dit object verboden is. Schrijf **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Bepaalt of het toevoegen van deze vorm aan een groep verboden is. Schrijf **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Bepaalt of het verplaatsen van deze vorm verboden is. Schrijf **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Bepaalt of het selecteren van deze vorm verboden is. Schrijf **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Bepaalt of het wijzigen van de grootte van deze vorm verboden is. Schrijf **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt de n'te sjabloonparameter in als een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers om te schakelen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Schakelt conversie van aangepaste objecten naar string in. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijmaakt alle interne datastructuren. |

## Zie ook

* Klasse [IBaseShapeLock](../ibaseshapelock/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)