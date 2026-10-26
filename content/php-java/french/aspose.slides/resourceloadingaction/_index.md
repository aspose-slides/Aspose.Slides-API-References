---
title: ResourceLoadingAction
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/resourceloadingaction/
---
## ResourceLoadingAction classe

Spécifie le mode de chargement des ressources externes.

## Constantes

| Nom | Valeur | Description |
| --- | --- | --- |
[Default](#Default) | 0 | Aspose.Slides chargera la ressource externe comme d'habitude. |
[Skip](#Skip) | 1 | Aspose.Slides ignorera le chargement de la ressource externe. Seul le lien sans données sera stocké pour une image. |
[UserProvided](#UserProvided) | 2 | Aspose.Slides utilisera le tableau d'octets fourni par l'utilisateur dans IResourceLoadingArgs#setData(byte[]) comme données d'image. |


---

### Default {#Default}
Aspose.Slides chargera la ressource externe comme d'habitude.

---

### Skip {#Skip}
Aspose.Slides ignorera le chargement de la ressource externe. Seul le lien sans données sera stocké pour une image.

---

### UserProvided {#UserProvided}
Aspose.Slides utilisera le tableau d'octets fourni par l'utilisateur dans IResourceLoadingArgs#setData(byte[]) comme données d'image.

---