---
title: SetLicense()
second_title: Référence de l'API Aspose.Slides pour C++
description: Licence le composant.
type: docs
weight: 14
url: /fr/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) méthode

Licence le composant.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Peut être un nom de fichier complet ou court ou le nom d'une ressource incorporée. Utilisez une chaîne vide pour passer en mode d'évaluation. |

## Remarques

Essaye de trouver la licence aux emplacements suivants :

1. Chemin explicite.
2. Le dossier de l'assembly du composant.
3. Le dossier de l'assembly appelant du client.
4. Le dossier de l'assembly d'entrée.
5. Une ressource incorporée dans l'assembly appelant du client.

**Note :** Sur le .NET Compact Framework, essaie de trouver la licence uniquement dans les emplacements suivants :

1. Chemin explicite.
2. Une ressource incorporée dans l'assembly appelant du client.

Dans cet exemple, une tentative sera effectuée pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée puis dans les ressources incorporées de l'assembly appelant. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) méthode

Licence le composant.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flux contenant la licence. |

## Remarques

Utilisez cette méthode pour charger une licence à partir d'un flux.

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [License](../)
* Classe [Stream](../../../system.io/stream/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)