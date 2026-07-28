---
title: Metafile
second_title: Aspose.Slides C++ API referencia
description: "Képviseli a grafikus metafájlt. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stackben vagy a new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az objektum argumentumként történő átadásához a függvényeknek."
type: docs
weight: 144
url: /hu/system.drawing.imaging/metafile/
---
## Metafile osztály

Képviseli a grafikus metafájlt. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy a new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az objektum paraméterként való átadásához a függvényeknek.

```cpp
class Metafile : public System::Drawing::Image
```

## Módszerek

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [Clone](./clone/)() override | Visszaadja a jelenlegi objektum másolatát. |
| void [Dispose](../../system.drawing/image/dispose/)() override | Felszabadítja a jelenlegi objektum által szerzett összes erőforrást. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [FromFile](../../system.drawing/image/fromfile/)(const [String](../../system/string/)\&, **bool**) | Létrehoz egy [Image](../../system.drawing/image/) objektumot a megadott fájlból. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](../../system.drawing/bitmap/)\> [FromHbitmap](../../system.drawing/image/fromhbitmap/)(IntPtr) | Létrehozza a [Bitmap](../../system.drawing/bitmap/) objektumot a megadott GDI bitmapből. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [FromStream](../../system.drawing/image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Létrehoz egy [Image](../../system.drawing/image/) objektumot a megadott adatfolyamból. |
| virtual **int32_t** [get_Flags](../../system.drawing/image/get_flags/)() const | Visszaad egy bitenkénti kombinációt az ImageFlags felsoroló értékekből, amely a kép attribútumait jelöli. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../../system.drawing/image/get_framedimensionslist/)() const | Visszaad egy GUID tömböt, amely a jelenlegi objektum által képviselt kép kereteinek méreteit jelöli. |
| int [get_Height](./get_height/)() const override | Visszaadja a kép magasságát pixelben. |
| **float** [get_HorizontalResolution](../../system.drawing/image/get_horizontalresolution/)() const | Visszaadja a kép vízszintes felbontását hüvelykenkénti pixelben. |
| virtual [Imaging::ColorPalettePtr](../colorpaletteptr/) [get_Palette](../../system.drawing/image/get_palette/)() const | Visszaadja a jelenlegi objektum által képviselt kép színpalettáját. |
| [Imaging::PixelFormat](../pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | Visszaad egy értéket, amely a pixelformátumot jelzi. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../../system.drawing/image/get_propertyidlist/)() const | Lekéri ennek a képnek a tárolt tulajdonságelemek azonosítóit. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../propertyitem/)\>\> [get_PropertyItems](../../system.drawing/image/get_propertyitems/)() const | Lekéri a képben tárolt összes tulajdonságelemet (metaadat darabokat). |
| [Imaging::ImageFormatPtr](../imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | Visszaad egy értéket, amely a képformátumot jelzi. |
| [Size](../../system.drawing/size/) [get_Size](../../system.drawing/image/get_size/)() const | Visszaad egy [Size](../../system.drawing/size/) objektumot, amely a kép szélességét és magasságát pixelben ábrázolja. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../../system.drawing/image/get_tag/)() const | Lekéri egy objektumot, amely további adatokat biztosít a képről. |
| **float** [get_VerticalResolution](../../system.drawing/image/get_verticalresolution/)() const | Visszaadja a kép függőleges felbontását hüvelykenkénti pixelben. |
| int [get_Width](./get_width/)() const override | Visszaadja a kép szélességét pixelben. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](../../system.drawing/image/getbounds/)([GraphicsUnit](../../system.drawing/graphicsunit/)\&) | Visszaadja a kép határait a megadott mértékegységekben. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| int [GetFrameCount](../../system.drawing/image/getframecount/)(const [Imaging::FrameDimensionPtr](../framedimensionptr/)\&) | Visszaadja a megadott képkocka dimenzió kereteinek számát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hash-elését. |
| IntPtr [GetHenhmetafile](./gethenhmetafile/)() | NINCS MEGVALÓSÍTVA. |
| [SharedPtr](../../system/sharedptr/)\<[MetafileHeader](../metafileheader/)\> [GetMetafileHeader](./getmetafileheader/)() | Visszaad egy fejlécet, amely a jelenlegi objektummal kapcsolatos. |
| static int [GetPixelFormatSize](../../system.drawing/image/getpixelformatsize/)([Imaging::PixelFormat](../pixelformat/)) | Visszaadja a megadott pixelformátumban a színmélység ábrázolásához használt bitek számát. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [GetThumbnailImage](../../system.drawing/image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../../system.drawing/image/getthumbnailimageabort/), IntPtr) | Lekér egy bélyegképet ehhez a [System::Drawing::Image](../../system.drawing/image/) objektumhoz. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példányát képviseli-e. A C# 'is' operátor analógiája. |
| static **bool** [IsAlphaPixelFormat](../../system.drawing/image/isalphapixelformat/)([Imaging::PixelFormat](../pixelformat/)) | Megállapítja, hogy a megadott pixelformátum tartalmaz-e alfa információt. |
| virtual **bool** [IsMultiImage](../../system.drawing/image/ismultiimage/)() const | Visszaadja, hogy az eredeti formátum többképes-e. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi az egyedi típusok klónozását. |
|  [Metafile](./metafile/)(const [System::String](../../system/string/)\&) | NINCS MEGVALÓSÍTVA. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&) | NINCS MEGVALÓSÍTVA. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [EmfType](../emftype/)) | NINCS MEGVALÓSÍTVA. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr) | NINCS MEGVALÓSÍTVA. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [Rectangle](../../system.drawing/rectangle/), [MetafileFrameUnit](../metafileframeunit/), [EmfType](../emftype/)) | NINCS MEGVALÓSÍTVA. |
|  [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [RectangleF](../../system.drawing/rectanglef/), [MetafileFrameUnit](../metafileframeunit/), [EmfType](../emftype/)) | NINCS MEGVALÓSÍTVA. |
|  [Metafile](./metafile/)(IntPtr, [EmfType](../emftype/)) | NINCS MEGVALÓSÍTVA. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelési operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| void [PlayRecord](./playrecord/)([EmfPlusRecordType](../emfplusrecordtype/), **int32_t**, **int32_t**, [System::ByteArrayPtr](../../system/bytearrayptr/)) | NINCS MEGVALÓSÍTVA. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlít össze értéktípusú objektumot a nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [RotateFlip](../../system.drawing/image/rotateflip/)([RotateFlipType](../../system.drawing/rotatefliptype/)) | Elforgatja a képet 90 fokos szorzóra és tükrözi. |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&) | Elmenti a jelenlegi objektum által képviselt képet a megadott fájlba PNG formátumban. |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../imageformatptr/)\&) | Elmenti a jelenlegi objektum által képviselt képet a megadott fájlba a megadott formátumban. |
| void [Save](../../system.drawing/image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../imageformatptr/)\&) | Elmenti a jelenlegi objektum által képviselt képet a megadott adatfolyamba a megadott formátumban. |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | Elmenti a jelenlegi objektum által képviselt képet a megadott fájlba a megadott enkóderrel és enkóder paraméterekkel. |
| void [Save](../../system.drawing/image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | Elmenti a jelenlegi objektum által képviselt képet a megadott adatfolyamba a megadott enkóderrel és enkóder paraméterekkel. |
| void [SaveAdd](../../system.drawing/image/saveadd/)(const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | Keretet ad a fájlhoz vagy adatfolyamhoz, amelyet a korábbi [Save()](../../system.drawing/image/save/) metódushívás határozott meg. |
| void [SaveAdd](../../system.drawing/image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\>\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | Keretet ad a fájlhoz vagy adatfolyamhoz, amelyet a korábbi [Save()](../../system.drawing/image/save/) metódushívás határozott meg. |
| int [SelectActiveFrame](../../system.drawing/image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../framedimensionptr/)\&, int) | Kiválasztja a megadott keretet. |
| virtual void [set_Palette](../../system.drawing/image/set_palette/)([Imaging::ColorPalettePtr](../colorpaletteptr/)) | Beállítja a jelenlegi objektum által képviselt kép színpalettáját. |
| virtual void [set_Tag](../../system.drawing/image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Beállít egy objektumot, amely további adatot szolgáltat a képről. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását gyenge módba a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi az egyedi objektumok karakterláncsá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Metafile](./~metafile/)() | Megsemmisítő. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Image](../../system.drawing/image/)
* Névtér [System::Drawing::Imaging](../)
* Könyvtár [Aspose.Slides](../../)