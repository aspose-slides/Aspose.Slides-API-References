---
title: CultureInfo
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: "Zbiór wartości i algorytmów zależnych od kultury. Operacje ustawiania są dostępne tylko w obiektach nie-tylko-do-odczytu. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go do funkcji jako argument."
type: docs
weight: 53
url: /pl/system.globalization/cultureinfo/
---
## CultureInfo klasa

Zbiór wartości i algorytmów zależnych od kultury. Operacje ustawiania są dostępne tylko w obiektach nie-tylko-do-odczytu. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argumentu.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [ClearCachedData](./clearcacheddata/)() | Odświeża pamięć podręczną informacji o kulturze. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Klonuje informacje o kulturze. |
| static [CultureInfoPtr](../cultureinfoptr/) [CreateSpecificCulture](./createspecificculture/)(const [String](../../system/string/)\&) | Tworzy kulturę na podstawie nazwy. |
| explicit  [CultureInfo](./cultureinfo/)(int) | Informacje RTTI. |
|  [CultureInfo](./cultureinfo/)(int, **bool**) | Konstruktor. |
| explicit  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&, **bool**) | Konstruktor. |
|  [CultureInfo](./cultureinfo/)(std::nullptr_t) | Zawsze zgłasza ArgumentNullException. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Porównuje obiekty. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [CalendarPtr](../calendarptr/) [get_Calendar](./get_calendar/)() const | Pobiera kalendarz używany przez kulturę. |
| virtual [CompareInfoPtr](../compareinfoptr/) [get_CompareInfo](./get_compareinfo/)() const | Pobiera porównywacz ciągów zgodny z regułami kultury. |
| [CultureTypes](../culturetypes/) [get_CultureTypes](./get_culturetypes/)() const | Pobiera bitową kombinację typów kultury opisujących bieżącą kulturę. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentCulture](./get_currentculture/)() | Pobiera kulturę ustawioną dla bieżącego wątku. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentUICulture](./get_currentuiculture/)() | Pobiera kulturę UI bieżącego wątku. |
| virtual [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_DateTimeFormat](./get_datetimeformat/)() const | Pobiera informacje o formacie daty. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | Pobiera domyślną kulturę w bieżącej domenie aplikacji. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | Pobiera domyślną kulturę UI w bieżącej domenie aplikacji. |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | Pobiera wyświetlaną nazwę kultury. |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | Pobiera angielską nazwę kultury. |
| [String](../../system/string/) [get_IetfLanguageTag](./get_ietflanguagetag/)() const | Pobiera nazwę RFC 4646 języka. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InstalledUICulture](./get_installeduiculture/)() | Pobiera kulturę zainstalowaną w systemie operacyjnym. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InvariantCulture](./get_invariantculture/)() | Pobiera kulturę invariant. |
| virtual **bool** [get_IsNeutralCulture](./get_isneutralculture/)() const | Sprawdza, czy kultura jest neutralna. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Sprawdza, czy obiekt kultury jest tylko do odczytu. |
| virtual int [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | Pobiera aktywny identyfikator ustawień regionalnych wejścia. |
| virtual int [get_LCID](./get_lcid/)() const | Pobiera identyfikator kultury. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | Pobiera nazwę kultury. |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | Pobiera natywną nazwę kultury. |
| virtual [NumberFormatInfoPtr](../numberformatinfoptr/) [get_NumberFormat](./get_numberformat/)() const | Pobiera informacje o formacie liczb. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[CalendarPtr](../calendarptr/)\> [get_OptionalCalendars](./get_optionalcalendars/)() const | Lista kalendarzy, które mogą być użyte z tą kulturą. |
| virtual [CultureInfoPtr](../cultureinfoptr/) [get_Parent](./get_parent/)() const | Pobiera kulturę nadrzędną. |
| virtual [TextInfoPtr](../textinfoptr/) [get_TextInfo](./get_textinfo/)() const | Pobiera parametry tekstu używane przez kulturę. |
| virtual [String](../../system/string/) [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | Pobiera trzy-literowy kod języka ISO 639-2. |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | Pobiera trzy-literowy kod języka zdefiniowany w API [Windows](../../system.windows/). |
| virtual [String](../../system/string/) [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | Pobiera dwuliterową nazwę języka ISO powiązaną z kulturą. |
| **bool** [get_UseUserOverride](./get_useuseroverride/)() const | Zwraca flagę wskazującą, czy [CultureInfo](./) używa ustawień kultury wybranych przez użytkownika. |
| [CultureInfoPtr](../cultureinfoptr/) [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | Pobiera alternatywną kulturę odpowiednią dla aplikacji konsolowych. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&) | Pobiera kulturę po jej nazwie. To samo co CreateSpecificCulture. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Pobiera kulturę po jej nazwie. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(**int32_t**) | Pobiera kulturę po identyfikatorze. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const [String](../../system/string/)\&) | Przestarzałe. Pobiera obiekt [CultureInfo](./) tylko do odczytu na podstawie podanego znacznika języka RFC 4646. |
| static [ArrayPtr](../../system/arrayptr/)\<[CultureInfoPtr](../cultureinfoptr/)\> [GetCultures](./getcultures/)([CultureTypes](../culturetypes/)) | Pobiera kultury należące do określonych typów. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Pobiera obiekt formatu dla określonego typu. |
| int [GetHashCode](./gethashcode/)() const override | Zwraca kod skrótu obiektu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| **bool** [IsInherited](./isinherited/)() const | Zwraca flagę dziedziczoności. FOR INTERNAL USE. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [CultureInfo](./)\& [operator=](./operator_equal/)(const [CultureInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| **bool** [operator==](./operator_equal_equal/)(const [CultureInfo](./)\&) const | Porównuje parametry kultury. |
| static [CultureInfoPtr](../cultureinfoptr/) [ReadOnly](./readonly/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Pobiera wersję tylko do odczytu kultury. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje obiekt typu wartości z nullptr przez referencję. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string oraz nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| static void [set_CurrentCulture](./set_currentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Ustawia kulturę dla bieżącego wątku. |
| static void [set_CurrentUICulture](./set_currentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Ustawia kulturę UI bieżącego wątku. |
| virtual void [set_DateTimeFormat](./set_datetimeformat/)([DateTimeFormatInfoPtr](../datetimeformatinfoptr/)) | Ustawia informacje o formacie daty. |
| static void [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Ustawia domyślną kulturę w bieżącej domenie aplikacji. |
| static void [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | Ustawia domyślną kulturę UI w bieżącej domenie aplikacji. |
| virtual void [set_NumberFormat](./set_numberformat/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Pobiera informacje o formacie liczb. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Inkrementuje licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Dekrementuje i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Konwertuje kulturę na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Inkrementuje licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Dekrementuje licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Klasa [IFormatProvider](../../system/iformatprovider/)
* Klasa [ICloneable](../../system/icloneable/)
* Przestrzeń nazw [System::Globalization](../)
* Biblioteka [Aspose.Slides](../../)