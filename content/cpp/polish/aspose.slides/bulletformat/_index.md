---
title: BulletFormat
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Reprezentuje właściwości formatowania wypunktowań akapitu.
type: docs
weight: 248
url: /pl/aspose.slides/bulletformat/
---
## BulletFormat klasa

Represents paragraph bullet formatting properties.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | Ustawia domyślne niezerowe przesunięcia dla rzeczywistego wcięcia akapitu (Indent) i lewego marginesu (MarginLeft), gdy wypunktowanie jest włączone (tak jak PowerPoint robi to, gdy włączone jest wypunktowanie/numerowanie akapitu). Jeśli wypunktowanie jest wyłączone, to po prostu resetuje wcięcie akapitu (Indent) i lewy margines (MarginLeft) (tak jak PowerPoint robi to, gdy wyłącza wypunktowanie/numerowanie akapitu). Przesunięcia wcięć są stosowane w odniesieniu do bieżącego kontekstu wypunktowania – IBulletFormat::get(set)_Type, .NumberedBulletStyle oraz FontHeight pierwszej części. Niezerowe przesunięcia wcięć są stosowane do rzeczywistego wcięcia (Indent) i lewego marginesu (MarginLeft) bieżącego akapitu (sprawiając, że wartości wynikowe są wartościami lokalnymi). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Porównuje z określonym obiektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych podwójnej precyzji w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| char16_t [get_Char](./get_char/)() override | Zwraca znak wypunktowania akapitu bez dziedziczenia. Odczyt **wchar_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | Zwraca format koloru wypunktowania akapitu bez dziedziczenia. Tylko do odczytu [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | Zwraca czcionkę wypunktowania akapitu bez dziedziczenia. Odczyt [IFontData](../ifontdata/). |
| **float** [get_Height](./get_height/)() override | Zwraca wysokość wypunktowania akapitu bez dziedziczenia. Wartość std::numeric_limits<float>::quiet_NaN() określa, że wypunktowanie dziedziczy wysokość z pierwszej części w akapicie. Odczyt **float**. |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | Określa, czy wypunktowanie ma własny kolor czy dziedziczy go z pierwszej części w akapicie. **[NullableBool::True](../nullablebool/)** jeśli wypunktowanie ma własny kolor i **[NullableBool::False](../nullablebool/)** jeśli wypunktowanie dziedziczy kolor z pierwszej części w akapicie. Odczyt [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | Określa, czy wypunktowanie ma własną czcionkę czy dziedziczy ją z pierwszej części w akapicie. **[NullableBool::True](../nullablebool/)** jeśli wypunktowanie ma własną czcionkę i **[NullableBool::False](../nullablebool/)** jeśli wypunktowanie dziedziczy czcionkę z pierwszej części w akapicie. Odczyt [NullableBool](../nullablebool/). |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | Zwraca pierwszą liczbę używaną dla grupy numerowanych wypunktowań bez dziedziczenia. Odczyt **int16_t**. |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | Zwraca styl numerowanego wypunktowania bez dziedziczenia. Odczyt [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Zwraca obiekt Parent_Immediate. Tylko do odczytu [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Zwraca rodzica [IPresentationComponent](../ipresentationcomponent/). Tylko do odczytu [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Zwraca obraz używany jako wypunktowanie w akapicie bez dziedziczenia. Tylko do odczytu [ISlidesPicture](../islidespicture/). |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | Zwraca typ wypunktowania akapitu bez dziedziczenia. Odczyt [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | Pobiera efektywne dane formatowania wypunktowania z zastosowanym dziedziczeniem. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Zwraca kod skrótu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczne do wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny do operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna do metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_Char](./set_char/)(char16_t) override | Ustawia znak wypunktowania akapitu bez dziedziczenia. Zapis **wchar_t**. |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Ustawia czcionkę wypunktowania akapitu bez dziedziczenia. Zapis [IFontData](../ifontdata/). |
| void [set_Height](./set_height/)(**float**) override | Ustawia wysokość wypunktowania akapitu bez dziedziczenia. Wartość std::numeric_limits<float>::quiet_NaN() określa, że wypunktowanie dziedziczy wysokość z pierwszej części w akapicie. Zapis **float**. |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | Określa, czy wypunktowanie ma własny kolor czy dziedziczy go z pierwszej części w akapicie. **[NullableBool::True](../nullablebool/)** jeśli wypunktowanie ma własny kolor i **[NullableBool::False](../nullablebool/)** jeśli wypunktowanie dziedziczy kolor z pierwszej części w akapicie. Zapis [NullableBool](../nullablebool/). |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | Określa, czy wypunktowanie ma własną czcionkę czy dziedziczy ją z pierwszej części w akapicie. **[NullableBool::True](../nullablebool/)** jeśli wypunktowanie ma własną czcionkę i **[NullableBool::False](../nullablebool/)** jeśli wypunktowanie dziedziczy czcionkę z pierwszej części w akapicie. Zapis [NullableBool](../nullablebool/). |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | Ustawia pierwszą liczbę używaną dla grupy numerowanych wypunktowań bez dziedziczenia. Zapis **int16_t**. |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | Ustawia styl numerowanego wypunktowania bez dziedziczenia. Zapis [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | Ustawia typ wypunktowania akapitu bez dziedziczenia. Zapis [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna do metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie obiektów niestandardowych na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [PVIObject](../pviobject/)
* Klasa [IBulletFormat](../ibulletformat/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)