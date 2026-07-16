---
title: GetParam()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le paramètre associé au nom qualifié par l'espace de noms.
type: docs
weight: 14
url: /fr/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) méthode

Renvoie le paramètre associé au nom qualifié par l'espace de noms.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Le nom du paramètre. [XsltArgumentList](../) ne vérifie pas que le nom fourni soit un nom local valide ; toutefois, le nom ne peut pas être **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | L'URI de l'espace de noms associé au paramètre. |

### Valeur de retour

L'objet paramètre ou **nullptr** s'il n'a pas été trouvé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [String](../../../system/string/)
* Classe [XsltArgumentList](../)
* Espace de noms [System::Xml::Xsl](../../)
* Bibliothèque [Aspose.Slides](../../../)