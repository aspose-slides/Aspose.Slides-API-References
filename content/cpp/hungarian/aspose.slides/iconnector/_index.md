---
title: IConnector
second_title: Aspose.Slides C++ API Referencia
description: Egy csatlót reprezentál.
type: docs
weight: 1847
url: /hu/aspose.slides/iconnector/
---
## IConnector osztály

Representa egy csatlót.

```cpp
class IConnector : public virtual Aspose::Slides::IGeometryShape
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Új helykitöltőt ad hozzá, ha nincs, és beállítja a helykitöltő tulajdonságait a megadottra. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Létrehozza és visszaadja a forma elemeinek tömbjét. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Visszaadja a forma beállítási értékét a megadott indexen. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Visszaadja a forma beállítási értékeinek gyűjteményét. Csak olvasható [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Visszaadja a forma alternatív szövegét. Olvas [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Visszaadja a forma alternatív szövegének címét. Olvas [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Tulajdonság megadja, hogyan jelenik meg a forma fekete-fehér nézetben. Olvas [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Visszaadja a forma kapcsolódási pontjainak számát. Csak olvasható **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IConnectorLock](../iconnectorlock/)\> [get_ConnectorLock](./get_connectorlock/)() | Visszaadja a [Connector](../connector/) zárolásait. Csak olvasható [IConnectorLock](../iconnectorlock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Visszaadja a forma egyedi adatait. Csak olvasható [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Visszaadja a [EffectFormat](../effectformat/) objektumot, amely a forma pixel effektjeit tartalmazza. Csak olvasható [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_EndShapeConnectedTo](./get_endshapeconnectedto/)() | Visszaadja a formát, amelyhez a csatló végpontja csatlakozik. Olvas [IShape](../ishape/). |
| virtual **uint32_t** [get_EndShapeConnectionSiteIndex](./get_endshapeconnectionsiteindex/)() | Visszaadja a végpont forma kapcsolódási hely indexét. Olvas **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Visszaadja a [FillFormat](../fillformat/) objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza. Csak olvasható [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Visszaadja a forma keret tulajdonságait. Olvas [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Lekéri a forma magasságát pontokban. Olvas **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Megállapítja, hogy a forma rejtett-e. Olvas **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Visszaadja az egérkattintásra definiált hiperhivatkozást. Olvas [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hiperhivatkozások kezelője Csak olvasható [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Visszaadja az egér fölé mozgatásra definiált hiperhivatkozást. Olvas [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Lekéri a „Mark as decorative” beállítást Olvasás/írás **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Megállapítja, hogy a forma csoportosított-e. Csak olvasható **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Megállapítja, hogy a forma TextHolder-e. Csak olvasható **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Visszaadja a [LineFormat](../lineformat/) objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Csak olvasható [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Visszaadja egy forma nevét. Olvas [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Visszaad egy diára korlátozott egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéből. Csak olvasható **uint32_t**. Lásd még [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Visszaadja a szülő [GroupShape](../groupshape/) objektumot, ha a forma csoportosított. Egyébként null értéket ad vissza. Csak olvasható [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Visszaadja a forma helykitöltőjét. Csak olvasható [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Visszaadja a prezentációt. Csak olvasható [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Visszaadja a nyers forma keret tulajdonságait. Olvas [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Visszaadja a fokok számát, amelyben a megadott forma a z-tengely körül elfordul. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellenkező irányú forgást. Olvas **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Visszaadja a forma zárolásait. Csak olvasható [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Visszaadja a forma stílusobjektumát. Csak olvasható [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Visszaadja a geometria előre beállított típusát. Megjegyzés: az érték módosításakor az összes beállítási érték visszaáll az alapértelmezett értékére. Olvas [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Visszaadja az alapslájdot. Csak olvasható [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_StartShapeConnectedTo](./get_startshapeconnectedto/)() | Visszaadja a formát, amelyhez a csatló kezdete csatlakozik. Olvas [IShape](../ishape/). |
| virtual **uint32_t** [get_StartShapeConnectionSiteIndex](./get_startshapeconnectionsiteindex/)() | Visszaadja a kezdő forma kapcsolódási hely indexét. Olvas **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Visszaadja a [ThreeDFormat](../threedformat/) objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Csak olvasható [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Visszaad egy belső, a prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy programozottan is újra hozzárendelheti, nem tekinthető állandó egyedi kulcsnak. Csak olvasható **uint32_t**. Lásd még [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Lekéri a forma szélességét pontokban. Olvas **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Lekéri a forma bal felső sarkának x koordinátáját pontokban. Olvas **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Lekéri a forma bal felső sarkának y koordinátáját pontokban. Olvas **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Visszaadja a forma pozícióját a z-rendben. A Shapes[0] a z-rend hátsó végén levő formát adja vissza, a Shapes[Shapes.Count - 1] pedig az előre levő formát. Csak olvasható **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Visszaad egy alap helykitöltő formát (a layoutból és/vagy a mester diáról származó formát, amelyből az aktuális forma örököl). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Visszaadja a geometriai forma útvonalának másolatát. A koordináták a forma bal felső sarkához relatívak. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Visszaadja a forma bélyegképét. Alapértelmezés szerint a [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) forma bélyegkép határ típust használja. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Visszaadja a forma bélyegképét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásával való konstrukciót. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásával való konstrukciót. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Meghatározza, hogy ez a forma nem helykitöltő. |
| virtual void [Reroute](./reroute/)() | Átirányítja a csatlót, hogy a legrövidebb lehetséges útvonalat vegye a csatlakoztatott formák között. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Beállítja a forma alternatív szövegét. Ír [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Beállítja a forma alternatív szövegének címét. Ír [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Tulajdonság megadja, hogyan jelenik meg a forma fekete-fehér nézetben. Ír [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_EndShapeConnectedTo](./set_endshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) | Beállítja a formát, amelyhez a csatló végpontja csatlakozik. Ír [IShape](../ishape/). |
| virtual void [set_EndShapeConnectionSiteIndex](./set_endshapeconnectionsiteindex/)(**uint32_t**) | Beállítja a végpont forma kapcsolódási hely indexét. Ír **uint32_t**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Beállítja a forma keret tulajdonságait. Ír [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Beállítja a forma magasságát pontokban. Ír **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Megadja, hogy a forma rejtett-e. Ír **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Beállítja az egérkattintásra definiált hiperhivatkozást. Ír [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Beállítja az egér fölé mozgatásra definiált hiperhivatkozást. Ír [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Beállítja a „Mark as decorative” opciót Olvasás/írás **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Beállítja egy forma nevét. Ír [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Beállítja a nyers forma keret tulajdonságait. Ír [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Beállítja a fokok számát, amelyben a megadott forma a z-tengely körül elfordul. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték a ellentétes irányú forgást. Ír **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Beállítja a geometria előre beállított típusát. Megjegyzés: az érték módosításakor az összes beállítási érték visszaáll az alapértelmezett értékére. Ír [Slides::ShapeType](../shapetype/). |
| virtual void [set_StartShapeConnectedTo](./set_startshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) | Beállítja a formát, amelyhez a csatló kezdete csatlakozik. Ír [IShape](../ishape/). |
| virtual void [set_StartShapeConnectionSiteIndex](./set_startshapeconnectionsiteindex/)(**uint32_t**) | Beállítja a kezdő forma kapcsolódási hely indexét. Ír **uint32_t**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Beállítja a forma szélességét pontokban. Ír **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Beállítja a forma bal felső sarkának x koordinátáját pontokban. Ír **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Beállítja a forma bal felső sarkának y koordinátáját pontokban. Ír **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Frissíti a forma geometriáját a [IGeometryPath](../igeometrypath/) objektumból. A koordinátáknak a forma bal felső sarkához relatívnak kell lenniük. A forma típusát ([ShapeType](../shapetype/)) [ShapeType::Custom](../shapetype/) típusra változtatja. |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Frissíti a forma geometriáját a [IGeometryPath](../igeometrypath/) tömbből. A koordinátáknak a forma bal felső sarkához relatívnak kell lenniük. A forma típusát ([ShapeType](../shapetype/)) [ShapeType::Custom](../shapetype/) típusra változtatja. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerben történő gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos pointereket vagy ThisProtector-t. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IGeometryShape](../igeometryshape/)
* Névterület [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)