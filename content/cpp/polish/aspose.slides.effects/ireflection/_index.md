---
title: IReflection
second_title: Aspose.Slides dla C++ - referencja API
description: Reprezentuje efekt odbicia.
type: docs
weight: 937
url: /pl/aspose.slides.effects/ireflection/
---
## IReflection klasa

Represents a reflection effect.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
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
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) promień. Odczyt **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Kierunek odbicia. Odczyt **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Odległość odbicia. Odczyt **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | Określa końcową pozycję (wzdłuż gradientu alfa) wartości końcowego alfa (procenty). Odczyt **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | Końcowa nieprzezroczystość odbicia. (procenty). Odczyt **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | Określa kierunek przesunięcia odbicia. (kąt). Odczyt **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Wyrównanie prostokąta. Odczyt [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Określa, czy odbicie powinno obracać się wraz z kształtem, gdy kształt jest obrócony. Odczyt **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Określa poziomy współczynnik skalowania, negatywne skalowanie powoduje odbicie. (procenty) Odczyt **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Określa pionowy współczynnik skalowania, negatywne skalowanie powoduje odbicie. (procenty) Odczyt **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Określa poziomy kąt pochylenia. Odczyt **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Określa pionowy kąt pochylenia. Odczyt **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | Określa początkową pozycję (wzdłuż gradientu alfa) wartości początkowego alfa (procenty). Odczyt **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | Początkowa nieprzezroczystość odbicia. (procenty). Odczyt **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Pobiera skuteczne dane z zastosowanym dziedziczeniem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza wspólny licznik referencji o podaną wartość. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) promień. Zapisz **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Kierunek odbicia. Zapisz **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Odległość odbicia. Zapisz **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | Określa końcową pozycję (wzdłuż gradientu alfa) wartości końcowego alfa (procenty). Zapisz **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | Końcowa nieprzezroczystość odbicia. (procenty). Zapisz **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | Określa kierunek przesunięcia odbicia. (kąt). Zapisz **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Wyrównanie prostokąta. Zapisz [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Określa, czy odbicie powinno obracać się wraz z kształtem, gdy kształt jest obrócony. Zapisz **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Określa poziomy współczynnik skalowania, negatywne skalowanie powoduje odbicie. (procenty) Zapisz **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Określa pionowy współczynnik skalowania, negatywne skalowanie powoduje odbicie. (procenty) Zapisz **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Określa poziomy kąt pochylenia. Zapisz **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Określa pionowy kąt pochylenia. Zapisz **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | Określa początkową pozycję (wzdłuż gradientu alfa) wartości początkowego alfa (procenty). Zapisz **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | Początkowa nieprzezroczystość odbicia. (procenty). Zapisz **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustaw n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [IImageTransformOperation](../iimagetransformoperation/)
* Klasa [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Przestrzeń nazw [Aspose::Slides::Effects](../)
* Biblioteka [Aspose.Slides](../../)