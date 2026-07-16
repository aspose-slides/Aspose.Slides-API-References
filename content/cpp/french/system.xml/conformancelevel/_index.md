---
title: ConformanceLevel
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie le niveau de vérification d'entrée ou de sortie effectué par les objets XmlReader et XmlWriter.
type: docs
weight: 625
url: /fr/system.xml/conformancelevel/
---
## ConformanceLevel enum

Spécifie le niveau de vérification d'entrée ou de sortie effectué par les objets [XmlReader](../xmlreader/) et [XmlWriter](../xmlwriter/).

```cpp
enum class ConformanceLevel
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | 0 | L'objet [XmlReader](../xmlreader/) ou [XmlWriter](../xmlwriter/) détecte automatiquement si une vérification au niveau du document ou du fragment doit être effectuée, et réalise la vérification appropriée. Si vous encapsulez un autre objet [XmlReader](../xmlreader/) ou [XmlWriter](../xmlwriter/), l'objet externe n'effectue aucune vérification de conformité supplémentaire. La vérification de conformité est laissée à l'objet sous-jacent. |
| Fragment | 1 | Les données XML sont un [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities), tel que défini par le W3C. Ce niveau de conformité représente un document XML qui peut ne pas avoir d'élément racine mais qui est autrement bien formé. Ce niveau de vérification garantit que le flux lu ou écrit peut être consommé par n'importe quel processeur en tant que [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities). |
| Document | 2 | Les données XML sont conformes aux règles d'un [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) bien formé, tel que défini par le W3C. Ce niveau de vérification garantit que le flux lu ou écrit peut être consommé par n'importe quel processeur en tant que [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed). |

## Voir aussi

* Espace de noms [System::Xml](../)
* Bibliothèque [Aspose.Slides](../../)