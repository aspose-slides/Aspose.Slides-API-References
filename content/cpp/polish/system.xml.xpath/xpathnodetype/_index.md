---
title: XPathNodeType
second_title: Aspose.Slides dla C++ – odniesienie API
description: Definiuje typy węzłów XPath, które mogą być zwrócone z klasy XPathNavigator.
type: docs
weight: 157
url: /pl/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum

Definiuje [XPath](../) typy węzłów, które mogą być zwrócone z klasy [XPathNavigator](../xpathnavigator/).

```cpp
enum class XPathNodeType
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Root | 0 | Węzeł główny dokumentu XML lub drzewa węzłów. |
| Element | 1 | Element, np. **<element>**. |
| Attribute | 2 | Atrybut, np. **id='123'**. |
| Namespace | 3 | Przestrzeń nazw, np. **xmlns=\"namespace\"**. |
| Text | 4 | Zawartość tekstowa węzła. Odpowiednik modelu dokumentu [Object](../../system/object/) (DOM) [Text](../../system.text/) i typów węzłów CDATA. Zawiera co najmniej jeden znak. |
| SignificantWhitespace | 5 | Węzeł zawierający znaki białych odstępów i atrybut **xml:space** ustawiony na **preserve**. |
| Whitespace | 6 | Węzeł zawierający wyłącznie znaki białych odstępów i nieposiadający istotnych białych odstępów. Znaki białych odstępów to **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | Instrukcja przetwarzania, np. **<?pi test?>**. Nie obejmuje ona deklaracji XML, które nie są widoczne dla klasy [XPathNavigator](../xpathnavigator/). |
| Comment | 8 | Komentarz, np. ****. |
| All | 9 | Dowolny z typów węzłów XPathNodeType. |

## Zobacz także

* Przestrzeń nazw [System::Xml::XPath](../)
* Biblioteka [Aspose.Slides](../../)