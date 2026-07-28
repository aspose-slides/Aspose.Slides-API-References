---
title: Bitmap
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: "Reprezentuje obraz bitmapowy GDI+. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy czasu wykonania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 1
url: /pl/system.drawing/bitmap/
---
## Klasa Bitmap

Reprezentuje obraz bitmapowy GDI+. Obiekty tej klasy powinny być tworzone wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy czasu wykonania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argumentu.

```cpp
class Bitmap : public System::Drawing::Image
```

## Metody

| Metoda | Opis |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | Włącza tryb przetwarzania pikseli. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | Tworzy nowy obiekt [Bitmap](./) z określonego istniejącego obrazu. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | Tworzy nowy obiekt [Bitmap](./) z określonego strumienia. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | Tworzy nowy obiekt [Bitmap](./) z określonego pliku. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | Tworzy nowy obiekt [Bitmap](./) z określonego pliku. |
| [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Tworzy nowy obiekt [Bitmap](./), który reprezentuje obraz bitmapowy o określonej szerokości, wysokości, formacie pikseli i danych pikseli. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | Tworzy nowy obiekt [Bitmap](./) z określonego istniejącego obrazu, skalowanego do podanego rozmiaru. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | Tworzy nowy obiekt [Bitmap](./) z określonego istniejącego obrazu z szerokością i wysokością skalowanymi do podanych wartości. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | Tworzy kopię bieżącego obiektu. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Tworzy obiekt [Bitmap](./), który reprezentuje kopię regionu obrazu bitmapowego reprezentowanego przez bieżący obiekt. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Tworzy obiekt [Bitmap](./), który reprezentuje kopię regionu obrazu bitmapowego reprezentowanego przez bieżący obiekt. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | Oblicza wartość skrótu SHA1. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | Tworzy kopię określonego obrazu bitmapowego z formatem pikseli zmienionym na Format32bppArgb. |
| void [Dispose](../image/dispose/)() override | Zwalnia wszystkie zasoby pozyskane przez bieżący obiekt. |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | Wyłącza tryb przetwarzania pikseli. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że wg IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych typu double w stylu C#, gdzie dwa NaN są uważane za równe, mimo że wg IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | Tworzy obiekt [Image](../image/) z określonego pliku. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | Tworzy obiekt [Bitmap](./) z określonej bitmapy GDI. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Tworzy obiekt [Image](../image/) z określonego strumienia. |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | Zwraca kombinację bitową wartości wyliczenia ImageFlags, która reprezentuje atrybuty obrazu. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | Zwraca tablicę GUID-ów reprezentujących wymiary klatek w obrazie reprezentowanym przez bieżący obiekt. |
| int [get_Height](./get_height/)() const override | Zwraca wysokość obrazu w pikselach. |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | Zwraca poziomą rozdzielczość obrazu reprezentowanego przez bieżący obiekt w pikselach na cal. |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | Zwraca paletę kolorów używaną przez obraz reprezentowany przez bieżący obiekt. |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | Zwraca format pikseli obrazu reprezentowanego przez bieżący obiekt. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | Pobiera identyfikatory elementów właściwości przechowywanych w tym obrazie. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | Pobiera wszystkie elementy właściwości (fragmenty metadanych) przechowywane w tym obrazie. |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | Zwraca format pliku obrazu reprezentowanego przez bieżący obiekt. |
| [Size](../size/) [get_Size](../image/get_size/)() const | Zwraca obiekt [Size](../size/), który reprezentuje szerokość i wysokość obrazu w pikselach. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | Pobiera obiekt, który dostarcza dodatkowe dane o obrazie. |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | Zwraca pionową rozdzielczość obrazu reprezentowanego przez bieżący obiekt w pikselach na cal. |
| int [get_Width](./get_width/)() const override | Zwraca szerokość obrazu w pikselach. |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | Zwraca granice obrazu w określonych jednostkach miary. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | Zwraca liczbę klatek w określonym wymiarze klatki. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| IntPtr [GetHbitmap](./gethbitmap/)() | Tworzy obiekt bitmapy GDI z bitmapy reprezentowanej przez bieżący obiekt. |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | Zwraca kolor określonego piksela. |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Zwraca liczbę bitów używanych do reprezentacji głębi kolorów w określonym formacie pikseli. |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | Zwraca surowy wskaźnik do podlegającego obiektu SkBitmap. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | Pobiera miniaturkę dla tego obiektu [System::Drawing::Image](../image/). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Określa, czy podany format pikseli zawiera informacje o alfabie. |
| **bool** [IsMultiImage](./ismultiimage/)() const override | Zwraca informację, czy oryginalny format jest wieloklatkowy. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę C# lock(). Wywołaj bezpośrednio lub użyj obiektu nadzoru [LockContext](../../system/lockcontext/). |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Blokuje [Bitmap](./) w pamięci systemowej. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Blokuje [Bitmap](./) w pamięci systemowej. |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | Zmieniam kolor wszystkich pikseli o określonym kolorze na przezroczysty. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów podklas. |
| void [PremultipleColors](./premultiplecolors/)() | Wstępnie mnoży kolory pikseli obrazu reprezentowanego przez bieżący obiekt. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | Obraca obraz o wielokrotność 90 stopni i odwraca. |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | Zapisuje obraz reprezentowany przez bieżący obiekt do określonego pliku w formacie PNG. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Zapisuje obraz reprezentowany przez bieżący obiekt do określonego pliku w podanym formacie. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Zapisuje obraz reprezentowany przez bieżący obiekt do określonego strumienia w podanym formacie. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Zapisuje obraz reprezentowany przez bieżący obiekt do określonego pliku przy użyciu podanego kodera i parametrów kodera. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Zapisuje obraz reprezentowany przez bieżący obiekt do określonego strumienia przy użyciu podanego kodera i parametrów kodera. |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Dodaje klatkę do pliku lub strumienia określonego w poprzednim wywołaniu metody [Save()](../image/save/). |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Dodaje klatkę do pliku lub strumienia określonego w poprzednim wywołaniu metody [Save()](../image/save/). |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | Wybiera określoną klatkę. |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | Ustawia paletę kolorów używaną przez obraz reprezentowany przez bieżący obiekt. |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ustawia obiekt, który dostarcza dodatkowe dane o obrazie. |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | Ustawia kolor określonego piksela w obrazie bitmapowym reprezentowanym przez bieżący obiekt. |
| void [SetResolution](./setresolution/)(**float**, **float**) | Ustawia rozdzielczość obrazu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie własnych obiektów na łańcuch znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie C# lock(). Wywołaj bezpośrednio lub użyj obiektu nadzoru [LockContext](../../system/lockcontext/). |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Odblokowuje określoną bitmapę z pamięci systemowej. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Image](../image/)
* Przestrzeń nazw [System::Drawing](../)
* Biblioteka [Aspose.Slides](../../)