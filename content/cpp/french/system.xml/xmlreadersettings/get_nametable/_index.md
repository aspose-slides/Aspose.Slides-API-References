---
title: get_NameTable()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le XmlNameTable utilisé pour les comparaisons de chaînes atomisées.
type: docs
weight: 1
url: /fr/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() méthode

Renvoie le [XmlNameTable](../../xmlnametable/) utilisé pour les comparaisons de chaînes atomisées.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```

### Valeur de retour

Le [XmlNameTable](../../xmlnametable/) qui stocke toutes les chaînes atomisées utilisées par toutes les instances [XmlReader](../../xmlreader/) créées en utilisant cet objet [XmlReaderSettings](../). La valeur par défaut est **nullptr**. L'instance [XmlReader](../../xmlreader/) créée utilisera un nouveau [NameTable](../../nametable/) vide si cette valeur est **nullptr**.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNameTable](../../xmlnametable/)
* Classe [XmlReaderSettings](../)
* Espace de noms [System::Xml](../../)
* Library [Aspose.Slides](../../../)