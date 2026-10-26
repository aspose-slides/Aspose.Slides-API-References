---
title: License
second_title: Référence de l'API Aspose.Slides pour Java
description: Fournit des méthodes pour licencier le composant.
type: docs
url: /fr/com.aspose.slides/license/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)  
```
public final class License implements ILicense
```

Fournit des méthodes pour licencier le composant.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [License()](#License--) | Initialise une nouvelle instance de cette classe. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licence le composant. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Licence le composant. |
| [getVersion()](#getVersion--) | Renvoie la version d'Aspose.Slides pour Java. |
| [resetLicense()](#resetLicense--) | Réinitialise la licence. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```

Initialise une nouvelle instance de cette classe.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```

Licence le composant.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Un flux contenant la licence. Utilisez null pour passer en mode d'évaluation. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```

Licence le composant.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| namePath | java.lang.String | Peut être un nom de fichier complet ou court ou le nom d'une ressource incorporée. Utilisez une chaîne vide pour passer en mode d'évaluation. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```

Renvoie la version d'Aspose.Slides pour Java.

**Retour :**  
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```

Réinitialise la licence. Utilisez cette méthode pour réinitialiser la licence dans le composant.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```

Vérifie si une licence est appliquée au composant

**Retour :**  
boolean