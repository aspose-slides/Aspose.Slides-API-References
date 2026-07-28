---
title: OleObjectFrame
second_title: Aspose.Slides C++ API referencia
description: OLE objektumot képvisel egy dián.
type: docs
weight: 4603
url: /hu/aspose.slides/oleobjectframe/
---
## OleObjectFrame osztály

OLE objektumot képvisel egy dián.

```cpp
class OleObjectFrame : public Aspose::Slides::GraphicalObject,
                       public Aspose::Slides::IOleObjectFrame
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Új helyőrzőt ad hozzá, ha nincs, és a helyőrző tulajdonságait egy megadottra állítja. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantikai szabályok szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Visszaadja a formához kapcsolódó alternatív szöveget. Olvasd [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Visszaadja a formához kapcsolódó alternatív szöveg címét. Olvasd [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | A tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítési módban. Olvasd [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Visszaadja a forma csatlakozási pontjainak számát. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Visszaadja a forma egyéni adatait. Csak olvasható [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Visszaadja a [EffectFormat](../effectformat/) objektumot, amely a forma alkalmazott pixel effektjeit tartalmazza. Megjegyzés: bizonyos forma típusoknál, amelyeknek nincs effektus tulajdonsága, null értéket adhat vissza. Csak olvasható [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() override | Az OLE beágyazott adatokkal kapcsolatos információkat kapja meg. Olvasd [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/). |
| [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() override | Visszaadja a beágyazott OLE objektum fájlnevét. |
| [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() override | Visszaadja a beágyazott OLE objektum elérési útját. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Visszaadja a [FillFormat](../fillformat/) objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formák esetén, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak olvasható [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Visszaadja a forma keretének tulajdonságait. Olvasd [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Visszaadja a forma zárolásait. Csak olvasható [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | A forma magasságát adja vissza pontban mérve. Olvas **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Meghatározza, hogy a forma rejtett-e. Olvas **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Visszaadja az egérkattintásra definiált hiperhivatkozást. Olvasd [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Visszaadja a hiperhivatkozáskezelőt. Csak olvasható [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Visszaadja az egér fölé húzásra definiált hiperhivatkozást. Olvasd [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Megkapja a 'Mark as decorative' opciót. Olvasás/írás **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Meghatározza, hogy a forma csoportosított-e. Csak olvasható **bool**. |
| **bool** [get_IsObjectIcon](./get_isobjecticon/)() override | Megállapítja, hogy az objektum ikonként látható-e. Olvas **bool**. |
| **bool** [get_IsObjectLink](./get_isobjectlink/)() override | Megállapítja, hogy az objektum külső fájlhoz van-e kapcsolva. Csak olvasható **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Megállapítja, hogy a forma TextHolder_PPT-e. Csak olvasható **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Visszaadja a [LineFormat](../lineformat/) objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos forma típusoknál, amelyeknek nincs vonal tulajdonsága, null értéket adhat vissza. Csak olvasható [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() override | Visszaadja a hivatkozott fájl teljes elérési útját. Rövid fájlnév lesz használva. Csak olvasható [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Visszaadja a hivatkozott fájl teljes elérési útját. Hosszú fájlnév lesz használva. Olvasd [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() override | Visszaadja a hivatkozott fájl relatív útját, ha létezik, különben egy üres karakterláncot ad vissza. Csak olvasható [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Visszaadja a forma nevét. Nem lehet null. Szükség esetén üres karakterlánc használható. Olvasd [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() override | Visszaadja egy objektum nevét. Olvasd [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() override | Visszaadja egy objektum ProgID-jét. Csak olvasható [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Visszaad egy diára korlátozódó egyedi azonosítót, amely a forma teljes élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasható **uint32_t**. Lásd még [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Visszaadja a szülő [GroupShape](../groupshape/) objektumot, ha a forma csoportosított. Egyébként null értéket ad vissza. Csak olvasható [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Visszaadja a forma helyőrzőjét. Ha a formának nincs helyőrzője, null értéket ad vissza. Csak olvasható [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Visszaadja egy dia szülő prezentációját. Csak olvasható [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Visszaadja a nyers forma keretének tulajdonságait. Olvasd [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Visszaadja a megadott forma Z-tengely körüli elfordulásának fokszámát. Pozitív érték a óramutató járásával megegyező forgást jelzi; negatív érték az ellenkező irányt. Olvas **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Visszaadja a forma zárolásait. Csak olvasható [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Visszaadja a forma szülő diáját. Csak olvasható [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() override | Visszaadja az OleObject képkitöltési tulajdonságok objektumát. Csak olvasható [IPictureFillFormat](../ipicturefillformat/). |
| [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() override | Visszaadja az OleObject ikon címét. Olvasd [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Visszaadja a [ThreeDFormat](../threedformat/) objektumot, amely a forma 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos formáknál, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak olvasható [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Visszaad egy belső, prezentációra korlátozódó azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy programozott módon újra lehet rendelni, nem tekinthető állandó egyedi kulcsnak. Csak olvasható **uint32_t**. Lásd még [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **bool** [get_UpdateAutomatic](./get_updateautomatic/)() override | Megállapítja, hogy a hivatkozott beágyazott objektum automatikusan frissül-e a prezentáció megnyitásakor vagy nyomtatásakor. Olvas **bool**. |
| **float** [get_Width](../shape/get_width/)() override | A forma szélességét adja vissza pontban mérve. Olvas **float**. |
| **float** [get_X](../shape/get_x/)() override | A forma bal felső sarkának x-koordinátáját adja vissza pontban mérve. Olvas **float**. |
| **float** [get_Y](../shape/get_y/)() override | A forma bal felső sarkának y-koordinátáját adja vissza pontban mérve. Olvas **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Visszaadja egy forma z-sorrendben elfoglalt pozícióját. A Shapes[0] a z-sorrend hátuljában lévő formát adja, a Shapes[Shapes.Count - 1] pedig az elejében lévő formát. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Visszaad egy alap helyőrző formát (formát, amely a layoutból és/vagy a mesterdiáról származik, ahonnan az aktuális forma származik). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | A objektumhoz tartozó referencia számláló adatstruktúrát adja vissza. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Visszaadja a forma bélyegképét. Alapértelmezés szerint a [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) forma bélyegkép határ típusát használja. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Visszaadja a forma bélyegképét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | A forma megjelenített határait adja vissza, amely a renderelt tartalomból számítódik. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum egy példány-e a targetType által leírt típusról. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást zároláshoz. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi a származtatott osztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi a származtatott osztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Érték típusú objektumot hivatkozás alapján hasonlít össze nullptr-rel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) string és nullptr esetére specializált változata. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) stringek esetére specializált változata. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Meghatározza, hogy ez a forma nem helyőrző. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Beállítja a forma alternatív szövegét. Írja [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Beállítja a forma alternatív szövegének címét. Írja [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | A tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér módon. Írja [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Beállítja a forma keret tulajdonságait. Írja [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Beállítja a forma magasságát pontban mérve. Írja **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Meghatározza, hogy a forma rejtett-e. Írja **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Beállítja az egérkattintásra definiált hiperhivatkozást. Írja [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Beállítja az egér fölé húzásra definiált hiperhivatkozást. Írja [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Beállítja a 'Mark as decorative' opciót. Olvasás/írás **bool**. |
| void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) override | Megállapítja, hogy az objektum ikonként látható-e. Írja **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Visszaadja a hivatkozott fájl teljes elérési útját. Hosszú fájlnév lesz használva. Írja [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Beállítja a forma nevét. Nem lehet null. Szükség esetén üres karakterláncot használjon. Írja [System::String](../../system/string/). |
| void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) override | Beállítja egy objektum nevét. Írja [System::String](../../system/string/). |
| void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) override | Visszaadja egy objektum ProgID-jét. Csak olvasható [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Beállítja a nyers forma keret tulajdonságait. Írja [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Beállítja a megadott forma Z-tengely körüli elfordulásának fokszámát. Pozitív érték az óramutató járásával megegyező forgást jelzi; negatív érték az ellenkező irányt. Írja **float**. |
| void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) override | Beállítja az OleObject ikon címét. Írja [System::String](../../system/string/). |
| void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) override | Megállapítja, hogy a hivatkozott beágyazott objektum automatikusan frissül-e a prezentáció megnyitásakor vagy nyomtatásakor. Írja **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | Beállítja a forma szélességét pontban mérve. Írja **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Beállítja a forma bal felső sarkának x-koordinátáját pontban mérve. Írja **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Beállítja a forma bal felső sarkának y-koordinátáját pontban mérve. Írja **float**. |
| void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | Beállítja az OLE beágyazott adatok információit. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablon argumentumot gyenge mutatóként állítja be (nem megosztott). Lehetővé teszi a mutatók tartályban való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referencia számláló aktuális értékét adja vissza. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések

A következő példa bemutatja, hogyan lehet hozzáférni az OLE objektum keretekhez. 
```cpp
// Betölti a PPTX fájlt egy prezentáció objektumba
auto pres = System::MakeObject<Presentation>(u"AccessingOLEObjectFrame.pptx");

// Eléri az első diát
auto slide = pres->get_Slides()->idx_get(0);
// Átcastolja a formát OleObjectFrame típusra
System::SharedPtr<OleObjectFrame> oleObjectFrame = System::AsCast<OleObjectFrame>(slide->get_Shapes()->idx_get(0));
// Reads the OLE Object and writes it to disk
if (oleObjectFrame != nullptr)
{
    // Lekéri a beágyazott fájl adatait
    System::ArrayPtr<uint8_t> data = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileData();
    // Lekéri a beágyazott fájl kiterjesztését
    System::String fileExtention = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileExtension();
    // Létrehozza az útvonalat a kinyert fájl mentéséhez
    System::String extractedPath = System::String(u"excelFromOLE_out") + fileExtention;
    // Elmenti a kinyert adatokat
    auto stream = System::MakeObject<System::IO::FileStream>(extractedPath,
                                                             System::IO::FileMode::Create,
                                                             System::IO::FileAccess::Write);
    stream->Write(data, 0, data->get_Length());
}
```

## Lásd még

* Osztály [GraphicalObject](../graphicalobject/)
* Osztály [IOleObjectFrame](../ioleobjectframe/)
* Névterület [Aspose::Slides](../)
* Library [Aspose.Slides](../../)