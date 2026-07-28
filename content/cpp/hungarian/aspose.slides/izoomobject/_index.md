---
title: IZoomObject
second_title: Aspose.Slides C++ API referenciája
description: Egy dián lévő Zoom objektumot képvisel.
type: docs
weight: 4265
url: /hu/aspose.slides/izoomobject/
---
## IZoomObject osztály


Egy dián lévő Zoom objektumot képvisel.

```cpp
class IZoomObject : public virtual Aspose::Slides::IGraphicalObject
```

## Metódusok

| Method | Leírás |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Új helyőrzőt ad hozzá, ha nincs, és a helyőrző tulajdonságait a megadottra állítja. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Visszaadja a alakzathoz társított alternatív szöveget. Olvasd [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Visszaadja az alakzathoz társított alternatív szöveg címét. Olvasd [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Tulajdonság megadja, hogyan jelenik meg az alakzat fekete-fehér megjelenítő módban. Olvasd [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Visszaadja az alakzaton lévő kapcsolati pontok számát. Csak olvasható **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Visszaadja az alakzat egyéni adatait. Csak olvasható [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Visszaadja a [EffectFormat](../effectformat/) objektumot, amely a alakzatra alkalmazott pixel hatásokat tartalmazza. Csak olvasható [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Visszaadja a [FillFormat](../fillformat/) objektumot, amely az alakzat kitöltési formázási tulajdonságait tartalmazza. Csak olvasható [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Visszaadja az alakzat keret tulajdonságait. Olvasd [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Visszaadja az alakzat zárolásait. Csak olvasható [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Lekéri az alakzat magasságát pontban mérve. Olvasd **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Megállapítja, hogy az alakzat rejtett-e. Olvasd **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Visszaadja a egérkattintásra definiált hiperhivatkozást. Olvasd [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hiperhivatkozás-kezelő. Csak olvasható [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Visszaadja az egér fölé mozgatására definiált hiperhivatkozást. Olvasd [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](./get_imagetype/)() | Lekéri egy zoom objektum kép típusát. Olvasd [ZoomImageType](../zoomimagetype/). Alapértelmezett érték: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Lekéri a 'Mark as decorative' opciót. Olvasás/írás **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Megállapítja, hogy az alakzat csoportosított-e. Csak olvasható **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Megállapítja, hogy az alakzat TextHolder-e. Csak olvasható **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Visszaadja a [LineFormat](../lineformat/) objektumot, amely az alakzat vonalformázási tulajdonságait tartalmazza. Csak olvasható [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Visszaadja egy alakzat nevét. Olvasd [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Visszaad egy diára korlátozott egyedi azonosítót, amely állandó a forma élettartama során, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéből. Csak olvasható **uint32_t**. Lásd még [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Visszaadja a szülő [GroupShape](../groupshape/) objektumot, ha az alakzat csoportosított. Egyébként null értéket ad vissza. Csak olvasható [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Visszaadja az alakzat helyőrzőjét. Csak olvasható [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Visszaadja a prezentációt. Csak olvasható [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Visszaadja a nyers alakzat keret tulajdonságait. Olvasd [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](./get_returntoparent/)() | Lekéri a diavetítés navigációs viselkedését. Olvasd **bool**. Alapértelmezett érték: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Visszaadja a fokok számát, amennyivel a megadott alakzat a z-tengely körül el van fordítva. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást. Olvasd **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Visszaadja az alakzat zárolásait. Csak olvasható [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](./get_showbackground/)() | Lekéri azt az értéket, amely meghatározza, hogy a Zoom a cél dia háttérét használja-e. Olvasd **bool**. Alapértelmezett érték: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Visszaadja az alap diát. Csak olvasható [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Visszaadja a [ThreeDFormat](../threedformat/) objektumot, amely egy alakzat vonalformázási tulajdonságait tartalmazza. Csak olvasható [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TransitionDuration](./get_transitionduration/)() | Lekéri a Zoom és dia közötti átmenet időtartamát. Olvasd **float**. Alapértelmezett érték: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy programozottan áthelyezheti, ezért nem tekinthető állandó egyedi kulcsnak. Csak olvasható **uint32_t**. Lásd még [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Lekéri az alakzat szélességét pontban mérve. Olvasd **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Lekéri az alakzat bal-felső sarkának x koordinátáját pontban mérve. Olvasd **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Lekéri az alakzat bal-felső sarkának y koordinátáját pontban mérve. Olvasd **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](./get_zoomimage/)() | Lekéri a zoom objektum képét. Olvasd [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Visszaadja egy alakzat pozícióját a z-sorrendben. A Shapes[0] a z-sorrend hátulját, a Shapes[Shapes.Count - 1] a frontját adja vissza. Csak olvasható **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Visszaad egy alap helyőrző alakzatot (az elrendezésből és/vagy fő diákról származó alakzat, amelyből a jelenlegi alakzat örököl). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyéni objektumok hash-elését. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Visszaadja az alakzat bélyegképét. Alapértelmezés szerint a [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) alakzat bélyegkép határai típusát használja. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Visszaadja az alakzat bélyegképét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) őr objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolás-építését. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolás-építését. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az érték típusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja sztring és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja sztringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Meghatározza, hogy ez az alakzat nem helyőrző. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Beállítja az alakzathoz társított alternatív szöveget. Írj [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Beállítja az alakzathoz társított alternatív szöveg címét. Írj [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Tulajdonság megadja, hogyan jelenik meg az alakzat fekete-fehér megjelenítő módban. Írj [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Beállítja az alakzat keret tulajdonságait. Írj [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Beállítja az alakzat magasságát, pontban mérve. Írj **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Megadja, hogy az alakzat rejtett-e. Írj **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Beállítja az egérkattintásra definiált hiperhivatkozást. Írj [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Beállítja az egér fölé mozgatásra definiált hiperhivatkozást. Írj [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](./set_imagetype/)([ZoomImageType](../zoomimagetype/)) | Beállítja egy zoom objektum kép típust. Írj [ZoomImageType](../zoomimagetype/). Alapértelmezett érték: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Beállítja a 'Mark as decorative' opciót. Olvasás/írás **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Beállítja egy alakzat nevét. Írj [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Beállítja a nyers alakzat keret tulajdonságait. Írj [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](./set_returntoparent/)(**bool**) | Beállítja a diavetítés navigációs viselkedését. Írj **bool**. Alapértelmezett érték: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Beállítja a fokok számát, amellyel a megadott alakzat a z-tengely körül el van fordítva. A pozitív érték az óramutató járásával megegyező, a negatív az ellenkező forgást jelzi. Írj **float**. |
| virtual void [set_ShowBackground](./set_showbackground/)(**bool**) | Beállítja azt az értéket, amely meghatározza, hogy a Zoom a cél dia háttérét használja-e. Írj **bool**. Alapértelmezett érték: true |
| virtual void [set_TransitionDuration](./set_transitionduration/)(**float**) | Beállítja a Zoom és dia közötti átmenet időtartamát. Írj **float**. Alapértelmezett érték: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Beállítja az alakzat szélességét pontban mérve. Írj **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Beállítja az alakzat bal-felső sarkának x koordinátáját pontban mérve. Írj **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Beállítja az alakzat bal-felső sarkának y koordinátáját pontban mérve. Írj **float**. |
| virtual void [set_ZoomImage](./set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | Beállítja a zoom objektum képét. Írj [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (nem megosztott). Lehetővé teszi a mutatók tárolókban való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem kell közvetlenül hívni; helyette használd az okos mutatókat vagy a ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem kell közvetlenül hívni; helyette használd az okos mutatókat vagy a ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyéni objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) őr objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem kell közvetlenül hívni; helyette használd az okos mutatókat vagy a ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem kell közvetlenül hívni; helyette használd az okos mutatókat vagy a ThisProtector-t. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Elmenti a [Shape](../shape/) tartalmát SVG fájlba. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Elmenti a [Shape](../shape/) tartalmát SVG fájlba. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IGraphicalObject](../igraphicalobject/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)