---
title: CreateFileStreamWrapper()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un FileStream avec le chemin spécifié et le mode de création.
type: docs
weight: 14
url: /fr/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) méthode

Crée un FileStream avec le chemin spécifié et le mode de création.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Nom de fichier [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Mode de fichier [System::IO::FileMode](../../../system.io/filemode/) |

### Valeur de retour

Wrapper de flux pour l'interface COM [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) méthode

Crée un FileStream avec le chemin spécifié, le mode de création et l'autorisation de lecture/écriture.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Nom de fichier [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Mode de fichier [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | Accès au fichier [System::IO::FileAccess](../../../system.io/fileaccess/) |

### Valeur de retour

Wrapper de flux pour l'interface COM [IStreamWrapper](../../istreamwrapper/)

## Voir aussi

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IStreamWrapper](../../istreamwrapper/)
* Classe [String](../../../system/string/)
* Classe [IStreamWrapperFactory](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)