---
title: SignedXml
second_title: Aspose.Slides dla C++ - dokumentacja API
description: "Używany do podpisywania i weryfikacji XML. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy wykonania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji."
type: docs
weight: 118
url: /pl/system.security.cryptography.xml/signedxml/
---
## SignedXml klasa

Used for XML signing and verification. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SignedXml : public System::Object
```

## Metody

| Method | Description |
| --- | --- |
| void [AddObject](./addobject/)([SharedPtr](../../system/sharedptr/)\<[DataObject](../dataobject/)\>) |  |
| void [AddReference](./addreference/)([SharedPtr](../../system/sharedptr/)\<[Reference](../reference/)\>) |  |
| **bool** [CheckSignature](./checksignature/)() |  |
| **bool** [CheckSignature](./checksignature/)([SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\>) |  |
| **bool** [CheckSignature](./checksignature/)([SharedPtr](../../system/sharedptr/)\<[X509Certificates::X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/)\>, **bool**) |  |
| **bool** [CheckSignatureReturningKey](./checksignaturereturningkey/)([SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\>\&) |  |
| void [ComputeSignature](./computesignature/)() |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [SharedPtr](../../system/sharedptr/)\<[KeyInfo](../keyinfo/)\> [get_KeyInfo](./get_keyinfo/)() |  |
| [String](../../system/string/) [get_SignatureLength](./get_signaturelength/)() |  |
| [String](../../system/string/) [get_SignatureMethod](./get_signaturemethod/)() |  |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_SignatureValue](./get_signaturevalue/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[SignedInfo](../signedinfo/)\> [get_SignedInfo](./get_signedinfo/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\> [get_SigningKey](./get_signingkey/)() |  |
| [String](../../system/string/) [get_SigningKeyName](./get_signingkeyname/)() |  |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlElement](../../system.xml/xmlelement/)\> [GetIdElement](./getidelement/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlDocument](../../system.xml/xmldocument/)\>, [String](../../system/string/)) |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlElement](../../system.xml/xmlelement/)\> [GetXml](./getxml/)() |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# `is`. |
| void [LoadXml](./loadxml/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlElement](../../system.xml/xmlelement/)\>) |  |
| void [Lock](../../system/object/lock/)() | Implementuje zachowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_KeyInfo](./set_keyinfo/)([SharedPtr](../../system/sharedptr/)\<[KeyInfo](../keyinfo/)\>) |  |
| void [set_SigningKey](./set_signingkey/)([SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\>) |  |
| void [set_SigningKeyName](./set_signingkeyname/)([String](../../system/string/)) |  |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
|  [SignedXml](./signedxml/)() |  |
|  [SignedXml](./signedxml/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlDocument](../../system.xml/xmldocument/)\>) |  |
|  [SignedXml](./signedxml/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlElement](../../system.xml/xmlelement/)\>) |  |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Pola

| Field | Description |
| --- | --- |
| static [XmlDecryptionTransformUrl](./xmldecryptiontransformurl/) |  |
| static [XmlDsigBase64TransformUrl](./xmldsigbase64transformurl/) |  |
| static [XmlDsigC14NTransformUrl](./xmldsigc14ntransformurl/) |  |
| static [XmlDsigC14NWithCommentsTransformUrl](./xmldsigc14nwithcommentstransformurl/) |  |
| static [XmlDsigCanonicalizationUrl](./xmldsigcanonicalizationurl/) |  |
| static [XmlDsigCanonicalizationWithCommentsUrl](./xmldsigcanonicalizationwithcommentsurl/) |  |
| static [XmlDsigDSAUrl](./xmldsigdsaurl/) |  |
| static [XmlDsigEnvelopedSignatureTransformUrl](./xmldsigenvelopedsignaturetransformurl/) |  |
| static [XmlDsigExcC14NTransformUrl](./xmldsigexcc14ntransformurl/) |  |
| static [XmlDsigExcC14NWithCommentsTransformUrl](./xmldsigexcc14nwithcommentstransformurl/) |  |
| static [XmlDsigHMACSHA1Url](./xmldsighmacsha1url/) |  |
| static [XmlDsigMinimalCanonicalizationUrl](./xmldsigminimalcanonicalizationurl/) |  |
| static [XmlDsigNamespaceUrl](./xmldsignamespaceurl/) |  |
| static [XmlDsigRSASHA1Url](./xmldsigrsasha1url/) |  |
| static [XmlDsigRSASHA256Url](./xmldsigrsasha256url/) |  |
| static [XmlDsigRSASHA384Url](./xmldsigrsasha384url/) |  |
| static [XmlDsigRSASHA512Url](./xmldsigrsasha512url/) |  |
| static [XmlDsigSHA1Url](./xmldsigsha1url/) |  |
| static [XmlDsigSHA256Url](./xmldsigsha256url/) |  |
| static [XmlDsigSHA384Url](./xmldsigsha384url/) |  |
| static [XmlDsigSHA512Url](./xmldsigsha512url/) |  |
| static [XmlDsigXPathTransformUrl](./xmldsigxpathtransformurl/) |  |
| static [XmlDsigXsltTransformUrl](./xmldsigxslttransformurl/) |  |
| static [XmlLicenseTransformUrl](./xmllicensetransformurl/) |  |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Security::Cryptography::Xml](../)
* Biblioteka [Aspose.Slides](../../)