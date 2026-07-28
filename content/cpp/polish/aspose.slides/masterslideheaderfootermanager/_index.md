---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Reprezentuje menedżera, który utrzymuje zachowanie stopki slajdu głównego, zastępników daty i czasu, numeru strony oraz wszystkich podrzędnych zastępników. Podrzędne zastępniki oznaczają, że zastępniki znajdują się na zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają i zależą od slajdu głównego.
type: docs
weight: 4499
url: /pl/aspose.slides/masterslideheaderfootermanager/
---
## MasterSlideHeaderFooterManager klasa

Reprezentuje menedżera, który utrzymuje zachowanie stopki slajdu głównego, zastępników daty i czasu, numeru strony oraz wszystkich podrzędnych zastępców. Podrzędne zastępniki oznaczają, że zastępniki są zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają oraz zależą od slajdu głównego.

```cpp
class MasterSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                       public Aspose::Slides::IMasterSlideHeaderFooterManager
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
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | Odczytuje wartość wskazującą, że obecny jest zastępnik daty i czasu. Odczyt**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | Odczytuje wartość wskazującą, że obecny jest zastępnik stopki. Odczyt **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | Odczytuje wartość wskazującą, że obecny jest zastępnik numeru strony. Odczyt**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o określoną wartość. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | Ustawia tekst w zastępniku daty i czasu slajdu głównego oraz we wszystkich podrzędnych zastępnikach daty i czasu. Podrzędne zastępniki oznaczają, że zastępniki są zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają oraz zależą od slajdu głównego. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | Zmienia widoczność zastępników daty i czasu slajdu głównego oraz wszystkich podrzędnych zastępników daty i czasu. Podrzędne zastępniki oznaczają, że zastępniki są zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają oraz zależą od slajdu głównego. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | Ustawia tekst w zastępniku daty i czasu slajdu. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | Zmienia widoczność zastępnika daty i czasu slajdu. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | Ustawia tekst w zastępniku stopki slajdu głównego oraz we wszystkich podrzędnych zastępcach stopki. Podrzędne zastępniki oznaczają, że zastępniki są zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają oraz zależą od slajdu głównego. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | Zmienia widoczność zastępników stopki slajdu głównego oraz wszystkich podrzędnych zastępników stopki. Podrzędne zastępniki oznaczają, że zastępniki są zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają oraz zależą od slajdu głównego. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | Ustawia tekst w zastępniku stopki slajdu. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | Zmienia widoczność zastępnika stopki slajdu. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | Zmienia widoczność zastępników numeru strony slajdu głównego oraz wszystkich podrzędnych zastępników numeru strony. Podrzędne zastępniki oznaczają, że zastępniki są zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają oraz zależą od slajdu głównego. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | Zmienia widoczność zastępnika numeru strony slajdu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach do trybu słabego. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na łańcuch znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* Klasa [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)