---
title: IOuterShadow
second_title: Aspose.Slides dla C++ – odniesienie API
description: Reprezentuje efekt zewnętrznego cienia.
type: docs
weight: 885
url: /pl/aspose.slides.effects/ioutershadow/
---
## IOuterShadow klasa


Reprezentuje efekt zewnętrznego cienia.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) promień, w punktach. Domyślna wartość \u2013 0 pt. Odczyt **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Kierunek cienia, w stopniach. Domyślna wartość \u2013 0 \u00B0 (od lewej do prawej). Odczyt **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Odległość cienia od obiektu, w punktach. Domyślna wartość \u2013 0 pt. Odczyt **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Wyrównanie prostokąta. Domyślna wartość \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Odczyt [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Określa, czy cień obraca się razem z kształtem. Domyślna wartość \u2013 true. Odczyt **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Poziomy współczynnik skali, w procentach oryginalnego rozmiaru. Ujemna skala powoduje odbicie. Domyślna wartość \u2013 100 %. Odczyt **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Pionowy współczynnik skali, w procentach oryginalnego rozmiaru. Ujemna skala powoduje odbicie. Domyślna wartość \u2013 100 %. Odczyt **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | Kolor cienia. Domyślna wartość \u2013 automatyczna czerń (zależna od motywu). Tylko do odczytu [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Poziomy kąt pochylenia, w stopniach. Domyślna wartość \u2013 0 \u00B0. Odczyt **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Pionowy kąt pochylenia, w stopniach. Domyślna wartość \u2013 0 \u00B0. Odczyt **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Pobiera efektywne dane z zastosowanym dziedziczeniem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczna metoda C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczne działanie operatora C# `is`. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę C# lock() . Wywołaj bezpośrednio lub użyj obiektu wartownika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) promień, w punktach. Domyślna wartość \u2013 0 pt. Zapisz **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Kierunek cienia, w stopniach. Domyślna wartość \u2013 0 \u00B0 (od lewej do prawej). Zapisz **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Odległość cienia od obiektu, w punktach. Domyślna wartość \u2013 0 pt. Zapisz **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Wyrównanie prostokąta. Domyślna wartość \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Zapisz [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Określa, czy cień obraca się razem z kształtem. Domyślna wartość \u2013 true. Zapisz **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Poziomy współczynnik skali, w procentach oryginalnego rozmiaru. Ujemna skala powoduje odbicie. Domyślna wartość \u2013 100 %. Zapisz **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Pionowy współczynnik skali, w procentach oryginalnego rozmiaru. Ujemna skala powoduje odbicie. Domyślna wartość \u2013 100 %. Zapisz **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Poziomy kąt pochylenia, w stopniach. Domyślna wartość \u2013 0 \u00B0. Zapisz **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Pionowy kąt pochylenia, w stopniach. Domyślna wartość \u2013 0 \u00B0. Zapisz **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia zmianę wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję niestandardowych obiektów do łańcucha znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie C# lock() . Wywołaj bezpośrednio lub użyj obiektu wartownika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [IImageTransformOperation](../iimagetransformoperation/)
* Klasa [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Przestrzeń nazw [Aspose::Slides::Effects](../)
* Biblioteka [Aspose.Slides](../../)