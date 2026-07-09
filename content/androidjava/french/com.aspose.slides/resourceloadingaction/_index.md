---
title: ResourceLoadingAction
second_title: Aspose.Slides pour Android via la référence API Java
description: Spécifie le mode de chargement des ressources externes.
type: docs
url: /fr/com.aspose.slides/resourceloadingaction/
---
**Héritage:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Spécifie le mode de chargement des ressources externes.
## Champs

| Champ | Description |
| --- | --- |
| [Default](#Default) | Aspose.Slides chargera la ressource externe comme d'habitude. |
| [Skip](#Skip) | Aspose.Slides ignorera le chargement de la ressource externe. |
| [UserProvided](#UserProvided) | Aspose.Slides utilisera le tableau d'octets fourni par l'utilisateur dans [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs#setData-byte---) comme données d'image. |

### Default {#Default}
```
public static final int Default
```

Aspose.Slides chargera la ressource externe comme d'habitude.

### Skip {#Skip}
```
public static final int Skip
```

Aspose.Slides ignorera le chargement de la ressource externe. Seul le lien sans données sera stocké pour une image.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides utilisera le tableau d'octets fourni par l'utilisateur dans [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs#setData-byte---) comme données d'image.