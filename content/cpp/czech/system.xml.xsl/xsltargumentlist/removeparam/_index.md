---
title: RemoveParam()
second_title: Aspose.Slides pro C++ API
description: Odstraní parametr z XsltArgumentList.
type: docs
weight: 66
url: /cs/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) metoda


Odstraní parametr z [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Název parametru, který se má odstranit. [XsltArgumentList](../) nekontroluje, zda předaný název je platný lokální název; název však nemůže být **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | URI jmenného prostoru parametru, který se má odstranit. |

### Návratová hodnota

Objekt parametru nebo **nullptr**, pokud nebyl nalezen.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [String](../../../system/string/)
* Třída [XsltArgumentList](../)
* Jmenný prostor [System::Xml::Xsl](../../)
* Knihovna [Aspose.Slides](../../../)