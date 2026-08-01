---
title: GeometryPath
second_title: Aspose.Slides voor C++ API-referentie
description: Representeert geometrisch pad van GeometryShape
type: docs
weight: 1067
url: /nl/aspose.slides/geometrypath/
---
## GeometryPath klasse


Represents geometry path of [GeometryShape](../geometryshape/)

```cpp
class GeometryPath : public Aspose::Slides::IGeometryPath
```

## Methoden

| Method | Description |
| --- | --- |
| void [ArcTo](./arcto/)(**float**, **float**, **float**, **float**) override | Voegt de gespecificeerde boog toe aan het pad. |
| void [CloseFigure](./closefigure/)() override | Sluit de huidige figuur van dit pad |
| void [CubicBezierTo](./cubicbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/)) override | Voegt een kubieke Bezier-curve toe aan het einde van het pad |
| void [CubicBezierTo](./cubicbezierto/)(**float**, **float**, **float**, **float**, **float**, **float**) override | Voegt een kubieke Bezier-curve toe aan het einde van het pad |
| void [CubicBezierTo](./cubicbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | Voegt een kubieke Bezier-curve toe op de opgegeven plaats van het pad |
| void [CubicBezierTo](./cubicbezierto/)(**float**, **float**, **float**, **float**, **float**, **float**, **uint32_t**) override | Voegt een kubieke Bezier-curve toe op de opgegeven plaats van het pad |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-achtige floating point-vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-achtige floating point-vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
|  [GeometryPath](./geometrypath/)() | Creëert een instantie van [GeometryPath](./) |
| [PathFillModeType](../pathfillmodetype/) [get_FillMode](./get_fillmode/)() override | Stelt de vulmodus in |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPathSegment](../ipathsegment/)\>\> [get_PathData](./get_pathdata/)() override | Retourneert het geometrische pad van [GeometryShape](../geometryshape/) als een array van padsegmenten. |
| **bool** [get_Stroke](./get_stroke/)() override | Stelt de lijnstijl in |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentie-teller datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C#-operator 'is'. |
| void [LineTo](./lineto/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Voegt een lijn toe aan het einde van het pad |
| void [LineTo](./lineto/)(**float**, **float**) override | Voegt een lijn toe aan het einde van het pad |
| void [LineTo](./lineto/)([System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | Voegt een lijn toe op de opgegeven plaats van het pad |
| void [LineTo](./lineto/)(**float**, **float**, **uint32_t**) override | Voegt een lijn toe op de opgegeven plaats van het pad |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarschuwingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
| void [MoveTo](./moveto/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Stelt de positie van het volgende punt in. |
| void [MoveTo](./moveto/)(**float**, **float**) override | Stelt de positie van het volgende punt in. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, eigenlijk, alleen een nieuw object initialiseren en kopieerconstructie van subklassen mogelijk maken. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, eigenlijk, alleen een nieuw object initialiseren en kopieerconstructie van subklassen mogelijk maken. |
| void [QuadraticBezierTo](./quadraticbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/)) override | Voegt een kwadratische Bezier-curve toe aan het einde van het pad |
| void [QuadraticBezierTo](./quadraticbezierto/)(**float**, **float**, **float**, **float**) override | Voegt een kwadratische Bezier-curve toe aan het einde van het pad |
| void [QuadraticBezierTo](./quadraticbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | Voegt een kwadratische Bezier-curve toe op de opgegeven plaats van het pad |
| void [QuadraticBezierTo](./quadraticbezierto/)(**float**, **float**, **float**, **float**, **uint32_t**) override | Voegt een kwadratische Bezier-curve toe op de opgegeven plaats van het pad |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt via referentie een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| void [RemoveAt](./removeat/)(**int32_t**) override | Verwijdert segment op de opgegeven index van het geometrische pad. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_FillMode](./set_fillmode/)([PathFillModeType](../pathfillmodetype/)) override | Stelt de vulmodus in |
| void [set_Stroke](./set_stroke/)(**bool**) override | Stelt de lijnstijl in |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeelde). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarschuwingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |
## Zie ook

* Klasse [IGeometryPath](../igeometrypath/)
* Naamruimte [Aspose::Slides](../)
* Library [Aspose.Slides](../../)