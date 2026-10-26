---
title: IAutoShapeLock
second_title: Aspose.Slides voor C++ API Referentie
description: Bepaalt welke bewerkingen zijn uitgeschakeld op de bovenliggende AutoshapeEx.
type: docs
weight: 1379
url: /nl/aspose.slides/iautoshapelock/
---
## IAutoShapeLock klasse


Bepaalt welke bewerkingen zijn uitgeschakeld op de bovenliggende AutoshapeEx.

```cpp
class IAutoShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevende-komma vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevende-komma vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Bepaalt of het wijzigen van aanpassingswaarden verboden is. Leest **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Bepaalt of het wijzigen van pijppunten verboden is. Leest **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Bepaalt of een vorm de beeldverhouding moet behouden bij schalen. Leest **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Bepaalt of een directe wijziging van de contour van deze vorm verboden is. Leest **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Bepaalt of het toevoegen van deze vorm aan een groep verboden is. Leest **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Retourneert true als alle vergrendelingsvlaggen zijn uitgeschakeld. Alleen-lezen **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Bepaalt of het verplaatsen van deze vorm verboden is. Leest **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | Bepaalt of het wijzigen van de rotatiehoek van deze vorm verboden is. Leest **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Bepaalt of het selecteren van deze vorm verboden is. Leest **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Bepaalt of het wijzigen van een vormtype verboden is. Leest **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Bepaalt of het schalen van deze vorm verboden is. Leest **bool**. |
| virtual **bool** [get_TextLocked](./get_textlocked/)() | Bepaalt of het bewerken van tekst verboden is. Leest **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Stelt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Stelt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, echt, alleen een nieuw object initialiseren en het kopiëren van subklassen mogelijk maken. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, alleen een nieuw object initialiseren en het kopiëren van subklassen mogelijk maken. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Bepaalt of het wijzigen van aanpassingswaarden verboden is. Schrijft **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Bepaalt of het wijzigen van pijppunten verboden is. Schrijft **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Bepaalt of een vorm de beeldverhouding moet behouden bij schalen. Schrijft **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Bepaalt of een directe wijziging van de contour van deze vorm verboden is. Schrijft **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Bepaalt of het toevoegen van deze vorm aan een groep verboden is. Schrijft **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Bepaalt of het verplaatsen van deze vorm verboden is. Schrijft **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | Bepaalt of het wijzigen van de rotatiehoek van deze vorm verboden is. Schrijft **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Bepaalt of het selecteren van deze vorm verboden is. Schrijft **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Bepaalt of het wijzigen van een vormtype verboden is. Schrijft **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Bepaalt of het schalen van deze vorm verboden is. Schrijft **bool**. |
| virtual void [set_TextLocked](./set_textlocked/)(**bool**) | Bepaalt of het bewerken van tekst verboden is. Schrijft **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Staat toe dat pointers in containers naar zwakke modus worden omgeschakeld. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Stelt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Bevrijdt alle interne gegevensstructuren. |
## Zie ook

* Klasse [IBaseShapeLock](../ibaseshapelock/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)