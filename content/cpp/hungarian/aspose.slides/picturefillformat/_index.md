---
title: PictureFillFormat
second_title: Aspose.Slides C++ API Referenciája
description: Képkitöltési stílust képvisel.
type: docs
weight: 4720
url: /hu/aspose.slides/picturefillformat/
---
## PictureFillFormat osztály

Képkitöltési stílust képvisel.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | Tömöríti a képet a forma mérete és a megadott felbontás alapján. Opcionálisan törli a levágott területeket. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | Tömöríti a képet a forma mérete és a megadott felbontás alapján. Opcionálisan törli a levágott területeket. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | A [Picture](../picture/) kitöltés levágott területeit törli. |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Összehasonlítja a megadott objektummal. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást utánoz, ahol két NaN egyenlőnek tekintendő annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást utánoz, ahol két NaN egyenlőnek tekintendő annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| **float** [get_CropBottom](./get_cropbottom/)() override | Visszaadja a valós képmagasság százalékos arányát, amely a kép aljáról levágásra kerül. Olvas **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | Visszaadja a valós kép szélességének százalékos arányát, amely a kép bal oldaláról levágásra kerül. Olvas **float**. |
| **float** [get_CropRight](./get_cropright/)() override | Visszaadja a valós kép szélességének százalékos arányát, amely a kép jobb oldaláról levágásra kerül. Olvas **float**. |
| **float** [get_CropTop](./get_croptop/)() override | Visszaadja a valós képmagasság százalékos arányát, amely a kép tetejéről levágásra kerül. Olvas **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | Visszaadja a képet kitöltéshez használt DPI értéket. Olvas **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Visszaadja a Parent_Immediate objektumot. Csak olvasható [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Visszaadja a szülő [IPresentationComponent](../ipresentationcomponent/). Csak olvasható [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Visszaadja a képet. Csak olvasható [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | Visszaadja a kép kitöltési módot. Olvas [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | Visszaadja a kitöltő téglalap alsó széleit, amelyet a forma keret alsó szélétől számított százalékos eltolás határoz meg. A pozitív százalék belső margót, a negatív százalék külső margót jelent. Olvas **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | Visszaadja a kitöltő téglalap bal széleit, amelyet a forma keret bal szélétől számított százalékos eltolás határoz meg. A pozitív százalék belső margót, a negatív százalék külső margót jelent. Olvas **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | Visszaadja a kitöltő téglalap jobb széleit, amelyet a forma keret jobb szélétől számított százalékos eltolás határoz meg. A pozitív százalék belső margót, a negatív százalék külső margót jelent. Olvas **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | Visszaadja a kitöltő téglalap felső széleit, amelyet a forma keret felső szélétől számított százalékos eltolás határoz meg. A pozitív százalék belső margót, a negatív százalék külső margót jelent. Olvas **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | Visszaadja, hogyan van a textúra igazítva a formában. Ez a beállítás a textúraminta kezdőpontját és ismétlődését szabályozza a formán belül. Olvas [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | A textúra csempét a vízszintes, függőleges vagy mindkét tengely körül tükrözi. Olvas [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | Visszaadja a textúra vízszintes eltolását a forma eredetétől pontban. A pozitív érték jobbra, a negatív balra mozdítja a textúrát. Olvas **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | Visszaadja a textúra függőleges eltolását a forma eredetétől pontban. A pozitív érték lefele, a negatív felfelé mozgatja a textúrát. Olvas **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | Visszaadja a textúra kitöltés vízszintes méretezését százalékban. Olvas **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | Visszaadja a textúra kitöltés függőleges méretezését százalékban. Olvas **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referencia számláló adatstruktúrát. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Visszaadja a hash kódot. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializál minden belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | Beállítja a valós képmagasság százalékos arányát, amely a kép aljáról levágásra kerül. Ír **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | Beállítja a valós kép szélességének százalékos arányát, amely a kép bal oldaláról levágásra kerül. Ír **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | Beállítja a valós kép szélességének százalékos arányát, amely a kép jobb oldaláról levágásra kerül. Ír **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | Beállítja a valós képmagasság százalékos arányát, amely a kép tetejéről levágásra kerül. Ír **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | Beállítja a képet kitöltéshez használt DPI értéket. Ír **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | Beállítja a kép kitöltési módot. Ír [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | Beállítja a kitöltő téglalap alsó szélét, amelyet a forma keret alsó szélétől számított százalékos eltolás határoz meg. A pozitív százalék belső margót, a negatív külső margót jelent. Ír **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | Beállítja a kitöltő téglalap bal szélét, amelyet a forma keret bal szélétől számított százalékos eltolás határoz meg. A pozitív százalék belső margót, a negatív külső margót jelent. Ír **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | Beállítja a kitöltő téglalap jobb szélét, amelyet a forma keret jobb szélétől számított százalékos eltolás határoz meg. A pozitív százalék belső margót, a negatív külső margót jelent. Ír **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | Beállítja a kitöltő téglalap felső szélét, amelyet a forma keret felső szélétől számított százalékos eltolás határoz meg. A pozitív százalék belső margót, a negatív külső margót jelent. Ír **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | Beállítja, hogyan van a textúra igazítva a formában. Ez a beállítás a textúraminta kezdőpontját és ismétlődését szabályozza a formán belül. Ír [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | A textúra csempét a vízszintes, függőleges vagy mindkét tengely körül tükrözi. Ír [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | Beállítja a textúra vízszintes eltolását a forma eredetétől pontban. A pozitív érték jobbra, a negatív balra mozdítja a textúrát. Ír **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | Beállítja a textúra függőleges eltolását a forma eredetétől pontban. A pozitív érték lefele, a negatív felfelé mozgatja a textúrát. Ír **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | Beállítja a textúra kitöltés vízszintes skáláját százalékban. Ír **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | Beállítja a textúra kitöltés függőleges skáláját százalékban. Ír **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a gyenge üzemmódra a konténerekben. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [PVIObject](../pviobject/)
* Osztály [IPictureFillFormat](../ipicturefillformat/)
* Névterület [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)