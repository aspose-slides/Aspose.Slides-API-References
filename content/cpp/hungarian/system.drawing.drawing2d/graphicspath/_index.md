---
title: GraphicsPath
second_title: Aspose.Slides C++ API Referencia
description: "Ábrázol egy összekapcsolt vonalakból és görbékből álló halmazt. Ennek az osztálynak az objektumait csak a System::MakeObject() függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként történő függvényhíváshoz."
type: docs
weight: 66
url: /hu/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath osztály

Egy összekapcsolt vonalakból és görbékből álló halmazt reprezentál. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

```cpp
class GraphicsPath : public System::Object
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | Hozzáadja a megadott ellipszis ívet az aktuális objektum által reprezentált úthoz. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | Hozzáadja a megadott ellipszis ívet az aktuális objektum által reprezentált úthoz. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | Hozzáadja a megadott ellipszis ívet az aktuális objektum által reprezentált úthoz. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Hozzáadja a megadott ellipszis ívet az aktuális objektum által reprezentált úthoz. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Hozzáadja a megadott köbös Bézier-görbét az aktuális objektum által reprezentált úthoz. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Hozzáadja a megadott köbös Bézier-görbét az aktuális objektum által reprezentált úthoz. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Hozzáadja a megadott köbös Bézier-görbét az aktuális objektum által reprezentált úthoz. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | Hozzáadja a megadott köbös Bézier-görbét az aktuális objektum által reprezentált úthoz. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Hozzáad egy sor összekapcsolt köbös Bézier-görbét az aktuális alakzathoz. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Hozzáad egy sor összekapcsolt köbös Bézier-görbét az aktuális alakzathoz. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Hozzáadja a megadott zárt görbét az aktuális objektum által reprezentált úthoz. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Hozzáadja a megadott zárt görbét az aktuális objektum által reprezentált úthoz. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Hozzáadja a megadott görbét az aktuális objektum által reprezentált úthoz. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Hozzáadja a megadott görbét az aktuális objektum által reprezentált úthoz. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | Hozzáadja a megadott görbét az aktuális objektum által reprezentált úthoz. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | Hozzáadja a megadott görbét az aktuális objektum által reprezentált úthoz. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | Hozzáadja a megadott ellipszist az aktuális objektum által reprezentált úthoz. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | Hozzáadja a megadott ellipszist az aktuális objektum által reprezentált úthoz. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Hozzáadja a megadott ellipszist az aktuális objektum által reprezentált úthoz. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Hozzáadja a megadott ellipszist az aktuális objektum által reprezentált úthoz. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Hozzáadja a megadott vonalat az aktuális objektum által reprezentált úthoz. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Hozzáadja a megadott vonalat az aktuális objektum által reprezentált úthoz. |
| void [AddLine](./addline/)(int, int, int, int) | Hozzáadja a megadott vonalat az aktuális objektum által reprezentált úthoz. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | Hozzáadja a megadott vonalat az aktuális objektum által reprezentált úthoz. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Hozzáadja a megadott összekapcsolt vonalszakaszok sorozatát az aktuális objektum által reprezentált úthoz. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Hozzáadja a megadott összekapcsolt vonalszakaszok sorozatát az aktuális objektum által reprezentált úthoz. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | Hozzáadja a megadott utat az aktuális objektum által reprezentált úthoz. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | Hozzáadja a megadott kördiagram körvonalát az aktuális objektum által reprezentált úthoz. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | Hozzáadja a megadott kördiagram körvonalát az aktuális objektum által reprezentált úthoz. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Hozzáadja a megadott kördiagram körvonalát az aktuális objektum által reprezentált úthoz. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Hozzáadja a megadott sokszöget az aktuális objektum által reprezentált úthoz. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Hozzáadja a megadott sokszöget az aktuális objektum által reprezentált úthoz. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Hozzáadja a megadott téglalapot az aktuális objektum által reprezentált úthoz. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Hozzáadja a megadott téglalapot az aktuális objektum által reprezentált úthoz. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | Hozzáadja a megadott téglalapok sorozatát az aktuális objektum által reprezentált úthoz. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | Hozzáadja a megadott téglalapok sorozatát az aktuális objektum által reprezentált úthoz. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Hozzáad egy szövegsorozatot az aktuális objektum által reprezentált úthoz. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Hozzáad egy szövegsorozatot az aktuális objektum által reprezentált úthoz. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Hozzáad egy szövegsorozatot az aktuális objektum által reprezentált úthoz. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Hozzáad egy szövegsorozatot az aktuális objektum által reprezentált úthoz. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | Létrehozza az aktuális objektum másolatát. |
| void [CloseAllFigures](./closeallfigures/)() | Bezárja az összes nyitott alakzatot és új rajzot indít. |
| void [CloseFigure](./closefigure/)() | Bezárja az aktuális alakzatot és újabbat indít. |
| void [Dispose](./dispose/)() | Felszabadítja az aktuális objektum által felvett összes operációs rendszer erőforrást. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| void [Flatten](./flatten/)() | Laposítja az út minden görbéjét, azokat összekapcsolt vonal sorozattá alakítva. 0.25 értékű laposságot használ. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | Laposítja az út minden görbéjét, azokat összekapcsolt vonal sorozattá alakítva. 0.25 értékű laposságot használ. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | Laposítja az út minden görbéjét, azokat összekapcsolt vonal sorozattá alakítva. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | Returns the fill mode of the current object. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | Visszaad egy [PathData](../pathdata/) objektumot, amely tartalmazza az aktuális objektum által reprezentált út pontjait és azok típusait. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | Visszaad egy tömböt, amely az aktuális objektum által reprezentált út pontjait tartalmazza. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | Visszaad egy tömböt, amely értékeket tartalmaz a pontok típusának jelzésére az aktuális objektum által reprezentált úton. |
| int [get_PointCount](./get_pointcount/)() const | Visszaadja az aktuális objektum által reprezentált út pontjainak számát. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | Visszaad egy [RectangleF](../../system.drawing/rectanglef/) objektumot, amely a megadott mátrixszal transzformált, az aktuális objektum által reprezentált utat körülölelő téglalapot jelenti. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | Visszaad egy értéket, amely a Detail::FigureType értékek bitenkénti kombinációja, és jelzi, hogy milyen típusú alakzatok találhatók az aktuális objektum által reprezentált úton. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | Visszaad egy [PointF](../../system.drawing/pointf/) objektumot, amely az út utolsó pontját reprezentálja. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | Létrehoz egy új példányt a [GraphicsPath](./) osztályból a megadott kitöltési móddal. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Létrehoz egy új [GraphicsPath](./) objektumot, amely a megadott utat reprezentálja. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Létrehoz egy új [GraphicsPath](./) objektumot, amely a megadott utat reprezentálja. |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum egy példány-e a targetType által leírt típusból. A C# 'is' operátor analógja. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Jeleníti, hogy a megadott pont a [GraphicsPath](./) körvonalán (alatt) van-e, amikor a megadott [Pen](../../system.drawing/pen/)-vel rajzolják. NINCS IMPLEMENTÁLVA. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | Megállapítja, hogy a megadott pont az aktuális objektum által reprezentált úton belül van-e. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | Megállapítja, hogy a megadott pont az aktuális objektum által reprezentált úton belül van-e. |
| void [Lock](../../system/object/lock/)() | Implementálja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-összehasonlítja az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [Reset](./reset/)() | Kiüríti az utat, eltávolítva róla az összes pontot. |
| void [Reverse](./reverse/)() | Megfordítja a pontok sorrendjét a [GraphicsPath](./) PathPoints tömbjében. |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | Beállítja az aktuális objektum kitöltési módját. |
| void [SetMarkers](./setmarkers/)() | NINCS IMPLEMENTÁLVA. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (nem megosztott). Lehetővé teszi a mutatók konténerben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [StartFigure](./startfigure/)() | Új alakzatot kezd. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | Átalakítja az aktuális objektum által reprezentált utat a megadott transzformációs mátrix alkalmazásával. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementálja a C# typeof([System.Object](../../system/object/)) szerkezetet. |
| void [Unlock](../../system/object/unlock/)() | Implementálja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Lecseréli ezt az utat egy körvonalra, amely az eredeti út körül húzódik. |
|  [~GraphicsPath](./~graphicspath/)() | Megsemmisítő. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [System::Drawing::Drawing2D](../)
* Könyvtár [Aspose.Slides](../../)