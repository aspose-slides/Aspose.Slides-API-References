---
title: IPictureFrame
second_title: Aspose.Slides pro C++ reference API
description: Představuje rámeček s obrázkem uvnitř.
type: docs
weight: 3251
url: /cs/aspose.slides/ipictureframe/
---
## IPictureFrame class

Represents a frame with a picture inside.

```cpp
class IPictureFrame : public virtual Aspose::Slides::IGeometryShape
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Přidá nový zástupný objekt, pokud neexistuje, a nastaví jeho vlastnosti na zadaný. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Vytvoří a vrátí pole prvků tvaru. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Vrací hodnotu úprav tvaru na zadaném indexu. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Vrací kolekci hodnot úprav tvaru. Pouze pro čtení [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Vrací alternativní text spojený s tvarem. Pouze čtení [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Vrací název alternativního textu spojeného s tvarem. Pouze čtení [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení. Pouze čtení [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Vrací počet připojovacích míst tvaru. Pouze pro čtení **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Vrací vlastní data tvaru. Pouze pro čtení [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Vrací objekt [EffectFormat](../effectformat/), který obsahuje pixelové efekty aplikované na tvar. Pouze pro čtení [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Vrací objekt [FillFormat](../fillformat/), který obsahuje vlastnosti výplně tvaru. Pouze pro čtení [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Vrací vlastnosti rámu tvaru. Pouze čtení [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Získá výšku tvaru v bodech. Pouze čtení **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Určuje, zda je tvar skrytý. Pouze čtení **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Vrací hypertextový odkaz definovaný pro kliknutí myší. Pouze čtení [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Správce hypertextových odkazů. Pouze pro čtení [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Vrací hypertextový odkaz definovaný pro přejetí myší. Pouze čtení [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Získá možnost „Označit jako dekorativní“. Čtení/zápis **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Určuje, zda je tvar seskupen. Pouze pro čtení **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Určuje, zda je tvar TextHolder. Pouze pro čtení **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Vrací objekt [LineFormat](../lineformat/), který obsahuje vlastnosti formátování čáry pro tvar. Pouze pro čtení [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Vrací název tvaru. Pouze čtení [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení **uint32_t**. Viz také [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Vrací nadřazený objekt [GroupShape](../groupshape/), pokud je tvar seskupen. Jinak vrací null. Pouze pro čtení [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](./get_pictureformat/)() | Vrací objekt [PictureFillFormat](../picturefillformat/) pro rámeček obrázku. Pouze pro čtení [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](./get_pictureframelock/)() | Vrací zámky [PictureFrame](../pictureframe/). Pouze pro čtení [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Vrací zástupný objekt pro tvar. Pouze pro čtení [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Vrací prezentaci. Pouze pro čtení [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Vrací surové vlastnosti rámu tvaru. Pouze čtení [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](./get_relativescaleheight/)() | Vrací měřítko výšky (relativně k původní velikosti obrázku) rámečku obrázku. Hodnota 1,0 odpovídá 100 %. Pouze čtení **float**. |
| virtual **float** [get_RelativeScaleWidth](./get_relativescalewidth/)() | Vrací měřítko šířky (relativně k původní velikosti obrázku) rámečku obrázku. Hodnota 1,0 odpovídá 100 %. Pouze čtení **float**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Vrací počet stupňů, o které je tvar otočen kolem osy z. Kladná hodnota značí otáčení po směru hodinových ručiček; záporná hodnota značí otáčení proti směru hodinových ručiček. Pouze čtení **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Vrací zámky tvaru. Pouze pro čtení [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Vrací objekt stylu tvaru. Pouze pro čtení [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Vrací přednastavený typ geometrie. Poznámka: při změně hodnoty se všechny hodnoty úprav resetují na výchozí. Pouze čtení [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Vrací základní snímek. Pouze pro čtení [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Vrací objekt [ThreeDFormat](../threedformat/), který obsahuje vlastnosti formátování čáry pro tvar. Pouze pro čtení [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem. Protože může být uživatelem nebo programově přidělen jinak, neměl by být považován za trvalý jedinečný klíč. Pouze pro čtení **uint32_t**. Viz také [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Získá šířku tvaru v bodech. Pouze čtení **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Získá x-souřadnici levého horního rohu tvaru v bodech. Pouze čtení **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Získá y-souřadnici levého horního rohu tvaru v bodech. Pouze čtení **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Vrací pozici tvaru v z-řadě. Shapes[0] vrací tvar na pozadí z-řady a Shapes[Shapes.Count - 1] vrací tvar v popředí z-řady. Pouze pro čtení **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Vrací základní zástupný tvar (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar odvozen). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Vrací miniaturu tvaru. Výchozí je typ ohraničení miniatury [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Vrací miniaturu tvaru. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovná referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Definuje, že tento tvar není zástupný. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Nastaví alternativní text spojený s tvarem. Zápis [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Nastaví název alternativního textu spojeného s tvarem. Zápis [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení. Zápis [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Nastaví vlastnosti rámu tvaru. Zápis [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Nastaví výšku tvaru v bodech. Zápis **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Určuje, zda je tvar skrytý. Zápis **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Nastaví hypertextový odkaz definovaný pro kliknutí myší. Zápis [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Nastaví hypertextový odkaz definovaný pro přejetí myší. Zápis [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Nastaví možnost „Označit jako dekorativní“. Čtení/zápis **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Nastaví název tvaru. Zápis [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Nastaví surové vlastnosti rámu tvaru. Zápis [IShapeFrame](../ishapeframe/). |
| virtual void [set_RelativeScaleHeight](./set_relativescaleheight/)(**float**) | Nastaví měřítko výšky (relativně k původní velikosti obrázku) rámečku obrázku. Hodnota 1,0 odpovídá 100 %. Zápis **float**. |
| virtual void [set_RelativeScaleWidth](./set_relativescalewidth/)(**float**) | Nastaví měřítko šířky (relativně k původní velikosti obrázku) rámečku obrázku. Hodnota 1,0 odpovídá 100 %. Zápis **float**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Nastaví počet stupňů, o které je tvar otočen kolem osy z. Kladná hodnota značí otáčení po směru hodinových ručiček; záporná hodnota značí otáčení proti směru hodinových ručiček. Zápis **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Nastaví přednastavený typ geometrie. Poznámka: při změně hodnoty se všechny hodnoty úprav resetují na výchozí. Zápis [Slides::ShapeType](../shapetype/). |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Nastaví šířku tvaru v bodech. Zápis **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Nastaví x-souřadnici levého horního rohu tvaru v bodech. Zápis **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Nastaví y-souřadnici levého horního rohu tvaru v bodech. Zápis **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Aktualizuje geometrii tvaru z objektu [IGeometryPath](../igeometrypath/). Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru ([ShapeType](../shapetype/)) na [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Aktualizuje geometrii tvaru z pole [IGeometryPath](../igeometrypath/). Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru ([ShapeType](../shapetype/)) na [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počitadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Ukládá obsah [Shape](../shape/) jako soubor SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Ukládá obsah [Shape](../shape/) jako soubor SVG. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [IGeometryShape](../igeometryshape/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)