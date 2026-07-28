---
title: GeometryShape
second_title: Aspose.Slides C++ API referencia
description: Az összes geometriai alakzat szülőosztályát képviseli.
type: docs
weight: 1080
url: /hu/aspose.slides/geometryshape/
---
## GeometryShape osztály

A szülőosztályt képviseli az összes geometriai alakzat számára.

```cpp
class GeometryShape : public Aspose::Slides::Shape,
                      public virtual Aspose::Slides::IGeometryShape
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Új helyőrzőt ad hozzá, ha nincs, és a helyőrző tulajdonságait egy meghatározottra állítja. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](./createshapeelements/)() override | Létrehozza és visszaadja az alakzat elemeinek tömbjét. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | A C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | A C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](./get_adjustment/)(**int32_t**) override | Visszaadja az alakzat beállítási értékét a megadott indexnél. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](./get_adjustments/)() override | Visszaadja az alakzat beállítási értékeinek gyűjteményét. Csak olvasható [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Visszaadja az alakzathoz tartozó alternatív szöveget. Olvasás [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Visszaadja az alakzathoz tartozó alternatív szöveg címét. Olvasás [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | A tulajdonság meghatározza, hogy az alakzat fekete-fehér megjelenítési módban hogyan jelenik meg. Olvasás [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Visszaadja az alakzaton lévő csatlakozási pontok számát. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Visszaadja az alakzat egyéni adatait. Csak olvasható [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Visszaadja a [EffectFormat](../effectformat/) objektumot, amely tartalmazza az alakzatra alkalmazott képponthatásokat. Megjegyzés: bizonyos alakzattípusoknál, amelyeknek nincs hatás tulajdonsága, null értéket ad vissza. Csak olvasható [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Visszaadja a [FillFormat](../fillformat/) objektumot, amely tartalmazza az alakzat kitöltésformázási tulajdonságait. Megjegyzés: bizonyos alakzattípusoknál, amelyeknek nincs kitöltési tulajdonsága, null értéket ad vissza. Csak olvasható [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Visszaadja az alakzat keret tulajdonságait. Olvasás [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Megkapja az alakzat magasságát pontokban mérve. Olvasás **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Megállapítja, hogy az alakzat rejtett-e. Olvasás **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Visszaadja az egérkattintásra definiált hiperhivatkozást. Olvasás [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Visszaadja a hiperhivatkozáskezelőt. Csak olvasható [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Visszaadja az egér fölé viszésre definiált hiperhivatkozást. Olvasás [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Megkapja a 'Mark as decorative' opciót Olvasás/írás **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Megállapítja, hogy az alakzat csoportosított-e. Csak olvasható **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Megállapítja, hogy az alakzat TextHolder_PPT-e. Csak olvasható **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Visszaadja a [LineFormat](../lineformat/) objektumot, amely tartalmazza az alakzat vonalformázási tulajdonságait. Megjegyzés: bizonyos alakzattípusoknál, amelyeknek nincs vonal tulajdonsága, null értéket ad vissza. Csak olvasható [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Visszaadja az alakzat nevét. Nem lehet null. Ha szükséges, használjon üres karakterláncot. Olvasás [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Visszaad egy diára korlátozódó egyedi azonosítót, amely az alakzat élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon az alakzatra a dokumentum bármely helyéről. Csak olvasható **uint32_t**. Lásd még [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Visszaadja a szülő [GroupShape](../groupshape/) objektumot, ha az alakzat csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Visszaadja az alakzat helyőrzőjét. Null értéket ad vissza, ha az alakzatnak nincs helyőrzője. Csak olvasható [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Visszaadja egy dia szülő prezentációját. Csak olvasható [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Visszaadja a nyers alakzat keret tulajdonságait. Olvasás [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Visszaadja, hány fokkal van elforgatva a megadott alakzat a z-tengely körül. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást. Olvasás **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Visszaadja az alakzat zárolásait. Csak olvasható [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](./get_shapestyle/)() override | Visszaadja az alakzat stílusobjektumát. Csak olvasható [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override | Visszaadja a geometria előre beállított típusát. Megjegyzés: az érték változtatásakor minden beállítási érték visszaáll az alapértelmezett értékre. Olvasás [Slides::ShapeType](../shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Visszaadja az alakzat szülő diáját. Csak olvasható [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Visszaadja a [ThreeDFormat](../threedformat/) objektumot, amely az alakzat 3D hatás tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusoknál, amelyeknek nincs 3D tulajdonsága, null értéket ad vissza. Csak olvasható [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Visszaad egy belső, a prezentációra korlátozódó azonosítót, amelyet bővítmények vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy programozottan át lehet rendelni, nem szabad azt állandó egyedi kulcsként kezelni. Csak olvasható **uint32_t**. Lásd még [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Megkapja az alakzat szélességét pontokban mérve. Olvasás **float**. |
| **float** [get_X](../shape/get_x/)() override | Megkapja az alakzat bal felső sarkának x-koordinátáját pontokban mérve. Olvasás **float**. |
| **float** [get_Y](../shape/get_y/)() override | Megkapja az alakzat bal felső sarkának y-koordinátáját pontokban mérve. Olvasás **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Visszaadja az alakzat pozícióját a z-rendben. A Shapes[0] a z-rend hátuljában lévő alakzatot adja vissza, a Shapes[Shapes.Count - 1] a z-rend elején lévő alakzatot. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Visszaad egy alap helyőrző alakzatot (az elrendezésből és/vagy a mesterdiából származó alakzatot, amelyből az aktuális alakzat örököl). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz tartozó referencia számláló adatstruktúrát. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](./getgeometrypaths/)() override | Visszaadja a geometriai alakzat útvonalának másolatát. A koordináták az alakzat bal felső sarkához képest relatívak. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus megfelelője. Lehetővé teszi az egyedi objektumok hash-elését. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Visszaadja az alakzat bélyegképét. Alapértelmezés szerint a [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) alakzat bélyegkép határ típust használják. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Visszaadja az alakzat bélyegképét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás megfelelője. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Megkapja az alakzat vizuális határait, amelyet a renderelt tartalma alapján számol. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus egy példánya-e. A C# 'is' operátor megfelelője. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus megfelelője. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referencia alapján hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referencia alapján hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia alapján hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Meghatározza, hogy ez az alakzat nem helyőrző. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Beállítja az alakzathoz tartozó alternatív szöveget. Írás [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Beállítja az alakzathoz tartozó alternatív szöveg címét. Írás [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | A tulajdonság meghatározza, hogyan jelenik meg az alakzat fekete-fehér megjelenítési módban. Írás [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Beállítja az alakzat keret tulajdonságait. Írás [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Beállítja az alakzat magasságát pontokban mérve. Írás **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Meghatározza, hogy az alakzat rejtett-e. Írás **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Beállítja az egérkattintásra definiált hiperhivatkozást. Írás [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Beállítja az egér fölé viszésre definiált hiperhivatkozást. Írás [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Beállítja a 'Mark as decorative' opciót Olvasás/írás **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Beállítja az alakzat nevét. Nem lehet null. Ha szükséges, használjon üres karakterláncot. Írás [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Beállítja a nyers alakzat keret tulajdonságait. Írás [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Beállítja, hány fokkal van elforgatva a megadott alakzat a z-tengely körül. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást. Írás **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override | Beállítja a geometria előre beállított típusát. Megjegyzés: az érték változtatásakor minden beállítási érték visszaáll az alapértelmezett értékre. Írás [Slides::ShapeType](../shapetype/). |
| void [set_Width](../shape/set_width/)(**float**) override | Beállítja az alakzat szélességét pontokban mérve. Írás **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Beállítja az alakzat bal felső sarkának x-koordinátáját pontokban mérve. Írás **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Beállítja az alakzat bal felső sarkának y-koordinátáját pontokban mérve. Írás **float**. |
| void [SetGeometryPath](./setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Frissíti az alakzat geometriáját a [IGeometryPath](../igeometrypath/) objektumból. A koordinátáknak az alakzat bal felső sarkához relatívnak kell lenniük. Megváltoztatja az alakzat típusát ([ShapeType](../shapetype/)) a [ShapeType::Custom](../shapetype/) típusra. |
| void [SetGeometryPaths](./setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Frissíti az alakzat geometriáját a [IGeometryPath](../igeometrypath/) tömbből. A koordinátáknak az alakzat bal felső sarkához relatívnak kell lenniük. Megváltoztatja az alakzat típusát ([ShapeType](../shapetype/)) a [ShapeType::Custom](../shapetype/) típusra. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablon argumentumot gyenge mutatóként (ahelyett, hogy megosztott). Lehetővé teszi a mutatók konténeren belüli váltását gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referencia számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus megfelelője. Lehetővé teszi az egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Mentse a [Shape](../shape/) tartalmát SVG fájlként. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Mentse a [Shape](../shape/) tartalmát SVG fájlként. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Shape](../shape/)
* Osztály [IGeometryShape](../igeometryshape/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)