---
title: IFillFormatEffectiveData
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Niezmienny obiekt zawierający skuteczne właściwości formatowania wypełnienia.
type: docs
weight: 2120
url: /pl/aspose.slides/ifillformateffectivedata/
---
## IFillFormatEffectiveData klasa

Niezmienny obiekt, który zawiera skuteczne właściwości formatowania wypełnienia.

```cpp
class IFillFormatEffectiveData : public Aspose::Slides::IFillParamSource
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [Aspose::Slides::FillType](../filltype/) [get_FillType](./get_filltype/)() | Zwraca typ wypełnienia. Tylko do odczytu [Slides::FillType](../filltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGradientFormatEffectiveData](../igradientformateffectivedata/)\> [get_GradientFormat](./get_gradientformat/)() | Zwraca format wypełnienia gradientowego. Tylko do odczytu [IGradientFormatEffectiveData](../igradientformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPatternFormatEffectiveData](../ipatternformateffectivedata/)\> [get_PatternFormat](./get_patternformat/)() | Zwraca format wypełnienia wzoru. Tylko do odczytu [IPatternFormatEffectiveData](../ipatternformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormatEffectiveData](../ipicturefillformateffectivedata/)\> [get_PictureFillFormat](./get_picturefillformat/)() | Zwraca format wypełnienia obrazu. Tylko do odczytu [IPictureFillFormatEffectiveData](../ipicturefillformateffectivedata/). |
| virtual **bool** [get_RotateWithShape](./get_rotatewithshape/)() | Określa, czy wypełnienie powinno być obrócone razem z kształtem. Tylko do odczytu **bool**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_SolidFillColor](./get_solidfillcolor/)() | Zwraca kolor wypełnienia. Tylko do odczytu [System::Drawing::Color](../../system.drawing/color/). |
| virtual [SchemeColor](../schemecolor/) [get_SolidFillSchemeColor](./get_solidfillschemecolor/)() | Pobiera kolor wypełnienia zdefiniowany w schemacie kolorów. Wartość [SchemeColor::NotDefined](../schemecolor/) wskazuje, że [IFillFormatEffectiveData::get_SolidFillColor](./get_solidfillcolor/) nie jest kolorem ze schematu. Tylko do odczytu [SchemeColor](../schemecolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/) . Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) . Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, naprawdę, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, naprawdę, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n'ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach do trybu słabego. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/) . Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Uwagi

Ten interfejs jest używany razem z interfejsem [IFillFormat](../ifillformat/) do zwracania skutecznych wartości formatowania z zastosowanym dziedziczeniem. 

## Zobacz także

* Klasa [IFillParamSource](../ifillparamsource/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)