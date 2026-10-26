---
title: ReadElementString()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Lit un élément contenant uniquement du texte. Cependant, il est recommandé d'utiliser la méthode XmlReader::ReadElementContentAsString à la place, car elle offre un moyen plus simple de gérer cette opération."
type: docs
weight: 859
url: /fr/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() méthode

Lit un élément contenant uniquement du texte. Cependant, il est recommandé d’utiliser la méthode [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) à la place, car elle offre un moyen plus simple de gérer cette opération.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### Valeur de retour

Le texte contenu dans l'element qui a été lu. Une chaine vide si l'element est vide.

## XmlReader::ReadElementString(String) méthode

Vérifie que la valeur [XmlReader::get_Name](../get_name/) de l'element trouvé correspond à la chaîne donnée avant de lire un élément contenant uniquement du texte. Cependant, il est recommandé d’utiliser la méthode [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) à la place, car elle offre un moyen plus simple de gérer cette opération.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom à vérifier. |

### Valeur de retour

Le texte contenu dans l'element qui a été lu. Une chaine vide si l'element est vide.

## XmlReader::ReadElementString(String, String) méthode

Vérifie que les valeurs [XmlReader::get_LocalName](../get_localname/) et [XmlReader::get_NamespaceURI](../get_namespaceuri/) de l'element trouvé correspondent aux chaînes données avant de lire un élément contenant uniquement du texte. Cependant, il est recommandé d’utiliser la méthode [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) à la place, car elle offre un moyen plus simple de gérer cette opération.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Le nom local à vérifier. |
| ns | [String](../../../system/string/) | L'URI d'espace de noms à vérifier. |

### Valeur de retour

Le texte contenu dans l'element qui a été lu. Une chaine vide si l'element est vide.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)