---
title: IOleObjectFrame
second_title: Aspose.Slides C++ API Referencia
description: Egy dián lévő OLE objektumot képvisel.
type: docs
weight: 3095
url: /hu/aspose.slides/ioleobjectframe/
---
## IOleObjectFrame osztály


Represents an OLE object on a slide.

```cpp
class IOleObjectFrame : public virtual Aspose::Slides::IGraphicalObject
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Új helyőrzőt ad hozzá, ha nem létezik, és a helyőrző tulajdonságait beállítja egy megadottra. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika alapján. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Visszaadja a alakzathoz kapcsolódó alternatív szöveget. Olvasd [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Visszaadja az alakzathoz kapcsolódó alternatív szöveg címét. Olvasd [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | A tulajdonság meghatározza, hogyan jelenik meg az alakzat fekete-fehér módon. Olvasd [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Visszaadja az alakzaton lévő kapcsolódási pontok számát. Csak olvasható **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Visszaadja az alakzat egyéni adatait. Csak olvasható [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Visszaadja a [EffectFormat](../effectformat/) objektumot, amely a alakzatra alkalmazott pixel effektusokat tartalmazza. Csak olvasható [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() | Információt kap az OLE beágyazott adatokról. Csak olvasható [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/). |
| virtual [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() | Visszaadja a beágyazott OLE objektum fájlnevét |
| virtual [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() | Visszaadja a beágyazott OLE objektum útvonalát |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Visszaadja a [FillFormat](../fillformat/) objektumot, amely egy alakzat kitöltési formázási tulajdonságait tartalmazza. Csak olvasható [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Visszaadja az alakzat keret tulajdonságait. Olvasd [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Visszaadja az alakzat zárolásait. Csak olvasható [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Visszaadja az alakzat magasságát pontban mérve. Csak olvasható **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Megállapítja, hogy az alakzat rejtett-e. Csak olvasható **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Visszaadja a egérkattintásra definiált hiperhivatkozást. Olvasd [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hiperhivatkozás-kezelő. Csak olvasható [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Visszaadja az egérmutatóra definiált hiperhivatkozást. Olvasd [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Megkapja a „Mark as decorative” opciót Olvasás/írás **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Megállapítja, hogy az alakzat csoportosított-e. Csak olvasható **bool**. |
| virtual **bool** [get_IsObjectIcon](./get_isobjecticon/)() | Megállapítja, hogy egy objektum ikonként látható-e. Csak olvasható **bool**. |
| virtual **bool** [get_IsObjectLink](./get_isobjectlink/)() | Megállapítja, hogy egy objektum külső fájlra hivatkozik-e. Csak olvasható **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Megállapítja, hogy az alakzat TextHolder-e. Csak olvasható **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Visszaadja a [LineFormat](../lineformat/) objektumot, amely egy alakzat vonalformázási tulajdonságait tartalmazza. Csak olvasható [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() | Visszaadja a hivatkozott fájl teljes útvonalát. A rövid fájlnév lesz használva. Csak olvasható [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | Visszaadja a hivatkozott fájl teljes útvonalát. A hosszú fájlnév lesz használva. Olvasd [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() | Visszaadja a hivatkozott fájl relatív útvonalát, ha létezik, egyébként üres karakterláncot ad. Csak olvasható [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Visszaadja egy alakzat nevét. Olvasd [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() | Visszaadja egy objektum nevét. Olvasd [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() | Visszaadja egy objektum ProgID-jét. Csak olvasható [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Visszaad egy diára korlátozott egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasható **uint32_t**. Lásd még [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Visszaadja a szülő [GroupShape](../groupshape/) objektumot, ha az alakzat csoportosított. Egyébként null értéket ad. Csak olvasható [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Visszaadja egy alakzat helyőrzőjét. Csak olvasható [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Visszaadja a bemutatót. Csak olvasható [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Visszaadja a nyers alakzat keret tulajdonságait. Olvasd [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Visszaadja a megadott alakzat a z-tengely körül elforduló fokok számát. Pozitív érték az óramutató járásával megegyező forgást jelzi; negatív érték az ellentétes irányú forgást jelzi. Csak olvasható **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Visszaadja az alakzat zárolásait. Csak olvasható [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Visszaadja az alap diát. Csak olvasható [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() | Visszaadja az OleObject kép kitöltési tulajdonságok objektumát. Csak olvasható [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() | Visszaadja az OleObject ikon címét. Olvasd [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Visszaadja a [ThreeDFormat](../threedformat/) objektumot, amely egy alakzat vonalformázási tulajdonságait tartalmazza. Csak olvasható [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Visszaad egy belső, a bemutatóra korlátozott azonosítót, amely kiegészítők vagy más kódok számára van fenntartva. Mivel ezt az értéket a felhasználó vagy programozottan át lehet rendelni, nem szabad állandó egyedi kulcsként kezelni. Csak olvasható **uint32_t**. Lásd még [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **bool** [get_UpdateAutomatic](./get_updateautomatic/)() | Megállapítja, hogy a hivatkozott beágyazott objektum automatikusan frissül-e a bemutató megnyitásakor vagy nyomtatásakor. Csak olvasható **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Visszaadja az alakzat szélességét pontban mérve. Csak olvasható **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Visszaadja az alakzat bal felső sarkának x-koordinátáját pontban mérve. Csak olvasható **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Visszaadja az alakzat bal felső sarkának y-koordinátáját pontban mérve. Csak olvasható **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Visszaadja egy alakzat pozícióját a z-rendben. A Shapes[0] a z-rend hátuljában lévő alakzatot adja vissza, a Shapes[Shapes.Count - 1] a frontban lévő alakzatot. Csak olvasható **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Visszaad egy alap helyőrző alakzatot (az elrendezésből és/vagy fő diából származó alakzat, amelyből az aktuális alakzat örököl). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógia a C# [Object.GetHashCode()](../../system/object/gethashcode/) metódusra. Engedélyezi az egyéni objektumok hash-elését. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Visszaadja az alakzat bélyegképét. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) alakzat bélyegkép határoló típusa van használva alapértelmezés szerint. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Visszaadja az alakzat bélyegképét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példányát képviseli-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyelő objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógia a C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódusra. Engedélyezi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál és engedélyezi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelési operátor. Valójában nem másol semmit, csak egy új objektumot inicializál és engedélyezi az alosztályok másolásos konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Meghatározza, hogy ez az alakzat nem helyőrző. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Beállítja az alakzathoz kapcsolódó alternatív szöveget. Írja [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Beállítja az alakzathoz kapcsolódó alternatív szöveg címét. Írja [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | A tulajdonság meghatározza, hogyan jelenjen meg egy alakzat fekete-fehér módban. Írja [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Beállítja az alakzat keret tulajdonságait. Írja [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Beállítja az alakzat magasságát pontban mérve. Írja **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Megállapítja, hogy az alakzat rejtett-e. Írja **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Beállítja a egérkattintásra definiált hiperhivatkozást. Írja [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Beállítja az egérmutatóra definiált hiperhivatkozást. Írja [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Beállítja a „Mark as decorative” opciót Olvasás/írás **bool**. |
| virtual void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) | Megállapítja, hogy egy objektum ikonként látható-e. Írja **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | Visszaadja a hivatkozott fájl teljes útvonalát. Hosszú fájlnév lesz használva. Írja [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Beállítja egy alakzat nevét. Írja [System::String](../../system/string/). |
| virtual void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) | Beállítja egy objektum nevét. Írja [System::String](../../system/string/). |
| virtual void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) | Visszaadja egy objektum ProgID-jét. Olvasd [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Beállítja a nyers alakzat keret tulajdonságait. Írja [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Beállítja a megadott alakzat a z-tengely körüli forgatási fokszámát. Pozitív érték az óramutató járásával megegyező forgást jelzi; negatív érték az ellenkező irányú forgást jelzi. Írja **float**. |
| virtual void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) | Beállítja az OleObject ikon címét. Írja [System::String](../../system/string/). |
| virtual void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) | Megállapítja, hogy a hivatkozott beágyazott objektum automatikusan frissül-e a bemutató megnyitásakor vagy nyomtatásakor. Írja **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Beállítja az alakzat szélességét pontban mérve. Írja **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Beállítja az alakzat bal felső sarkának x-koordinátáját pontban mérve. Írja **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Beállítja az alakzat bal felső sarkának y-koordinátáját pontban mérve. Írja **float**. |
| virtual void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) | Beállítja az OLE beágyazott adatokra vonatkozó információkat. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóként (nem shared) állítja be. Lehetővé teszi a mutatók konténerben való weak módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; használjon intelligens mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; használjon intelligens mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Engedélyezi egyéni objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) szerkezetet. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyelő objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; használjon intelligens mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; használjon intelligens mutatókat vagy ThisProtector-t. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IGraphicalObject](../igraphicalobject/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)