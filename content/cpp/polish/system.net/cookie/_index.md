---
title: Cookie
second_title: Aspose.Slides dla C++ – odniesienie do API
description: "Reprezentuje ciasteczko HTTP. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy wykonania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go do funkcji jako argument."
type: docs
weight: 1
url: /pl/system.net/cookie/
---
## Klasa Cookie

Reprezentuje ciasteczko HTTP. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy wykonania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania go do funkcji jako argument.

```cpp
class Cookie : public System::Object
```

## Metody

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | Tworzy kopię bieżącej instancji. |
| [Cookie](./cookie/)() | Tworzy nową instancję. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | Tworzy nową instancję. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Tworzy nową instancję. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Tworzy nową instancję. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | Pobiera wartość atrybutu 'Comment'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | Pobiera wartość atrybutu 'CommentURL'. |
| **bool** [get_Discard](./get_discard/)() const | Pobiera wartość atrybutu 'Discard'. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | Pobiera wartość atrybutu 'Domain'. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | Pobiera wartość wskazującą, czy domena jest niejawna. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | Zwraca klucz domeny. |
| **bool** [get_Expired](./get_expired/)() | Pobiera wartość wskazującą, czy ciasteczko wygasło. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | Pobiera wartość atrybutu 'Expires'. |
| **bool** [get_HttpOnly](./get_httponly/)() const | Pobiera wartość atrybutu 'HttpOnly'. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Pobiera nazwę ciasteczka. |
| [String](../../system/string/) [get_Path](./get_path/)() const | Pobiera wartość atrybutu 'Path'. |
| **bool** [get_Plain](./get_plain/)() const | Zwraca wartość wskazującą, czy specyfikacja ciasteczka jest 'Plain'. |
| [String](../../system/string/) [get_Port](./get_port/)() const | Pobiera wartość atrybutu 'Port'. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | Zwraca zbiór wartości atrybutu 'Port'. |
| **bool** [get_Secure](./get_secure/)() const | Pobiera wartość atrybutu 'Secure'. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | Zwraca czas utworzenia ciasteczka. |
| [String](../../system/string/) [get_Value](./get_value/)() const | Pobiera wartość ciasteczka. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | Pobiera specyfikację ciasteczka. |
| **int32_t** [get_Version](./get_version/)() const | Pobiera wartość atrybutu '[Version](../../system/version/)'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | Ta metoda jest wywoływana przez inne metody w celu ustawienia nazwy metody. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | Ustawia wartość atrybutu 'Comment'. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Ustawia wartość atrybutu 'CommentURL'. |
| void [set_Discard](./set_discard/)(**bool**) | Ustawia wartość atrybutu 'Discard'. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | Ustawia wartość atrybutu 'Domain'. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | Ustawia wartość wskazującą, czy domena jest niejawna. |
| void [set_Expired](./set_expired/)(**bool**) | Ustawia wartość wskazującą, czy ciasteczko wygasło. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | Ustawia wartość atrybutu 'Expires'. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | Ustawia wartość atrybutu 'HttpOnly'. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Ustawia nazwę ciasteczka. |
| void [set_Path](./set_path/)([String](../../system/string/)) | Ustawia wartość atrybutu 'Path'. |
| void [set_Port](./set_port/)([String](../../system/string/)) | Ustawia wartość atrybutu 'Port'. |
| void [set_Secure](./set_secure/)(**bool**) | Ustawia wartość atrybutu 'Secure'. |
| void [set_Value](./set_value/)([String](../../system/string/)) | Ustawia wartość ciasteczka. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | Ustawia specyfikację ciasteczka. |
| void [set_Version](./set_version/)(**int32_t**) | Ustawia wartość atrybutu '[Version](../../system/version/)'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera aktualną wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | Serializuje bieżącą instancję do reprezentacji łańcucha znaków. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na łańcuch znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | Weryfikuje i ustawia domyślne wartości atrybutów. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Pola

| Pole | Opis |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | Nazwa atrybutu 'Comment'. |
| static [CommentUrlAttributeName](./commenturlattributename/) | Nazwa atrybutu 'CommentURL'. |
| static [DiscardAttributeName](./discardattributename/) | Nazwa atrybutu 'Discard'. |
| static [DomainAttributeName](./domainattributename/) | Nazwa atrybutu 'Domain'. |
| static [EqualsLiteral](./equalsliteral/) | Separator używany do oddzielania nazwy i wartości atrybutu. |
| static [ExpiresAttributeName](./expiresattributename/) | Nazwa atrybutu 'Expires'. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | Nazwa atrybutu 'HttpOnly'. |
| static [MaxAgeAttributeName](./maxageattributename/) | Nazwa atrybutu 'Max-Age'. |
| static [MaxSupportedVersion](./maxsupportedversion/) | Maksymalna obsługiwana wersja. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | Reprezentacja łańcuchowa maksymalnej obsługiwanej wersji. |
| static [PathAttributeName](./pathattributename/) | Nazwa atrybutu 'Path'. |
| static [PortAttributeName](./portattributename/) | Nazwa atrybutu 'Port'. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | Tablica zawierająca delimitery dla wartości atrybutu 'Port'. |
| static [QuotesLiteral](./quotesliteral/) | Symbol używany do otaczania części atrybutu. |
| static [ReservedToName](./reservedtoname/) | Wartość zarezerwowana dla nazwy ciasteczka. |
| static [ReservedToValue](./reservedtovalue/) | Wartość zarezerwowana dla wartości ciasteczka. |
| static [SecureAttributeName](./secureattributename/) | Nazwa atrybutu 'Secure'. |
| static [SeparatorLiteral](./separatorliteral/) | Separator atrybutów. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | Prefiks nazw specjalnych atrybutów. |
| static [VersionAttributeName](./versionattributename/) | Nazwa atrybutu '[Version](../../system/version/)'. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Net](../)
* Biblioteka [Aspose.Slides](../../)