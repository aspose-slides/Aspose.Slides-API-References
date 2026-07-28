---
title: XmlValidatingReader()
second_title: Aspose.Slides dla C++ API Reference
description: Inicjalizuje nową instancję klasy XmlValidatingReader, która waliduje zawartość zwróconą przez podany XmlReader.
type: docs
weight: 430
url: /pl/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlValidatingReader](../), która waliduje zawartość zwróconą przez podany [XmlReader](../../xmlreader/).

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | [XmlReader](../../xmlreader/) do odczytu podczas walidacji. Obecna implementacja obsługuje tylko [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlValidatingReader](../) przy użyciu określonych wartości.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Ciąg znaków zawierający fragment XML do parsowania. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Typ XmlNodeType fragmentu XML. Decyduje również, co ciąg fragmentu może zawierać (zobacz tabelę poniżej). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) w którym ma zostać przetworzony fragment XML. Obejmuje to [NameTable](../../nametable/) do użycia, kodowanie, zakres przestrzeni nazw, bieżący **xml:lang** i zakres **xml:space**. |

## Uwagi



Poniższa tabela wymienia prawidłowe wartości dla **fragType** oraz sposób, w jaki czytnik analizuje każdy z różnych typów węzłów. 

| XmlNodeType | Fragment może zawierać |
| --- | --- |
| Element| Dowolna prawidłowa zawartość elementu (np. dowolna kombinacja elementów, komentarzy, instrukcji przetwarzania, cdata, tekstu i odwołań do encji). |
| [Attribute](../../../system/attribute/)| Wartość atrybutu (część wewnątrz cudzysłowów). |
| Document| Zawartość całego dokumentu XML; wymusza reguły na poziomie dokumentu. |


## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) konstruktor


Inicjalizuje nową instancję klasy [XmlValidatingReader](../) przy użyciu określonych wartości.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień zawierający fragment XML do przetworzenia. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Typ XmlNodeType fragmentu XML. Decyduje, co fragment może zawierać (zobacz tabelę poniżej). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) w którym ma zostać przetworzony fragment XML. Obejmuje to [XmlNameTable](../../xmlnametable/) do użycia, kodowanie, zakres przestrzeni nazw, bieżący **xml:lang** i zakres **xml:space**. |

## Uwagi



Poniższa tabela wymienia prawidłowe wartości dla **fragType** oraz sposób, w jaki czytnik analizuje każdy z różnych typów węzłów. 

| XmlNodeType | Fragment może zawierać |
| --- | --- |
| Element| Dowolna prawidłowa zawartość elementu (np. dowolna kombinacja elementów, komentarzy, instrukcji przetwarzania, cdata, tekstu i odwołań do encji). |
| [Attribute](../../../system/attribute/)| Wartość atrybutu (część wewnątrz cudzysłowów). |
| Document| Zawartość całego dokumentu XML; wymusza reguły na poziomie dokumentu. |


## Zobacz także

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlValidatingReader](../)
* Class [String](../../../system/string/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)