---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: Provides methods to license the component.
type: docs
url: /fr/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Fournit des méthodes pour activer la licence du composant.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Active la licence du composant. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Active la licence du composant. |
| [resetLicense()](#resetLicense--) | Réinitialise la licence |
| [isLicensed()](#isLicensed--) | Vérifie si la licence est appliquée au composant |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```

Active la licence du composant.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Paramètres**:
| Paramètre | Type | Description |
| --- | --- | --- |
| licenseName | java.lang.String | Peut être un nom de fichier complet ou court ou le nom d’une ressource incorporée. Utilisez une chaîne vide pour passer en mode d’évaluation.

--------------------

Tente de trouver la licence aux emplacements suivants :

1. Chemin explicite.
2. Le dossier de l’assembly du composant.
3. Le dossier de l’assembly appelant du client.
4. Le dossier de l’assembly d’entrée.
5. Une ressource incorporée dans l’assembly appelant du client. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```

Active la licence du composant.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Paramètres**:
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Un flux contenant la licence.

--------------------

Utilisez cette méthode pour charger une licence à partir d’un flux. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```

Réinitialise la licence

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

Utilisez cette méthode pour réinitialiser la licence dans le composant

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```

Vérifie si la licence est appliquée au composant

**Retour**:
boolean - true si le composant est licencié, sinon false