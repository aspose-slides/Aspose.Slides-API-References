---
title: XmlConvert
second_title: Aspose.Slides dla C++ – odniesienie API
description: Koduje i dekoduje nazwy XML oraz udostępnia metody konwertowania między typami w czasie wykonywania a typami języka definicji schematu XML (XSD). Przy konwertowaniu typów danych zwracane wartości są niezależne od ustawień regionalnych.
type: docs
weight: 157
url: /pl/system.xml/xmlconvert/
---
## XmlConvert klasa

Koduje i dekoduje nazwy XML oraz udostępnia metody konwertowania między typami w czasie wykonywania a typami języka definicji XML [Schema](../../system.xml.schema/) (XSD). Przy konwertowaniu typów danych zwracane wartości są niezależne od ustawień regionalnych.

```cpp
class XmlConvert : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | Dekoduje nazwę. Ta metoda wykonuje odwrotność metod XmlConvert::EncodeName(String) i XmlConvert::EncodeLocalName(String). |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | Konwertuje nazwę na prawidłową lokalną nazwę XML. |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | Konwertuje nazwę na prawidłową nazwę XML. |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | Weryfikuje, czy nazwa jest prawidłowa zgodnie ze specyfikacją XML. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych podwójnej precyzji w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji skojarzoną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | Sprawdza, czy przekazany znak jest prawidłowym typem znaku niebędącego dwukropkiem. |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | Zwraca przekazany znak, jeśli znak w argumencie jest prawidłowym znakiem publicznego identyfikatora, w przeciwnym razie **nullptr**. |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | Sprawdza, czy przekazany znak jest prawidłowym typem znaku początkowego nazwy. |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | Sprawdza, czy przekazany znak jest prawidłowym znakiem białej spacji XML. |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | Sprawdza, czy przekazany znak jest prawidłowym znakiem XML. |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | Sprawdza, czy przekazana para znaków surrogatowych jest prawidłowym znakiem XML. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia zmianę wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | Konwertuje [String](../../system/string/) na odpowiednik [Boolean](../../system/boolean/). |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | Konwertuje [String](../../system/string/) na odpowiednik [Byte](../../system/byte/). |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | Konwertuje [String](../../system/string/) na odpowiednik [Char](../../system/char/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | Konwertuje [String](../../system/string/) na odpowiednik [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Konwertuje [String](../../system/string/) na odpowiednik [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Konwertuje [String](../../system/string/) na odpowiednik [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Konwertuje [String](../../system/string/) na [DateTime](../../system/datetime/) przy użyciu określonego XmlDateTimeSerializationMode. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | Konwertuje dostarczony [String](../../system/string/) na odpowiednik [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Konwertuje dostarczony [String](../../system/string/) na odpowiednik [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Konwertuje dostarczony [String](../../system/string/) na odpowiednik [DateTimeOffset](../../system/datetimeoffset/). |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | Konwertuje [String](../../system/string/) na odpowiednik [Decimal](../../system/decimal/). |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | Konwertuje [String](../../system/string/) na odpowiednik [Double](../../system/double/). |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | Konwertuje [String](../../system/string/) na odpowiednik [Guid](../../system/guid/). |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | Konwertuje [String](../../system/string/) na odpowiednik [Int16](../../system/int16/). |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | Konwertuje [String](../../system/string/) na odpowiednik [Int32](../../system/int32/). |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | Konwertuje [String](../../system/string/) na odpowiednik [Int64](../../system/int64/). |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | Konwertuje [String](../../system/string/) na odpowiednik [SByte](../../system/sbyte/). |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | Konwertuje [String](../../system/string/) na odpowiednik [Single](../../system/single/). |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | Konwertuje [Boolean](../../system/boolean/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | Konwertuje [Char](../../system/char/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | Konwertuje [Decimal](../../system/decimal/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | Konwertuje [SByte](../../system/sbyte/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | Konwertuje [Int16](../../system/int16/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | Konwertuje [Int32](../../system/int32/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | Konwertuje [Int64](../../system/int64/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | Konwertuje [Byte](../../system/byte/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | Konwertuje [UInt16](../../system/uint16/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | Konwertuje [UInt32](../../system/uint32/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | Konwertuje [UInt64](../../system/uint64/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | Konwertuje [Single](../../system/single/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | Konwertuje [Double](../../system/double/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | Konwertuje [TimeSpan](../../system/timespan/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | Konwertuje [DateTime](../../system/datetime/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | Konwertuje [DateTime](../../system/datetime/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Konwertuje [DateTime](../../system/datetime/) na [String](../../system/string/) używając określonego XmlDateTimeSerializationMode. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | Konwertuje dostarczony [DateTimeOffset](../../system/datetimeoffset/) na [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | Konwertuje dostarczony [DateTimeOffset](../../system/datetimeoffset/) na [String](../../system/string/) w określonym formacie. |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | Konwertuje [Guid](../../system/guid/) na [String](../../system/string/). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do string. |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | Konwertuje [String](../../system/string/) na odpowiednik [TimeSpan](../../system/timespan/). |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | Konwertuje [String](../../system/string/) na odpowiednik [UInt16](../../system/uint16/). |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | Konwertuje [String](../../system/string/) na odpowiednik [UInt32](../../system/uint32/). |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | Konwertuje [String](../../system/string/) na odpowiednik [UInt64](../../system/uint64/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | Weryfikuje, czy nazwa jest prawidłowa zgodnie z zaleceniami W3C Extended Markup Language. |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | Weryfikuje, czy nazwa jest prawidłowym **NCName** zgodnie z zaleceniami W3C Extended Markup Language. **NCName** to nazwa, która nie może zawierać dwukropka. |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | Weryfikuje, czy ciąg jest prawidłowym NMTOKEN zgodnie z zaleceniami W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes. |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | Zwraca przekazany ciąg, jeśli wszystkie znaki w argumencie są prawidłowymi znakami publicznego identyfikatora. |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | Weryfikuje, czy ciąg jest prawidłowym tokenem zgodnie z zaleceniami W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes. |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | Zwraca przekazany ciąg, jeśli wszystkie znaki w argumencie są prawidłowymi znakami białej spacji. |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | Zwraca przekazany ciąg, jeśli wszystkie znaki i pary znaków surrogatowych w argumencie są prawidłowymi znakami XML, w przeciwnym razie wyrzucany jest XmlException z informacją o pierwszym nieprawidłowym znaku. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Typedefy

| Typedef | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla współdzielonego wskaźnika do instancji tej klasy. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)