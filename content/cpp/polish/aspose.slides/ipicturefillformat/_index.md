---
title: IPictureFillFormat
second_title: Aspose.Slides dla C++ Referencja API
description: Reprezentuje styl wypełniania obrazem.
type: docs
weight: 3225
url: /pl/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat klasa

Reprezentuje styl wypełniania obrazem.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | Kompresuje obraz, zmniejszając jego rozmiar w zależności od rozmiaru kształtu i określonej rozdzielczości. Opcjonalnie usuwa również przycięte obszary. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | Kompresuje obraz, zmniejszając jego rozmiar w zależności od rozmiaru kształtu i określonej rozdzielczości. Opcjonalnie usuwa również przycięte obszary. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | Usuwa przycięte obszary wypełnienia [Picture](../picture/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | Zwraca liczbę procent rzeczywistej wysokości obrazu, które są przycięte od dołu obrazu. Odczyt **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | Zwraca liczbę procent rzeczywistej szerokości obrazu, które są przycięte od lewej strony obrazu. Odczyt **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | Zwraca liczbę procent rzeczywistej szerokości obrazu, które są przycięte od prawej strony obrazu. Odczyt **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | Zwraca liczbę procent rzeczywistej wysokości obrazu, które są przycięte od górnej części obrazu. Odczyt **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | Zwraca DPI używane do wypełniania obrazem. Odczyt **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Zwraca obraz. Tylko do odczytu [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | Zwraca tryb wypełnienia obrazu. Odczyt [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | Zwraca dolną krawędź prostokąta wypełnienia definiowaną jako przesunięcie procentowe od dolnej krawędzi ramki ograniczającej kształt. Dodatni procent określa wcięcie, ujemny – wystawienie. Odczyt **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | Zwraca lewą krawędź prostokąta wypełnienia definiowaną jako przesunięcie procentowe od lewej krawędzi ramki ograniczającej kształt. Dodatni procent określa wcięcie, ujemny – wystawienie. Odczyt **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | Zwraca prawą krawędź prostokąta wypełnienia definiowaną jako przesunięcie procentowe od prawej krawędzi ramki ograniczającej kształt. Dodatni procent określa wcięcie, ujemny – wystawienie. Odczyt **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | Zwraca górną krawędź prostokąta wypełnienia definiowaną jako przesunięcie procentowe od górnej krawędzi ramki ograniczającej kształt. Dodatni procent określa wcięcie, ujemny – wystawienie. Odczyt **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | Zwraca sposób wyrównania tekstury w obrębie kształtu. To ustawienie kontroluje punkt początkowy wzoru tekstury i sposób jego powtarzania na kształcie. Odczyt [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | Obraca kafelek tekstury wokół osi poziomej, pionowej lub obu. Odczyt [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | Zwraca poziome przesunięcie tekstury od początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w prawo, ujemna w lewo. Odczyt **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | Zwraca pionowe przesunięcie tekstury od początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w dół, ujemna w górę. Odczyt **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | Zwraca poziomą skalę wypełnienia teksturą jako procent. Odczyt **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | Zwraca pionową skalę wypełnienia teksturą jako procent. Odczyt **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie klas pochodnych. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie klas pochodnych. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje obiekt typu wartościowego z nullptr przez referencję. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | Ustawia liczbę procent rzeczywistej wysokości obrazu przyciętej od dołu obrazu. Zapisz **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | Ustawia liczbę procent rzeczywistej szerokości obrazu przyciętej od lewej strony obrazu. Zapisz **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | Ustawia liczbę procent rzeczywistej szerokości obrazu przyciętej od prawej strony obrazu. Zapisz **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | Ustawia liczbę procent rzeczywistej wysokości obrazu przyciętej od górnej części obrazu. Zapisz **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | Ustawia DPI używane do wypełniania obrazu. Zapisz **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | Ustawia tryb wypełnienia obrazu. Zapisz [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | Ustawia dolną krawędź prostokąta wypełnienia definiowaną jako przesunięcie procentowe od dolnej krawędzi ramki ograniczającej kształt. Dodatni procent określa wcięcie, ujemny – wystawienie. Zapisz **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | Ustawia lewą krawędź prostokąta wypełnienia definiowaną jako przesunięcie procentowe od lewej krawędzi ramki ograniczającej kształt. Dodatni procent określa wcięcie, ujemny – wystawienie. Zapisz **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | Ustawia prawą krawędź prostokąta wypełnienia definiowaną jako przesunięcie procentowe od prawej krawędzi ramki ograniczającej kształt. Dodatni procent określa wcięcie, ujemny – wystawienie. Zapisz **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | Ustawia górną krawędź prostokąta wypełnienia definiowaną jako przesunięcie procentowe od górnej krawędzi ramki ograniczającej kształt. Dodatni procent określa wcięcie, ujemny – wystawienie. Zapisz **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | Ustawia sposób wyrównania tekstury w obrębie kształtu. To ustawienie kontroluje punkt początkowy wzoru tekstury i sposób jego powtarzania na kształcie. Zapisz [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | Obraca kafelek tekstury wokół osi poziomej, pionowej lub obu. Zapisz [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | Ustawia poziome przesunięcie tekstury od początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w prawo, ujemna w lewo. Zapisz **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | Ustawia pionowe przesunięcie tekstury od początku kształtu w punktach. Dodatnia wartość przesuwa teksturę w dół, ujemna w górę. Zapisz **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | Ustawia poziomą skalę wypełnienia teksturą jako procent. Zapisz **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | Ustawia pionową skalę wypełnienia teksturą jako procent. Zapisz **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala na przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [IFillParamSource](../ifillparamsource/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)