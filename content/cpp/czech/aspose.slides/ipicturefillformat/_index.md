---
title: IPictureFillFormat
second_title: Aspose.Slides pro C++ referenci API
description: Reprezentuje styl výplně obrázkem.
type: docs
weight: 3225
url: /cs/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat třída


Reprezentuje styl výplně obrázkem.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | Odstraňuje oříznuté oblasti výplně [Picture](../picture/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnávání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnávání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | Vrací počet procent výšky skutečného obrázku, která je oříznuta dole od obrázku. Číst **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | Vrací počet procent šířky skutečného obrázku, která je oříznuta vlevo od obrázku. Číst **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | Vrací počet procent šířky skutečného obrázku, která je oříznuta vpravo od obrázku. Číst **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | Vrací počet procent výšky skutečného obrázku, která je oříznuta nahoře od obrázku. Číst **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | Vrací DPI, které se používá k výplni obrázku. Číst **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Vrací obrázek. Pouze pro čtení [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | Vrací režim výplně obrázku. Číst [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | Vrací spodní okraj výplňového obdélníku, který je definován procentuálním posunem od spodního okraje ohraničujícího rámečku tvaru. Kladné procento určuje útlum, záporné výstupek. Číst **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | Vrací levý okraj výplňového obdélníku, který je definován procentuálním posunem od levého okraje ohraničujícího rámečku tvaru. Kladné procento určuje útlum, záporné výstupek. Číst **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | Vrací pravý okraj výplňového obdélníku, který je definován procentuálním posunem od pravého okraje ohraničujícího rámečku tvaru. Kladné procento určuje útlum, záporné výstupek. Číst **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | Vrací horní okraj výplňového obdélníku, který je definován procentuálním posunem od horního okraje ohraničujícího rámečku tvaru. Kladné procento určuje útlum, záporné výstupek. Číst **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | Vrací, jak je textura zarovnána uvnitř tvaru. Toto nastavení řídí výchozí bod vzoru textury a jak se opakuje přes tvar. Číst [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | Otáčí dlaždici textury kolem její vodorovné, svislé nebo obou osí. Číst [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | Vrací vodorovný posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu doprava, záporná doleva. Číst **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | Vrací svislý posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu dolů, záporná nahoru. Číst **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | Vrací vodorovné měřítko výplně texturou jako procento. Číst **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | Vrací svislé měřítko výplně texturou jako procento. Číst **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie k metodě C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie k volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného cílovým typem. Analogie k operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte strážný objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie k metodě C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | Nastavuje počet procent výšky skutečného obrázku, která je oříznuta dole od obrázku. Zapsat **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | Nastavuje počet procent šířky skutečného obrázku, která je oříznuta vlevo od obrázku. Zapsat **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | Nastavuje počet procent šířky skutečného obrázku, která je oříznuta vpravo od obrázku. Zapsat **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | Nastavuje počet procent výšky skutečného obrázku, která je oříznuta nahoře od obrázku. Zapsat **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | Nastavuje DPI, které se používá k výplni obrázku. Zapsat **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | Nastavuje režim výplně obrázku. Zapsat [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | Nastavuje spodní okraj výplňového obdélníku, který je definován procentuálním posunem od spodního okraje ohraničujícího rámečku tvaru. Kladné procento určuje útlum, záporné výstupek. Zapsat **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | Nastavuje levý okraj výplňového obdélníku, který je definován procentuálním posunem od levého okraje ohraničujícího rámečku tvaru. Kladné procento určuje útlum, záporné výstupek. Zapsat **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | Nastavuje pravý okraj výplňového obdélníku, který je definován procentuálním posunem od pravého okraje ohraničujícího rámečku tvaru. Kladné procento určuje útlum, záporné výstupek. Zapsat **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | Nastavuje horní okraj výplňového obdélníku, který je definován procentuálním posunem od horního okraje ohraničujícího rámečku tvaru. Kladné procento určuje útlum, záporné výstupek. Zapsat **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | Nastavuje, jak je textura zarovnána uvnitř tvaru. Toto nastavení řídí výchozí bod vzoru textury a jak se opakuje přes tvar. Zapsat [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | Otáčí dlaždici textury kolem její vodorovné, svislé nebo obou osí. Zapsat [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | Nastavuje vodorovný posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu doprava, záporná doleva. Zapsat **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | Nastavuje svislý posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu dolů, záporná nahoru. Zapsat **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | Nastavuje vodorovné měřítko výplně texturou jako procento. Zapsat **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | Nastavuje svislé měřítko výplně texturou jako procento. Zapsat **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastavuje n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie k metodě C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte strážný objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počítadlo slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počítadlo slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niči objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [IFillParamSource](../ifillparamsource/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)