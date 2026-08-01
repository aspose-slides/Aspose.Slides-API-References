---
title: GraphicsPath
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een set van verbonden lijnen en curven voor. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit resulteert in runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 66
url: /nl/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath klasse


Stelt een set van verbonden lijnen en curven voor. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class GraphicsPath : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | Voegt de opgegeven elliptische boog toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | Voegt de opgegeven elliptische boog toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | Voegt de opgegeven elliptische boog toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Voegt de opgegeven elliptische boog toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Voegt de opgegeven kubieke Bézier-curve toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Voegt de opgegeven kubieke Bézier-curve toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Voegt de opgegeven kubieke Bézier-curve toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | Voegt de opgegeven kubieke Bézier-curve toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Voegt een reeks verbonden kubieke Bézier-curves toe aan de huidige figuur. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Voegt een reeks verbonden kubieke Bézier-curves toe aan de huidige figuur. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Voegt de opgegeven gesloten curve toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Voegt de opgegeven gesloten curve toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Voegt de opgegeven curve toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Voegt de opgegeven curve toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | Voegt de opgegeven curve toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | Voegt de opgegeven curve toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | Voegt de opgegeven ellips toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | Voegt de opgegeven ellips toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Voegt de opgegeven ellips toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Voegt de opgegeven ellips toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Voegt de opgegeven lijn toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Voegt de opgegeven lijn toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddLine](./addline/)(int, int, int, int) | Voegt de opgegeven lijn toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | Voegt de opgegeven lijn toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Voegt de opgegeven reeks verbonden lijnsegmenten toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Voegt de opgegeven reeks verbonden lijnsegmenten toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | Voegt het opgegeven pad toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | Voegt de opgegeven omtrek van de taartvorm toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | Voegt de opgegeven omtrek van de taartvorm toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Voegt de opgegeven omtrek van de taartvorm toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Voegt het opgegeven polygon toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Voegt het opgegeven polygon toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Voegt het opgegeven rechthoek toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Voegt het opgegeven rechthoek toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | Voegt de opgegeven reeks rechthoeken toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | Voegt de opgegeven reeks rechthoeken toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Voegt een reeks tekst toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Voegt een reeks tekst toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Voegt een reeks tekst toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Voegt een reeks tekst toe aan het pad dat wordt vertegenwoordigd door het huidige object. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | Maakt een kopie van het huidige object. |
| void [CloseAllFigures](./closeallfigures/)() | Sluit alle geopende figuren en start een nieuwe. |
| void [CloseFigure](./closefigure/)() | Sluit de huidige figuur en start een nieuwe. |
| void [Dispose](./dispose/)() | Vrijt alle door het huidige object verworven besturingssysteembronnen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-achtige floating-point vergelijking waarbij twee NaN’s als gelijk worden beschouwd, ook al wordt volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-achtige floating-point vergelijking waarbij twee NaN’s als gelijk worden beschouwd, ook al wordt volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| void [Flatten](./flatten/)() | Vlak maakt elke curve in het pad door ze om te zetten in een reeks verbonden lijnen. De vlakheidswaarde van 0.25 wordt gebruikt. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | Vlak maakt elke curve in het pad door ze om te zetten in een reeks verbonden lijnen. De vlakheidswaarde van 0.25 wordt gebruikt. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | Vlak maakt elke curve in het pad door ze om te zetten in een reeks verbonden lijnen. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | Retourneert de vulmodus van het huidige object. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | Retourneert een [PathData](../pathdata/) object dat de punten bevat die een pad vormen dat wordt vertegenwoordigd door het huidige object en hun types. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | Retourneert een array die punten bevat die een pad vormen dat wordt vertegenwoordigd door het huidige object. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | Retourneert een array die waarden bevat die de types van de punten aangeven die een pad vormen dat wordt vertegenwoordigd door het huidige object. |
| int [get_PointCount](./get_pointcount/)() const | Retourneert het aantal punten in het pad dat wordt vertegenwoordigd door het huidige object. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | Retourneert een [RectangleF](../../system.drawing/rectanglef/) object dat een rechthoek vertegenwoordigt die het pad begrenst dat wordt vertegenwoordigd door het huidige object wanneer dit wordt getransformeerd met de opgegeven matrix. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | Retourneert een waarde die een bitgewijze combinatie is van Detail::FigureType-waarden die aangeven welke type figuren zich in het pad bevinden dat wordt vertegenwoordigd door het huidige object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashen van aangepaste objecten mogelijk. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | Retourneert een [PointF](../../system.drawing/pointf/) object dat het laatste punt in het pad weergeeft. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) oproep. |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | Construeert een nieuw exemplaar van [GraphicsPath](./) klasse met de opgegeven vulmodus. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Construeert een nieuw exemplaar van [GraphicsPath](./) object dat het opgegeven pad vertegenwoordigt. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Construeert een nieuw exemplaar van [GraphicsPath](./) object dat het opgegeven pad vertegenwoordigt. |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of een object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is' operator. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Geeft aan of het opgegeven punt zich bevindt binnen (onder) de omtrek van dit [GraphicsPath](./) wanneer getekend met de opgegeven [Pen](../../system.drawing/pen/). NIET GEREALISEERD. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | Bepaalt of het opgegeven punt zich bevindt binnen het pad dat wordt vertegenwoordigd door het huidige object. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | Bepaalt of het opgegeven punt zich bevindt binnen het pad dat wordt vertegenwoordigd door het huidige object. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) toezichthouderobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignatie-operator. Kopieert niets, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentie-waarde van een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van een string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [Reset](./reset/)() | Leegt het pad door alle punten te verwijderen. |
| void [Reverse](./reverse/)() | Keert de volgorde van punten in de PathPoints-array van deze [GraphicsPath](./) om. |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | Stelt de vulmodus van het huidige object in. |
| void [SetMarkers](./setmarkers/)() | NIET GEREALISEERD. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [StartFigure](./startfigure/)() | Start een nieuwe figuur. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | Transformeert het pad dat wordt vertegenwoordigd door het huidige object door de opgegeven transformatie-matrix toe te passen. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) toezichthouderobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Vervangt dit pad door een omtrek rond het oorspronkelijke pad. |
|  [~GraphicsPath](./~graphicspath/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Bibliotheek [Aspose.Slides](../../)