---
title: GroupShapeLock
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt welke bewerkingen zijn uitgeschakeld op de bovenliggende GroupShape.
type: docs
weight: 1210
url: /nl/aspose.slides/groupshapelock/
---
## GroupShapeLock klasse

Bepaalt welke bewerkingen zijn uitgeschakeld op de bovenliggende [GroupShape](../groupshape/).

```cpp
class GroupShapeLock : public Aspose::Slides::BaseShapeLock,
                       public Aspose::Slides::IGroupShapeLock
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Bepaalt of de vorm de aspectverhouding moet behouden bij het wijzigen van de grootte. Lezen **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Bepaalt of het toevoegen van deze vorm aan een groep verboden is. Lezen **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Retourneert true als alle vergrendelingsvlaggen zijn uitgeschakeld. Alleen-lezen **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Bepaalt of het verplaatsen van deze vorm verboden is. Lezen **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Bepaalt of het wijzigen van de rotatiehoek van deze vorm verboden is. Lezen **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Bepaalt of het selecteren van deze vorm verboden is. Lezen **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Bepaalt of het wijzigen van de grootte van deze vorm verboden is. Lezen **bool**. |
| **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() override | Bepaalt of het splitsen van deze groepsvorm verboden is. Lezen **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van de C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een referentie-waarde-type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Bepaalt of de vorm de aspectverhouding moet behouden bij het wijzigen van de grootte. Schrijf **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Bepaalt of het toevoegen van deze vorm aan een groep verboden is. Schrijf **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Bepaalt of het verplaatsen van deze vorm verboden is. Schrijf **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Bepaalt of het wijzigen van de rotatiehoek van deze vorm verboden is. Schrijf **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Bepaalt of het selecteren van deze vorm verboden is. Schrijf **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Bepaalt of het wijzigen van de grootte van deze vorm verboden is. Schrijf **bool**. |
| void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) override | Bepaalt of het splitsen van deze groepsvorm verboden is. Schrijf **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te wisselen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [BaseShapeLock](../baseshapelock/)
* Klasse [IGroupShapeLock](../igroupshapelock/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)