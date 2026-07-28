---
title: Metafile
second_title: Odwołanie API Aspose.Slides dla C++
description: "Reprezentuje plik graficzny metafile. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject() . Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 144
url: /pl/system.drawing.imaging/metafile/
---
## Klasa Metafile


Reprezentuje plik graficzny metafile. Obiekty tej klasy powinny być alokowane wyłącznie za pomocą funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji.

```cpp
class Metafile : public System::Drawing::Image
```

## Metody

| Metoda | Opis |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [Clone](./clone/)() override | Zwraca kopię bieżącego obiektu. |
| void [Dispose](../../system.drawing/image/dispose/)() override | Zwalnia wszystkie zasoby nabyte przez bieżący obiekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imituje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imituje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [FromFile](../../system.drawing/image/fromfile/)(const [String](../../system/string/)\&, **bool**) | Tworzy obiekt [Image](../../system.drawing/image/) z podanego pliku. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](../../system.drawing/bitmap/)\> [FromHbitmap](../../system.drawing/image/fromhbitmap/)(IntPtr) | Tworzy obiekt [Bitmap](../../system.drawing/bitmap/) z podanego bitmapu GDI. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [FromStream](../../system.drawing/image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Tworzy obiekt [Image](../../system.drawing/image/) z podanego strumienia. |
| virtual **int32_t** [get_Flags](../../system.drawing/image/get_flags/)() const | Zwraca kombinację bitową wartości wyliczenia ImageFlags, która reprezentuje atrybuty obrazu. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../../system.drawing/image/get_framedimensionslist/)() const | Zwraca tablicę GUID-ów, które reprezentują wymiary klatek w obrazie reprezentowanym przez bieżący obiekt. |
| int [get_Height](./get_height/)() const override | Zwraca wysokość obrazu w pikselach. |
| **float** [get_HorizontalResolution](../../system.drawing/image/get_horizontalresolution/)() const | Zwraca poziomą rozdzielczość obrazu reprezentowanego przez bieżący obiekt w pikselach na cal. |
| virtual [Imaging::ColorPalettePtr](../colorpaletteptr/) [get_Palette](../../system.drawing/image/get_palette/)() const | Zwraca paletę kolorów używaną przez obraz reprezentowany przez bieżący obiekt. |
| [Imaging::PixelFormat](../pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | Zwraca wartość wskazującą format pikseli. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../../system.drawing/image/get_propertyidlist/)() const | Pobiera identyfikatory elementów właściwości przechowywanych w tym obrazie. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../propertyitem/)\>\> [get_PropertyItems](../../system.drawing/image/get_propertyitems/)() const | Pobiera wszystkie elementy właściwości (fragmenty metadanych) przechowywane w tym obrazie. |
| [Imaging::ImageFormatPtr](../imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | Zwraca wartość wskazującą format obrazu. |
| [Size](../../system.drawing/size/) [get_Size](../../system.drawing/image/get_size/)() const | Zwraca obiekt [Size](../../system.drawing/size/) reprezentujący szerokość i wysokość obrazu w pikselach. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../../system.drawing/image/get_tag/)() const | Pobiera obiekt, który dostarcza dodatkowe dane o obrazie. |
| **float** [get_VerticalResolution](../../system.drawing/image/get_verticalresolution/)() const | Zwraca pionową rozdzielczość obrazu reprezentowanego przez bieżący obiekt w pikselach na cal. |
| int [get_Width](./get_width/)() const override | Zwraca szerokość obrazu w pikselach. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](../../system.drawing/image/getbounds/)([GraphicsUnit](../../system.drawing/graphicsunit/)\&) | Zwraca granice obrazu w określonych jednostkach miary. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| int [GetFrameCount](../../system.drawing/image/getframecount/)(const [Imaging::FrameDimensionPtr](../framedimensionptr/)\&) | Zwraca liczbę klatek określonego wymiaru klatki. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda do C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| IntPtr [GetHenhmetafile](./gethenhmetafile/)() | NIE ZAIMPLEMENTOWANO. |
| [SharedPtr](../../system/sharedptr/)\<[MetafileHeader](../metafileheader/)\> [GetMetafileHeader](./getmetafileheader/)() | Zwraca nagłówek powiązany z bieżącym obiektem. |
| static int [GetPixelFormatSize](../../system.drawing/image/getpixelformatsize/)([Imaging::PixelFormat](../pixelformat/)) | Zwraca liczbę bitów używanych do reprezentacji głębi kolorów w określonym formacie pikseli. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\> [GetThumbnailImage](../../system.drawing/image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../../system.drawing/image/getthumbnailimageabort/), IntPtr) | Pobiera miniaturę dla tego obiektu [System::Drawing::Image](../../system.drawing/image/). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczny wywołaniu C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| static **bool** [IsAlphaPixelFormat](../../system.drawing/image/isalphapixelformat/)([Imaging::PixelFormat](../pixelformat/)) | Określa, czy podany format pikseli zawiera informacje o alphy. |
| virtual **bool** [IsMultiImage](../../system.drawing/image/ismultiimage/)() const | Zwraca, czy oryginalny format jest wielokrotnym obrazem. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda do C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [Metafile](./metafile/)(const [System::String](../../system/string/)\&) | NIE ZAIMPLEMENTOWANO. |
| [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&) | NIE ZAIMPLEMENTOWANO. |
| [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [EmfType](../emftype/)) | NIE ZAIMPLEMENTOWANO. |
| [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr) | NIE ZAIMPLEMENTOWANO. |
| [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [Rectangle](../../system.drawing/rectangle/), [MetafileFrameUnit](../metafileframeunit/), [EmfType](../emftype/)) | NIE ZAIMPLEMENTOWANO. |
| [Metafile](./metafile/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, IntPtr, [RectangleF](../../system.drawing/rectanglef/), [MetafileFrameUnit](../metafileframeunit/), [EmfType](../emftype/)) | NIE ZAIMPLEMENTOWANO. |
| [Metafile](./metafile/)(IntPtr, [EmfType](../emftype/)) | NIE ZAIMPLEMENTOWANO. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstrukcji podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstrukcji podklas. |
| void [PlayRecord](./playrecord/)([EmfPlusRecordType](../emfplusrecordtype/), **int32_t**, **int32_t**, [System::ByteArrayPtr](../../system/bytearrayptr/)) | NIE ZAIMPLEMENTOWANO. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [RotateFlip](../../system.drawing/image/rotateflip/)([RotateFlipType](../../system.drawing/rotatefliptype/)) | Obraca obraz o wielokrotność 90 stopni i odbija. |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&) | Zapisuje obraz reprezentowany przez bieżący obiekt do określonego pliku w formacie PNG. |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../imageformatptr/)\&) | Zapisuje obraz reprezentowany przez bieżący obiekt do określonego pliku w podanym formacie. |
| void [Save](../../system.drawing/image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../imageformatptr/)\&) | Zapisuje obraz reprezentowany przez bieżący obiekt do określonego strumienia w podanym formacie. |
| void [Save](../../system.drawing/image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | Zapisuje obraz reprezentowany przez bieżący obiekt do określonego pliku przy użyciu podanego enkodera i parametrów enkodera. |
| void [Save](../../system.drawing/image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | Zapisuje obraz reprezentowany przez bieżący obiekt do określonego strumienia przy użyciu podanego enkodera i parametrów enkodera. |
| void [SaveAdd](../../system.drawing/image/saveadd/)(const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | Dodaje klatkę do pliku lub strumienia określonego w poprzednim wywołaniu metody [Save()](../../system.drawing/image/save/). |
| void [SaveAdd](../../system.drawing/image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../../system.drawing/image/)\>\&, const [Imaging::EncoderParametersPtr](../encoderparametersptr/)\&) | Dodaje klatkę do pliku lub strumienia określonego w poprzednim wywołaniu metody [Save()](../../system.drawing/image/save/). |
| int [SelectActiveFrame](../../system.drawing/image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../framedimensionptr/)\&, int) | Wybiera określoną klatkę. |
| virtual void [set_Palette](../../system.drawing/image/set_palette/)([Imaging::ColorPalettePtr](../colorpaletteptr/)) | Ustawia paletę kolorów używaną przez obraz reprezentowany przez bieżący obiekt. |
| virtual void [set_Tag](../../system.drawing/image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ustawia obiekt, który dostarcza dodatkowe dane o obrazie. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie należy wywoływać bezpośrednio; zamiast tego używać inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie należy wywoływać bezpośrednio; zamiast tego używać inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda do C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na łańcuch. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie należy wywoływać bezpośrednio; zamiast tego używać inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie należy wywoływać bezpośrednio; zamiast tego używać inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Metafile](./~metafile/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Image](../../system.drawing/image/)
* Przestrzeń nazw [System::Drawing::Imaging](../)
* Biblioteka [Aspose.Slides](../../)