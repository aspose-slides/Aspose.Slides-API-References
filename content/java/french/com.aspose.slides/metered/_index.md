---
title: Metered
second_title: Référence API Aspose.Slides pour Java
description: Fournit des méthodes pour définir la clé mesurée.
type: docs
url: /fr/com.aspose.slides/metered/
---
**Héritage:**
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
| [isMeteredLicensed()](#isMeteredLicensed--) | Vérifie si la licence mesurée est activée |
### Metered() {#Metered--}
```
public Metered()
```


Initialise une nouvelle instance de cette classe.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Définit la clé publique et privée mesurée. Si vous achetez une licence mesurée, lorsque vous démarrez l'application, cette API doit être appelée, normalement, cela suffit. Cependant, si le téléchargement des données de consommation échoue toujours et dépasse 24 heures, la licence sera mise en statut d'évaluation ; pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence, si elle est en statut d'évaluation, appelez à nouveau cette API.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | clé publique |
| privateKey | java.lang.String | clé privée |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Obtient la taille du fichier de consommation

**Retourne:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Obtient le crédit de consommation

**Retourne:**
double - quantité de consommation
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```


Vérifie si la licence mesurée est activée

**Retourne:**
boolean - True ou false