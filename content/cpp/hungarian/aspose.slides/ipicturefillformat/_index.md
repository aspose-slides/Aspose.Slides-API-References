---
title: IPictureFillFormat
second_title: Aspose.Slides C++ API-referencia
description: Képkitöltési stílust ábrázol.
type: docs
weight: 3225
url: /hu/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat osztály

Képkitöltési stílust ábrázol.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | A képet az alakzat mérete és a megadott felbontás alapján csökkentve tömöríti. Opcionálisan a levágott területeket is törli. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | A képet az alakzat mérete és a megadott felbontás alapján csökkentve tömöríti. Opcionálisan a levágott területeket is törli. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | A(z) [Picture](../picture/) kitöltés levágott területeit törli. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | Visszaadja a valós képmagasság százalékának azt a részét, amely alulról levágott a képen. Olvasás **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | Visszaadja a valós kép szélességének százalékának azt a részét, amely balról levágott a képen. Olvasás **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | Visszaadja a valós kép szélességének százalékának azt a részét, amely jobbról levágott a képen. Olvasás **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | Visszaadja a valós képmagasság százalékának azt a részét, amely felülről levágott a képen. Olvasás **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | Visszaadja a képet kitöltéshez használt DPI értékét. Olvasás **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Visszaadja a képet. Csak olvasható [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | Visszaadja a kép kitöltési módot. Olvasás [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | Visszaadja a kitöltési téglalap alsó szélét, amely a alakzat határoló keretének alsó szélétől százalékos eltolással van meghatározva. A pozitív százalék belső eltolást, a negatív százalék kiterjesztést jelez. Olvasás **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | Visszaadja a kitöltési téglalap bal szélét, amely az alakzat határoló keretének bal szélétől százalékos eltolással van meghatározva. A pozitív százalék belső eltolást, a negatív százalék kiterjesztést jelez. Olvasás **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | Visszaadja a kitöltési téglalap jobb szélét, amely az alakzat határoló keretének jobb szélétől százalékos eltolással van meghatározva. A pozitív százalék belső eltolást, a negatív százalék kiterjesztést jelez. Olvasás **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | Visszaadja a kitöltési téglalap felső szélét, amely az alakzat határoló keretének felső szélétől százalékos eltolással van meghatározva. A pozitív százalék belső eltolást, a negatív százalék kiterjesztést jelez. Olvasás **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | Visszaadja, hogyan igazodik a textúra az alakzaton belül. Ez a beállítás a textúraminta kezdőpontját és annak ismétlődését szabályozza. Olvasás [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | Tükrözi a textúra csempét a vízszintes, függőleges vagy mindkét tengely körül. Olvasás [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | Visszaadja a textúra vízszintes eltolását a forma eredetétől pontban. A pozitív érték jobbra, a negatív balra mozgatja a textúrát. Olvasás **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | Visszaadja a textúra függőleges eltolását a forma eredetétől pontban. A pozitív érték lejjebb, a negatív felfelé mozgatja a textúrát. Olvasás **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | Visszaadja a textúra kitöltés vízszintes méretezését százalékban. Olvasás **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | Visszaadja a textúra kitöltés függőleges méretezését százalékban. Olvasás **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekérdezi az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyéni objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekérdezi az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Érték típusú objektumot referenciával hasonlít a nullptr-hez. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott érték szerint. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | Beállítja a valós képmagasság százalékának azt a részét, amely alulról levágott a képen. Írás **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | Beállítja a valós kép szélességének százalékának azt a részét, amely balról levágott a képen. Írás **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | Beállítja a valós kép szélességének százalékának azt a részét, amely jobbról levágott a képen. Írás **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | Beállítja a valós képmagasság százalékának azt a részét, amely felülről levágott a képen. Írás **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | Beállítja a képet kitöltéshez használt DPI értéket. Írás **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | Beállítja a kép kitöltési módot. Írás [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | Beállítja a kitöltési téglalap alsó szélét, amely a alakzat határoló keretének alsó szélétől százalékos eltolással van meghatározva. A pozitív százalék belső eltolást, a negatív százalék kiterjesztést jelez. Írás **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | Beállítja a kitöltési téglalap bal szélét, amely az alakzat határoló keretének bal szélétől százalékos eltolással van meghatározva. A pozitív százalék belső eltolást, a negatív százalék kiterjesztést jelez. Írás **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | Beállítja a kitöltési téglalap jobb szélét, amely az alakzat határoló keretének jobb szélétől százalékos eltolással van meghatározva. A pozitív százalék belső eltolást, a negatív százalék kiterjesztést jelez. Írás **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | Beállítja a kitöltési téglalap felső szélét, amely az alakzat határoló keretének felső szélétől százalékos eltolással van meghatározva. A pozitív százalék belső eltolást, a negatív százalék kiterjesztést jelez. Írás **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | Beállítja, hogyan igazodik a textúra az alakzaton belül. Ez a beállítás a textúraminta kezdőpontját és annak ismétlődését szabályozza. Írás [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | Tükrözi a textúra csempét a vízszintes, függőleges vagy mindkét tengely körül. Írás [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | Beállítja a textúra vízszintes eltolását a forma eredetétől pontban. A pozitív érték jobbra, a negatív balra mozgatja a textúrát. Írás **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | Beállítja a textúra függőleges eltolását a forma eredetétől pontban. A pozitív érték lejjebb, a negatív felfelé mozgatja a textúrát. Írás **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | Beállítja a textúra kitöltés vízszintes méretezését százalékban. Írás **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | Beállítja a textúra kitöltés függőleges méretezését százalékban. Írás **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonparamétert gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerben való weak módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekérdezi a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyéni objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IFillParamSource](../ifillparamsource/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)