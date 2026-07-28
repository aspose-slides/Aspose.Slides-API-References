---
title: RemoveParam()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Usuwa parametr z XsltArgumentList.
type: docs
weight: 66
url: /pl/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) metoda

Usuwa parametr z [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nazwa parametru do usunięcia. [XsltArgumentList](../) nie sprawdza, czy podana nazwa jest prawidłową nazwą lokalną; jednak nazwa nie może być **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | Identyfikator URI przestrzeni nazw parametru do usunięcia. |

### Wartość zwracana

Obiekt parametru lub **nullptr**, jeśli nie został znaleziony.

## Zobacz również

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [String](../../../system/string/)
* Klasa [XsltArgumentList](../)
* Przestrzeń nazw [System::Xml::Xsl](../../)
* Biblioteka [Aspose.Slides](../../../)