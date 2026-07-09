---
title: BlobManagementOptions
second_title: Référence API Java pour Aspose.Slides sur Android
description: Représente les options qui peuvent être utilisées pour gérer les règles de manipulation des BLOB et d'autres paramètres BLOB.
type: docs
url: /fr/com.aspose.slides/blobmanagementoptions/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)  
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Représente les options qui peuvent être utilisées pour gérer les règles de manipulation des BLOB et d'autres paramètres BLOB.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Crée de nouvelles options de gestion de BLOB par défaut. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Cette propriété définit si une instance de la classe Presentation peut être propriétaire de la source – fichier ou flux pendant la durée de vie de l'instance. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Cette propriété définit si une instance de la classe Presentation peut être propriétaire de la source – fichier ou flux pendant la durée de vie de l'instance. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Cette propriété définit si des fichiers temporaires peuvent être créés lors de la manipulation des BLOB, ce qui réduit considérablement la consommation de mémoire mais nécessite des autorisations pour créer des fichiers. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Cette propriété définit si des fichiers temporaires peuvent être créés lors de la manipulation des BLOB, ce qui réduit considérablement la consommation de mémoire mais nécessite des autorisations pour créer des fichiers. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Le chemin racine où les fichiers temporaires seront créés. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Le chemin racine où les fichiers temporaires seront créés. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Définit la taille totale maximale (en octets) que tous les BLOB peuvent occuper en mémoire. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Définit la taille totale maximale (en octets) que tous les BLOB peuvent occuper en mémoire. |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Crée de nouvelles options de gestion de BLOB par défaut.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Cette propriété définit si une instance de la classe Presentation peut être propriétaire de la source – fichier ou flux pendant la durée de vie de l'instance. Si l'instance est propriétaire, elle verrouille la source. Cela aide à améliorer la consommation de mémoire et les performances lors de la manipulation des BLOB, mais la source (flux ou fichier) ne peut pas être modifiée pendant la durée de vie de l'instance Presentation.

**Renvoie :**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Cette propriété définit si une instance de la classe Presentation peut être propriétaire de la source – fichier ou flux pendant la durée de vie de l'instance. Si l'instance est propriétaire, elle verrouille la source. Cela aide à améliorer la consommation de mémoire et les performances lors de la manipulation des BLOB, mais la source (flux ou fichier) ne peut pas être modifiée pendant la durée de vie de l'instance Presentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Cette propriété définit si des fichiers temporaires peuvent être créés lors de la manipulation des BLOB, ce qui réduit considérablement la consommation de mémoire mais nécessite des autorisations pour créer des fichiers.

--------------------

Tous les fichiers seront supprimés une fois le travail avec la présentation terminé.

**Renvoie :**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Cette propriété définit si des fichiers temporaires peuvent être créés lors de la manipulation des BLOB, ce qui réduit considérablement la consommation de mémoire mais nécessite des autorisations pour créer des fichiers.

--------------------

Tous les fichiers seront supprimés une fois le travail avec la présentation terminé.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

Le chemin racine où les fichiers temporaires seront créés. Le répertoire temporaire du système sera utilisé par défaut. Le processus hébergeant doit disposer des autorisations nécessaires pour créer des fichiers et dossiers à cet emplacement.

**Renvoie :**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

Le chemin racine où les fichiers temporaires seront créés. Le répertoire temporaire du système sera utilisé par défaut. Le processus hébergeant doit disposer des autorisations nécessaires pour créer des fichiers et dossiers à cet emplacement.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Définit la taille totale maximale (en octets) que tous les BLOB peuvent occuper en mémoire. Par défaut, tous les BLOB sont chargés en mémoire ; ce n'est que lorsque cette limite est atteinte que des mécanismes alternatifs (comme les fichiers temporaires) sont utilisés. Conserver les BLOB en mémoire maximise les performances mais peut entraîner une forte consommation de mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos exigences.

--------------------

Cette propriété est ignorée si \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) est défini sur false, car la mémoire devient alors le seul emplacement de stockage disponible et la limitation de l'utilisation des BLOB en mémoire n'a aucun effet.

--------------------

La valeur par défaut est de 629 145 600 octets (600 Mo).

--------------------

Vous pouvez définir cette propriété à zéro, mais une petite quantité minimale de mémoire sera tout de même réservée.

**Renvoie :**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Définit la taille totale maximale (en octets) que tous les BLOB peuvent occuper en mémoire. Par défaut, tous les BLOB sont chargés en mémoire ; ce n'est que lorsque cette limite est atteinte que des mécanismes alternatifs (comme les fichiers temporaires) sont utilisés. Conserver les BLOB en mémoire maximise les performances mais peut entraîner une forte consommation de mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos exigences.

--------------------

Cette propriété est ignorée si \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) est défini sur false, car la mémoire devient alors le seul emplacement de stockage disponible et la limitation de l'utilisation des BLOB en mémoire n'a aucun effet.

--------------------

La valeur par défaut est de 629 145 600 octets (600 Mo).

--------------------

Vous pouvez définir cette propriété à zéro, mais une petite quantité minimale de mémoire sera tout de même réservée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |