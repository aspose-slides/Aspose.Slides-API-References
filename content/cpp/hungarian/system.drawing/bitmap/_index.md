---
title: Bitmap
second_title: "Aspose.Slides C++ API referenciája"
description: "A GDI+ bitmap képet képviseli. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new-val, mert futási hibákat és/vagy állítási hibákat okoz. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és ezt a mutatót használja az argumentumként történő függvényhívásokhoz."
type: docs
weight: 1
url: /hu/system.drawing/bitmap/
---
## Bitmap osztály

Represents a GDI+ bitmap image. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Bitmap : public System::Drawing::Image
```

## Módszerek

| Method | Leírás |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | Engedélyezi a pixel-feldolgozási módot. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | Létrehoz egy új [Bitmap](./) objektumot a megadott létező képből. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | Létrehoz egy új [Bitmap](./) objektumot a megadott adatfolyamból. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | Létrehoz egy új [Bitmap](./) objektumot a megadott fájlból. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | Létrehoz egy új [Bitmap](./) objektumot a megadott fájlból. |
| [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Létrehoz egy új [Bitmap](./) objektumot, amely a megadott szélességű, magasságú, pixelformátumú és pixeladatai által definiált bitmap képet képviseli. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | Létrehoz egy új [Bitmap](./) objektumot a megadott létező képből, a megadott méretre méretezve. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | Létrehoz egy új [Bitmap](./) objektumot a megadott létező képből, a szélesség és magasság a megadott értékekre méretezve. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | Létrehoz egy másolatot a jelenlegi objektumról. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Létrehoz egy [Bitmap](./) objektumot, amely a jelenlegi objektum által képviselt bitmap kép egy régiójának másolatát ábrázolja. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Létrehoz egy [Bitmap](./) objektumot, amely a jelenlegi objektum által képviselt bitmap kép egy régiójának másolatát ábrázolja. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | Kiszámítja a SHA1 hash értékét. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | Létrehoz egy másolatot a megadott bitmap képről, a pixelformátumot Format32bppArgb-ra módosítva. |
| void [Dispose](../image/dispose/)() override | Felszabadítja a jelenlegi objektum által felvett összes erőforrást. |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | Letiltja a pixel-feldolgozási módot. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szintaxis szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | Létrehoz egy [Image](../image/) objektumot a megadott fájlból. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | Létrehoz egy [Bitmap](./) objektumot a megadott GDI bitmapből. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Létrehoz egy [Image](../image/) objektumot a megadott adatfolyamból. |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | Visszaad egy bitenkénti kombinációt az ImageFlags enum értékeiből, amely a kép attribútumait jelöli. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | Visszaad egy GUID-tömböt, amely a jelenlegi objektum által képviselt képen belüli keretek dimenzióit jelöli. |
| int [get_Height](./get_height/)() const override | Visszaadja a kép magasságát pixelben. |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | Visszaadja a kép vízszintes felbontását képpont per hüvelykben. |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | Visszaadja a kép által használt színpalettát. |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | Visszaadja a kép pixelformátumát. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | Lekéri a képben tárolt tulajdonságelemek azonosítóit. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | Lekéri a képben tárolt összes tulajdonságelemet (metaadat darabokat). |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | Visszaadja a kép fájlformátumát. |
| [Size](../size/) [get_Size](../image/get_size/)() const | Visszaad egy [Size](../size/) objektumot, amely a kép szélességét és magasságát pixelben ábrázolja. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | Lekéri egy olyan objektumot, amely további adatokat biztosít a képről. |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | Visszaadja a kép függőleges felbontását képpont per hüvelykben. |
| int [get_Width](./get_width/)() const override | Visszaadja a kép szélességét pixelben. |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | Visszaadja a kép határait a megadott mértékegységekben. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | Visszaadja a megadott képkocka-dimenzió keretek számát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) módszer analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| IntPtr [GetHbitmap](./gethbitmap/)() | Létrehoz egy GDI bitmap objektumot a jelenlegi objektum által képviselt bitmapből. |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | Visszaadja a megadott pixel színét. |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Visszaadja a megadott pixelformátumban a színmélység ábrázolásához használt bitek számát. |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | Visszaad egy nyers mutatót az alapul szolgáló SkBitmap objektumra. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | Lekér egy bélyegképet ehhez a [System::Drawing::Image](../image/) objektumhoz. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Megállapítja, hogy a megadott pixelformátum tartalmaz-e alfa információt. |
| **bool** [IsMultiImage](./ismultiimage/)() const override | Visszaadja, hogy az eredeti formátum több képet tartalmaz-e. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Zárol egy [Bitmap](./)-t a rendszer memóriájában. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Zárol egy [Bitmap](./)-t a rendszer memóriájában. |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | Megváltoztatja a megadott színű összes pixel színét átlátszóvá. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) módszer analógiája. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktort. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| void [PremultipleColors](./premultiplecolors/)() | Elvégzi a pixel színek előszorzását a jelenlegi objektum által képviselt képen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tél. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | Elforgatja a képet 90 fokos szögek többszörösére és tükrözi. |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | Elmenti a jelenlegi objektum által képviselt képet a megadott fájlba PNG formátumban. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Elmenti a képet a megadott fájlba a megadott formátumban. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Elmenti a képet a megadott adatfolyamba a megadott formátumban. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Elmenti a képet a megadott fájlba a megadott enkóder és enkóder paraméterek használatával. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Elmenti a képet a megadott adatfolyamba a megadott enkóder és enkóder paraméterek használatával. |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Kerete hozzáad a fájlhoz vagy adatfolyamhoz, amelyet korábban a [Save()](../image/save/) metódus hívott. |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Kerete hozzáad a fájlhoz vagy adatfolyamhoz, amelyet korábban a [Save()](../image/save/) metódus hívott. |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | Kiválasztja a megadott keretet. |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | Beállítja a jelenlegi objektum által képviselt kép színpalettáját. |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Beállít egy objektumot, amely további adatokat biztosít a képről. |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | Beállítja a megadott pixel színét a bitmap képen. |
| void [SetResolution](./setresolution/)(**float**, **float**) | Beállítja a kép felbontását. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (nem megosztott). Lehetővé teszi a mutatók konténerben való weak módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok string-gé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Feloldja a megadott bitmapet a rendszer memóriájából. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Image](../image/)
* Névterület [System::Drawing](../)
* Könyvtár [Aspose.Slides](../../)