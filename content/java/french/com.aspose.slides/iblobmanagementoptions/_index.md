---
title: IBlobManagementOptions
second_title: Référence de l'API Aspose.Slides pour Java
description: Un objet binaire volumineux BLOB est une donnée binaire stockée comme une entité unique - i.e.
type: docs
url: /fr/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Un objet binaire volumineux (BLOB) est une donnée binaire stockée comme une entité unique - i.e. le BLOB peut être un audio, une vidéo ou la présentation elle-même. Un certain nombre de techniques sont utilisées pour optimiser la consommation de mémoire lors du travail avec les BLOBs - qui ont déjà été stockés dans la présentation ou qui peuvent être ajoutés ultérieurement de manière programmatique. En utilisant [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) vous pouvez modifier différents aspects du comportement concernant la gestion des BLOBs pour la durée de vie de l'instance [IPresentation](../../com.aspose.slides/ipresentation).

## Méthodes

| Méthode | Description |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Cette propriété définit si une instance de la classe Presentation peut être propriétaire de la source - fichier ou flux pendant la durée de vie de l'instance. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Cette propriété définit si une instance de la classe Presentation peut être propriétaire de la source - fichier ou flux pendant la durée de vie de l'instance. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Cette propriété définit si des fichiers temporaires peuvent être créés lors du travail avec les BLOBs, ce qui réduit considérablement la consommation de mémoire mais nécessite des autorisations pour créer des fichiers. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Cette propriété définit si des fichiers temporaires peuvent être créés lors du travail avec les BLOBs, ce qui réduit considérablement la consommation de mémoire mais nécessite des autorisations pour créer des fichiers. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Le chemin racine où les fichiers temporaires seront créés. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Le chemin racine où les fichiers temporaires seront créés. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Cette propriété définit si une instance de la classe Presentation peut être propriétaire de la source - fichier ou flux pendant la durée de vie de l'instance. Si l'instance est propriétaire, elle verrouille la source. Cela aide à améliorer la consommation de mémoire et les performances lors du travail avec les BLOBs, mais la source (flux ou fichier) ne peut pas être modifiée pendant la durée de vie de l'instance Presentation. Voici un exemple :

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException sera levée car pres.pptx est verrouillé pendant la durée de vie d'une Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // après que l'objet Presentation soit libéré, le fichier est déverrouillé et peut être supprimé
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Retour :**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Cette propriété définit si une instance de la classe Presentation peut être propriétaire de la source - fichier ou flux pendant la durée de vie de l'instance. Si l'instance est propriétaire, elle verrouille la source. Cela aide à améliorer la consommation de mémoire et les performances lors du travail avec les BLOBs, mais la source (flux ou fichier) ne peut pas être modifiée pendant la durée de vie de l'instance Presentation. Voici un exemple :

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException sera levée car pres.pptx est verrouillé pendant la durée de vie d'une Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // après que l'objet Presentation soit libéré, le fichier est déverrouillé et peut être supprimé
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Cette propriété définit si des fichiers temporaires peuvent être créés lors du travail avec les BLOBs, ce qui réduit considérablement la consommation de mémoire mais nécessite des autorisations pour créer des fichiers.

--------------------

Tous les fichiers seront supprimés une fois le travail avec la présentation terminé.

**Retour :**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Cette propriété définit si des fichiers temporaires peuvent être créés lors du travail avec les BLOBs, ce qui réduit considérablement la consommation de mémoire mais nécessite des autorisations pour créer des fichiers.

--------------------

Tous les fichiers seront supprimés une fois le travail avec la présentation terminé.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

Le chemin racine où les fichiers temporaires seront créés. Le répertoire temporaire du système sera utilisé par défaut. Le processus d'hébergement doit avoir les autorisations pour créer des fichiers et dossiers à cet emplacement.

**Retour :**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Le chemin racine où les fichiers temporaires seront créés. Le répertoire temporaire du système sera utilisé par défaut. Le processus d'hébergement doit avoir les autorisations pour créer des fichiers et dossiers à cet emplacement.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. Par défaut, tous les BLOBs sont chargés en mémoire ; ce n'est qu'une fois cette limite atteinte que des mécanismes alternatifs (tels que les fichiers temporaires) sont utilisés. Conserver les BLOBs en mémoire maximise les performances mais peut entraîner une forte utilisation de la mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos exigences.

--------------------

Cette propriété est ignorée si \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) est défini sur false, car la mémoire est alors le seul emplacement de stockage disponible et la limitation de l'utilisation des BLOBs en mémoire n'a aucun effet.

--------------------

La valeur par défaut est de 629 145 600 octets (600 Mo).

--------------------

Vous pouvez définir cette propriété sur zéro, mais une petite quantité minimale de mémoire sera tout de même réservée.

**Retour :**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. Par défaut, tous les BLOBs sont chargés en mémoire ; ce n'est qu'une fois cette limite atteinte que des mécanismes alternatifs (tels que les fichiers temporaires) sont utilisés. Conserver les BLOBs en mémoire maximise les performances mais peut entraîner une forte utilisation de la mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos exigences.

--------------------

Cette propriété est ignorée si \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) est défini sur false, car la mémoire est alors le seul emplacement de stockage disponible et la limitation de l'utilisation des BLOBs en mémoire n'a aucun effet.

--------------------

La valeur par défaut est de 629 145 600 octets (600 Mo).

--------------------

Vous pouvez définir cette propriété sur zéro, mais une petite quantité minimale de mémoire sera tout de même réservée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |