---
title: GraphicsPath
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt eine Menge verbundener Linien und Kurven dar. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 66
url: /de/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath Klasse

Stellt eine Menge verbundener Linien und Kurven dar. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class GraphicsPath : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | Fügt den angegebenen elliptischen Bogen zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | Fügt den angegebenen elliptischen Bogen zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | Fügt den angegebenen elliptischen Bogen zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Fügt den angegebenen elliptischen Bogen zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Fügt die angegebene kubische Bézierkurve zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Fügt die angegebene kubische Bézierkurve zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Fügt die angegebene kubische Bézierkurve zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | Fügt die angegebene kubische Bézierkurve zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Fügt eine Sequenz verbundener kubischer Bézierkurven zur aktuellen Figur hinzu. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Fügt eine Sequenz verbundener kubischer Bézierkurven zur aktuellen Figur hinzu. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Fügt die angegebene geschlossene Kurve zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Fügt die angegebene geschlossene Kurve zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Fügt die angegebene Kurve zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Fügt die angegebene Kurve zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | Fügt die angegebene Kurve zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | Fügt die angegebene Kurve zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | Fügt die angegebene Ellipse zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | Fügt die angegebene Ellipse zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Fügt die angegebene Ellipse zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Fügt die angegebene Ellipse zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Fügt die angegebene Linie zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Fügt die angegebene Linie zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddLine](./addline/)(int, int, int, int) | Fügt die angegebene Linie zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | Fügt die angegebene Linie zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Fügt die angegebene Serie verbundener Liniensegmente zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Fügt die angegebene Serie verbundener Liniensegmente zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | Fügt den angegebenen Pfad zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | Fügt die angegebene Kontur der Kuchenform zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | Fügt die angegebene Kontur der Kuchenform zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Fügt die angegebene Kontur der Kuchenform zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Fügt das angegebene Polygon zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Fügt das angegebene Polygon zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Fügt das angegebene Rechteck zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Fügt das angegebene Rechteck zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | Fügt die angegebene Serie von Rechtecken zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | Fügt die angegebene Serie von Rechtecken zum Pfad hinzu, der vom aktuellen Objekt dargestellt wird. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Fügt dem Pfad, der vom aktuellen Objekt dargestellt wird, eine Textzeichenkette hinzu. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Fügt dem Pfad, der vom aktuellen Objekt dargestellt wird, eine Textzeichenkette hinzu. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Fügt dem Pfad, der vom aktuellen Objekt dargestellt wird, eine Textzeichenkette hinzu. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Fügt dem Pfad, der vom aktuellen Objekt dargestellt wird, eine Textzeichenkette hinzu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | Erstellt eine Kopie des aktuellen Objekts. |
| void [CloseAllFigures](./closeallfigures/)() | Schließt alle offenen Figuren und startet eine neue. |
| void [CloseFigure](./closefigure/)() | Schließt die aktuelle Figur und startet eine neue. |
| void [Dispose](./dispose/)() | Gibt alle vom aktuellen Objekt erworbenen Betriebssystemressourcen frei. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| void [Flatten](./flatten/)() | Flacht jede Kurve im Pfad ab, indem sie in eine Serie verbundener Linien umgewandelt wird. Der Flachheitswert 0,25 wird verwendet. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | Flacht jede Kurve im Pfad ab, indem sie in eine Serie verbundener Linien umgewandelt wird. Der Flachheitswert 0,25 wird verwendet. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | Flacht jede Kurve im Pfad ab, indem sie in eine Serie verbundener Linien umgewandelt wird. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | Gibt den Füllmodus des aktuellen Objekts zurück. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | Gibt ein [PathData](../pathdata/) Objekt zurück, das die Punkte enthält, aus denen ein vom aktuellen Objekt dargestellter Pfad besteht, sowie deren Typen. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | Gibt ein Array zurück, das die Punkte enthält, aus denen ein vom aktuellen Objekt dargestellter Pfad besteht. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | Gibt ein Array zurück, das Werte enthält, die die Typen der Punkte angeben, aus denen ein vom aktuellen Objekt dargestellter Pfad besteht. |
| int [get_PointCount](./get_pointcount/)() const | Gibt die Anzahl der Punkte im Pfad zurück, der vom aktuellen Objekt dargestellt wird. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | Gibt ein [RectangleF](../../system.drawing/rectanglef/) Objekt zurück, das ein Rechteck beschreibt, das den Pfad umschließt, wenn er mit der angegebenen Matrix transformiert wird. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | Gibt einen Wert zurück, der eine bitweise Kombination von Detail::FigureType-Werten ist und angibt, welche Figurtypen im Pfad enthalten sind. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | Gibt ein [PointF](../../system.drawing/pointf/) Objekt zurück, das den letzten Punkt im Pfad darstellt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analogie zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | Konstruiert eine neue Instanz der Klasse [GraphicsPath](./) mit dem angegebenen Füllmodus. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Konstruiert eine neue Instanz des Objekts [GraphicsPath](./), das den angegebenen Pfad darstellt. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Konstruiert eine neue Instanz des Objekts [GraphicsPath](./), das den angegebenen Pfad darstellt. |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs ist. Analogie zum C#-„is“-Operator. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses [GraphicsPath](./) liegt, wenn er mit dem angegebenen [Pen](../../system.drawing/pen/) gezeichnet wird. NICHT IMPLEMENTIERT. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | Bestimmt, ob der angegebene Punkt innerhalb des Pfads liegt, der vom aktuellen Objekt dargestellt wird. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | Bestimmt, ob der angegebene Punkt innerhalb des Pfads liegt, der vom aktuellen Objekt dargestellt wird. |
| void [Lock](../../system/object/lock/)() | Implementiert das C# lock()-Statement. Direkt aufrufen oder das Sentry-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [Reset](./reset/)() | Leert den Pfad, indem alle Punkte entfernt werden. |
| void [Reverse](./reverse/)() | Kehrt die Reihenfolge der Punkte im PathPoints-Array dieses [GraphicsPath](./) um. |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | Setzt den Füllmodus des aktuellen Objekts. |
| void [SetMarkers](./setmarkers/)() | NICHT IMPLEMENTIERT. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umstellen von Zeigern in Containern auf schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [StartFigure](./startfigure/)() | Startet eine neue Figur. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in eine Zeichenkette. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | Transformiert den Pfad, der vom aktuellen Objekt dargestellt wird, indem die angegebene Transformationsmatrix darauf angewendet wird. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das C# lock()-Statement zum Entsperren. Direkt aufrufen oder das Sentry-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Ersetzt diesen Pfad durch eine Kontur um den ursprünglichen Pfad. |
|  [~GraphicsPath](./~graphicspath/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Drawing::Drawing2D](../)
* Bibliothek [Aspose.Slides](../../)