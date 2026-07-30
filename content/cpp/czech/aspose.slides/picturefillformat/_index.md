---
title: PictureFillFormat
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Reprezentuje styl výplně obrázkem.
type: docs
weight: 4720
url: /cs/aspose.slides/picturefillformat/
---
## PictureFillFormat třída


Represents a picture fill style.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | Odstraňuje oříznuté oblasti výplně [Picture](../picture/). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Porovná se se zadaným objektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| **float** [get_CropBottom](./get_cropbottom/)() override | Vrací počet procent skutečné výšky obrázku, která je oříznuta ze spodní části obrázku. Čtení **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | Vrací počet procent skutečné šířky obrázku, která je oříznuta z levé strany obrázku. Čtení **float**. |
| **float** [get_CropRight](./get_cropright/)() override | Vrací počet procent skutečné šířky obrázku, která je oříznuta z pravé strany obrázku. Čtení **float**. |
| **float** [get_CropTop](./get_croptop/)() override | Vrací počet procent skutečné výšky obrázku, která je oříznuta z horní části obrázku. Čtení **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | Vrací dpi, které se používá k vyplnění obrázku. Čtení **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Vrací objekt Parent_Immediate. Pouze pro čtení [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Vrací nadřazený [IPresentationComponent](../ipresentationcomponent/). Pouze pro čtení [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Vrací obrázek. Pouze pro čtení [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | Vrací režim výplně obrázku. Čtení [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | Vrací spodní okraj výplňového obdélníku, který je definován procentuálním posunem od spodního okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější vysunutí. Čtení **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | Vrací levý okraj výplňového obdélníku, který je definován procentuálním posunem od levého okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější vysunutí. Čtení **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | Vrací pravý okraj výplňového obdélníku, který je definován procentuálním posunem od pravého okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější vysunutí. Čtení **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | Vrací horní okraj výplňového obdélníku, který je definován procentuálním posunem od horního okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější vysunutí. Čtení **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | Vrací způsob zarovnání textury uvnitř tvaru. Toto nastavení řídí výchozí bod vzoru textury a způsob, jakým se opakuje po celém tvaru. Čtení [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | Otáčí dlaždici textury kolem její vodorovné, svislé nebo obou os. Čtení [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | Vrací horizontální posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu doprava, záporná hodnota ji posouvá doleva. Čtení **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | Vrací vertikální posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu dolů, záporná ji posouvá nahoru. Čtení **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | Vrací horizontální měřítko výplně textury v procentech. Čtení **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | Vrací vertikální měřítko výplně textury v procentech. Čtení **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Vrací hash kód. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ověřuje, zda objekt představuje instanci typu popsaného parametrem targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování uživatelských typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený počítadlo referencí o zadanou hodnotu. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | Upravuje počet procent skutečné výšky obrázku, která je oříznuta ze spodní části obrázku. Zápis **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | Upravuje počet procent skutečné šířky obrázku, která je oříznuta z levé strany obrázku. Zápis **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | Upravuje počet procent skutečné šířky obrázku, která je oříznuta z pravé strany obrázku. Zápis **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | Upravuje počet procent skutečné výšky obrázku, která je oříznuta z horní části obrázku. Zápis **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | Nastavuje dpi, které se používá k vyplnění obrázku. Zápis **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | Nastavuje režim výplně obrázku. Zápis [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | Nastavuje spodní okraj výplňového obdélníku, který je definován procentuálním posunem od spodního okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější vysunutí. Zápis **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | Nastavuje levý okraj výplňového obdélníku, který je definován procentuálním posunem od levého okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější vysunutí. Zápis **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | Nastavuje pravý okraj výplňového obdélníku, který je definován procentuálním posunem od pravého okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější vysunutí. Zápis **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | Nastavuje horní okraj výplňového obdélníku, který je definován procentuálním posunem od horního okraje ohraničujícího rámečku tvaru. Kladné procento udává vnitřní odsazení, záporné procento vnější vysunutí. Zápis **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | Nastavuje, jak je textura zarovnána uvnitř tvaru. Toto nastavení řídí výchozí bod vzoru textury a způsob, jakým se opakuje po celém tvaru. Zápis [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | Otočí dlaždici textury kolem její vodorovné, svislé nebo obou os. Zápis [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | Nastavuje horizontální posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu doprava, záporná ji posouvá doleva. Zápis **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | Nastavuje vertikální posun textury od počátku tvaru v bodech. Kladná hodnota posouvá texturu dolů, záporná ji posouvá nahoru. Zápis **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | Nastavuje horizontální měřítko výplně textury v procentech. Zápis **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | Nastavuje vertikální měřítko výplně textury v procentech. Zápis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [PVIObject](../pviobject/)
* Třída [IPictureFillFormat](../ipicturefillformat/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)