---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Reprezentuje menedżera, który kontroluje zachowanie stopki slajdu notatek głównych, placeholderów daty-czasu, numeru strony oraz wszystkich podrzędnych placeholderów. Podrzędne placeholdery oznaczają, że placeholdery są zawarte na zależnych slajdach notatek. Zależne slajdy notatek używają i zależą od slajdu notatek głównych.
type: docs
weight: 2900
url: /pl/aspose.slides/imasternotesslideheaderfootermanager/
---
## IMasterNotesSlideHeaderFooterManager klasa

Represents manager which holds behavior of the master notes slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending notes slides. Depending notes slides use and depend on master notes slide.

```cpp
class IMasterNotesSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseHandoutNotesSlideHeaderFooterManag
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | Zwraca wartość wskazującą, że placeholder daty-czasu jest obecny. Read**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | Zwraca wartość wskazującą, że placeholder stopki jest obecny. Read **bool**. |
| virtual **bool** [get_IsHeaderVisible](../ibasehandoutnotesslideheaderfootermanag/get_isheadervisible/)() | Zwraca wartość wskazującą, że placeholder nagłówka jest obecny. Read **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | Zwraca wartość wskazującą, że placeholder numeru strony jest obecny. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Zwraca strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | Ustawia tekst w placeholderze daty-czasu slajdu notatek głównych oraz we wszystkich podrzędnych placeholderach daty-czasu. Podrzędne placeholdery oznaczają, że placeholdery są zawarte na zależnych slajdach notatek. Zależne slajdy notatek używają i zależą od slajdu notatek głównych. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | Zmienia widoczność placeholdera daty-czasu slajdu notatek głównych oraz wszystkich podrzędnych placeholderów daty-czasu. Podrzędne placeholdery oznaczają, że placeholdery są zawarte na zależnych slajdach notatek. Zależne slajdy notatek używają i zależą od slajdu notatek głównych. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | Ustawia tekst w placeholderze daty-czasu slajdu. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | Zmienia widoczność placeholdera daty-czasu slajdu. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | Ustawia tekst w placeholderze stopki slajdu notatek głównych oraz we wszystkich podrzędnych placeholderach stopki. Podrzędne placeholdery oznaczają, że placeholdery są zawarte na zależnych slajdach notatek. Zależne slajdy notatek używają i zależą od slajdu notatek głównych. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | Zmienia widoczność placeholdera stopki slajdu notatek głównych oraz wszystkich podrzędnych placeholderów stopki. Podrzędne placeholdery oznaczają, że placeholdery są zawarte na zależnych slajdach notatek. Zależne slajdy notatek używają i zależą od slajdu notatek głównych. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | Ustawia tekst w placeholderze stopki slajdu. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | Zmienia widoczność placeholdera stopki slajdu. |
| virtual void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) | Ustawia tekst w placeholderze nagłówka slajdu notatek głównych oraz we wszystkich podrzędnych placeholderach nagłówka. Podrzędne placeholdery oznaczają, że placeholdery są zawarte na zależnych slajdach notatek. Zależne slajdy notatek używają i zależą od slajdu notatek głównych. |
| virtual void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) | Zmienia widoczność placeholdera nagłówka slajdu notatek głównych oraz wszystkich podrzędnych placeholderów nagłówka. Podrzędne placeholdery oznaczają, że placeholdery są zawarte na zależnych slajdach notatek. Zależne slajdy notatek używają i zależą od slajdu notatek głównych. |
| virtual void [SetHeaderText](../ibasehandoutnotesslideheaderfootermanag/setheadertext/)([System::String](../../system/string/)) | Ustawia tekst w placeholderze nagłówka slajdu. |
| virtual void [SetHeaderVisibility](../ibasehandoutnotesslideheaderfootermanag/setheadervisibility/)(**bool**) | Zmienia widoczność placeholdera nagłówka slajdu. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | Zmienia widoczność placeholdera numeru strony slajdu notatek głównych oraz wszystkich podrzędnych placeholderów numeru strony. Podrzędne placeholdery oznaczają, że placeholdery są zawarte na zależnych slajdach notatek. Zależne slajdy notatek używają i zależą od slajdu notatek głównych. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | Zmienia widoczność placeholdera numeru strony slajdu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-th argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Zwraca bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [IBaseHandoutNotesSlideHeaderFooterManag](../ibasehandoutnotesslideheaderfootermanag/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)