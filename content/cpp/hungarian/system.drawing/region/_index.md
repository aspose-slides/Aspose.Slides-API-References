---
title: Region
second_title: Aspose.Slides for C++ API Referencia
description: "A grafikus alakzat belsejét reprezentálja. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót a függvényekhez argumentumként történő átadáshoz."
type: docs
weight: 261
url: /hu/system.drawing/region/
---
## Region osztály

A grafikus alakzat belsejét reprezentálja. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozza létre ennek a típusnak példányát a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként történő átadáshoz.

```cpp
class Region : public System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | Visszaadja az aktuális objektum másolatát. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott téglalap által meghatározott, az ezzel a régióval nem metsződő részre. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott téglalap által meghatározott, az ezzel a régióval nem metsződő részre. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott úttal meghatározott, az ezzel a régióval nem metsződő részre. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott régió azon részére, amely nem metsződik ezzel a régióval. |
| void [Dispose](./dispose/)() | Felszabadítja az aktuális objektum által megszerzett összes operációs rendszer erőforrást. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Megállapítja, hogy a megadott régió azonos-e a jelenlegi objektum által képviselt régióval a megadott rajzoló felületen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott téglalap által definiált régió kizárásának eredményére. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott téglalap által definiált régió kizárásának eredményére. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott úttal definiált régió kizárásának eredményére. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott régió kizárásának eredményére. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Lekéri egy [RectangleF](../rectanglef/) struktúrát, amely egy téglalapot reprezentál, mely a [Region](./)-et határolja a [Graphics](../graphics/) objektum rajzoló felületén. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi az egyedi objektumok hash-elését. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | Visszaad egy RegionData objektumot, amely adatokat tartalmaz, melyek definiálják az aktuális objektum által képviselt régiót. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | Visszaad egy [RectangleF](../rectanglef/) struktúratömböt, amely közelíti ezt a [Region](./)-t a megadott mátrix transzformáció alkalmazása után. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott téglalappal definiált régióval való metszet eredményére. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott téglalappal definiált régióval való metszet eredményére. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott úttal definiált régióval való metszet eredményére. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott régióval való metszet eredményére. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Megállapítja, hogy az aktuális objektum által képviselt régiónak üres belső területe van-e a megadott rajzoló felületen. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Megállapítja, hogy az aktuális objektum által képviselt régiónak végtelen belső területe van-e a megadott rajzoló felületen. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | Megállapítja, hogy a megadott pont a jelenlegi objektum által képviselt régióban van-e. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | Megállapítja, hogy a megadott pont a jelenlegi objektum által képviselt régióban van-e. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | Megállapítja, hogy a megadott téglalap bármely része a jelenlegi objektum által képviselt régióban van-e. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | Megállapítja, hogy a megadott téglalap bármely része a jelenlegi objektum által képviselt régióban van-e. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Megállapítja, hogy a megadott pont a jelenlegi objektum által képviselt régióban van-e a megadott grafika használatával. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Megállapítja, hogy a megadott pont a jelenlegi objektum által képviselt régióban van-e a megadott grafika használatával. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Megállapítja, hogy a megadott téglalap bármely része a jelenlegi objektum által képviselt régióban van-e a megadott grafika használatával. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Megállapítja, hogy a megadott téglalap bármely része a jelenlegi objektum által képviselt régióban van-e a megadott grafika használatával. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | Megállapítja, hogy a megadott pont a jelenlegi objektum által képviselt régióban van-e. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Megállapítja, hogy a megadott pont a jelenlegi objektum által képviselt régióban van-e a megadott grafika használatával. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| void [MakeEmpty](./makeempty/)() | Inicializálja az aktuális objektumot üres belső területtel. |
| void [MakeInfinite](./makeinfinite/)() | Inicializálja ezt a régió objektumot végtelen belső területtel. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi alosztályok másolását. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi alosztályok másolását. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával összehasonlítja az értéktípusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
|  [Region](./region/)() | Létrehozza a [Region](./) osztály új példányát. |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | Létrehozza a [Region](./) osztály új példányát, amely a megadott téglalappal definiált régiót reprezentál. |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | Létrehozza a [Region](./) osztály új példányát, amely a megadott téglalappal definiált régiót reprezentál. |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Létrehozza a [Region](./) osztály új példányát, amely a megadott úttal definiált régiót reprezentál. |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | Létrehozza a [Region](./) osztály új példányát, amely a megadott RegionData objektummal definiált régiót reprezentál. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (nem megosztottra). Lehetővé teszi a mutatók átkapcsolását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Átalakítja ezt a régiót a megadott mátrixszal. |
| void [Transform](./transform/)(const SkMatrix\&) | Átalakítja ezt a régiót a megadott mátrixszal. |
| void [Translate](./translate/)(int, int) | Elmozdítja a régió koordinátáit a megadott mennyiséggel. |
| void [Translate](./translate/)(**float**, **float**) | Elmozdítja a régió koordinátáit a megadott mennyiséggel. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott téglalappal definiált régióval végzett unió művelet eredményére. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott téglalappal definiált régióval végzett unió eredményére. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott úttal definiált régióval végzett unió eredményére. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott régióval végzett unió eredményére. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott téglalappal definiált, azzal nem metsződő részek eredményére. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott téglalappal definiált, azzal nem metsződő részek eredményére. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott úttal definiált, azzal nem metsződő részek eredményére. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Lecseréli az aktuális objektum által képviselt régiót a megadott régióval, azzal nem metsződő részek eredményére. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
| virtual  [~Region](./~region/)() | Destruktor. |
## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [System::Drawing](../)
* Könyvtár [Aspose.Slides](../../)