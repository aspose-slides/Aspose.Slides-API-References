---
title: PictureFrameLock
second_title: Aspose.Slides voor C++ API Referentie
description: Bepaalt welke bewerkingen zijn uitgeschakeld op de bovenliggende PictureFrame.
type: docs
weight: 4746
url: /nl/aspose.slides/pictureframelock/
---
## PictureFrameLock klasse

Bepaalt welke bewerkingen zijn uitgeschakeld op de bovenliggende [PictureFrame](../pictureframe/).

```cpp
class PictureFrameLock : public Aspose::Slides::BaseShapeLock,
                         public Aspose::Slides::IPictureFrameLock
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl drijvende-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl drijvende-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Bepaalt of een wijzigende aanpassingswaarde verboden is. Lees **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Bepaalt of een wijzigende pijlpunten verboden zijn. Lees **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Bepaalt of een vorm de beeldverhoudingen moet behouden bij het schalen. Lees **bool**. |
| **bool** [get_CropLocked](./get_croplocked/)() override | Bepaalt of bijsnijden van een afbeelding verboden is. Lees **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Bepaalt of een directe wijziging van de contour van deze vorm verboden is. Lees **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Bepaalt of het toevoegen van deze vorm aan een groep verboden is. Lees **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Retourneert true als alle vergrendelingsvlaggen zijn uitgeschakeld. Alleen-lezen **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Bepaalt of het verplaatsen van deze vorm verboden is. Lees **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Bepaalt of het wijzigen van de rotatiehoek van deze vorm verboden is. Lees **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Bepaalt of het selecteren van deze vorm verboden is. Lees **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Bepaalt of het wijzigen van een vormtype verboden is. Lees **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Bepaalt of het wijzigen van de grootte van deze vorm verboden is. Lees **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie van het door targetType beschreven type vertegenwoordigt. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopiërende constructor. Kopieert in feite niets, alleen een nieuw object initialiseren en het kopiëren van subklassen mogelijk maken. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert in feite niets, alleen een nieuw object initialiseren en het kopiëren van subklassen mogelijk maken. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Bepaalt of een wijzigende aanpassingswaarde verboden is. Schrijf **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Bepaalt of een wijzigende pijlpunten verboden zijn. Schrijf **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Bepaalt of een vorm de beeldverhoudingen moet behouden bij het schalen. Schrijf **bool**. |
| void [set_CropLocked](./set_croplocked/)(**bool**) override | Bepaalt of bijsnijden van een afbeelding verboden is. Schrijf **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Bepaalt of een directe wijziging van de contour van deze vorm verboden is. Schrijf **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Bepaalt of het toevoegen van deze vorm aan een groep verboden is. Schrijf **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Bepaalt of het verplaatsen van deze vorm verboden is. Schrijf **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Bepaalt of het wijzigen van de rotatiehoek van deze vorm verboden is. Schrijf **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Bepaalt of het selecteren van deze vorm verboden is. Schrijf **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Bepaalt of het wijzigen van een vormtype verboden is. Schrijf **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Bepaalt of het wijzigen van de grootte van deze vorm verboden is. Schrijf **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers te schakelen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks aangeroepen worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks aangeroepen worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks aangeroepen worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks aangeroepen worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [BaseShapeLock](../baseshapelock/)
* Klasse [IPictureFrameLock](../ipictureframelock/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)