---
title: GetParam()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwraca parametr powiązany z nazwą kwalifikowaną przestrzeni nazw.
type: docs
weight: 14
url: /pl/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) method

Zwraca parametr powiązany z nazwą kwalifikowaną przestrzeni nazw.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nazwa parametru. [XsltArgumentList](../) nie sprawdza, czy podana nazwa jest prawidłową nazwą lokalną; jednak nazwa nie może być **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | Identyfikator URI przestrzeni nazw powiązany z parametrem. |

### Wartość zwracana

Obiekt parametru lub **nullptr**, jeśli nie został znaleziony.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [String](../../../system/string/)
* Klasa [XsltArgumentList](../)
* Przestrzeń nazw [System::Xml::Xsl](../../)
* Biblioteka [Aspose.Slides](../../../)