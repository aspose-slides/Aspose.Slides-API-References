---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une nouvelle partie xml personnalisée.
type: docs
weight: 53
url: /fr/aspose.slides/customxmlpartcollection/add/
---
## CustomXmlPartCollection::Add(System::String) méthode

Ajoute une nouvelle partie xml personnalisée.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::String xmlString) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | La chaîne xml de la nouvelle partie à ajouter. |

### Valeur de retour

Partie xml personnalisée créée.

## CustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) méthode

Ajoute une nouvelle partie xml personnalisée.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Les données xml de la nouvelle partie à ajouter. |

### Valeur de retour

Partie xml personnalisée créée.

## CustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) méthode

Ajoute une nouvelle partie xml personnalisée.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Le flux d'entrée contenant les données xml de la nouvelle partie à ajouter. |

### Valeur de retour

Partie xml personnalisée créée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICustomXmlPart](../../icustomxmlpart/)
* Classe [String](../../../system/string/)
* Classe [CustomXmlPartCollection](../)
* Classe [Stream](../../../system.io/stream/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)