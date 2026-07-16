---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides pour C++ Référence de l'API
description: Spécifie comment traiter la valeur de temps lors de la conversion entre une chaîne et DateTime.
type: docs
weight: 781
url: /fr/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode énum

Spécifie comment traiter la valeur de temps lors de la conversion entre une chaîne et [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Local | 0 | Traite comme l'heure locale. Si l'objet [DateTime](../../system/datetime/) représente une Heure Universelle Coordonnée (UTC), il est converti à l'heure locale. |
| Utc | 1 | Traite comme un UTC. Si l'objet [DateTime](../../system/datetime/) représente l'heure locale, il est converti en UTC. |
| Unspecified | 2 | Traite comme l'heure locale si un [DateTime](../../system/datetime/) est converti en chaîne. Si une chaîne est convertie en [DateTime](../../system/datetime/), convertissez en heure locale si un fuseau horaire est spécifié. |
| RoundtripKind | 3 | Les informations de fuseau horaire doivent être conservées lors de la conversion. |

## Voir aussi

* Espace de noms [System::Xml](../)
* Bibliothèque [Aspose.Slides](../../)