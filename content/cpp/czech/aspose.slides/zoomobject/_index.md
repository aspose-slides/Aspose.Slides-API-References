---
title: ZoomObject
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje objekt Zoom v snímku.
type: docs
weight: 5591
url: /cs/aspose.slides/zoomobject/
---
## ZoomObject třída

Reprezentuje objekt Zoom na snímku.

```cpp
class ZoomObject : public Aspose::Slides::GraphicalObject,
                   public virtual Aspose::Slides::IZoomObject
```

## Metody

| Metoda | Popis |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Přidá nový zástupný znak, pokud neexistuje, a nastaví vlastnosti zástupného znaku na zadaný. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Vrací alternativní text spojený s objektem. Přečtěte si [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Vrací nadpis alternativního textu spojeného s objektem. Přečtěte si [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Vlastnost určuje, jak bude objekt vykreslen v černobílém režimu. Přečtěte si [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Vrací počet připojovacích míst na objektu. Pouze pro čtení **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Vrací vlastní data objektu. Pouze pro čtení [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Vrací objekt [EffectFormat](../effectformat/), který obsahuje pixlové efekty aplikované na objekt. Poznámka: může vrátit null pro některé typy objektů, které nemají vlastnosti efektu. Pouze pro čtení [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Vrací objekt [FillFormat](../fillformat/), který obsahuje vlastnosti formátování výplně pro objekt. Poznámka: může vrátit null pro některé typy objektů, které nemají vlastnosti výplně. Pouze pro čtení [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Vrací vlastnosti rámce objektu. Přečtěte si [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Vrací zámky objektu. Pouze pro čtení [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Získává výšku objektu v bodech. Pouze pro čtení **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Určuje, zda je objekt skrytý. Pouze pro čtení **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Vrací hyperodkaz definovaný pro kliknutí myší. Přečtěte si [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Vrací správce hyperodkazů. Pouze pro čtení [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Vrací hyperodkaz definovaný pro přejetí myší. Přečtěte si [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](./get_imagetype/)() override | Získává typ obrázku objektu zoom. Přečtěte si [ZoomImageType](../zoomimagetype/). Výchozí hodnota: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Získává možnost „Mark as decorative“. Čtení/zápis **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Určuje, zda je objekt seskupen. Pouze pro čtení **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Určuje, zda je objekt TextHolder_PPT. Pouze pro čtení **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Vrací objekt [LineFormat](../lineformat/), který obsahuje vlastnosti formátování čáry pro objekt. Poznámka: může vrátit null pro některé typy objektů, které nemají vlastnosti čáry. Pouze pro čtení [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Vrací název objektu. Nesmí být null. V případě potřeby použijte prázdný řetězec. Přečtěte si [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou dobu existence objektu a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na objekt odkudkoli v dokumentu. Pouze pro čtení **uint32_t**. Viz také [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Vrací nadřazený objekt [GroupShape](../groupshape/), pokud je objekt seskupen. Jinak vrací null. Pouze pro čtení [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Vrací zástupný znak pro objekt. Vrací null, pokud objekt nemá zástupný znak. Pouze pro čtení [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Vrací nadřazenou prezentaci snímku. Pouze pro čtení [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Vrací surové vlastnosti rámce objektu. Přečtěte si [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](./get_returntoparent/)() override | Získává chování navigace v prezentaci. Pouze pro čtení **bool**. Výchozí hodnota: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | Vrací počet stupňů, o které je specifikovaný objekt otočen kolem osy z. Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček. Pouze pro čtení **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Vrací zámky objektu. Pouze pro čtení [IBaseShapeLock](../ibaseshapelock/). |
| **bool** [get_ShowBackground](./get_showbackground/)() override | Získává hodnotu určující, zda Zoom použije pozadí cílového snímku. Pouze pro čtení **bool**. Výchozí hodnota: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Vrací nadřazený snímek objektu. Pouze pro čtení [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Vrací objekt [ThreeDFormat](../threedformat/) s 3D vlastnostmi efektu pro objekt. Poznámka: může vrátit null pro některé typy objektů, které nemají 3D vlastnosti. Pouze pro čtení [IThreeDFormat](../ithreedformat/). |
| **float** [get_TransitionDuration](./get_transitionduration/)() override | Získává dobu trvání přechodu mezi Zoom a snímkem. Pouze pro čtení **float**. Výchozí hodnota: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem. Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována za trvalý jedinečný klíč. Pouze pro čtení **uint32_t**. Viz také [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Získává šířku objektu v bodech. Pouze pro čtení **float**. |
| **float** [get_X](../shape/get_x/)() override | Získává x-souřadnici levého horního rohu objektu v bodech. Pouze pro čtení **float**. |
| **float** [get_Y](../shape/get_y/)() override | Získává y-souřadnici levého horního rohu objektu v bodech. Pouze pro čtení **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](./get_zoomimage/)() override | Získává obrázek pro objekt zoom. Přečtěte si [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Vrací pozici objektu v z-pořadí. Shapes[0] vrací objekt na konci z-pořadí a Shapes[Shapes.Count - 1] vrací objekt na začátku z-pořadí. Pouze pro čtení **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Vrací základní zástupný tvar (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Vrací miniaturu tvaru. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) typ ohraničení miniatury tvaru se používá ve výchozím nastavení. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Vrací miniaturu tvaru. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Získává vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Volá se přímo nebo se použije strážní objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje konstrukci kopií podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Přiřazovací operátor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje konstrukci kopií podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač odkazů o zadanou hodnotu. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definuje, že tento tvar není zástupný. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Nastavuje alternativní text spojený s tvarem. Zapište [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Nastavuje titulek alternativního textu spojeného s tvarem. Zapište [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Vlastnost určuje, jak se tvar vykreslí v režimu černobílého zobrazení. Zapište [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Nastavuje vlastnosti rámečku tvaru. Zapište [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Nastavuje výšku tvaru, měřenou v bodech. Zapište **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Určuje, zda je tvar skrytý. Zapište **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Nastavuje hypertextový odkaz definovaný pro kliknutí myší. Zapište [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Nastavuje hypertextový odkaz definovaný pro přejetí myší. Zapište [IHyperlink](../ihyperlink/). |
| void [set_ImageType](./set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | Nastavuje typ obrázku zoom objektu. Zapište [ZoomImageType](../zoomimagetype/). Výchozí hodnota: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Nastavuje volbu 'Mark as decorative'. Čtení/zápis **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Nastavuje název tvaru. Nesmí být null. V případě potřeby použijte prázdný řetězec. Zapište [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Nastavuje surové vlastnosti rámečku tvaru. Zapište [IShapeFrame](../ishapeframe/). |
| void [set_ReturnToParent](./set_returntoparent/)(**bool**) override | Nastavuje chování navigace v prezentaci. Zapište **bool**. Výchozí hodnota: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Nastavuje počet stupňů, o které je daný tvar otočen kolem osy z. Kladná hodnota označuje otočení po směru hodinových ručiček; záporná hodnota označuje otočení proti směru hodinových ručiček. Zapište **float**. |
| void [set_ShowBackground](./set_showbackground/)(**bool**) override | Nastavuje hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Zapište **bool**. Výchozí hodnota: true |
| void [set_TransitionDuration](./set_transitionduration/)(**float**) override | Nastavuje dobu trvání přechodu mezi Zoom a snímkem. Zapište **float**. Výchozí hodnota: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | Nastavuje šířku tvaru, měřenou v bodech. Zapište **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Nastavuje souřadnici x levého horního rohu tvaru, měřenou v bodech. Zapište **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Nastavuje souřadnici y levého horního rohu tvaru, měřenou v bodech. Zapište **float**. |
| void [set_ZoomImage](./set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | Nastavuje obrázek pro zoom objekt. Zapište [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastavuje n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného počítadla odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený počitadlo odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený počitadlo odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Volá se přímo nebo se použije strážní objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabé počitadlo odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabé počitadlo odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Ukládá obsah [Shape](../shape/) jako SVG soubor. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Ukládá obsah [Shape](../shape/) jako SVG soubor. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |
## Viz také

* Třída [GraphicalObject](../graphicalobject/)
* Třída [IZoomObject](../izoomobject/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)