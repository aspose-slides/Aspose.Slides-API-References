---
title: GraphicsPath
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en samling av anslutna linjer och kurvor. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körtidsfel och/eller assertionsfel. Inslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 66
url: /sv/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath klass

Representerar en samling av anslutna linjer och kurvor. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körtidsfel och/eller assertionfel. Inslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class GraphicsPath : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | Lägger till den angivna elliptiska bågen till den bana som representeras av det aktuella objektet. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | Lägger till den angivna elliptiska bågen till den bana som representeras av det aktuella objektet. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | Lägger till den angivna elliptiska bågen till den bana som representeras av det aktuella objektet. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Lägger till den angivna elliptiska bågen till den bana som representeras av det aktuella objektet. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Lägger till den angivna kubiska Bezier-kurvan till den bana som representeras av det aktuella objektet. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Lägger till den angivna kubiska Bezier-kurvan till den bana som representeras av det aktuella objektet. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Lägger till den angivna kubiska Bezier-kurvan till den bana som representeras av det aktuella objektet. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | Lägger till den angivna kubiska Bezier-kurvan till den bana som representeras av det aktuella objektet. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Lägger till en sekvens av anslutna kubiska Bezier-kurvor till den aktuella figuren. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Lägger till en sekvens av anslutna kubiska Bezier-kurvor till den aktuella figuren. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Lägger till den angivna slutna kurvan till den bana som representeras av det aktuella objektet. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Lägger till den angivna slutna kurvan till den bana som representeras av det aktuella objektet. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Lägger till den angivna kurvan till den bana som representeras av det aktuella objektet. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Lägger till den angivna kurvan till den bana som representeras av det aktuella objektet. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | Lägger till den angivna kurvan till den bana som representeras av det aktuella objektet. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | Lägger till den angivna kurvan till den bana som representeras av det aktuella objektet. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | Lägger till den angivna ellipsen till den bana som representeras av det aktuella objektet. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | Lägger till den angivna ellipsen till den bana som representeras av det aktuella objektet. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Lägger till den angivna ellipsen till den bana som representeras av det aktuella objektet. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Lägger till den angivna ellipsen till den bana som representeras av det aktuella objektet. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Lägger till den angivna linjen till den bana som representeras av det aktuella objektet. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Lägger till den angivna linjen till den bana som representeras av det aktuella objektet. |
| void [AddLine](./addline/)(int, int, int, int) | Lägger till den angivna linjen till den bana som representeras av det aktuella objektet. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | Lägger till den angivna linjen till den bana som representeras av det aktuella objektet. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Lägger till den angivna serien av anslutna linjesegment till den bana som representeras av det aktuella objektet. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Lägger till den angivna serien av anslutna linjesegment till den bana som representeras av det aktuella objektet. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | Lägger till den angivna banan till den bana som representeras av det aktuella objektet. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | Lägger till den angivna konturen av pajformen till den bana som representeras av det aktuella objektet. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | Lägger till den angivna konturen av pajformen till den bana som representeras av det aktuella objektet. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Lägger till den angivna konturen av pajformen till den bana som representeras av det aktuella objektet. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Lägger till den angivna polygonen till den bana som representeras av det aktuella objektet. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Lägger till den angivna polygonen till den bana som representeras av det aktuella objektet. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Lägger till den angivna rektangeln till den bana som representeras av det aktuella objektet. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Lägger till den angivna rektangeln till den bana som representeras av det aktuella objektet. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | Lägger till den angivna serien av rektanglar till den bana som representeras av det aktuella objektet. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | Lägger till den angivna serien av rektanglar till den bana som representeras av det aktuella objektet. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Lägger till en textsträng till den bana som representeras av det aktuella objektet. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Lägger till en textsträng till den bana som representeras av det aktuella objektet. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Lägger till en textsträng till den bana som representeras av det aktuella objektet. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Lägger till en textsträng till den bana som representeras av det aktuella objektet. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | Skapar en kopia av det aktuella objektet. |
| void [CloseAllFigures](./closeallfigures/)() | Stänger alla öppna figurer och startar en ny. |
| void [CloseFigure](./closefigure/)() | Stänger den aktuella figuren och startar en ny. |
| void [Dispose](./dispose/)() | Frigör alla operativsystemresurser som har erhållits av det aktuella objektet. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| void [Flatten](./flatten/)() | Förenklar varje kurva i banan genom att konvertera dem till en serie av anslutna linjer. Värdet för flatness på 0.25 används. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | Förenklar varje kurva i banan genom att konvertera dem till en serie av anslutna linjer. Värdet för flatness på 0.25 används. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | Förenklar varje kurva i banan genom att konvertera dem till en serie av anslutna linjer. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | Returnerar fyllningsläget för det aktuella objektet. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | Returnerar ett [PathData](../pathdata/)-objekt som innehåller de punkter som bildar en bana som representeras av det aktuella objektet samt deras typer. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | Returnerar en array som innehåller punkter som bildar en bana som representeras av det aktuella objektet. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | Returnerar en array som innehåller värden som indikerar typerna på de punkter som bildar en bana som representeras av det aktuella objektet. |
| int [get_PointCount](./get_pointcount/)() const | Returnerar antalet punkter i den bana som representeras av det aktuella objektet. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | Returnerar ett [RectangleF](../../system.drawing/rectanglef/)-objekt som representerar en rektangel som omger den bana som representeras av det aktuella objektet när den transformeras med den angivna matrisen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastrukturen som är associerad med objektet. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | Returnerar ett värde som är en bitvis kombination av Detail::FigureType-värden som indikerar vilka typer av figurer som finns i den bana som representeras av det aktuella objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av egna objekt. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | Returnerar ett [PointF](../../system.drawing/pointf/)-objekt som representerar den sista punkten i banan. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | Skapar en ny instans av klassen [GraphicsPath](./) med det angivna fyllningsläget. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Skapar en ny instans av objektet [GraphicsPath](./) som representerar den angivna banan. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Skapar en ny instans av objektet [GraphicsPath](./) som representerar den angivna banan. |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Anger om den angivna punkten ligger inom (under) konturen av detta [GraphicsPath](./) när den ritas med den angivna [Pen](../../system.drawing/pen/). INTE IMPLEMENTERAD. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | Bestämmer om den angivna punkten ligger inom den bana som representeras av det aktuella objektet. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | Bestämmer om den angivna punkten ligger inom den bana som representeras av det aktuella objektet. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-uttrycket. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av egna typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopiekonstruktion av subklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopiekonstruktion av subklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför ett värdetyp-objekt med nullptr efter referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med det angivna värdet. |
| void [Reset](./reset/)() | Tömmer banan genom att ta bort alla punkter från den. |
| void [Reverse](./reverse/)() | Vänder ordningen på punkterna i PathPoints-arrayen för denna [GraphicsPath](./). |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | Ställer in fyllningsläget för det aktuella objektet. |
| void [SetMarkers](./setmarkers/)() | INTE IMPLEMENTERAD. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [StartFigure](./startfigure/)() | Startar en ny figur. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av egna objekt till sträng. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | Transformerar banan som representeras av det aktuella objektet genom att applicera den angivna omvandlingsmatrisen på den. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning enligt C# lock()-uttrycket. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Ersätter denna bana med en kontur runt den ursprungliga banan. |
|  [~GraphicsPath](./~graphicspath/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [System::Drawing::Drawing2D](../)
* Bibliotek [Aspose.Slides](../../)