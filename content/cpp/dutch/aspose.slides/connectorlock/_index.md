---
title: ConnectorLock
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt welke bewerkingen zijn uitgeschakeld op de bovenliggende Connector.
type: docs
weight: 495
url: /nl/aspose.slides/connectorlock/
---
## ConnectorLock klasse

Determines which operations are disabled on the parent [Connector](../connector/).

```cpp
class ConnectorLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IConnectorLock
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl floating-point vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl floating-point vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Bepaalt of het wijzigen van aanpassingswaarden verboden is. Leest **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Bepaalt of het wijzigen van pijlpuntjes verboden is. Leest **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Bepaalt of een vorm de beeldverhouding moet behouden bij schalen. Leest **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Bepaalt of een directe wijziging van de contour van deze vorm verboden is. Leest **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Bepaalt of het toevoegen van deze vorm aan een groep verboden is. Leest **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Geeft true terug als alle lock-flags uitgeschakeld zijn. Alleen-lezen **bool**. |
| **bool** [get_PositionMove](./get_positionmove/)() override | Bepaalt of het verplaatsen van deze vorm verboden is. Leest **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | Bepaalt of het wijzigen van de rotatiehoek van deze vorm verboden is. Leest **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Bepaalt of het selecteren van deze vorm verboden is. Leest **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Bepaalt of het wijzigen van een vormtype verboden is. Leest **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Bepaalt of het schalen van deze vorm verboden is. Leest **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of object een instantie van het type dat door targetType wordt beschreven, is. Analoge van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, echt, initialiseert slechts een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert slechts een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object referentieel met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentieteller met de opgegeven waarde. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Bepaalt of het wijzigen van aanpassingswaarden verboden is. Schrijft **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Bepaalt of het wijzigen van pijlpuntjes verboden is. Schrijft **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Bepaalt of een vorm de beeldverhouding moet behouden bij schalen. Schrijft **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Bepaalt of een directe wijziging van de contour van deze vorm verboden is. Schrijft **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Bepaalt of het toevoegen van deze vorm aan een groep verboden is. Schrijft **bool**. |
| void [set_PositionMove](./set_positionmove/)(**bool**) override | Bepaalt of het verplaatsen van deze vorm verboden is. Schrijft **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | Bepaalt of het wijzigen van de rotatiehoek van deze vorm verboden is. Schrijft **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Bepaalt of het selecteren van deze vorm verboden is. Schrijft **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Bepaalt of het wijzigen van een vormtype verboden is. Schrijft **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Bepaalt of het schalen van deze vorm verboden is. Schrijft **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Stelt schakelen van pointers in containers naar zwakke modus toe. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt omzetten van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [BaseShapeLock](../baseshapelock/)
* Klasse [IConnectorLock](../iconnectorlock/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)