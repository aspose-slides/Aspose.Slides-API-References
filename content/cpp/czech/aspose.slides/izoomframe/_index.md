---
title: IZoomFrame
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Zastupuje objekt Zoom na snímku.
type: docs
weight: 4252
url: /cs/aspose.slides/izoomframe/
---
## IZoomFrame třída

Zastupuje objekt Zoom [Slide](../slide/) na snímku.

```cpp
class IZoomFrame : public virtual Aspose::Slides::IZoomObject
```

## Metody

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví vlastnosti zástupného prvku na zadaný. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Vrací alternativní text přiřazený k tvaru. Přečtěte si [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Vrací název alternativního textu přiřazeného k tvaru. Přečtěte si [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení. Přečtěte si [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Vrací počet míst pro připojení na tvaru. Pouze pro čtení **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Vrací vlastní data tvaru. Pouze pro čtení [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Vrací objekt [EffectFormat](../effectformat/), který obsahuje pixelové efekty aplikované na tvar. Pouze pro čtení [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Vrací objekt [FillFormat](../fillformat/), který obsahuje vlastnosti výplně formátování pro tvar. Pouze pro čtení [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Vrací vlastnosti rámce tvaru. Přečtěte si [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Vrací zamčení tvaru. Pouze pro čtení [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Získá výšku tvaru, měřenou v bodech. Čtení **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Určuje, zda je tvar skrytý. Čtení **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Vrací hypertextový odkaz definovaný pro kliknutí myší. Přečtěte si [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Správce hypertextových odkazů Pouze pro čtení [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Vrací hypertextový odkaz definovaný pro přejetí myší. Přečtěte si [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | Získá typ obrázku zoom objektu. Čtení [ZoomImageType](../zoomimagetype/). Výchozí hodnota: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Získá volbu 'Označit jako dekorativní'. Čtení/zápis **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Určuje, zda je tvar seskupen. Pouze pro čtení **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Určuje, zda je tvar TextHolder. Pouze pro čtení **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Vrací objekt [LineFormat](../lineformat/), který obsahuje vlastnosti formátování čáry pro tvar. Pouze pro čtení [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Vrací název tvaru. Přečtěte si [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou dobu existence tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení **uint32_t**. Viz také [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Vrací nadřazený objekt [GroupShape](../groupshape/), pokud je tvar seskupen. Jinak vrací null. Pouze pro čtení [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Vrací zástupný prvek pro tvar. Pouze pro čtení [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Vrací prezentaci. Pouze pro čtení [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Vrací surové vlastnosti rámce tvaru. Přečtěte si [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | Získá chování navigace v prezentaci. Čtení **bool**. Výchozí hodnota: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Vrací počet stupňů, o které je daný tvar otočen kolem osy z. Kladná hodnota označuje otočení po směru hodinových ručiček; záporná hodnota označuje otočení proti směru hodinových ručiček. Čtení **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Vrací zamčení tvaru. Pouze pro čtení [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | Získá hodnotu určující, zda Zoom použije pozadí cílového snímku. Čtení **bool**. Výchozí hodnota: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Vrací základní snímek. Pouze pro čtení [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() | Získá objekt snímku, na který odkazuje Zoom objekt [Slide](../slide/). Přečtěte si [ISlide](../islide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Vrací objekt [ThreeDFormat](../threedformat/), který obsahuje vlastnosti formátování čáry pro tvar. Pouze pro čtení [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | Získá dobu trvání přechodu mezi Zoom a snímkem. Čtení **float**. Výchozí hodnota: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem. Protože tato hodnota může být uživatelem nebo programově změněna, neměla by být považována za trvalý jedinečný klíč. Pouze pro čtení **uint32_t**. Viz také [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Získá šířku tvaru, měřenou v bodech. Čtení **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Získá souřadnici x levého horního rohu tvaru, měřenou v bodech. Čtení **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Získá souřadnici y levého horního rohu tvaru, měřenou v bodech. Čtení **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | Získá obrázek pro zoom objekt. Čtení [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Vrací pozici tvaru v z-řadě. Shapes[0] vrací tvar v zadní části z-řady a Shapes[Shapes.Count - 1] vrací tvar v přední části z-řady. Pouze pro čtení **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Vrací základní zástupný tvar (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar odvozen). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Vrací miniaturu tvaru. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) výchozí typ ohraničení miniatury tvaru je použit. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Vrací miniaturu tvaru. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Volat přímo nebo použít hlídací objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje počet sdílených referencí o zadanou hodnotu. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Definuje, že tento tvar není zástupný prvek. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Nastaví alternativní text přiřazený k tvaru. Zapište [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Nastaví název alternativního textu přiřazeného k tvaru. Zapište [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení. Zapište [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Nastaví vlastnosti rámce tvaru. Zapište [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Nastaví výšku tvaru, měřenou v bodech. Zapište **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Určuje, zda je tvar skrytý. Zapište **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Nastaví hypertextový odkaz definovaný pro kliknutí myší. Zapište [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Nastaví hypertextový odkaz definovaný pro přejetí myší. Zapište [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | Nastaví typ obrázku zoom objektu. Zapište [ZoomImageType](../zoomimagetype/). Výchozí hodnota: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Nastaví volbu 'Označit jako dekorativní'. Čtení/zápis **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Nastaví název tvaru. Zapište [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Nastaví surové vlastnosti rámce tvaru. Zapište [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | Nastaví chování navigace v prezentaci. Zapište **bool**. Výchozí hodnota: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Nastaví počet stupňů, o které je daný tvar otočen kolem osy z. Kladná hodnota označuje otáčení po směru hodinových ručiček; záporná hodnota označuje otáčení proti směru hodinových ručiček. Zapište **float**. |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | Nastaví hodnotu určující, zda Zoom použije pozadí cílového snímku. Zapište **bool**. Výchozí hodnota: true |
| virtual void [set_TargetSlide](./set_targetslide/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | Nastaví objekt snímku, na který odkazuje Zoom objekt [Slide](../slide/). Zapište [ISlide](../islide/). |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | Nastaví dobu trvání přechodu mezi Zoom a snímkem. Zapište **float**. Výchozí hodnota: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Nastaví šířku tvaru, měřenou v bodech. Zapište **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Nastaví souřadnici x levého horního rohu tvaru, měřenou v bodech. Zapište **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Nastaví souřadnici y levého horního rohu tvaru, měřenou v bodech. Zapište **float**. |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | Nastaví obrázek pro zoom objekt. Zapište [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje konverzi vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Volat přímo nebo použít hlídací objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Uloží obsah [Shape](../shape/) jako soubor SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Uloží obsah [Shape](../shape/) jako soubor SVG. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [IZoomObject](../izoomobject/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)