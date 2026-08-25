---
title: LoadingStreamBehavior
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/loadingstreambehavior/
---
## classe LoadingStreamBehavior

 Le java.io.InputStream passé à une méthode est considéré comme un Binary Large Object (BLOB) (voir la description de IBlobManagementOptions). Les valeurs de cette énumération indiquent comment le java.io.InputStream doit être traité lorsqu’il est passé à la méthode. Selon les exigences, différentes décisions peuvent être prises pour offrir le comportement le plus efficace.

## Constantes

| Nom | Valeur | Description |
| --- | --- | --- |
[ReadStreamAndRelease](#ReadStreamAndRelease) | 0 | Le flux sera lu jusqu’à la fin puis libéré – c’est-à-dire qu’il sera garanti que ce flux ne sera plus utilisé par l’instance IPresentation à l’avenir. Il peut être fermé par le code client ou utilisé de toute autre manière. Presentation pres = new Presentation(); try { FileInputStream fileStream = new FileInputStream(new File("video.avi")); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease); fileStream.close(); // le flux peut être fermé, il n’est plus nécessaire pour l’objet « pres ». } finally { if (pres != null) pres.dispose(); } |
[KeepLocked](#KeepLocked) | 1 | Le flux sera verrouillé à l’intérieur de l’objet IPresentation, c’est-à-dire que la propriété du flux sera transférée. L’objet IPresentation sera responsable de libérer correctement le flux lorsque cet objet sera lui-même libéré. Ce comportement est extrêmement utile lorsque vous devez sérialiser un gros fichier BLOB (par exemple une grande vidéo ou un audio – voir la description de IBlobManagementOptions) et que vous souhaitez éviter de charger ce fichier en mémoire ou d’autres problèmes de performance. Vous pouvez simplement ouvrir le java.io.FileInputStream pour ce fichier et le passer à une méthode, en choisissant LoadingStreamBehavior#KeepLocked LoadingStreamBehavior. Presentation pres = new Presentation(); try { FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked); // fileStream.close(); // Vous ne devez pas fermer le flux ou interagir avec lui d’une autre manière, cela entraînerait une erreur dans la méthode Save. // Le fileStream sera utilisé pour l’enregistrement, ce qui évitera une forte consommation de mémoire pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx); } finally { if (pres != null) pres.dispose(); } |

---

### ReadStreamAndRelease {#ReadStreamAndRelease}
Le flux sera lu jusqu’à la fin puis libéré – c’est-à-dire qu’il sera garanti que ce flux ne sera plus utilisé par l’instance IPresentation à l’avenir. Il peut être fermé par le code client ou utilisé de toute autre manière. Presentation pres = new Presentation(); try { FileInputStream fileStream = new FileInputStream(new File("video.avi")); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease); fileStream.close(); // le flux peut être fermé, il n’est plus nécessaire pour l’objet « pres ». } finally { if (pres != null) pres.dispose(); }

---

### KeepLocked {#KeepLocked}
Le flux sera verrouillé à l’intérieur de l’objet IPresentation, c’est-à-dire que la propriété du flux sera transférée. L’objet IPresentation sera responsable de libérer correctement le flux lorsque cet objet sera lui-même libéré. Ce comportement est extrêmement utile lorsque vous devez sérialiser un gros fichier BLOB (par exemple une grande vidéo ou un audio – voir la description de IBlobManagementOptions) et que vous souhaitez éviter de charger ce fichier en mémoire ou d’autres problèmes de performance. Vous pouvez simplement ouvrir le java.io.FileInputStream pour ce fichier et le passer à une méthode, en choisissant LoadingStreamBehavior#KeepLocked LoadingStreamBehavior. Presentation pres = new Presentation(); try { FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked); // fileStream.close(); // Vous ne devez pas fermer le flux ou interagir avec lui d’une autre manière, cela entraînerait une erreur dans la méthode Save. // Le fileStream sera utilisé pour l’enregistrement, ce qui évitera une forte consommation de mémoire pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx); } finally { if (pres != null) pres.dispose(); } 

---