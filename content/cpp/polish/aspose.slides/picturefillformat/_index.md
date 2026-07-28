---
title: PictureFillFormat
second_title: Aspose.Slides dla C++ – odniesienie API
description: Reprezentuje styl wypełnienia obrazem.
type: docs
weight: 4720
url: /pl/aspose.slides/picturefillformat/
---
## PictureFillFormat klasa


Reprezentuje styl wypełnienia obrazem.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## Metody

| Method | Description |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | Kompresuje obraz, zmniejszając jego rozmiar w oparciu o rozmiar kształtu i określoną rozdzielczość. Opcjonalnie usuwa także przycięte obszary. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | Kompresuje obraz, zmniejszając jego rozmiar w oparciu o rozmiar kształtu i określoną rozdzielczość. Opcjonalnie usuwa także przycięte obszary. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | Usuń przycięte obszary wypełnienia [Picture](../picture/). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Porównuje z określonym obiektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **float** [get_CropBottom](./get_cropbottom/)() override | Zwraca liczbę procent rzeczywistej wysokości obrazu, które są odcięte od dołu obrazu. Odczyt **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | Zwraca liczbę procent rzeczywistej szerokości obrazu, które są odcięte od lewej strony obrazu. Odczyt **float**. |
| **float** [get_CropRight](./get_cropright/)() override | Zwraca liczbę procent rzeczywistej szerokości obrazu, które są odcięte od prawej strony obrazu. Odczyt **float**. |
| **float** [get_CropTop](./get_croptop/)() override | Zwraca liczbę procent rzeczywistej wysokości obrazu, które są odcięte od góry obrazu. Odczyt **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | Zwraca dpi używane do wypełnienia obrazu. Odczyt **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Zwraca obiekt Parent_Immediate. Tylko do odczytu [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Zwraca rodzica [IPresentationComponent](../ipresentationcomponent/). Tylko do odczytu [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Zwraca obraz. Tylko do odczytu [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | Zwraca tryb wypełniania obrazem. Odczyt [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | Zwraca dolny brzeg prostokąta wypełnienia określony przez przesunięcie procentowe od dolnego brzegu ramki otaczającej kształt. Pozytywny procent określa wcięcie, natomiast ujemny procent określa występ. Odczyt **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | Zwraca lewy brzeg prostokąta wypełnienia określony przez przesunięcie procentowe od lewego brzegu ramki otaczającej kształt. Pozytywny procent określa wcięcie, natomiast ujemny procent określa występ. Odczyt **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | Zwraca prawy brzeg prostokąta wypełnienia określony przez przesunięcie procentowe od prawego brzegu ramki otaczającej kształt. Pozytywny procent określa wcięcie, natomiast ujemny procent określa występ. Odczyt **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | Zwraca górny brzeg prostokąta wypełnienia określony przez przesunięcie procentowe od górnego brzegu ramki otaczającej kształt. Pozytywny procent określa wcięcie, natomiast ujemny procent określa występ. Odczyt **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | Zwraca sposób, w jaki tekstura jest wyrównana w kształcie. To ustawienie kontroluje punkt początkowy wzoru tekstury i sposób jej powtarzania w kształcie. Odczyt [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | Odwraca kafelek tekstury wokół osi poziomej, pionowej lub obu. Odczyt [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | Zwraca poziome przesunięcie tekstury względem pochodzenia kształtu w punktach. Pozytywna wartość przesuwa teksturę w prawo, natomiast ujemna w lewo. Odczyt **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | Zwraca pionowe przesunięcie tekstury względem pochodzenia kształtu w punktach. Pozytywna wartość przesuwa teksturę w dół, natomiast ujemna w górę. Odczyt **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | Zwraca poziomą skalę wypełnienia teksturą jako procent. Odczyt **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | Zwraca pionową skalę wypełnienia teksturą jako procent. Odczyt **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Zwraca kod skrótu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o określoną wartość. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | Ustawia liczbę procent rzeczywistej wysokości obrazu, które są odcięte od dołu obrazu. Zapis **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | Ustawia liczbę procent rzeczywistej szerokości obrazu, które są odcięte od lewej strony obrazu. Zapis **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | Ustawia liczbę procent rzeczywistej szerokości obrazu, które są odcięte od prawej strony obrazu. Zapis **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | Ustawia liczbę procent rzeczywistej wysokości obrazu, które są odcięte od góry obrazu. Zapis **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | Ustawia dpi używane do wypełnienia obrazu. Zapis **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | Ustawia tryb wypełnienia obrazu. Zapis [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | Ustawia dolny brzeg prostokąta wypełnienia określony przez przesunięcie procentowe od dolnego brzegu ramki otaczającej kształt. Pozytywny procent określa wcięcie, natomiast ujemny procent określa występ. Zapis **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | Ustawia lewy brzeg prostokąta wypełnienia określony przez przesunięcie procentowe od lewego brzegu ramki otaczającej kształt. Pozytywny procent określa wcięcie, natomiast ujemny procent określa występ. Zapis **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | Ustawia prawy brzeg prostokąta wypełnienia określony przez przesunięcie procentowe od prawego brzegu ramki otaczającej kształt. Pozytywny procent określa wcięcie, natomiast ujemny procent określa występ. Zapis **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | Ustawia górny brzeg prostokąta wypełnienia określony przez przesunięcie procentowe od górnego brzegu ramki otaczającej kształt. Pozytywny procent określa wcięcie, natomiast ujemny procent określa występ. Zapis **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | Ustawia sposób, w jaki tekstura jest wyrównana w kształcie. To ustawienie kontroluje punkt początkowy wzoru tekstury i sposób jej powtarzania w kształcie. Zapis [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | Odwraca kafelek tekstury wokół osi poziomej, pionowej lub obu. Zapis [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | Ustawia poziome przesunięcie tekstury względem pochodzenia kształtu w punktach. Pozytywna wartość przesuwa teksturę w prawo, natomiast ujemna w lewo. Zapis **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | Ustawia pionowe przesunięcie tekstury względem pochodzenia kształtu w punktach. Pozytywna wartość przesuwa teksturę w dół, natomiast ujemna w górę. Zapis **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | Ustawia poziomą skalę wypełnienia teksturą jako procent. Zapis **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | Ustawia pionową skalę wypełnienia teksturą jako procent. Zapis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustaw n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie obiektów niestandardowych na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Zobacz także

* Klasa [PVIObject](../pviobject/)
* Klasa [IPictureFillFormat](../ipicturefillformat/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)