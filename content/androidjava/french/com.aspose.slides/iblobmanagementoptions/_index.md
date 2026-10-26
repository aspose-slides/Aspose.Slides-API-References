---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: A Binary Large Object BLOB is a binary data stored as a single entity - i.e.
type: docs
url: /fr/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Un objet binaire volumineux (BLOB) est une donnée binaire stockée en une seule entité - c’est-à-dire qu’un BLOB peut être un audio, une vidéo ou la présentation elle-même. Un certain nombre de techniques sont utilisées pour optimiser la consommation de mémoire lors de la manipulation des BLOBs - qu’ils soient déjà stockés dans la présentation ou ajoutés ultérieurement par programme. En utilisant [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) vous pouvez modifier différents aspects du comportement concernant la gestion des BLOBs pour la durée de vie de l’instance [IPresentation](../../com.aspose.slides/ipresentation).

## Méthodes

| Méthode | Description |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Cette propriété indique si une instance de la classe Presentation peut être propriétaire de la source - fichier ou flux - pendant la durée de vie de l’instance. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Cette propriété indique si une instance de la classe Presentation peut être propriétaire de la source - fichier ou flux - pendant la durée de vie de l’instance. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Cette propriété indique si des fichiers temporaires peuvent être créés lors de la manipulation des BLOBs, ce qui réduit fortement la consommation de mémoire mais nécessite des autorisations de création de fichiers. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Cette propriété indique si des fichiers temporaires peuvent être créés lors de la manipulation des BLOBs, ce qui réduit fortement la consommation de mémoire mais nécessite des autorisations de création de fichiers. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Le chemin racine où les fichiers temporaires seront créés. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Le chemin racine où les fichiers temporaires seront créés. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. |
### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Cette propriété indique si une instance de la classe Presentation peut être propriétaire de la source - fichier ou flux - pendant la durée de vie de l’instance. Si l’instance est propriétaire, elle verrouille la source. Cela contribue à améliorer la consommation de mémoire et les performances lors de la manipulation des BLOBs, mais la source (flux ou fichier) ne peut pas être modifiée pendant la durée de vie de l’instance Presentation. Voici un exemple :

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException will be thrown because pres.pptx is locked for a Presentation lifetime
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // after Presentation object disposed, file is unlocked and can be deleted
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Returns:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. If the instance is an owner, it locks the source. This helps to improve memory consumption and performance while working with BLOBs, but the source (stream or file) can't be changed during Presentation's instance lifetime. This is an example:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException sera levée parce que pres.pptx est verrouillé pendant la durée de vie d'une Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // après que l'objet Presentation soit détruit, le fichier est déverrouillé et peut être supprimé
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files.

--------------------

All files will be deleted after work with the presentation will be finished.

**Returns:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```


This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files.

--------------------

All files will be deleted after work with the presentation will be finished.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```


The root path where temporary files will be created. System temorary directory will be used by default. Hosting process should have permissions to create files and folders there.

**Returns:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```


The root path where temporary files will be created. System temorary directory will be used by default. Hosting process should have permissions to create files and folders there.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. By default, all BLOBs are loaded into memory; only once this limit is reached are alternative mechanisms (such as temporary files) employed. Keeping BLOBs in memory maximizes performance but can lead to high memory usage. Use this property to tailor behavior to your environment or requirements.

--------------------

This property is ignored if \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) is set to false, since memory is then the only storage location available and limiting in-memory BLOB usage has no effect.

--------------------

The default value is 629,145,600 bytes (600 MB).

--------------------

You may set this property to zero, but a small minimum amount of memory will still be reserved.

**Returns:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)

Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. Par défaut, tous les BLOBs sont chargés en mémoire ; ce n’est qu’une fois cette limite atteinte que des mécanismes alternatifs (comme les fichiers temporaires) sont utilisés. Conserver les BLOBs en mémoire maximise les performances mais peut entraîner une consommation élevée de mémoire. Utilisez cette propriété pour adapter le comportement à votre environnement ou à vos besoins.

--------------------

Cette propriété est ignorée si \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) est définie sur false, car la mémoire est alors le seul emplacement de stockage disponible et la limitation de l’utilisation des BLOBs en mémoire n’a aucun effet.

--------------------

La valeur par défaut est de 629 145 600 octets (600 Mo).

--------------------

Vous pouvez définir cette propriété à zéro, mais une petite quantité minimale de mémoire sera tout de même réservée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |