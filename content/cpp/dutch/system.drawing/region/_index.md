---
title: Region
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt het interieur van een grafische vorm voor. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Omhul deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om het als argument aan functies door te geven."
type: docs
weight: 261
url: /nl/system.drawing/region/
---
## Region klasse

Stelt het interieur van een grafische vorm voor. Objecten van deze klasse moeten alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om hem als argument aan functies door te geven.

```cpp
class Region : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | Retourneert een kopie van het huidige object. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | Vervangt het gebied dat door het huidige object wordt gerepresenteerd door het gedeelte van het gebied dat wordt gedefinieerd door de opgegeven rechthoek en dat niet overlapt met dit gebied. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | Vervangt het gebied dat door het huidige object wordt gerepresenteerd door het gedeelte van het gebied dat wordt gedefinieerd door de opgegeven rechthoek en dat niet overlapt met dit gebied. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Vervangt het gebied dat door het huidige object wordt gerepresenteerd door het gedeelte van het gebied dat wordt gedefinieerd door het opgegeven pad en dat niet overlapt met dit gebied. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Vervangt het gebied dat door het huidige object wordt gerepresenteerd door het gedeelte van het opgegeven gebied dat niet overlapt met dit gebied. |
| void [Dispose](./dispose/)() | Vrijgeeft alle besturingssysteembronnen die door het huidige object zijn verkregen. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Bepaalt of het opgegeven gebied identiek is aan het gebied dat door het huidige object wordt gerepresenteerd op het opgegeven tekenoppervlak. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | Vervangt het gebied dat door het huidige object wordt gerepresenteerd door het resultaat van het uitsluiten van het gebied dat door de opgegeven rechthoek wordt gedefinieerd. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | Vervangt het gebied dat door het huidige object wordt gerepresenteerd door het resultaat van het uitsluiten van het gebied dat door de opgegeven rechthoek wordt gedefinieerd. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Vervangt het gebied dat door het huidige object wordt gerepresenteerd door het resultaat van het uitsluiten van het gebied dat door het opgegeven pad wordt gedefinieerd. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Vervangt het gebied dat door het huidige object wordt gerepresenteerd door het resultaat van het uitsluiten van het opgegeven gebied. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Haalt een [RectangleF](../rectanglef/)-structuur op die een rechthoek vertegenwoordigt die dit [Region](./) begrenst op het tekenoppervlak van een [Graphics](../graphics/)-object. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | Retourneert een RegionData-object dat gegevens bevat die het gebied definiëren dat door het huidige object wordt gerepresenteerd. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | Retourneert een array van [RectangleF](../rectanglef/)-structuren die dit [Region](./) benaderen nadat de opgegeven matrixtransformatie is toegepast. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | Vervangt het gebied ... door het resultaat van de intersectie van dit gebied en een door de opgegeven rechthoek gedefinieerd gebied. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | Vervangt het gebied ... door het resultaat van de intersectie van dit gebied en een door de opgegeven rechthoek gedefinieerd gebied. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Vervangt het gebied ... door het resultaat van de intersectie van dit gebied en een door het opgegeven pad gedefinieerd gebied. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Vervangt het gebied ... door het resultaat van de intersectie van dit gebied en het opgegeven gebied. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van de C# ‘is’-operator. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Bepaalt of het door het huidige object gerepresenteerde gebied een lege binnenkant heeft op het opgegeven tekenoppervlak. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Bepaalt of het door het huidige object gerepresenteerde gebied een oneindige binnenkant heeft op het opgegeven tekenoppervlak. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | Bepaalt of het opgegeven punt zich binnen het door het huidige object gerepresenteerde gebied bevindt. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | Bepaalt of het opgegeven punt zich binnen het door het huidige object gerepresenteerde gebied bevindt. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | Bepaalt of een deel van de opgegeven rechthoek zich binnen het door het huidige object gerepresenteerde gebied bevindt. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | Bepaalt of een deel van de opgegeven rechthoek zich binnen het door het huidige object gerepresenteerde gebied bevindt. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Bepaalt of het opgegeven punt zich binnen het door het huidige object gerepresenteerde gebied bevindt, gebruikmakend van de opgegeven graphics. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Bepaalt of het opgegeven punt zich binnen het door het huidige object gerepresenteerde gebied bevindt, gebruikmakend van de opgegeven graphics. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Bepaalt of een deel van de opgegeven rechthoek zich binnen het door het huidige object gerepresenteerde gebied bevindt, gebruikmakend van de opgegeven graphics. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Bepaalt of een deel van de opgegeven rechthoek zich binnen het door het huidige object gerepresenteerde gebied bevindt, gebruikmakend van de opgegeven graphics. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | Bepaalt of het opgegeven punt zich binnen het door het huidige object gerepresenteerde gebied bevindt. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Bepaalt of het opgegeven punt zich binnen het door het huidige object gerepresenteerde gebied bevindt, gebruikmakend van de opgegeven graphics. |
| void [Lock](../../system/object/lock/)() | Implementeert de C# lock()-statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| void [MakeEmpty](./makeempty/)() | Initialiseert het huidige object met een lege binnenkant. |
| void [MakeInfinite](./makeinfinite/)() | Initialiseert dit gebiedsobject met een oneindige binnenkant. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
| [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object via referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van een string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| [Region](./region/)() | Construeert een nieuw exemplaar van de [Region](./) klasse. |
| [Region](./region/)(const [RectangleF](../rectanglef/)\&) | Construeert een nieuw exemplaar van de [Region](./) klasse die een gebied vertegenwoordigt gedefinieerd door de opgegeven rechthoek. |
| [Region](./region/)(const [Rectangle](../rectangle/)\&) | Construeert een nieuw exemplaar van de [Region](./) klasse die een gebied vertegenwoordigt gedefinieerd door de opgegeven rechthoek. |
| [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Construeert een nieuw exemplaar van de [Region](./) klasse die een gebied vertegenwoordigt gedefinieerd door het opgegeven pad. |
| [Region](./region/)(const SkPath\&) |  |
| [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | Construeert een nieuw exemplaar van de [Region](./) klasse die een gebied vertegenwoordigt gedefinieerd door het opgegeven RegionData-object. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-templatesargument in op een zwakke pointer (in plaats van gedeeld). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Transformeert dit gebied met de opgegeven matrix. |
| void [Transform](./transform/)(const SkMatrix\&) | Transformeert dit gebied met de opgegeven matrix. |
| void [Translate](./translate/)(int, int) | Verplaatst de coördinaten van het gebied met de opgegeven hoeveelheid. |
| void [Translate](./translate/)(**float**, **float**) | Verplaatst de coördinaten van het gebied met de opgegeven hoeveelheid. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | Vervangt het gebied ... door het resultaat van de unie-operatie van dit gebied en een gebied gedefinieerd door de opgegeven rechthoek. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | Vervangt het gebied ... door het resultaat van de unie-operatie van dit gebied en een gebied gedefinieerd door de opgegeven rechthoek. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Vervangt het gebied ... door het resultaat van de unie-operatie van dit gebied en een gebied gedefinieerd door het opgegeven pad. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Vervangt het gebied ... door het resultaat van de unie van dit gebied en het opgegeven gebied. |
| void [Unlock](../../system/object/unlock/)() | Implementeert de C# lock()-statement ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | Vervangt het gebied ... door de delen van dit gebied en het door de opgegeven rechthoek gedefinieerde gebied die niet overlappen. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | Vervangt het gebied ... door de delen van dit gebied en het door de opgegeven rechthoek gedefinieerde gebied die niet overlappen. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Vervangt het gebied ... door de delen van dit gebied en het door het opgegeven pad gedefinieerde gebied die niet overlappen. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Vervangt het gebied ... door de delen van dit gebied en het opgegeven gebied die niet overlappen. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |
| virtual  [~Region](./~region/)() | Destructor. |

## Zie ook

* Klasse [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Bibliotheek [Aspose.Slides](../../)