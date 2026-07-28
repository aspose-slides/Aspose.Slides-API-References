---
title: IColorFormat
second_title: Aspose.Slides dla C++ – referencja API
description: Reprezentuje kolor używany w prezentacji.
type: docs
weight: 1691
url: /pl/aspose.slides/icolorformat/
---
## IColorFormat klasa

Reprezentuje kolor używany w prezentacji.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | Kopiuje format koloru z \"color\". |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równe żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równe żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual **uint8_t** [get_B](./get_b/)() | Zwraca niebieski składnik koloru. Wszystkie transformacje koloru są ignorowane. Odczyt **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | Zwraca wynikowy kolor (z zastosowanymi wszystkimi transformacjami koloru). Ustawia kolory RGB i usuwa wszystkie transformacje koloru. Odczyt [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | Zwraca operację transformacji koloru zastosowaną do koloru o podanym indeksie. Odczyt/zapis [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | Zwraca kolekcję transformacji koloru zastosowanych do koloru. Tylko odczyt [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | Zwraca metodę definicji koloru. Odczyt [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | Zwraca niebieski składnik koloru. Wszystkie transformacje koloru są ignorowane. Odczyt **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | Zwraca zielony składnik koloru. Wszystkie transformacje koloru są ignorowane. Odczyt **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | Zwraca czerwony składnik koloru. Wszystkie transformacje koloru są ignorowane. Odczyt **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | Zwraca zielony składnik koloru. Wszystkie transformacje koloru są ignorowane. Odczyt **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | Zwraca składnik odcienia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | Zwraca składnik jasności koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | Zwraca domyślny kolor. Odczyt [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | Zwraca czerwony składnik koloru. Wszystkie transformacje koloru są ignorowane. Odczyt **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | Zwraca składnik nasycenia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | Zwraca kolor określony przez schemat kolorów. Odczyt [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | Zwraca kolor określony przez systemową tabelę kolorów. Odczyt [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia mieszanie niestandardowych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczne wywołanie C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_B](./set_b/)(**uint8_t**) | Ustawia niebieski składnik koloru. Wszystkie transformacje koloru są ignorowane. Zapis **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | Ustawia wynikowy kolor (z zastosowanymi wszystkimi transformacjami koloru). Ustawia kolory RGB i usuwa wszystkie transformacje koloru. Zapis [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | Ustawia operację transformacji koloru zastosowaną do koloru o podanym indeksie. Odczyt/zapis [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | Ustawia metodę definicji koloru. Zapis [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | Ustawia niebieski składnik koloru. Wszystkie transformacje koloru są ignorowane. Zapis **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | Ustawia zielony składnik koloru. Wszystkie transformacje koloru są ignorowane. Zapis **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | Ustawia czerwony składnik koloru. Wszystkie transformacje koloru są ignorowane. Zapis **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | Ustawia zielony składnik koloru. Wszystkie transformacje koloru są ignorowane. Zapis **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | Ustawia składnik odcienia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Zapis **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | Ustawia składnik jasności koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Zapis **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | Ustawia domyślny kolor. Zapis [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | Ustawia czerwony składnik koloru. Wszystkie transformacje koloru są ignorowane. Zapis **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | Ustawia składnik nasycenia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Zapis **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | Ustawia kolor określony przez schemat kolorów. Zapis [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | Ustawia kolor określony przez systemową tabelę kolorów. Zapis [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | Zwraca [System::String](../../system/string/) reprezentujący bieżący format koloru. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję niestandardowych obiektów do stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Zobacz także

* Klasa [IFillParamSource](../ifillparamsource/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)