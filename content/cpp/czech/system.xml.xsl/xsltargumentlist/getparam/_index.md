---
title: GetParam()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vrací parametr spojený s názvem kvalifikovaným jmenným prostorem.
type: docs
weight: 14
url: /cs/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) metoda

Vrací parametr spojený s názvem kvalifikovaným jmenným prostorem.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Název parametru. [XsltArgumentList](../) nekontroluje, zda je předaný název platným lokálním názvem; nicméně název nesmí být **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | URI jmenného prostoru spojený s parametrem. |

### Návratová hodnota

Objekt parametru nebo **nullptr**, pokud nebyl nalezen.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [String](../../../system/string/)
* Třída [XsltArgumentList](../)
* Jmenný prostor [System::Xml::Xsl](../../)
* Knihovna [Aspose.Slides](../../../)