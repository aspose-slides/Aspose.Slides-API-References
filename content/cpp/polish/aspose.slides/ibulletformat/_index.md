---
title: IBulletFormat
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Reprezentuje właściwości formatowania wypunktowania akapitu.
type: docs
weight: 1561
url: /pl/aspose.slides/ibulletformat/
---
## IBulletFormat klasa


Reprezentuje właściwości formatowania wypunktowania akapitu.

```cpp
class IBulletFormat : public virtual System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() | Ustawia domyślne nie-zerowe przemieszczenia dla efektywnego wcięcia (Indent) i lewego marginesu (MarginLeft) akapitu, gdy wypunktowanie jest włączone (tak jak PowerPoint robi, jeśli włączyć wypunktowanie/numery w akapicie). Jeśli wypunktowanie jest wyłączone, po prostu resetuje wcięcie (Indent) i lewy margines (MarginLeft) akapitu (tak jak PowerPoint robi, jeśli wyłączyć wypunktowanie/numery w akapicie). Przesunięcia wcięć są stosowane w odniesieniu do bieżącego kontekstu wypunktowania – IBulletFormat::get(set)_Type, .NumberedBulletStyle i FontHeight pierwszej części. Nie-zerowe przemieszczenia wcięć są stosowane do efektywnego Indent i MarginLeft bieżącego akapitu (tworząc wartości lokalne). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do celów wewnętrznych. |
| virtual char16_t [get_Char](./get_char/)() | Zwraca znak wypunktowania akapitu bez dziedziczenia. Odczyt **wchar_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() | Zwraca format koloru wypunktowania akapitu bez dziedziczenia. Tylko do odczytu [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() | Zwraca czcionkę wypunktowania akapitu bez dziedziczenia. Odczyt [IFontData](../ifontdata/). |
| virtual **float** [get_Height](./get_height/)() | Zwraca wysokość wypunktowania akapitu bez dziedziczenia. Wartość std::numeric_limits<float>::quiet_NaN() oznacza, że wypunktowanie dziedziczy wysokość z pierwszej części akapitu. Odczyt **float**. |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() | Określa, czy wypunktowanie ma własny kolor czy dziedziczy go z pierwszej części akapitu. **[NullableBool::True](../nullablebool/)** jeśli wypunktowanie ma własny kolor i **[NullableBool::False](../nullablebool/)** jeśli wypunktowanie dziedziczy kolor z pierwszej części akapitu. Odczyt [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() | Określa, czy wypunktowanie ma własną czcionkę czy dziedziczy ją z pierwszej części akapitu. **[NullableBool::True](../nullablebool/)** jeśli wypunktowanie ma własną czcionkę i **[NullableBool::False](../nullablebool/)** jeśli wypunktowanie dziedziczy czcionkę z pierwszej części akapitu. Odczyt [NullableBool](../nullablebool/). |
| virtual **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() | Zwraca pierwszą liczbę używaną dla grupy numerowanych wypunktowań bez dziedziczenia. Odczyt **int16_t**. |
| virtual [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() | Zwraca styl numerowanego wypunktowania bez dziedziczenia. Odczyt [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Zwraca obraz używany jako wypunktowanie w akapicie bez dziedziczenia. Tylko do odczytu [ISlidesPicture](../islidespicture/). |
| virtual [BulletType](../bullettype/) [get_Type](./get_type/)() | Zwraca typ wypunktowania akapitu bez dziedziczenia. Odczyt [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() | Pobiera efektywne dane formatowania wypunktowania z zastosowanym dziedziczeniem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera faktyczny typ obiektu. Analogiczne wywołanie C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez odniesienie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez odniesienie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_Char](./set_char/)(char16_t) | Ustawia znak wypunktowania akapitu bez dziedziczenia. Zapis **wchar_t**. |
| virtual void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Ustawia czcionkę wypunktowania akapitu bez dziedziczenia. Zapis [IFontData](../ifontdata/). |
| virtual void [set_Height](./set_height/)(**float**) | Ustawia wysokość wypunktowania akapitu bez dziedziczenia. Wartość std::numeric_limits<float>::quiet_NaN() oznacza, że wypunktowanie dziedziczy wysokość z pierwszej części akapitu. Zapis **float**. |
| virtual void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) | Określa, czy wypunktowanie ma własny kolor czy dziedziczy go z pierwszej części akapitu. **[NullableBool::True](../nullablebool/)** jeśli wypunktowanie ma własny kolor i **[NullableBool::False](../nullablebool/)** jeśli wypunktowanie dziedziczy kolor z pierwszej części akapitu. Zapis [NullableBool](../nullablebool/). |
| virtual void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) | Określa, czy wypunktowanie ma własną czcionkę czy dziedziczy ją z pierwszej części akapitu. **[NullableBool::True](../nullablebool/)** jeśli wypunktowanie ma własną czcionkę i **[NullableBool::False](../nullablebool/)** jeśli wypunktowanie dziedziczy czcionkę z pierwszej części akapitu. Zapis [NullableBool](../nullablebool/). |
| virtual void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) | Ustawia pierwszą liczbę używaną dla grupy numerowanych wypunktowań bez dziedziczenia. Zapis **int16_t**. |
| virtual void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) | Ustawia styl numerowanego wypunktowania bez dziedziczenia. Zapis [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual void [set_Type](./set_type/)([BulletType](../bullettype/)) | Ustawia typ wypunktowania akapitu bez dziedziczenia. Zapis [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączyć wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)