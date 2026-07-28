---
title: XmlSchemaInference
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy schemat XML Schema Definition Language (XSD) na podstawie dokumentu XML. Klasa XmlSchemaInference nie może być dziedziczona.
type: docs
weight: 508
url: /pl/system.xml.schema/xmlschemainference/
---
## XmlSchemaInference klasa

Infers an XML [Schema](../) Definition Language (XSD) schema from an XML document. The [XmlSchemaInference](./) class cannot be inherited.

```cpp
class XmlSchemaInference : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if\<![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [XmlSchemaInference::InferenceOption](./inferenceoption/) [get_Occurrence](./get_occurrence/)() | Zwraca wartość [XmlSchemaInference::InferenceOption](./inferenceoption/), która wpływa na deklaracje wystąpień schematu wywnioskowane z dokumentu XML. |
| [XmlSchemaInference::InferenceOption](./inferenceoption/) [get_TypeInference](./get_typeinference/)() | Zwraca wartość [XmlSchemaInference::InferenceOption](./inferenceoption/), która wpływa na typy wywnioskowane z dokumentu XML. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogia wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\> [InferSchema](./inferschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | Tworzy schemat XML [Schema](../) Definition Language (XSD) na podstawie dokumentu XML zawartego w określonym obiekcie [XmlReader](../../system.xml/xmlreader/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\> [InferSchema](./inferschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\>) | Tworzy schemat XML [Schema](../) Definition Language (XSD) z dokumentu XML zawartego w określonym obiekcie [XmlReader](../../system.xml/xmlreader/), i udoskonala wywnioskowany schemat przy użyciu istniejącego schematu w określonym obiekcie [XmlSchemaSet](../xmlschemaset/) o tym samym docelowym przestrzeni nazw. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogia operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [set_Occurrence](./set_occurrence/)([XmlSchemaInference::InferenceOption](./inferenceoption/)) | Ustawia wartość [XmlSchemaInference::InferenceOption](./inferenceoption/), która wpływa na deklaracje wystąpień schematu wywnioskowane z dokumentu XML. |
| void [set_TypeInference](./set_typeinference/)([XmlSchemaInference::InferenceOption](./inferenceoption/)) | Ustawia wartość [XmlSchemaInference::InferenceOption](./inferenceoption/), która wpływa na typy wywnioskowane z dokumentu XML. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do ciągu znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [XmlSchemaInference](./xmlschemainference/)() | Inicjalizuje nową instancję klasy [XmlSchemaInference](./). |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Wyliczenia

| Wyliczenie | Opis |
| --- | --- |
| [InferenceOption](./inferenceoption/) | Wpływa na informacje o wystąpieniach i typach wywnioskowane przez klasę [XmlSchemaInference](./) dla elementów i atrybutów w dokumencie XML. |

## Definicje typów

| Alias typu | Opis |
| --- | --- |
| [Ptr](./ptr/) | Alias dla współdzielonego wskaźnika do instancji tej klasy. |

## Uwagi



Obiekty tej klasy powinny być tworzone wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie działania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika przy przekazywaniu go jako argument do funkcji. 

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Xml::Schema](../)
* Biblioteka [Aspose.Slides](../../)