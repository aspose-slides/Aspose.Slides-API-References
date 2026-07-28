---
title: ISectionZoomFrame
second_title: Aspose.Slides C++ API-referencia
description: Egy dián lévő Section Zoom objektumot képvisel.
type: docs
weight: 3602
url: /hu/aspose.slides/isectionzoomframe/
---
## ISectionZoomFrame osztály


Képviseli a [Section](../section/) Zoom objektumot egy dián.

```cpp
class ISectionZoomFrame : public virtual Aspose::Slides::IZoomObject
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Új helyfoglalót ad hozzá, ha nincs, és beállítja a helyfoglaló tulajdonságait egy megadottra. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Visszaadja a formához társított alternatív szöveget. Olvasd [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Visszaadja a formához társított alternatív szöveg címét. Olvasd [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | A tulajdonság meghatározza, hogy a forma hogyan jelenik meg fekete-fehér megjelenítési módban. Olvasd [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Visszaadja a forma csatlakozási pontjainak számát. Csak olvasható **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Visszaadja a forma egyéni adatait. Csak olvasható [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Visszaadja a [EffectFormat](../effectformat/) objektumot, amely a forma alkalmazott pixelhatásait tartalmazza. Csak olvasható [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Visszaadja a [FillFormat](../fillformat/) objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza. Csak olvasható [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Visszaadja a forma keretének tulajdonságait. Olvasd [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Visszaadja a forma zárolásait. Csak olvasható [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Lekéri a forma magasságát pontokban mérve. Olvasd **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Megállapítja, hogy a forma rejtett-e. Olvasd **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Visszaadja az egérkattintásra definiált hiperhivatkozást. Olvasd [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hiperhivatkozások kezelője. Csak olvasható [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Visszaadja az egér fölé vitt eseményhez definiált hiperhivatkozást. Olvasd [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | Lekéri egy zoom objektum kép típusát. Olvasd [ZoomImageType](../zoomimagetype/). Alapértelmezett érték: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Lekéri a 'Mark as decorative' opciót. Olvasás/írás **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Megállapítja, hogy a forma csoportosított-e. Csak olvasható **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Megállapítja, hogy a forma TextHolder-e. Csak olvasható **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Visszaadja a [LineFormat](../lineformat/) objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Csak olvasható [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Visszaadja a forma nevét. Olvasd [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Hozzáad egy diára korlátozott egyedi azonosítót, amely a forma életciklusa során állandó, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasható **uint32_t**. Lásd még [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Visszaadja a szülő [GroupShape](../groupshape/) objektumot, ha a forma csoportosított. Egyébként null értéket ad vissza. Csak olvasható [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Visszaadja a forma helyfoglalóját. Csak olvasható [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Visszaadja a bemutatót. Csak olvasható [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Visszaadja a nyers forma keretének tulajdonságait. Olvasd [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | Lekéri a diavetítés navigációs viselkedését. Olvasd **bool**. Alapértelmezett érték: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Visszaadja a fokok számát, amellyel a megadott forma elfordul a z-tengely körül. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást. Olvasd **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Visszaadja a forma zárolásait. Csak olvasható [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | Lekéri azt az értéket, amely meghatározza, hogy a Zoom a cél dia háttérét használja-e. Olvasd **bool**. Alapértelmezett érték: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Visszaadja az alap diát. Csak olvasható [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](./get_targetsection/)() | Lekéri a szakasz objektumot, amelyhez a [Section](../section/) Zoom objektum kapcsolódik. Olvasd [ISection](../isection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Visszaadja a [ThreeDFormat](../threedformat/) objektumot, amely egy forma vonalformázási tulajdonságait tartalmazza. Csak olvasható [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | Lekéri a Zoom és dia közötti átmenet időtartamát. Olvasd **float**. Alapértelmezett érték: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Hozzáad egy belső, bemutató átfogó azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy programozottan újra hozzárendelheti, nem szabad állandó egyedi kulcsként kezelni. Csak olvasható **uint32_t**. Lásd még [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Lekéri a forma szélességét pontokban mérve. Olvasd **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Lekéri a forma bal-felső sarkának x-koordinátáját pontokban mérve. Olvasd **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Lekéri a forma bal-felső sarkának y-koordinátáját pontokban mérve. Olvasd **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | Lekéri a zoom objektum képét. Olvasd [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Visszaadja egy forma z-sorrendben betöltött pozícióját. A Shapes[0] a z-sorrend végén lévő formát adja vissza, a Shapes[Shapes.Count - 1] pedig az elején lévő formát. Csak olvasható **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Visszaad egy alap helyfoglaló formát (a layout vagy mesterdia típusú formát, amelyből a jelenlegi forma örököl). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciacsökkentő adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi a saját objektumok hash-elését. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Visszaadja a forma bélyegképét. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) forma bélyegkép határ típust használ alapértelmezésként. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Visszaadja a forma bélyegképét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzés, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őr objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi a saját típusok másolását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló létrehozását. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló létrehozását. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípust a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciák számát a megadott értékkel. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Meghatározza, hogy ez a forma nem helyfoglaló. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Beállítja a formához társított alternatív szöveget. Írj [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Beállítja a formához társított alternatív szöveg címét. Írj [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | A tulajdonság meghatározza, hogy a forma hogyan jelenik meg fekete-fehér megjelenítési módban. Írj [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Beállítja a forma keretének tulajdonságait. Írj [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Beállítja a forma magasságát pontokban mérve. Írj **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Megállapítja, hogy a forma rejtett-e. Írj **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Beállítja az egérkattintásra definiált hiperhivatkozást. Írj [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Beállítja az egér fölé vitt eseményhez definiált hiperhivatkozást. Írj [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | Beállítja a zoom objektum kép típusát. Írj [ZoomImageType](../zoomimagetype/). Alapértelmezett érték: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Beállítja a 'Mark as decorative' opciót. Olvasás/írás **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Beállítja a forma nevét. Írj [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Beállítja a nyers forma keretének tulajdonságait. Írj [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | Beállítja a diavetítés navigációs viselkedését. Írj **bool**. Alapértelmezett érték: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Beállítja a fokok számát, amellyel a megadott forma elfordul a z-tengely körül. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást. Írj **float**. |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | Beállítja azt az értéket, amely meghatározza, hogy a Zoom a cél dia háttérét használja-e. Írj **bool**. Alapértelmezett érték: true |
| virtual void [set_TargetSection](./set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) | Beállítja a szakasz objektumot, amelyhez a [Section](../section/) Zoom objektum kapcsolódik. Írj [ISection](../isection/). |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | Beállítja a Zoom és dia közötti átmenet időtartamát. Írj **float**. Alapértelmezett érték: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Beállítja a forma szélességét pontokban mérve. Írj **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Beállítja a forma bal-felső sarkának x-koordinátáját pontokban mérve. Írj **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Beállítja a forma bal-felső sarkának y-koordinátáját pontokban mérve. Írj **float**. |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | Beállítja a zoom objektum képét. Írj [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (nem megosztott). Lehetővé teszi a mutatók átváltását a tárolókban gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciacsökkentő aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciák számát. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciák számát. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi a saját objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őr objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciák számát. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciák számát. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Lásd még

* Osztály [IZoomObject](../izoomobject/)
* Névtere [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)