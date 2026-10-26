---
title: TextFrameFormat
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zawiera właściwości formatTextFrameFormatting obiektu TextFrame.
type: docs
weight: 5461
url: /pl/aspose.slides/textframeformat/
---
## TextFrameFormat klasa

Zawiera właściwości formatTextFrameFormatting [TextFrame](../textframe/).

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## Metody

| Metoda | Opis |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Porównuje z określonym obiektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typów referencyjnych w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | Zwraca pionowy tekst kotwicy w [TextFrame](../textframe/). Odczytaj [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | Zwraca tryb automatycznego dopasowywania tekstu. Odczytaj [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | Jeśli [NullableBool::True](../nullablebool/), tekst powinien być wyśrodkowany w ramce w poziomie. Odczytaj [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Zwraca liczbę kolumn w obszarze tekstu. Wartość musi być liczbą dodatnią. W przeciwnym razie zostanie ustawiona na zero. Wartość 0 oznacza nieokreśloną wartość. Odczytaj **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | Zwraca odstęp między kolumnami tekstu w obszarze tekstu (w punktach). Powinno mieć zastosowanie tylko gdy jest więcej niż 1 kolumna. Wartość musi być dodatnia. W przeciwnym razie zostanie ustawiona na zero. Odczytaj **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | Pobiera informację o utrzymaniu płaskości tekstu nawet po zastosowaniu efektu 3-D Rotation. Odczytaj **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Zwraca dolny margines (punkty) w [TextFrame](../textframe/). Odczytaj **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Zwraca lewy margines (punkty) w [TextFrame](../textframe/). Odczytaj **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Zwraca prawy margines (punkty) w [TextFrame](../textframe/). Odczytaj **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Zwraca górny margines (punkty) w [TextFrame](../textframe/). Odczytaj **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Zwraca obiekt Parent_Immediate. Tylko do odczytu [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Zwraca nadrzędny [IPresentationComponent](../ipresentationcomponent/). Tylko do odczytu [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | Określa własny kąt obrotu stosowany do tekstu w obrębie ramki. Jeśli nie jest określony, używany jest obrót powiązanego kształtu. Jeśli jest określony, jest stosowany niezależnie od kształtu. Oznacza to, że kształt może mieć zastosowany obrót oprócz obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowuje tę właściwość i wstępnie zdefiniowany typ pionowy w właściwości TextVerticalType. Odczytaj **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowuje tę właściwość i własny kąt w właściwości RotationAngle. Odczytaj [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Zwraca obiekt [ThreeDFormat](../threedformat/) reprezentujący właściwości efektu 3D dla tekstu. Tylko do odczytu [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | Pobiera kształt zawijania tekstu. Odczytaj [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True** jeśli tekst jest zawijany przy marginesach [TextFrame](../textframe/). Odczytaj [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | Pobiera efektywne dane formatowania ramki tekstu z zastosowanym dziedziczeniem. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Zwraca kod hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | Ustawia pionowy tekst kotwicy w [TextFrame](../textframe/). Zapisz [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | Ustawia tryb automatycznego dopasowywania tekstu. Zapisz [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | Jeśli [NullableBool::True](../nullablebool/), tekst powinien być wyśrodkowany w ramce w poziomie. Zapisz [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | Ustawia liczbę kolumn w obszarze tekstu. Wartość musi być dodatnia. W przeciwnym razie zostanie ustawiona na zero. Wartość 0 oznacza nieokreśloną wartość. Zapisz **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | Ustawia odstęp między kolumnami tekstu w obszarze tekstu (w punktach). Powinno mieć zastosowanie tylko gdy jest więcej niż 1 kolumna. Wartość musi być dodatnia. W przeciwnym razie zostanie ustawiona na zero. Zapisz **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | Ustawia utrzymanie płaskości tekstu nawet po zastosowaniu efektu 3-D Rotation. Zapisz **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Ustawia dolny margines (punkty) w [TextFrame](../textframe/). Zapisz **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Ustawia lewy margines (punkty) w [TextFrame](../textframe/). Zapisz **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Ustawia prawy margines (punkty) w [TextFrame](../textframe/). Zapisz **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Ustawia górny margines (punkty) w [TextFrame](../textframe/). Zapisz **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | Określa własny kąt obrotu stosowany do tekstu w obrębie ramki. Jeśli nie jest określony, używany jest obrót powiązanego kształtu. Jeśli jest określony, jest stosowany niezależnie od kształtu. Oznacza to, że kształt może mieć zastosowany obrót oprócz obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowuje tę właściwość i wstępnie zdefiniowany typ pionowy w właściwości TextVerticalType. Zapisz **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowuje tę właściwość i własny kąt w właściwości RotationAngle. Zapisz [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | Ustawia kształt zawijania tekstu. Zapisz [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True** jeśli tekst jest zawijany przy marginesach [TextFrame](../textframe/). Zapisz [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia zmianę wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [TextFrameFormat](./textframeformat/)() | Inicjalizuje nową instancję klasy [TextFrameFormat](./). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję obiektów niestandardowych na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Patrz także

* Klasa [PVIObject](../pviobject/)
* Klasa [ITextFrameFormat](../itextframeformat/)
* Klasa [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)