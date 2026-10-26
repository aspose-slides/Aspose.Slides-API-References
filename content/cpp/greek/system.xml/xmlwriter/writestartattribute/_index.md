---
title: WriteStartAttribute()
second_title: Aspose.Slides για C++ API Αναφορά
description: Γράφει την αρχή ενός χαρακτηριστικού με το καθορισμένο τοπικό όνομα και το URI του χώρου ονομάτων.
type: docs
weight: 144
url: /el/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String\&, const String\&) μέθοδος

Γράφει την αρχή ενός χαρακτηριστικού με το καθορισμένο τοπικό όνομα και το URI του χώρου ονομάτων.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Το τοπικό όνομα του χαρακτηριστικού. |
| ns | const [String](../../../system/string/)\& | Το URI του χώρου ονομάτων του χαρακτηριστικού. |

## XmlWriter::WriteStartAttribute(const String\&, const String\&, const String\&) μέθοδος

Όταν αντικαθίσταται σε μια κληρονομούσα κλάση, γράφει την αρχή ενός χαρακτηριστικού με το καθορισμένο πρόθεμα, το τοπικό όνομα και το URI του χώρου ονομάτων.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Το πρόθεμα του χώρου ονομάτων του χαρακτηριστικού. |
| localName | const [String](../../../system/string/)\& | Το τοπικό όνομα του χαρακτηριστικού. |
| ns | const [String](../../../system/string/)\& | Το URI του χώρου ονομάτων για το χαρακτηριστικό. |

## XmlWriter::WriteStartAttribute(const String\&) μέθοδος

Γράφει την αρχή ενός χαρακτηριστικού με το καθορισμένο τοπικό όνομα.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Το τοπικό όνομα του χαρακτηριστικού. |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlWriter](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)