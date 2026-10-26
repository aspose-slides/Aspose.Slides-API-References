---
title: CreateMemoryStreamWrapper()
second_title: Référence API Aspose.Slides pour C++
description: Crée un wrapper MemoryStream.
type: docs
weight: 1
url: /fr/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() méthode

Crée un wrapper MemoryStream.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```

### Valeur de retour

Wrapper de flux pour l'interface COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) méthode

Crée un wrapper MemoryStream basé sur le tableau d'octets spécifié.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tableau d'octets **uint8_t**[] |

### Valeur de retour

Wrapper de flux pour l'interface COM [IStreamWrapper](../../istreamwrapper/)

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IStreamWrapper](../../istreamwrapper/)
* Classe [IStreamWrapperFactory](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)