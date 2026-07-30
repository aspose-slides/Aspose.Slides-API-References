---
title: ISummaryZoomSection
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Reprezentuje objekt sekce Summary Zoom v rámci rámce Summary Zoom.
type: docs
weight: 3927
url: /cs/aspose.slides/isummaryzoomsection/
---
## ISummaryZoomSection třída


Represents a Summary Zoom [Section](../section/) object in a Summary Zoom frame.

```cpp
class ISummaryZoomSection : public virtual Aspose::Slides::ISectionZoomFrame
```

## Metody

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Přidá nový zástupný objekt, pokud neexistuje, a nastaví jeho vlastnosti na určený. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Vrací alternativní text spojený s tvarem. Přečtěte [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Vrací název alternativního textu spojeného s tvarem. Přečtěte [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Vlastnost určuje, jak bude tvar vykreslen v černobílém zobrazení. Přečtěte [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Vrací počet připojovacích míst na tvaru. Pouze pro čtení **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Vrací vlastní data tvaru. Pouze pro čtení [ICustomData](../icustomdata/). |
| virtual [System::String](../../system/string/) [get_Description](./get_description/)() | Vrací textový popis objektu Summary Zoom [Section](../section/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Vrací objekt [EffectFormat](../effectformat/), který obsahuje pixelové efekty aplikované na tvar. Pouze pro čtení [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Vrací objekt [FillFormat](../fillformat/), který obsahuje vlastnosti výplně pro tvar. Pouze pro čtení [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Vrací vlastnosti rámečku tvaru. Přečtěte [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Vrací zámky tvaru. Pouze pro čtení [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Získá výšku tvaru, měřenou v bodech. Čtení **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Určuje, zda je tvar skrytý. Čtení **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Vrací hyperodkaz definovaný pro kliknutí myší. Přečtěte [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Správce hyperodkazů Pouze pro čtení [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Vrací hyperodkaz definovaný pro najetí myší. Přečtěte [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | Získá typ obrazu zoom objektu. Přečtěte [ZoomImageType](../zoomimagetype/). Výchozí hodnota: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Získá možnost 'Mark as decorative'. Čtení/zápis **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Určuje, zda je tvar seskupen. Pouze pro čtení **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Určuje, zda je tvar TextHolder. Pouze pro čtení **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Vrací objekt [LineFormat](../lineformat/), který obsahuje vlastnosti formátování čáry pro tvar. Pouze pro čtení [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Vrací název tvaru. Přečtěte [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení **uint32_t**. Viz také [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Vrací rodičovský objekt [GroupShape](../groupshape/), pokud je tvar seskupen. Jinak vrací null. Pouze pro čtení [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Vrací zástupný objekt pro tvar. Pouze pro čtení [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Vrací prezentaci. Pouze pro čtení [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Vrací surové vlastnosti rámečku tvaru. Přečtěte [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | Získá chování navigace v prezentaci. Čtení **bool**. Výchozí hodnota: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Vrací počet stupňů, o které je daný tvar otočen kolem osy z. Kladná hodnota označuje otočení po směru hodinových ručiček; záporná hodnota označuje otočení proti směru hodinových ručiček. Čtení **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Vrací zámky tvaru. Pouze pro čtení [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | Získá hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Čtení **bool**. Výchozí hodnota: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Vrací základní snímek. Pouze pro čtení [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](../isectionzoomframe/get_targetsection/)() | Získá objekt sekce, na který je objekt [Section](../section/) Zoom propojen. Přečtěte [ISection](../isection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Vrací objekt [ThreeDFormat](../threedformat/), který obsahuje vlastnosti formátování čáry pro tvar. Pouze pro čtení [IThreeDFormat](../ithreedformat/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Vrací textový název objektu Summary Zoom [Section](../section/). |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | Získá dobu trvání přechodu mezi Zoom a snímkem. Čtení **float**. Výchozí hodnota: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem. Protože může být uživatelem nebo programově přidělen znovu, nesmí být považován za trvalý jedinečný klíč. Pouze pro čtení **uint32_t**. Viz také [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Získá šířku tvaru, měřenou v bodech. Čtení **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Získá souřadnici x levého horního rohu tvaru, měřenou v bodech. Čtení **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Získá souřadnici y levého horního rohu tvaru, měřenou v bodech. Čtení **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | Získá obrázek pro zoom objekt. Přečtěte [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Vrací pozici tvaru ve vrstvě z. Shapes[0] vrací tvar v zadní části vrstvy z a Shapes[Shapes.Count - 1] vrací tvar v přední části vrstvy z. Pouze pro čtení **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Vrací základní zástupný tvar (tvar z rozvržení a/nebo hlavní snímky, ze kterého je aktuální tvar zděděn). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počitadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Vrací náhled tvaru. Typ ohraničení náhledu [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) je použit jako výchozí. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Vrací náhled tvaru. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie C# [System.Object.GetType()](../../system/object/gettype/) volání. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie C# operátoru 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Definuje, že tento tvar není zástupný. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Nastavuje alternativní text spojený s tvarem. Zápis [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Nastavuje název alternativního textu spojeného s tvarem. Zápis [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu. Zápis [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Description](./set_description/)([System::String](../../system/string/)) | Vrací textový popis objektu Summary Zoom [Section](../section/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Nastavuje vlastnosti rámečku tvaru. Zápis [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Nastavuje výšku tvaru, měřenou v bodech. Zápis **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Určuje, zda je tvar skrytý. Zápis **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Nastavuje hyperodkaz definovaný pro kliknutí myší. Zápis [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Nastavuje hyperodkaz definovaný pro najetí myší. Zápis [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | Nastavuje typ obrazu zoom objektu. Zápis [ZoomImageType](../zoomimagetype/). Výchozí hodnota: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Nastavuje možnost 'Mark as decorative'. Čtení/zápis **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Nastavuje název tvaru. Zápis [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Nastavuje surové vlastnosti rámečku tvaru. Zápis [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | Nastavuje chování navigace v prezentaci. Zápis **bool**. Výchozí hodnota: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Nastavuje počet stupňů, o které je daný tvar otočen kolem osy z. Kladná hodnota označuje otočení po směru hodinových ručiček; záporná hodnota označuje otočení proti směru hodinových ručiček. Zápis **float**. |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | Nastavuje hodnotu, která určuje, zda Zoom použije pozadí cílového snímku. Zápis **bool**. Výchozí hodnota: true |
| virtual void [set_TargetSection](../isectionzoomframe/set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) | Nastavuje objekt sekce, ke kterému je objekt [Section](../section/) Zoom propojen. Zápis [ISection](../isection/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Vrací textový název objektu Summary Zoom [Section](../section/). |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | Nastavuje dobu trvání přechodu mezi Zoom a snímkem. Zápis **float**. Výchozí hodnota: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Nastavuje šířku tvaru, měřenou v bodech. Zápis **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Nastavuje souřadnici x levého horního rohu tvaru, měřenou v bodech. Zápis **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Nastavuje souřadnici y levého horního rohu tvaru, měřenou v bodech. Zápis **float**. |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | Nastavuje obrázek pro zoom objekt. Zápis [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převádět vlastní objekty na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Uloží obsah [Shape](../shape/) jako SVG soubor. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Uloží obsah [Shape](../shape/) jako SVG soubor. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [ISectionZoomFrame](../isectionzoomframe/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)