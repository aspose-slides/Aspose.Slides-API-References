---
title: IAutoShape
second_title: Aspose.Slides C++ API referencia
description: Az AutoShape-et képviseli.
type: docs
weight: 1366
url: /hu/aspose.slides/iautoshape/
---
## IAutoShape osztály

Represents an [AutoShape](../autoshape/).

```cpp
class IAutoShape : public virtual Aspose::Slides::IGeometryShape
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Új helyfoglalót ad hozzá, ha nincs, és a helyfoglaló tulajdonságait egy megadottra állítja. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [AddTextFrame](./addtextframe/)([System::String](../../system/string/)) | Új [TextFrame](../textframe/)-t ad a formához. Ha a forma már rendelkezik [TextFrame](../textframe/)-val, akkor egyszerűen megváltoztatja a szövegét. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Létrehoz és visszaad egy tömböt a forma elemeiről. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Visszaadja a forma beállítási értékét a megadott indexnél. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Visszaadja a forma beállítási értékeinek gyűjteményét. Csak olvasható [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Visszaadja a formához kapcsolódó alternatív szöveget. Olvas [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Visszaadja a formához kapcsolódó alternatív szöveg címét. Olvas [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShapeLock](../iautoshapelock/)\> [get_AutoShapeLock](./get_autoshapelock/)() | Visszaadja [AutoShape](../autoshape/) zárolásait. Csak olvasható [IAutoShapeLock](../iautoshapelock/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Tulajdonság megadja, hogy a forma hogyan jelenik meg fekete-fehér módon. Olvas [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Visszaadja a forma csatlakozási pontjainak számát. Csak olvasható **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Visszaadja a forma egyedi adatait. Csak olvasható [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Visszaadja a [EffectFormat](../effectformat/) objektumot, amely a forma alkalmazott képpont hatásait tartalmazza. Csak olvasható [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Visszaadja a [FillFormat](../fillformat/) objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza. Csak olvasható [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Visszaadja a forma keret tulajdonságait. Olvas [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Lekéri a forma magasságát pontban mérve. Olvas **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Megállapítja, hogy a forma rejtett-e. Olvas **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Visszaadja az egérkattintásra definiált hiperhivatkozást. Olvas [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hiperhivatkozások kezelője Csak olvasható [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Visszaadja az egérmutató fölé helyezésekor definiált hiperhivatkozást. Olvas [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Lekéri a 'Mark as decorative' opciót Olvas/írás **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Megállapítja, hogy a forma csoportosított-e. Csak olvasható **bool**. |
| virtual **bool** [get_IsTextBox](./get_istextbox/)() | Megadja, hogy a forma szövegdoboz-e. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Megállapítja, hogy a forma TextHolder-e. Csak olvasható **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Visszaadja a [LineFormat](../lineformat/) objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Csak olvasható [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Visszaadja a forma nevét. Olvas [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Visszaad egy diára korlátozódó egyedi azonosítót, amely a forma életciklusa alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a formára a dokumentum bármely pontjáról. Csak olvasható **uint32_t**. Lásd még [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Visszaadja a szülő [GroupShape](../groupshape/) objektumot, ha a forma csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Visszaadja a forma helyfoglalóját. Csak olvasható [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Visszaadja a bemutatót. Csak olvasható [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Visszaadja a formanyerszabály nyers keret tulajdonságait. Olvas [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Visszaadja a fokok számát, amelyben a megadott forma körül a z-tengely körül el van fordítva. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellentétes irányt. Olvas **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Visszaadja a forma zárolásait. Csak olvasható [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Visszaadja a forma stílusobjektumát. Csak olvasható [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Visszaadja a geometria előre beállított típusát. Megjegyzés: az érték változtatásakor az összes beállítási érték visszaáll az alapértelmezett értékre. Olvas [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Visszaadja az alapdiát. Csak olvasható [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | Visszaadja a [TextFrame](../textframe/) objektumot a [AutoShape](../autoshape/)-hez. Csak olvasható [ITextFrame](../itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Visszaadja a [ThreeDFormat](../threedformat/) objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Csak olvasható [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Visszaad egy belső, bemutatóhoz kötött azonosítót, amelyet kiegészítők vagy más kódok használhatnak. Mivel ezt az értéket a felhasználó vagy programozottan át lehet rendelni, nem szabad tartós egyedi kulcsként kezelni. Csak olvasható **uint32_t**. Lásd még [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **bool** [get_UseBackgroundFill](./get_usebackgroundfill/)() | Megállapítja, hogy ez az autoshape a dia háttérkitöltésével legyen-e kitöltve a stílus vagy kitöltés formátum helyett. Olvas **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Lekéri a forma szélességét pontban mérve. Olvas **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Lekéri a forma bal felső sarkának x-koordinátáját pontban mérve. Olvas **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Lekéri a forma bal felső sarkának y-koordinátáját pontban mérve. Olvas **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Visszaadja a forma pozícióját a z-sorrendben. A Shapes[0] a z-sorrend hátulján lévő formát adja vissza, a Shapes[Shapes.Count - 1] a fronton lévő formát. Csak olvasható **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Visszaad egy alap helyfoglaló formát (a jelenlegi formától örökölt elrendezés- vagy fődia formát). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Visszaadja a geometriai forma útvonalának másolatát. A koordináták a forma bal felső sarkához relatívak. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Engedélyezi az egyedi objektumok hash-elését. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Visszaadja a forma bélyegképét. Alapértelmezés szerint a [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) forma bélyegkép határoló típust használja. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Visszaadja a forma bélyegképét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Engedélyezi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Meghatározza, hogy ez a forma nem helyfoglaló. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Beállítja a formához kapcsolódó alternatív szöveget. Írás [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Beállítja a formához kapcsolódó alternatív szöveg címét. Írás [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Tulajdonság megadja, hogy a forma hogyan jelenik meg fekete-fehér módon. Írás [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Beállítja a forma keret tulajdonságait. Írás [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Beállítja a forma magasságát pontban mérve. Írás **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Megállapítja, hogy a forma rejtett-e. Írás **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Beállítja az egérkattintásra definiált hiperhivatkozást. Írás [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Beállítja az egérmutató fölé helyezésére definiált hiperhivatkozást. Írás [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Beállítja a 'Mark as decorative' opciót Olvas/írás **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Beállítja a forma nevét. Írás [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Beállítja a nyers forma keret tulajdonságait. Írás [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Beállítja a fokok számát, amelyben a megadott forma körül a z-tengely körül el van fordítva. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellentétes irányt. Írás **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Beállítja a geometria előre beállított típusát. Megjegyzés: az érték változtatásakor az összes beállítási érték visszaáll az alapértelmezett értékre. Írás [Slides::ShapeType](../shapetype/). |
| virtual void [set_UseBackgroundFill](./set_usebackgroundfill/)(**bool**) | Megállapítja, hogy ez az autoshape a dia háttérkitöltésével legyen-e kitöltve a stílus vagy kitöltés formátum helyett. Írás **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Beállítja a forma szélességét pontban mérve. Írás **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Beállítja a forma bal felső sarkának x-koordinátáját pontban mérve. Írás **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Beállítja a forma bal felső sarkának y-koordinátáját pontban mérve. Írás **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Frissíti a forma geometriáját a [IGeometryPath](../igeometrypath/) objektumból. A koordináták a forma bal felső sarkához relatívak kell legyenek. A forma típusát ([ShapeType](../shapetype/)) [ShapeType::Custom](../shapetype/)-ra módosítja. |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Frissíti a forma geometriáját a [IGeometryPath](../igeometrypath/) tömbből. A koordináták a forma bal felső sarkához relatívak kell legyenek. A forma típusát ([ShapeType](../shapetype/)) [ShapeType::Custom](../shapetype/)-ra módosítja. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonparamétert gyenge mutatóra (nem megosztottra). Lehetővé teszi a mutatók konténerben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IGeometryShape](../igeometryshape/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)