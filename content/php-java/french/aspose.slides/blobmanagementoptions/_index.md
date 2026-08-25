---
title: BlobManagementOptions
second_title: Référence de l'API Java via PHP d'Aspose.Sildes
description: 
type: docs
url: /fr/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions classe

 Représente les options qui peuvent être utilisées pour gérer les règles de manipulation des BLOB et d’autres paramètres des BLOB.
 
### BlobManagementOptions {#BlobManagementOptions}

| Nom | Description |
| --- | --- |
| BlobManagementOptions() | Crée de nouvelles options de gestion de BLOB par défaut. |

 **Retour :**
BlobManagementOptions


---


### getMaxBlobsBytesInMemory {#getMaxBlobsBytesInMemory}

| Nom | Description |
| --- | --- |
| getMaxBlobsBytesInMemory () | Définit la taille totale maximale (en octets) que tous les BLOB peuvent occuper en mémoire. Par défaut, tous les BLOB sont chargés en mémoire ; ce n’est qu’une fois cette limite atteinte que des mécanismes alternatifs (tels que des fichiers temporaires) sont utilisés. Conserver les BLOB en mémoire maximise les performances mais peut entraîner une consommation élevée de mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos exigences. Cette propriété est ignorée si #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean) est définie sur false, car la mémoire est alors le seul emplacement de stockage disponible et limiter l’utilisation des BLOB en mémoire n’a aucun effet. La valeur par défaut est de 629 145 600 octets (600 Mo). Vous pouvez définir cette propriété à zéro, mais une petite quantité minimale de mémoire sera néanmoins réservée. |

 **Retour :**
long


---


### getPresentationLockingBehavior {#getPresentationLockingBehavior}

| Nom | Description |
| --- | --- |
| getPresentationLockingBehavior () | Cette propriété définit si une instance de la classe Presentation peut être propriétaire de la source - fichier ou flux pendant la durée de vie de l’instance. Si l’instance est propriétaire, elle verrouille la source. Cela aide à améliorer la consommation de mémoire et les performances lors du travail avec les BLOB, mais la source (flux ou fichier) ne peut pas être modifiée pendant la durée de vie de l’instance de Presentation. |

 **Retour :**
int


---


### getTempFilesRootPath {#getTempFilesRootPath}

| Nom | Description |
| --- | --- |
| getTempFilesRootPath () | Le chemin racine où les fichiers temporaires seront créés. Le répertoire temporaire du système sera utilisé par défaut. Le processus d’hébergement doit disposer des autorisations nécessaires pour créer des fichiers et dossiers à cet emplacement. |

 **Retour :**
String


---


### isTemporaryFilesAllowed {#isTemporaryFilesAllowed}

| Nom | Description |
| --- | --- |
| isTemporaryFilesAllowed () | Cette propriété définit si des fichiers temporaires peuvent être créés lors du travail avec les BLOB, ce qui réduit considérablement la consommation de mémoire mais nécessite des autorisations de création de fichiers. Tous les fichiers seront supprimés une fois le travail avec la présentation terminé. |

 **Retour :**
boolean


---


### setMaxBlobsBytesInMemory {#setMaxBlobsBytesInMemory}

| Nom | Description |
| --- | --- |
| setMaxBlobsBytesInMemory (long) | Définit la taille totale maximale (en octets) que tous les BLOB peuvent occuper en mémoire. Par défaut, tous les BLOB sont chargés en mémoire ; ce n’est qu’une fois cette limite atteinte que des mécanismes alternatifs (tels que des fichiers temporaires) sont utilisés. Conserver les BLOB en mémoire maximise les performances mais peut entraîner une consommation élevée de mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos exigences. Cette propriété est ignorée si #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean) est définie sur false, car la mémoire est alors le seul emplacement de stockage disponible et limiter l’utilisation des BLOB en mémoire n’a aucun effet. La valeur par défaut est de 629 145 600 octets (600 Mo). Vous pouvez définir cette propriété à zéro, mais une petite quantité minimale de mémoire sera néanmoins réservée. |

 **Retour :**
void


---


### setPresentationLockingBehavior {#setPresentationLockingBehavior}

| Nom | Description |
| --- | --- |
| setPresentationLockingBehavior (int) | Cette propriété définit si une instance de la classe Presentation peut être propriétaire de la source - fichier ou flux pendant la durée de vie de l’instance. Si l’instance est propriétaire, elle verrouille la source. Cela aide à améliorer la consommation de mémoire et les performances lors du travail avec les BLOB, mais la source (flux ou fichier) ne peut pas être modifiée pendant la durée de vie de l’instance de Presentation. |

 **Retour :**
void


---


### setTempFilesRootPath {#setTempFilesRootPath}

| Nom | Description |
| --- | --- |
| setTempFilesRootPath (String) | Le chemin racine où les fichiers temporaires seront créés. Le répertoire temporaire du système sera utilisé par défaut. Le processus d’hébergement doit disposer des autorisations nécessaires pour créer des fichiers et dossiers à cet emplacement. |

 **Retour :**
void


---


### setTemporaryFilesAllowed {#setTemporaryFilesAllowed}

| Nom | Description |
| --- | --- |
| setTemporaryFilesAllowed (boolean) | Cette propriété définit si des fichiers temporaires peuvent être créés lors du travail avec les BLOB, ce qui réduit considérablement la consommation de mémoire mais nécessite des autorisations de création de fichiers. Tous les fichiers seront supprimés une fois le travail avec la présentation terminé. |

 **Retour :**
void


---