---
title: ColorFormat
second_title: Aspose.Slides dla C++ – odniesienie API
description: Reprezentuje kolor używany w prezentacji.
type: docs
weight: 339
url: /pl/aspose.slides/colorformat/
---
## ColorFormat klasa

Represents a color used in a presentation.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## Metody

| Method | Description |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | Skopiuje format koloru z \"color\". |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Sprawdza równość z określonym obiektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **uint8_t** [get_B](./get_b/)() override | Zwraca niebieski składnik koloru. Wszystkie transformacje koloru są ignorowane. Odczyt **uint8_t**. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | Zwraca wynikowy kolor (z zastosowanymi wszystkimi transformacjami koloru). Ustawia kolory RGB i usuwa wszystkie transformacje koloru. Odczyt [System::Drawing::Color](../../system.drawing/color/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | Zwraca operację transformacji koloru zastosowaną do koloru o określonym indeksie. Odczyt/zapis [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | Zwraca kolekcję transformacji koloru zastosowanych do koloru. Tylko do odczytu [IColorOperationCollection](../icoloroperationcollection/). |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | Zwraca metodę definiowania koloru. Odczyt [Slides::ColorType](../colortype/). |
| **float** [get_FloatB](./get_floatb/)() override | Zwraca niebieski składnik koloru. Wszystkie transformacje koloru są ignorowane. Odczyt **float**. |
| **float** [get_FloatG](./get_floatg/)() override | Zwraca zielony składnik koloru. Wszystkie transformacje koloru są ignorowane. Odczyt **float**. |
| **float** [get_FloatR](./get_floatr/)() override | Zwraca czerwony składnik koloru. Wszystkie transformacje koloru są ignorowane. Odczyt **float**. |
| **uint8_t** [get_G](./get_g/)() override | Zwraca zielony składnik koloru. Wszystkie transformacje koloru są ignorowane. |
| **float** [get_Hue](./get_hue/)() override | Zwraca składnik odcienia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt **float**. |
| **float** [get_Luminance](./get_luminance/)() override | Zwraca składnik luminancji koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Zwraca obiekt Parent_Immediate. Tylko do odczytu [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Zwraca nadrzędny [IPresentationComponent](../ipresentationcomponent/). Tylko do odczytu [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | Zwraca predefiniowany kolor. Odczyt [Slides::PresetColor](../presetcolor/). |
| **uint8_t** [get_R](./get_r/)() override | Zwraca czerwony składnik koloru. Wszystkie transformacje koloru są ignorowane. Odczyt **uint8_t**. |
| **float** [get_Saturation](./get_saturation/)() override | Zwraca składnik nasycenia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt **float**. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | Zwraca kolor określony przez schemat kolorów. Odczyt [Slides::SchemeColor](../schemecolor/). |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | Zwraca kolor określony przez systemową tabelę kolorów. Odczyt [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązanej z obiektem. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Zwraca kod skrótu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczny do wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów własnych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_B](./set_b/)(**uint8_t**) override | Ustawia niebieski składnik koloru. Wszystkie transformacje koloru są ignorowane. Zapis **uint8_t**. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | Zwraca wynikowy kolor (z zastosowanymi wszystkimi transformacjami koloru). Ustawia kolory RGB i usuwa wszystkie transformacje koloru. Zapis [System::Drawing::Color](../../system.drawing/color/). |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | Ustawia operację transformacji koloru zastosowaną do koloru o określonym indeksie. Odczyt/zapis [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | Ustawia metodę definiowania koloru. Zapis [Slides::ColorType](../colortype/). |
| void [set_FloatB](./set_floatb/)(**float**) override | Ustawia niebieski składnik koloru. Wszystkie transformacje koloru są ignorowane. Zapis **float**. |
| void [set_FloatG](./set_floatg/)(**float**) override | Ustawia zielony składnik koloru. Wszystkie transformacje koloru są ignorowane. Zapis **float**. |
| void [set_FloatR](./set_floatr/)(**float**) override | Ustawia czerwony składnik koloru. Wszystkie transformacje koloru są ignorowane. Zapis **float**. |
| void [set_G](./set_g/)(**uint8_t**) override | Ustawia zielony składnik koloru. Wszystkie transformacje koloru są ignorowane. |
| void [set_Hue](./set_hue/)(**float**) override | Ustawia składnik odcienia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Zapis **float**. |
| void [set_Luminance](./set_luminance/)(**float**) override | Ustawia składnik luminancji koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Zapis **float**. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | Ustawia predefiniowany kolor. Zapis [Slides::PresetColor](../presetcolor/). |
| void [set_R](./set_r/)(**uint8_t**) override | Ustawia czerwony składnik koloru. Wszystkie transformacje koloru są ignorowane. Zapis **uint8_t**. |
| void [set_Saturation](./set_saturation/)(**float**) override | Ustawia składnik nasycenia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Zapis **float**. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | Ustawia kolor określony przez schemat kolorów. Zapis [Slides::SchemeColor](../schemecolor/). |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | Ustawia kolor określony przez systemową tabelę kolorów. Zapis [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | Zwraca [System::String](../../system/string/) reprezentujący bieżący format koloru. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję obiektów własnych do string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [PVIObject](../pviobject/)
* Klasa [IColorFormat](../icolorformat/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)