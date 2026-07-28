---
title: Image
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Podstawowa klasa dla klas System::Drawing::Bitmap i System::Drawing::Metafile zapewniająca podstawową funkcjonalność. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub awarie asercji. Zawsze opakowuj tę klasę we wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 144
url: /pl/system.drawing/image/
---
## Klasa Image

Podstawowa klasa dla [System::Drawing::Bitmap](../bitmap/) i klas System::Drawing::Metafile zapewniająca podstawową funkcjonalność. Obiekty tej klasy powinny być tworzone wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ doprowadzi to do błędów w czasie wykonywania i/lub awarii asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji.

```cpp
class Image : public virtual System::IDisposable
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [Clone](./clone/)() | Tworzy kopię bieżącego obiektu. |
| void [Dispose](./dispose/)() override | Zwalnia wszystkie zasoby pozyskane przez bieżący obiekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [FromFile](./fromfile/)(const [String](../../system/string/)\&, **bool**) | Tworzy obiekt [Image](./) z określonego pliku. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](../bitmap/)\> [FromHbitmap](./fromhbitmap/)(IntPtr) | Tworzy obiekt [Bitmap](../bitmap/) z określonej bitmapy GDI. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [FromStream](./fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Tworzy obiekt [Image](./) z określonego strumienia. |
| virtual **int32_t** [get_Flags](./get_flags/)() const | Zwraca bitową kombinację wartości wyliczenia ImageFlags, które reprezentują atrybuty obrazu. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](./get_framedimensionslist/)() const | Zwraca tablicę GUID-ów, które reprezentują wymiary klatek w obrazie reprezentowanym przez bieżący obiekt. |
| virtual int [get_Height](./get_height/)() const | Zwraca wysokość obrazu w pikselach. |
| **float** [get_HorizontalResolution](./get_horizontalresolution/)() const | Zwraca poziomą rozdzielczość obrazu reprezentowanego przez bieżący obiekt w pikselach na cal. |
| virtual [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const | Zwraca paletę kolorów używaną przez obraz reprezentowany przez bieżący obiekt. |
| virtual [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const | Zwraca format pikseli obrazu reprezentowanego przez bieżący obiekt. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](./get_propertyidlist/)() const | Pobiera identyfikatory elementów właściwości przechowywanych w tym obrazie. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](./get_propertyitems/)() const | Pobiera wszystkie elementy właściwości (fragmenty metadanych) przechowywane w tym obrazie. |
| virtual [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const | Zwraca format pliku obrazu reprezentowanego przez bieżący obiekt. |
| [Size](../size/) [get_Size](./get_size/)() const | Zwraca obiekt [Size](../size/), który reprezentuje szerokość i wysokość obrazu w pikselach. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](./get_tag/)() const | Pobiera obiekt, który dostarcza dodatkowych danych o obrazie. |
| **float** [get_VerticalResolution](./get_verticalresolution/)() const | Zwraca pionową rozdzielczość obrazu reprezentowanego przez bieżący obiekt w pikselach na cal. |
| virtual int [get_Width](./get_width/)() const | Zwraca szerokość obrazu w pikselach. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)([GraphicsUnit](../graphicsunit/)\&) | Zwraca granice obrazu w określonych jednostkach miary. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązanego z obiektem. |
| int [GetFrameCount](./getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | Zwraca liczbę klatek w określonym wymiarze klatki. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| static int [GetPixelFormatSize](./getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Zwraca liczbę bitów używanych do reprezentacji głębi koloru w określonym formacie pikseli. |
| virtual const SkBitmap * [GetSkBitmap](./getskbitmap/)() const | Zwraca podstawowy obiekt SkBitmap. |
| [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [GetThumbnailImage](./getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](./getthumbnailimageabort/), IntPtr) | Pobiera miniaturę dla tego obiektu [System::Drawing::Image](./). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| static **bool** [IsAlphaPixelFormat](./isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Określa, czy podany format pikseli zawiera informacje alfa. |
| virtual **bool** [IsMultiImage](./ismultiimage/)() const | Zwraca, czy oryginalny format jest wielokrotnym obrazem. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia konstrukcję kopiującą podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia konstrukcję kopiującą podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) | Obraca obraz o wielokrotność 90 stopni i odwraca. |
| void [Save](./save/)(const [String](../../system/string/)\&) | Zapisuje obraz reprezentowany przez bieżący obiekt do określonego pliku w formacie PNG. |
| void [Save](./save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Zapisuje obraz reprezentowany przez bieżący obiekt do określonego pliku w podanym formacie. |
| void [Save](./save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Zapisuje obraz reprezentowany przez bieżący obiekt do określonego strumienia w podanym formacie. |
| void [Save](./save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Zapisuje obraz reprezentowany przez bieżący obiekt do określonego pliku przy użyciu podanego enkodera i parametrów enkodera. |
| void [Save](./save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Zapisuje obraz reprezentowany przez bieżący obiekt do określonego strumienia przy użyciu podanego enkodera i parametrów enkodera. |
| void [SaveAdd](./saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Dodaje klatkę do pliku lub strumienia określonego w poprzednim wywołaniu metody [Save()](./save/). |
| void [SaveAdd](./saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](./)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Dodaje klatkę do pliku lub strumienia określonego w poprzednim wywołaniu metody [Save()](./save/). |
| int [SelectActiveFrame](./selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | Wybiera określoną klatkę. |
| virtual void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) | Ustawia paletę kolorów używaną przez obraz reprezentowany przez bieżący obiekt. |
| virtual void [set_Tag](./set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ustawia obiekt, który dostarcza dodatkowych danych o obrazie. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach do trybu słabego. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [GetThumbnailImageAbort](./getthumbnailimageabort/) | Wywołanie zwrotne służące do anulowania wykonywania GetThumbnailImage. |

## Zobacz także

* Klasa [IDisposable](../../system/idisposable/)
* Przestrzeń nazw [System::Drawing](../)
* Biblioteka [Aspose.Slides](../../)