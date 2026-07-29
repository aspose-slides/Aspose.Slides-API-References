---
title: ToString()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar strängvärdet för XmlQualifiedName.
type: docs
weight: 79
url: /sv/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const metod

Returnerar strängvärdet för [XmlQualifiedName](../).

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```

### Returvärde

Strängvärdet för [XmlQualifiedName](../) i formatet **namespace:localname**. Om objektet inte har någon namnrymd definierad, returnerar denna metod bara det lokala namnet.

## XmlQualifiedName::ToString(const String\&, const String\&) metod

Returnerar strängvärdet för [XmlQualifiedName](../).

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Namnet på objektet. |
| ns | const [String](../../../system/string/)\& | Namnrymden för objektet. |

### Returvärde

Strängvärdet för [XmlQualifiedName](../) i formatet **namespace:localname**. Om objektet inte har någon namnrymd definierad, returnerar denna metod bara det lokala namnet.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlQualifiedName](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)