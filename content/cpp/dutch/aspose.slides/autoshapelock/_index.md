---
title: AutoShapeLock
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt welke bewerkingen uitgeschakeld zijn op de bovenliggende AutoshapeEx.
type: docs
weight: 79
url: /nl/aspose.slides/autoshapelock/
---
## AutoShapeLock klasse


Bepaalt welke bewerkingen zijn uitgeschakeld op de bovenliggende AutoshapeEx.

```cpp
class AutoShapeLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IAutoShapeLock
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagelijking waarbij twee NaN's als gelijk worden beschouwd, ondanks dat volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagelijking waarbij twee NaN's als gelijk worden beschouwd, ondanks dat volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Bepaalt of een wijziging van aanpassingswaarden verboden is. Alleen-lezen **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Bepaalt of een wijziging van pijlpunten verboden is. Alleen-lezen **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Bepaalt of een vorm de beeldverhouding moet behouden bij schalen. Alleen-lezen **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Bepaalt of een directe wijziging van de contour van deze vorm verboden is. Alleen-lezen **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Bepaalt of het toevoegen van deze vorm aan een groep verboden is. Alleen-lezen **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Geeft true terug als alle vergrendelingsvlaggen zijn uitgeschakeld. Alleen-lezen **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Bepaalt of het verplaatsen van deze vorm verboden is. Alleen-lezen **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | Bepaalt of een wijziging van de rotatiehoek van deze vorm verboden is. Alleen-lezen **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Bepaalt of het selecteren van deze vorm verboden is. Alleen-lezen **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Bepaalt of een wijziging van een vormtype verboden is. Alleen-lezen **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Bepaalt of het aanpassen van de grootte van deze vorm verboden is. Alleen-lezen **bool**. |
| **bool** [get_TextLocked](./get_textlocked/)() override | Bepaalt of het bewerken van tekst verboden is. Alleen-lezen **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentie-teller datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentinel-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieconstructor. Kopieert niets, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt via referentie waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Bepaalt of een wijziging van aanpassingswaarden verboden is. Schrijf **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Bepaalt of een wijziging van pijlpunten verboden is. Schrijf **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Bepaalt of een vorm de beeldverhouding moet behouden bij schalen. Schrijf **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Bepaalt of een directe wijziging van de contour van deze vorm verboden is. Schrijf **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Bepaalt of het toevoegen van deze vorm aan een groep verboden is. Schrijf **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Bepaalt of het verplaatsen van deze vorm verboden is. Schrijf **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | Bepaalt of een wijziging van de rotatiehoek van deze vorm verboden is. Schrijf **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Bepaalt of het selecteren van deze vorm verboden is. Schrijf **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Bepaalt of een wijziging van een vormtype verboden is. Schrijf **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Bepaalt of het aanpassen van de grootte van deze vorm verboden is. Schrijf **bool**. |
| void [set_TextLocked](./set_textlocked/)(**bool**) override | Bepaalt of het bewerken van tekst verboden is. Schrijf **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als zwakke pointer (in plaats van gedeeld). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentinel-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [BaseShapeLock](../baseshapelock/)
* Klasse [IAutoShapeLock](../iautoshapelock/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)