---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une nouvelle partie XML personnalisée.
type: docs
weight: 14
url: /fr/aspose.slides/icustomxmlpartcollection/add/
---
## ICustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) méthode


Ajoute une nouvelle partie XML personnalisée.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData)=0
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Les données XML de la nouvelle partie à ajouter. |

### Valeur de retour

Partie XML personnalisée créée.

## ICustomXmlPartCollection::Add(System::String) méthode


Ajoute une nouvelle partie XML personnalisée.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::String xmlString)=0
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | La chaîne XML de la nouvelle partie à ajouter. |

### Valeur de retour

Partie XML personnalisée créée.

## ICustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) méthode


Ajoute une nouvelle partie XML personnalisée.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream)=0
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Le flux d’entrée contenant les données XML de la nouvelle partie à ajouter. |

### Valeur de retour

Partie XML personnalisée créée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICustomXmlPart](../../icustomxmlpart/)
* Classe [ICustomXmlPartCollection](../)
* Classe [String](../../../system/string/)
* Classe [Stream](../../../system.io/stream/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)