---
title: ITextFrameFormat
second_title: Aspose.Slides dla C++ – referencja API
description: Zawiera właściwości formatowania TextFrame.
type: docs
weight: 4083
url: /pl/aspose.slides/itextframeformat/
---
## ITextFrameFormat klasa

Zawiera właściwości formatowania [TextFrame](../textframe/).

```cpp
class ITextFrameFormat : public virtual System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Zwraca pionowy tekst zakotwiczony w [TextFrame](../textframe/). Zobacz [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | Zwraca tryb automatycznego dopasowania tekstu. Zobacz [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | Jeśli [NullableBool::True](../nullablebool/) to tekst powinien być wyśrodkowany w poziomie w ramce. Zobacz [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Zwraca liczbę kolumn w obszarze tekstu. Wartość musi być liczbą dodatnią. W przeciwnym razie zostanie ustawiona na zero. Wartość 0 oznacza nieokreśloną wartość. Zobacz **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | Zwraca odstęp między kolumnami tekstu w obszarze tekstu (w punktach). Dotyczy tylko gdy istnieje więcej niż 1 kolumna. Wartość musi być liczbą dodatnią. W przeciwnym razie zostanie ustawiona na zero. Zobacz **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | Zwraca lub ustawia zachowanie tekstu poza sceną 3D. Zobacz **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Zwraca dolny margines (punkty) w [TextFrame](../textframe/). Zobacz **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Zwraca lewy margines (punkty) w [TextFrame](../textframe/). Zobacz **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Zwraca prawy margines (punkty) w [TextFrame](../textframe/). Zobacz **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Zwraca górny margines (punkty) w [TextFrame](../textframe/). Zobacz **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Określa niestandardowy obrót stosowany do tekstu w ramce. Jeśli nie jest podany, używany jest obrót powiązanego kształtu. Jeśli jest podany, zostaje zastosowany niezależnie od kształtu. Ostateczna wartość wizualnego obrotu tekstu podsumowana jest z tej właściwości i wstępnie określonego typu pionowego w właściwości TextVerticalType. Zobacz **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | Zwraca styl tekstu. Tylko do odczytu [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i niestandardowego kąta w właściwości RotationAngle. Zobacz [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Zwraca obiekt [ThreeDFormat](../threedformat/) reprezentujący właściwości efektu 3D dla tekstu. Tylko do odczytu [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | Pobiera kształt zawijania tekstu. Zobacz [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **Prawda** jeśli tekst jest zawijany w marginesach [TextFrame](../textframe/). Zobacz [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | Pobiera efektywne dane formatowania ramki tekstu z zastosowanym dziedziczeniem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, naprawdę, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, naprawdę, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | Ustawia pionowy tekst zakotwiczony w [TextFrame](../textframe/). Zapisz [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | Ustawia tryb automatycznego dopasowania tekstu. Zapisz [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | Jeśli [NullableBool::True](../nullablebool/) to tekst powinien być wyśrodkowany w poziomie w ramce. Zapisz [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | Ustawia liczbę kolumn w obszarze tekstu. Wartość musi być liczbą dodatnią. W przeciwnym razie zostanie ustawiona na zero. Wartość 0 oznacza nieokreśloną wartość. Zapisz **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | Ustawia odstęp między kolumnami tekstu w obszarze tekstu (w punktach). Dotyczy tylko gdy istnieje więcej niż 1 kolumna. Wartość musi być liczbą dodatnią. W przeciwnym razie zostanie ustawiona na zero. Zapisz **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | Zwraca lub ustawia zachowanie tekstu poza sceną 3D. Zapisz **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Ustawia dolny margines (punkty) w [TextFrame](../textframe/). Zapisz **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Ustawia lewy margines (punkty) w [TextFrame](../textframe/). Zapisz **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Ustawia prawy margines (punkty) w [TextFrame](../textframe/). Zapisz **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Ustawia górny margines (punkty) w [TextFrame](../textframe/). Zapisz **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Określa niestandardowy obrót stosowany do tekstu w ramce. Jeśli nie jest podany, używany jest obrót powiązanego kształtu. Jeśli jest podany, zostaje zastosowany niezależnie od kształtu. Ostateczna wartość wizualnego obrotu tekstu podsumowana jest z tej właściwości i wstępnie określonego typu pionowego w właściwości TextVerticalType. Zapisz **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i niestandardowego kąta w właściwości RotationAngle. Zapisz [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | Ustawia kształt zawijania tekstu. Zapisz [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **Prawda** jeśli tekst jest zawijany w marginesach [TextFrame](../textframe/). Zapisz [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala na zmianę wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)