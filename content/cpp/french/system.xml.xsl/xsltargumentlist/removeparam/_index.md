---
title: RemoveParam()
second_title: Référence API Aspose.Slides pour C++
description: Supprime le paramètre de XsltArgumentList.
type: docs
weight: 66
url: /fr/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) méthode


Supprime le paramètre de [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Le nom du paramètre à supprimer. [XsltArgumentList](../) ne vérifie pas que le nom passé soit un nom local valide ; toutefois, le nom ne peut pas être **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | L'URI d'espace de noms du paramètre à supprimer. |

### Valeur de retour

L'objet paramètre ou **nullptr** si aucun n'a été trouvé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)