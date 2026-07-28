---
title: ZoomFrame
second_title: Aspose.Slides a C++ API hivatkozás
description: Egy dián lévő Slide Zoom objektumot képvisel.
type: docs
weight: 5578
url: /hu/aspose.slides/zoomframe/
---
## ZoomFrame osztály

Egy [Slide](../slide/) Zoom objektumot képvisel egy dián.

```cpp
class ZoomFrame : public Aspose::Slides::ZoomObject,
                  public Aspose::Slides::IZoomFrame
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Új helyőrzőt ad hozzá, ha nincs, és beállítja a helyőrző tulajdonságait egy megadottra. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Visszaadja a alakzathoz kapcsolódó alternatív szöveget. Olvasd [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Visszaadja az alakzathoz kapcsolódó alternatív szöveg címét. Olvasd [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Az legyen, hogy az alakzat fekete-fehér megjelenítési módban hogyan jelenik meg. Olvasd [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Visszaadja az alakzon lévő kapcsolódási pontok számát. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Visszaadja az alakzat egyedi adatait. Csak olvasható [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Visszaadja a [EffectFormat](../effectformat/) objektumot, amely a alakzatra alkalmazott pixel-effekteket tartalmazza. Megjegyzés: bizonyos alakzattípusok esetén, amelyeknek nincs effektus tulajdonsága, null értéket adhat vissza. Csak olvasható [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Visszaadja a [FillFormat](../fillformat/) objektumot, amely az alakzat kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak olvasható [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Visszaadja az alakzat keretének tulajdonságait. Olvasd [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Visszaadja az alakzat zárolásait. Csak olvasható [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Megkapja az alakzat magasságát pontban mérve. Olvas **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Megállapítja, hogy az alakzat rejtett-e. Olvas **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Visszaadja az egérkattintásra definiált hiperhivatkozást. Olvasd [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasható [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Visszaadja az egér-felé-húzásra definiált hiperhivatkozást. Olvasd [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](../zoomobject/get_imagetype/)() override | Megkapja egy zoom objektum kép típusát. Olvas [ZoomImageType](../zoomimagetype/). Alapértelmezett érték: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Megkapja a „Megjelölés dekoratívként” opciót Olvasás/írás **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Megállapítja, hogy az alakzat csoportosított-e. Csak olvasható **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Megállapítja, hogy az alakzat TextHolder_PPT-e. Csak olvasható **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Visszaadja a [LineFormat](../lineformat/) objektumot, amely az alakzat vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusoknál, amelyeknek nincs vonal tulajdonsága, null értéket adhat vissza. Csak olvasható [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Visszaadja egy alakzat nevét. Nem lehet null. Szükség esetén üres karakterláncot használjon. Olvasd [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Visszaad egy diára vonatkozó egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy interoperációs kód megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasható **uint32_t**. Lásd még [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Visszaadja a szülő [GroupShape](../groupshape/) objektumot, ha az alakzat csoportosított. Egyébként null értéket ad vissza. Csak olvasható [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Visszaadja egy alakzat helyőrzőjét. Null értéket ad vissza, ha az alakzatnak nincs helyőrzője. Csak olvasható [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Visszaadja egy dia szülő prezentációját. Csak olvasható [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Visszaadja a nyers alakzatkeret tulajdonságait. Olvasd [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](../zoomobject/get_returntoparent/)() override | Megkapja a diavetítés navigációs viselkedését. Olvas **bool**. Alapértelmezett érték: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | Visszaadja, hány fokkal van a megadott alakzat elforgatva a z-tengely körül. A pozitív érték az óramutató járásának irányú forgást jelzi; a negatív érték az ellenkező irányt. Olvas **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Visszaadja az alakzat zárolásait. Csak olvasható [IBaseShapeLock](../ibaseshapelock/). |
| **bool** [get_ShowBackground](../zoomobject/get_showbackground/)() override | Megkapja azt az értéket, amely meghatározza, hogy a Zoom a cél dia hátterét használja-e. Olvas **bool**. Alapértelmezett érték: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Visszaadja egy alakzat szülő diáját. Csak olvasható [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | Megkapja a diát, amelyhez a [Slide](../slide/) Zoom objektum kapcsolódik. Olvasd [ISlide](../islide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Visszaadja a [ThreeDFormat](../threedformat/) objektumot, amely az alakzat 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusok esetén, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak olvasható [IThreeDFormat](../ithreedformat/). |
| **float** [get_TransitionDuration](../zoomobject/get_transitionduration/)() override | Megkapja a Zoom és dia közötti átmenet időtartamát. Olvas **float**. Alapértelmezett érték: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Visszaad egy belső, prezentációra vonatkozó azonosítót, amelyet kiegészítők vagy más kódok használhatnak. Mivel ezt az értéket a felhasználó vagy programozottan át lehet állítani, nem tekinthető állandó egyedi kulcsnak. Csak olvasható **uint32_t**. Lásd még [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Megkapja az alakzat szélességét pontban mérve. Olvas **float**. |
| **float** [get_X](../shape/get_x/)() override | Megkapja az alakzat bal-felső sarkának x-koordinátáját pontban mérve. Olvas **float**. |
| **float** [get_Y](../shape/get_y/)() override | Megkapja az alakzat bal-felső sarkának y-koordinátáját pontban mérve. Olvas **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../zoomobject/get_zoomimage/)() override | Megkapja a zoom objektum képét. Olvasd [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Visszaadja egy alakzat z-sorrendbeli pozícióját. A Shapes[0] a z-sorrend hátsó alakzatát adja vissza, a Shapes[Shapes.Count - 1] pedig az elülső alakzatot. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Visszaad egy egyszerű helyőrző alakzatot (a jelenlegi alakzatra alkalmazott elrendezésből és/vagy mester diáról örökölt alakzat). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz tartozó referencia számláló adatstruktúráját. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hash-elését. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Visszaadja az alakzat bélyegképét. Alapértelmezésként a [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) alakzat bélyegkép határ típusa használatos. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Visszaadja az alakzat bélyegképét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Megkapja az alakzat vizuális határait, ami a megjelenített tartalom alapján számított. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | A C# lock() utasítás zárolását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referencia alapján hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referencia alapján hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-alapú összehasonlítás értéktípusú objektum és nullptr között. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Meghatározza, hogy ez az alakzat nem helyőrző. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Beállítja az alakzathoz kapcsolódó alternatív szöveget. Írás [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Beállítja az alakzathoz kapcsolódó alternatív szöveg címét. Írás [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | A tulajdonság meghatározza, hogy egy alakzat fekete-fehér megjelenítési módban hogyan jelenik meg. Írás [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Beállítja az alakzatkeret tulajdonságait. Írás [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Beállítja az alakzat magasságát pontban mérve. Írás **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Megadja, hogy az alakzat rejtett-e. Írás **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Beállítja az egérkattintásra definiált hiperhivatkozást. Írás [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Beállítja az egér-felé-húzásra definiált hiperhivatkozást. Írás [IHyperlink](../ihyperlink/). |
| void [set_ImageType](../zoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | Beállítja egy zoom objektum kép típusát. Írás [ZoomImageType](../zoomimagetype/). Alapértelmezett érték: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Beállítja a „Megjelölés dekoratívként” opciót Olvasás/írás **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Beállítja az alakzat nevét. Nem lehet null. Szükség esetén üres karakterláncot használjon. Írás [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Beállítja a nyers alakzatkeret tulajdonságait. Írás [IShapeFrame](../ishapeframe/). |
| void [set_ReturnToParent](../zoomobject/set_returntoparent/)(**bool**) override | Beállítja a diavetítés navigációs viselkedését. Írás **bool**. Alapértelmezett érték: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Beállítja a megadott alakzat z-tengely körüli forgatási fokszámát. A pozitív érték az óramutató járásának irányú forgást jelzi; a negatív az ellenkező irányt. Írás **float**. |
| void [set_ShowBackground](../zoomobject/set_showbackground/)(**bool**) override | Beállítja azt az értéket, amely meghatározza, hogy a Zoom a cél dia hátterét használja-e. Írás **bool**. Alapértelmezett érték: true |
| void [set_TargetSlide](./set_targetslide/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | Beállítja a diát, amelyhez a [Slide](../slide/) Zoom objektum kapcsolódik. Írás [ISlide](../islide/). |
| void [set_TransitionDuration](../zoomobject/set_transitionduration/)(**float**) override | Beállítja a Zoom és dia közötti átmenet időtartamát. Írás **float**. Alapértelmezett érték: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | Beállítja az alakzat szélességét pontban mérve. Írás **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Beállítja az alakzat bal-felső sarkának x-koordinátáját pontban mérve. Írás **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Beállítja az alakzat bal-felső sarkának y-koordinátáját pontban mérve. Írás **float**. |
| void [set_ZoomImage](../zoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | Beállítja a zoom objektum képét. Írás [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóvá (nem megosztottá) állítja. Lehetővé teszi a mutatók konténerben való gyenge módra történő váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referencia számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | A C# typeof([System.Object](../../system/object/)) konstrukciót valósítja meg. |
| void [Unlock](../../system/object/unlock/)() | A C# lock() utasítás feloldását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [ZoomObject](../zoomobject/)
* Osztály [IZoomFrame](../izoomframe/)
* Névterület [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)