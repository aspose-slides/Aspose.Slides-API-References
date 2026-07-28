---
title: INormalViewProperties
second_title: Aspose.Slides for C++ – Referencja API
description: "Reprezentuje właściwości normalnego widoku. Normalny widok składa się z trzech obszarów treści: samego slajdu, bocznego obszaru treści oraz dolnego obszaru treści."
type: docs
weight: 2978
url: /pl/aspose.slides/inormalviewproperties/
---
## INormalViewProperties klasa


Reprezentuje właściwości normalnego widoku. Normalny widok składa się z trzech obszarów treści: samego slajdu, bocznego obszaru treści i dolnego obszaru treści.

```cpp
class INormalViewProperties : public virtual System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [SplitterBarStateType](../splitterbarstatetype/) [get_HorizontalBarState](./get_horizontalbarstate/)() | Określa stan, w którym powinna być wyświetlana pozioma belka podziału. Pozioma belka podziału oddziela slajd od obszaru treści pod slajdem. |
| virtual **bool** [get_PreferSingleView](./get_prefersingleview/)() | Określa, czy użytkownik preferuje wyświetlanie jednego obszaru treści na pełnym oknie zamiast standardowego normalnego widoku z trzema obszarami treści. Jeśli włączone, aplikacja może wybrać wyświetlenie jednego z obszarów treści w całym oknie. Odczyt **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredLeft](./get_restoredleft/)() | Ten element określa rozmiar bocznego obszaru treści normalnego widoku, gdy region ma zmienny przywrócony rozmiar (nie zminimalizowany ani zmaksymalizowany). Tylko do odczytu [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredTop](./get_restoredtop/)() | Ten element określa rozmiar górnego obszaru slajdu normalnego widoku, gdy region ma zmienny przywrócony rozmiar (nie zminimalizowany ani zmaksymalizowany). Tylko do odczytu [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| virtual **bool** [get_ShowOutlineIcons](./get_showoutlineicons/)() | Określa, czy aplikacja powinna wyświetlać ikony podczas wyświetlania treści zarysów w którymkolwiek z obszarów treści trybu normalnego widoku. Odczyt **bool**. |
| virtual **bool** [get_SnapVerticalSplitter](./get_snapverticalsplitter/)() | Określa, czy pionowa belka podziału powinna przyciągać do stanu zminimalizowanego, gdy boczny region jest wystarczająco mały. Odczyt **bool**. |
| virtual [SplitterBarStateType](../splitterbarstatetype/) [get_VerticalBarState](./get_verticalbarstate/)() | Określa stan, w którym powinna być wyświetlana pionowa belka podziału. Pionowa belka podziału oddziela slajd od bocznego obszaru treści. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_HorizontalBarState](./set_horizontalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) | Określa stan, w którym powinna być wyświetlana pozioma belka podziału. Pozioma belka podziału oddziela slajd od obszaru treści pod slajdem. |
| virtual void [set_PreferSingleView](./set_prefersingleview/)(**bool**) | Określa, czy użytkownik preferuje wyświetlanie jednego obszaru treści na pełnym oknie zamiast standardowego normalnego widoku z trzema obszarami treści. Jeśli włączone, aplikacja może wybrać wyświetlenie jednego z obszarów treści w całym oknie. Zapis **bool**. |
| virtual void [set_ShowOutlineIcons](./set_showoutlineicons/)(**bool**) | Określa, czy aplikacja powinna wyświetlać ikony podczas wyświetlania treści zarysu w którymkolwiek z obszarów treści trybu normalnego widoku. Zapis **bool**. |
| virtual void [set_SnapVerticalSplitter](./set_snapverticalsplitter/)(**bool**) | Określa, czy pionowa belka podziału powinna przyciągać do stanu zminimalizowanego, gdy boczny region jest wystarczająco mały. Zapis **bool**. |
| virtual void [set_VerticalBarState](./set_verticalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) | Określa stan, w którym powinna być wyświetlana pionowa belka podziału. Pionowa belka podziału oddziela slajd od bocznego obszaru treści. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączenie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)