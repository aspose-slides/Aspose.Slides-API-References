---
title: XmlNodeType
second_title: Odwołanie do API Aspose.Slides dla C++
description: Określa typ węzła.
type: docs
weight: 833
url: /pl/system.xml/xmlnodetype/
---
## XmlNodeType enum

Określa typ węzła.

```cpp
enum class XmlNodeType
```

### Values

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| None | 0 | Zwracane jest przez [XmlReader](../xmlreader/), jeśli metoda **Read** nie została wywołana. |
| Element | 1 | Element (na przykład **<item>**). |
| Attribute | 2 | Atrybut (na przykład **id='123'**). |
| Text | 3 | Zawartość tekstowa węzła. Węzeł [XmlNodeType::Text](./) nie może mieć żadnych węzłów potomnych. Może pojawić się jako węzeł potomny węzłów [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./) i [XmlNodeType::EntityReference](./). |
| CDATA | 4 | Sekcja CDATA (na przykład **my escaped text**). |
| EntityReference | 5 | Odniesienie do encji (na przykład **&num;**). |
| Entity | 6 | Deklaracja encji (na przykład **<!ENTITY...>**). |
| ProcessingInstruction | 7 | Instrukcja przetwarzania (na przykład **<?pi test?>**). |
| Comment | 8 | Komentarz (na przykład ****). |
| Document | 9 | Obiekt dokumentu, który jako korzeń drzewa dokumentu zapewnia dostęp do całego dokumentu XML. |
| DocumentType | 10 | Deklaracja typu dokumentu, wskazywana przez następujący znacznik (na przykład **<!DOCTYPE...>**). |
| DocumentFragment | 11 | Fragment dokumentu. |
| Notation | 12 | Notacja w deklaracji typu dokumentu (na przykład **<!NOTATION...>**). |
| Whitespace | 13 | Biała spacja pomiędzy znacznikami. |
| SignificantWhitespace | 14 | Biała spacja pomiędzy znacznikami w modelu mieszanej zawartości lub biała spacja wewnątrz zakresu **xml:space="preserve"**. |
| EndElement | 15 | Znacznik kończący element (na przykład ****). |
| EndEntity | 16 | Zwracane, gdy [XmlReader](../xmlreader/) dochodzi do końca zamiany encji w wyniku wywołania [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | Deklaracja XML (na przykład **<?xml version='1.0'?>**). Węzeł [XmlNodeType::XmlDeclaration](./) musi być pierwszym węzłem w dokumencie. Nie może mieć potomków. Jest potomkiem węzła [XmlNodeType::Document](./). Może mieć atrybuty podające informację o wersji i kodowaniu. |

## See Also

* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)