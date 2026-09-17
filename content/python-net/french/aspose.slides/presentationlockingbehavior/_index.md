---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior énumération

Représente le comportement concernant le traitement de la source [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation) (fichier ou **io.RawIOBase**) lors du chargement et de l'utilisation d'une instance de [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation).

Le type PresentationLockingBehavior expose les membres suivants :

## Champs

| Champ | Description |
| :- | :- |
| LOAD_AND_RELEASE | La source sera verrouillée uniquement pendant la durée d'exécution du constructeur [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation).<br/>            Si [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/fr/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) est défini sur false, tous les BLOBs <br/>            seront chargés en mémoire. Sinon, d'autres moyens tels que des fichiers temporaires pourraient être utilisés.Ce comportement est plus lent que [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/fr/aspose.slides/presentationlockingbehavior/KEEP_LOCKED), et s'il est possible de transférer la <br/>            propriété de la source à [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation), il est recommandé d'utiliser [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/fr/aspose.slides/presentationlockingbehavior/KEEP_LOCKED). |
| KEEP_LOCKED | La source sera verrouillée pendant toute la durée de vie de l'instance [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation), jusqu'à ce qu'elle <br/>            soit libérée.<br/>            [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/fr/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) doit être défini sur true pour utiliser <br/>            ce comportement, sinon une exception sera levée.Ce comportement est recommandé, il est plus rapide et consomme moins de mémoire que [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/fr/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |

### Remarques

La source est le paramètre passé au constructeur [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). Dans l'exemple ci-dessous, la source est le fichier "pres.pptx" :

Dans cet exemple, la source ("pres.pptx" file) sera verrouillée pendant la durée de vie d'une instance [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation), c’est-à-dire qu’elle ne pourra pas être modifiée ou supprimée par un autre processus.

### Voir aussi
* classe [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)