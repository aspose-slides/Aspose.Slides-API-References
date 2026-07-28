---
title: OuterShadow
second_title: Odnośnik API Aspose.Slides dla C++
description: Reprezentuje efekt zewnętrznego cienia.
type: docs
weight: 1041
url: /pl/aspose.slides.effects/outershadow/
---
## Klasa OuterShadow

Represents an Outer Shadow effect.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## Metody

| Metoda | Opis |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Określa, czy podany [OuterShadow](./) jest równy bieżącemu [OuterShadow](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) promień, w punktach. Domyślna wartość \\u2013 0 pt. Odczyt **double**. |
| **float** [get_Direction](./get_direction/)() override | Kierunek cienia, w stopniach. Domyślna wartość \\u2013 0 \\u00B0 (od lewego do prawego). Odczyt **float**. |
| **double** [get_Distance](./get_distance/)() override | Odległość cienia od obiektu, w punktach. Domyślna wartość \\u2013 0 pt. Odczyt **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Zwraca rodzica [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Tylko do odczytu [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Wyrównanie prostokąta. Domyślna wartość \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Odczyt [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Wskazuje, czy cień obraca się razem z kształtem. Domyślna wartość \\u2013 true. Odczyt **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Poziomy współczynnik skalowania, w procentach pierwotnego rozmiaru. Ujemne skalowanie powoduje odbicie. Domyślna wartość \\u2013 100 %. Odczyt **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Pionowy współczynnik skalowania, w procentach pierwotnego rozmiaru. Ujemne skalowanie powoduje odbicie. Domyślna wartość \\u2013 100 %. Odczyt **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | Kolor cienia. Domyślna wartość \\u2013 automatyczny czarny (zależny od motywu). Tylko do odczytu [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Poziomy kąt pochylania, w stopniach. Domyślna wartość \\u2013 0 \\u00B0. Odczyt **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Pionowy kąt pochylania, w stopniach. Domyślna wartość \\u2013 0 \\u00B0. Odczyt **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Wersja. Tylko do odczytu **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | Pobiera efektywne dane efektu Outer Shadow z zastosowanym dziedziczeniem. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Służy jako funkcja skrótu dla konkretnego typu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu ochronnego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje właściwie nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje właściwie nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\\![IsSmartPtr](../../system/issmartptr/)\\<T\\>::value, **bool**\\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\\&, T const\\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\\![IsSmartPtr](../../system/issmartptr/)\\<T\\>::value, **bool**\\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\\&, [String](../../system/string/) const\\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) promień, w punktach. Domyślna wartość \\u2013 0 pt. Zapis **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Kierunek cienia, w stopniach. Domyślna wartość \\u2013 0 \\u00B0 (od lewego do prawego). Zapis **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Odległość cienia od obiektu, w punktach. Domyślna wartość \\u2013 0 pt. Zapis **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Wyrównanie prostokąta. Domyślna wartość \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Zapis [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Wskazuje, czy cień obraca się razem z kształtem. Domyślna wartość \\u2013 true. Zapis **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Poziomy współczynnik skalowania, w procentach pierwotnego rozmiaru. Ujemne skalowanie powoduje odbicie. Domyślna wartość \\u2013 100 %. Zapis **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Pionowy współczynnik skalowania, w procentach pierwotnego rozmiaru. Ujemne skalowanie powoduje odbicie. Domyślna wartość \\u2013 100 %. Zapis **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Poziomy kąt pochylania, w stopniach. Domyślna wartość \\u2013 0 \\u00B0. Zapis **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Pionowy kąt pochylania, w stopniach. Domyślna wartość \\u2013 0 \\u00B0. Zapis **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu ochronnego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [IOuterShadow](../ioutershadow/)
* Klasa [IVisualEffect](../ivisualeffect/)
* Klasa [IPVIObject](../../aspose.slides/ipviobject/)
* Przestrzeń nazw [Aspose::Slides::Effects](../)
* Biblioteka [Aspose.Slides](../../)