---
title: LoadingStreamBehavior
second_title: Référence API Aspose.Slides pour C++
description: "Le System::IO::Stream transmis à une méthode est considéré comme un Binary Large Object (BLOB) (voir la description de IBlobManagementOptions). Les valeurs de cette énumération identifient comment le System::IO::Stream doit être traité lorsqu'il est transmis à la méthode. En fonction des exigences, différentes décisions peuvent être prises pour fournir le comportement le plus efficace."
type: docs
weight: 6735
url: /fr/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

Le [System::IO::Stream](../../system.io/stream/) transmis à une méthode est considéré comme un Binary Large Object (BLOB) (voir [IBlobManagementOptions](../iblobmanagementoptions/) description). Les valeurs de cette enumeration identifient comment le [System::IO::Stream](../../system.io/stream/) doit être traité lorsqu'il est transmis à la méthode. En fonction des exigences, différentes décisions peuvent être prises pour fournir le comportement le plus efficace.

```cpp
enum class LoadingStreamBehavior
```

### Valeurs

| Name | Value | Description |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | Le flux sera lu jusqu'à la fin puis libéré - c'est-à-dire qu'il sera garanti que ce flux ne sera plus utilisé par une instance [IPresentation](../ipresentation/) à l'avenir. Il peut être fermé par le code client ou utilisé de toute autre manière. |
| KeepLocked | 1 | Le flux sera verrouillé à l'intérieur de l'objet [IPresentation](../ipresentation/), c'est-à-dire que la propriété du flux sera transférée. L'objet [IPresentation](../ipresentation/) sera responsable de libérer correctement le flux lorsque cet objet sera lui-même libéré. Ce comportement est extrêmement utile lorsque vous devez sérialiser un gros fichier BLOB (tel qu'une grande vidéo ou audio - voir [IBlobManagementOptions](../iblobmanagementoptions/) description) et que vous souhaitez éviter de charger ce fichier en mémoire ou d'autres problèmes de performances. Vous pouvez simplement ouvrir le [System::IO::FileStream](../../system.io/filestream/) pour ce fichier et le transmettre à une méthode, en choisissant [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior. |

## Voir aussi

* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)