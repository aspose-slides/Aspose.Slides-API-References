---
title: IConnectorLock
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt welke bewerkingen zijn uitgeschakeld op de bovenliggende Connector.
type: docs
weight: 1860
url: /nl/aspose.slides/iconnectorlock/
---
## IConnectorLock klasse

Bepaalt welke bewerkingen uitgeschakeld zijn op de bovenliggende [Connector](../connector/).

```cpp
class IConnectorLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-kommagelijkheid vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-kommagelijkheid vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Bepaalt of het wijzigen van aanpassingswaarden verboden is. Lezen **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Bepaalt of het wijzigen van pijlpuntinstellingen verboden is. Lezen **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Bepaalt of een vorm de beeldverhouding moet behouden bij schalen. Lezen **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Bepaalt of een directe wijziging van de contour van deze vorm verboden is. Lezen **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Bepaalt of het toevoegen van deze vorm aan een groep verboden is. Lezen **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Retourneert true als alle lock-vlaggen zijn uitgeschakeld. Alleen-lezen **bool**. |
| virtual **bool** [get_PositionMove](./get_positionmove/)() | Bepaalt of het verplaatsen van deze vorm verboden is. Lezen **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | Bepaalt of het wijzigen van de rotatiehoek van deze vorm verboden is. Lezen **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Bepaalt of het selecteren van deze vorm verboden is. Lezen **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Bepaalt of het wijzigen van een vormtype verboden is. Lezen **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Bepaalt of het schalen van deze vorm verboden is. Lezen **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hash-generatie voor aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert eigenlijk niets, initialiseert slechts een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert slechts een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Bepaalt of het wijzigen van aanpassingswaarden verboden is. Schrijven **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Bepaalt of het wijzigen van pijlpuntinstellingen verboden is. Schrijven **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Bepaalt of een vorm de beeldverhouding moet behouden bij schalen. Schrijven **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Bepaalt of een directe wijziging van de contour van deze vorm verboden is. Schrijven **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Bepaalt of het toevoegen van deze vorm aan een groep verboden is. Schrijven **bool**. |
| virtual void [set_PositionMove](./set_positionmove/)(**bool**) | Bepaalt of het verplaatsen van deze vorm verboden is. Schrijven **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | Bepaalt of het wijzigen van de rotatiehoek van deze vorm verboden is. Schrijven **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Bepaalt of het selecteren van deze vorm verboden is. Schrijven **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Bepaalt of het wijzigen van een vormtype verboden is. Schrijven **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Bepaalt of het schalen van deze vorm verboden is. Schrijven **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Staat toe pointers in containers om te schakelen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |
## Zie ook

* Klasse [IBaseShapeLock](../ibaseshapelock/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)