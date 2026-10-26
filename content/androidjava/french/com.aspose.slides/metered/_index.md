---
title: Metered
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Fournit des méthodes pour définir la clé mesurée.
type: docs
url: /fr/com.aspose.slides/metered/
---
**Héritage :**  
java.lang.Object  
```
public class Metered
```

Fournit des méthodes pour définir la clé mesurée.  
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Metered()](#Metered--) | Initialise une nouvelle instance de cette classe. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Définit la clé publique et privée mesurée. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Obtient la taille du fichier de consommation |
| [getConsumptionCredit()](#getConsumptionCredit--) | Obtient le crédit de consommation |
| [isMeteredLicensed()](#isMeteredLicensed--) | Vérifie si le compte mesuré est licencié |
### Metered() {#Metered--}
```
public Metered()
```

Initialise une nouvelle instance de cette classe.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

Définit la clé publique et privée mesurée. Si vous achetez une licence mesurée, au démarrage de l’application, cette API doit être appelée ; normalement, cela suffit. Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence passera en statut d’évaluation. Pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence et, s’il est en évaluation, rappeler cette API.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | clé publique |
| privateKey | java.lang.String | clé privée |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

Obtient la taille du fichier de consommation

**Renvoie :**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

Obtient le crédit de consommation

**Renvoie :**
double - quantité de consommation
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

Vérifie si le compte mesuré est licencié

**Renvoie :**
boolean - Vrai ou faux