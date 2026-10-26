---
title: Matrix
second_title: Aspose.Slides for C++ API-referentie
description: "Stelt een 3x3 matrix voor die transformatie-bewerkingen definieert. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze door te geven aan functies als argument."
type: docs
weight: 118
url: /nl/system.drawing.drawing2d/matrix/
---
## Matrixklasse


Stelt een 3x3 matrix voor die transformatie-bewerkingen definieert. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze aan functies als argument door te geven.

```cpp
class Matrix : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | Maakt een kopie van het huidige object. |
| void [Dispose](./dispose/)() | Vrijgeeft alle door het huidige object verworven systeem-bronnen. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | Test of het opgegeven object een [Matrix](./) is en identiek is aan dit object. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | Retourneert een array die de elementen van de matrix bevat in de volgende volgorde: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | Bepaalt of de matrix die door het huidige object wordt weergegeven een identiteitsmatrix is. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | Bepaalt of de matrix die door het huidige object wordt weergegeven inverteerbaar is. |
| **float** [get_OffsetX](./get_offsetx/)() const | Retourneert de X-verplaatsingswaarde van de matrix die door het huidige object wordt weergegeven. |
| **float** [get_OffsetY](./get_offsety/)() const | Retourneert de Y-verplaatsingswaarde van de matrix die door het huidige object wordt weergegeven. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| void [Invert](./invert/)() | Keert de matrix die door het huidige object wordt weergegeven om. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat door targetType wordt beschreven. Analog van de C# ‘is’-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert de vergrendeling van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-sentry-object. |
| [Matrix](./matrix/)() | Construeert een nieuw exemplaar van de [Matrix](./)-klasse die een identiteitsmatrix vertegenwoordigt. |
| [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | Construeert een nieuw exemplaar van de [Matrix](./)-klasse en initialiseert deze met de opgegeven waarden. |
| [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Construeert een nieuw exemplaar van de [Matrix](./)-klasse voor de geometrische transformatie gedefinieerd door het opgegeven rechthoek en de array van punten. |
| [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Construeert een nieuw exemplaar van de [Matrix](./)-klasse voor de geometrische transformatie gedefinieerd door het opgegeven rechthoek en de array van punten. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | Vermenigvuldigt de matrix die door het huidige object wordt weergegeven met de opgegeven matrix. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | Vermenigvuldigt de matrix die door het huidige object wordt weergegeven met de opgegeven matrix. |
| [Object](../../system/object/object/)() | Creëert het object. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object referentieel met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [Reset](./reset/)() | Reset de matrix die door het huidige object wordt weergegeven zodat deze een identiteitsmatrix wordt. |
| void [Rotate](./rotate/)(**float**) | Roteert de matrix die door het huidige object wordt weergegeven met de klok mee met de opgegeven hoek. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | Roteert de matrix die door het huidige object wordt weergegeven met de klok mee rond de oorsprong met de opgegeven hoek. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | Roteert de matrix die door het huidige object wordt weergegeven met de klok mee rond het opgegeven punt met de opgegeven hoek. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | Roteert de matrix die door het huidige object wordt weergegeven met de klok mee rond het opgegeven punt met de opgegeven hoek. |
| void [Scale](./scale/)(**float**, **float**) | Past de opgegeven schaalvector toe op de matrix die door het huidige object wordt weergegeven. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Past de opgegeven schaalvector toe op de matrix die door het huidige object wordt weergegeven. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th template-argument in als een zwakke pointer (in plaats van gedeeld). Stelt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [Shear](./shear/)(**float**, **float**) | Past de opgegeven schaafvector toe op de matrix die door het huidige object wordt weergegeven. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Past de opgegeven schaafvector toe op de matrix die door het huidige object wordt weergegeven. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Past de geometrische transformatie toe die wordt gedefinieerd door de matrix van het huidige object op de opgegeven punten. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Past de geometrische transformatie toe die wordt gedefinieerd door de matrix van het huidige object op de opgegeven punten. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Past de geometrische transformatie toe die wordt gedefinieerd door de matrix van het huidige object op de opgegeven punten. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Past de geometrische transformatie toe die wordt gedefinieerd door de matrix van het huidige object op de opgegeven punten. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Past alleen de schaal- en rotatie-componenten van de matrix van het huidige object toe op de opgegeven punten. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Past alleen de schaal- en rotatie-componenten van de matrix van het huidige object toe op de opgegeven punten. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Past alleen de schaal- en rotatie-componenten van de matrix van het huidige object toe op de opgegeven punten. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Past alleen de schaal- en rotatie-componenten van de matrix van het huidige object toe op de opgegeven punten. |
| void [Translate](./translate/)(**float**, **float**) | Past de opgegeven translatievector toe op de matrix die door het huidige object wordt weergegeven. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Past de opgegeven translatievector toe op de matrix die door het huidige object wordt weergegeven. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-sentry-object. |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Vermenigvuldigt elke vector in een array met de matrix die door het huidige object wordt weergegeven. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Vermenigvuldigt elke vector in een array met de matrix die door het huidige object wordt weergegeven. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Matrix](./~matrix/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Drawing::Drawing2D](../)
* Bibliotheek [Aspose.Slides](../../)