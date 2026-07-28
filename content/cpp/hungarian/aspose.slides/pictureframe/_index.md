---
title: PictureFrame
second_title: Aspose.Slides C++ API hivatkozás
description: Egy képet tartalmazó keretet reprezentál.
type: docs
weight: 4733
url: /hu/aspose.slides/pictureframe/
---
## PictureFrame osztály

Represents a frame with a picture inside.

```cpp
class PictureFrame : public Aspose::Slides::GeometryShape,
                     public virtual Aspose::Slides::IPictureFrame
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Új helyőrzőt ad hozzá, ha nincs, és a helyőrző tulajdonságait egy megadottra állítja. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Létrehozza és visszaadja a alakzat elemeinek tömbjét. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Visszaadja egy alakzat beállítási értékét a megadott indexnél. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Visszaadja egy alakzat beállítási értékeinek gyűjteményét. Csak olvasható [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Visszaadja az alakzathoz kapcsolódó alternatív szöveget. Olvassa [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Visszaadja az alakzathoz kapcsolódó alternatív szöveg címét. Olvassa [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | A tulajdonság megadja, hogyan jelenik meg egy alakzat fekete-fehér megjelenítési módban. Olvassa [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Visszaadja az alakzat csatlakozási helyeinek számát. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Visszaadja az alakzat egyéni adatait. Csak olvasható [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Visszaadja a [EffectFormat](../effectformat/) objektumot, amely a alakzatra alkalmazott pixelhatásokat tartalmazza. Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincs effektus tulajdonsága, null értéket adhat vissza. Csak olvasható [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Visszaadja a [FillFormat](../fillformat/) objektumot, amely az alakzat kitöltésformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak olvasható [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Visszaadja az alakzat keretének tulajdonságait. Olvassa [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Megkapja az alakzat magasságát pontban mérve. Olvassa **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Megállapítja, hogy az alakzat rejtett-e. Olvassa **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Visszaadja az egérkattintásra definiált hiperhivatkozást. Olvassa [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasható [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Visszaadja az egér fölé mozgatásra definiált hiperhivatkozást. Olvassa [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](./get_iscameo/)() | Megállapítja, hogy a(z) [PictureFrame](./) Cameo objektum-e vagy sem. Csak olvasható **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Megkapja a 'Mark as decorative' beállítást Olvas/ír **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Megállapítja, hogy az alakzat csoportosított-e. Csak olvasható **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Megállapítja, hogy az alakzat TextHolder_PPT-e. Csak olvasható **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Visszaadja a [LineFormat](../lineformat/) objektumot, amely az alakzat vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincs vonal tulajdonsága, null értéket adhat vissza. Csak olvasható [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Visszaadja egy alakzat nevét. Nem lehet null. Szükség esetén használjon üres karakterláncot. Olvassa [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Visszaad egy diára korlátozott egyedi azonosítót, amely a forma élettartama során állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasható **uint32_t**. Lásd még [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Visszaadja a szülő [GroupShape](../groupshape/) objektumot, ha az alakzat csoportosított. Egyébként null értéket ad vissza. Csak olvasható [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](./get_pictureformat/)() override | Visszaadja a [PictureFillFormat](../picturefillformat/) objektumot egy képkerethez. Csak olvasható [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](./get_pictureframelock/)() override | Visszaadja az alakzat zárolásait. Csak olvasható [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Visszaadja egy alakzat helyőrzőjét. Null értéket ad vissza, ha az alakzatnak nincs helyőrzője. Csak olvasható [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Visszaadja egy dia szülő előpresentationjét. Csak olvasható [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Visszaadja a nyers alakzat keretének tulajdonságait. Olvassa [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](./get_relativescaleheight/)() override | Visszaadja a képkeret magasságának (az eredeti kép méretéhez viszonyítva) méretezését. Az 1,0 érték 100%-nak felel meg. Olvassa **float**. |
| **float** [get_RelativeScaleWidth](./get_relativescalewidth/)() override | Visszaadja a képkeret szélességének (az eredeti kép méretéhez viszonyítva) méretezését. Az 1,0 érték 100%-nak felel meg. Olvassa **float**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Visszaadja a megadott alakzat Z-tengely körüli elforgatási fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást. Olvassa **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Visszaadja az alakzat zárolásait. Csak olvasható [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Visszaadja az alakzat stílusobjektumát. Csak olvasható [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Visszaadja egy alakzat szülő diáit. Csak olvasható [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Visszaadja a [ThreeDFormat](../threedformat/) objektumot, amely egy alakzat 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak olvasható [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kódok használhatnak. Mivel ezt az értéket a felhasználó vagy programozottan újra hozzárendelheti, nem tekinthető állandó egyedi kulcsnak. Csak olvasható **uint32_t**. Lásd még [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Megkapja az alakzat szélességét pontban mérve. Olvassa **float**. |
| **float** [get_X](../shape/get_x/)() override | Megkapja az alakzat bal felső sarkának x-koordinátáját pontban mérve. Olvassa **float**. |
| **float** [get_Y](../shape/get_y/)() override | Megkapja az alakzat bal felső sarkának y-koordinátáját pontban mérve. Olvassa **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Visszaadja egy alakzat pozícióját a Z-sorrendben. A Shapes[0] a Z-sorrend hátuljában lévő alakzatot adja, a Shapes[Shapes.Count - 1] az elöl lévő alakzatot. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Visszaad egy alap helyőrző alakzatot (az elrendezésből és/vagy mesterdiából származó alakzat, amelyből a jelenlegi alakzat örököl). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz kapcsolódó hivatkozásszámláló adatstruktúrát. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Visszaadja a geometriai alakzat útvonalának másolatát. A koordináták az alakzat bal felső sarkához képest relatívak. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyéni objektumok hash-olását. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Visszaadja az alakzat bélyegképét. Alapértelmezés szerint a [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) alakzat bélyegkép határoló típusa használatos. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Visszaadja az alakzat bélyegképét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Megkapja az alakzat megjelenített tartalma alapján számított vizuális határait. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciák alapján. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciák alapján. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlít össze értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámlálót a megadott értékkel. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Meghatározza, hogy ez az alakzat nem helyőrző. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Beállítja az alakzathoz kapcsolódó alternatív szöveget. Írja [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Beállítja az alakzathoz kapcsolódó alternatív szöveg címét. Írja [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | A tulajdonság megadja, hogyan jelenik meg egy alakzat fekete-fehér megjelenítési módban. Írja [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Beállítja az alakzat keretének tulajdonságait. Írja [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Beállítja az alakzat magasságát pontban mérve. Írja **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Megállapítja, hogy az alakzat rejtett-e. Írja **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Beállítja az egérkattintásra definiált hiperhivatkozást. Írja [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Beállítja az egér fölé mozgatásra definiált hiperhivatkozást. Írja [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Beállítja a 'Mark as decorative' opciót Olvas/ír **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Beállítja egy alakzat nevét. Nem lehet null. Szükség esetén használjon üres karakterláncot. Írja [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Beállítja a nyers alakzat keretének tulajdonságait. Írja [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](./set_relativescaleheight/)(**float**) override | Beállítja a képkeret magasságának (az eredeti kép méretéhez viszonyítva) méretezését. Az 1,0 érték 100%-nak felel meg. Írja **float**. |
| void [set_RelativeScaleWidth](./set_relativescalewidth/)(**float**) override | Beállítja a képkeret szélességének (az eredeti kép méretéhez viszonyítva) méretezését. Az 1,0 érték 100%-nak felel meg. Írja **float**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Beállítja a megadott alakzat Z-tengely körüli elforgatási fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást. Írja **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_Width](../shape/set_width/)(**float**) override | Beállítja az alakzat szélességét pontban mérve. Írja **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Beállítja az alakzat bal felső sarkának x-koordinátáját pontban mérve. Írja **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Beállítja az alakzat bal felső sarkának y-koordinátáját pontban mérve. Írja **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Frissíti az alakzat geometriáját a [IGeometryPath](../igeometrypath/) objektumtól. A koordinátáknak az alakzat bal felső sarkához képest relatívnak kell lenniük. Megváltoztatja az alakzat típusát ([ShapeType](../shapetype/)) [ShapeType::Custom](../shapetype/)-re. |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Frissíti az alakzat geometriáját a [IGeometryPath](../igeometrypath/) tömbből. A koordinátáknak az alakzat bal felső sarkához képest relatívnak kell lenniük. Megváltoztatja az alakzat típusát ([ShapeType](../shapetype/)) [ShapeType::Custom](../shapetype/)-re. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonparamétert gyenge mutatóra (nem megosztottra). Lehetővé teszi, hogy a tárolók mutatóit gyenge módba cserélje. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott hivatkozásszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okosmutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okosmutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyéni objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okosmutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okosmutatókat vagy ThisProtector-t. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések

A következő példák bemutatják, hogyan lehet módosítani a [Audio](../audio/) Keret bélyegképét.
```cpp
auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Hozzáad egy audio keretet a diára a megadott pozícióval és mérettel.
auto audioStream = System::MakeObject<System::IO::FileStream>(u"sample2.mp3", System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(150.0f, 100.0f, 50.0f, 50.0f, audioStream);
audioStream->Dispose();

// Hozzáad egy képet a prezentáció erőforrásaihoz.
auto imageStream = System::IO::File::OpenRead(u"eagle.jpeg");
auto audioImage = presentation->get_Images()->AddImage(imageStream);
imageStream->Dispose();

// Beállítja a képet az audio kerethez.
audioFrame->get_PictureFormat()->get_Picture()->set_Image(audioImage);

//Mentse a módosított prezentációt a lemezre
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [GeometryShape](../geometryshape/)
* Osztály [IPictureFrame](../ipictureframe/)
* Névtere [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)