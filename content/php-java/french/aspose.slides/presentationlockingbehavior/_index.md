---
title: PresentationLockingBehavior
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs
url: /fr/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior classe

Représente le comportement concernant le traitement de la source IPresentation (fichier ou java.io.InputStream) lors du chargement et de l'utilisation d'une instance de IPresentation.  
La source est le paramètre passé au constructeur IPresentation. Dans l'exemple ci-dessous, la source est le fichier "pres.pptx".  
Pour cet exemple, la source ("pres.pptx" file) sera verrouillée pendant toute la durée de vie de l'instance IPresentation, c'est-à-dire qu'elle ne peut pas être modifiée ou supprimée par un autre processus.

## Constantes

| Nom | Valeur | Description |
| --- | --- | --- |
[LoadAndRelease](#LoadAndRelease) | 0 | La source sera verrouillée uniquement pendant l'exécution du constructeur IPresentation. Si ( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) est défini sur false, tous les BLOBs seront chargés en mémoire. Sinon, d'autres moyens tels que des fichiers temporaires pourraient être utilisés. Ce comportement est plus lent que PresentationLockingBehavior#KeepLocked, et s'il est possible de transmettre la propriété de la source à IPresentation, il est recommandé d'utiliser PresentationLockingBehavior#KeepLocked. |
[KeepLocked](#KeepLocked) | 1 | La source sera verrouillée pendant toute la durée de vie de l'instance IPresentation, jusqu'à ce qu'elle soit libérée. IBlobManagementOptions#isTemporaryFilesAllowed( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) doit être défini sur true pour utiliser ce comportement, sinon une exception sera levée. Ce comportement est recommandé, il est plus rapide et consomme moins de mémoire que PresentationLockingBehavior#LoadAndRelease. |

---

### LoadAndRelease {#LoadAndRelease}
La source sera verrouillée uniquement pendant l'exécution du constructeur IPresentation. Si ( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) est défini sur false, tous les BLOBs seront chargés en mémoire. Sinon, d'autres moyens tels que des fichiers temporaires pourraient être utilisés. Ce comportement est plus lent que PresentationLockingBehavior#KeepLocked, et s'il est possible de transmettre la propriété de la source à IPresentation, il est recommandé d'utiliser PresentationLockingBehavior#KeepLocked.

---

### KeepLocked {#KeepLocked}
La source sera verrouillée pendant toute la durée de vie de l'instance IPresentation, jusqu'à ce qu'elle soit libérée. IBlobManagementOptions#isTemporaryFilesAllowed( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) doit être défini sur true pour utiliser ce comportement, sinon une exception sera levée. Ce comportement est recommandé, il est plus rapide et consomme moins de mémoire que PresentationLockingBehavior#LoadAndRelease.

---