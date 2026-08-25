---
title: Metered
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/metered/
---
## Classe Metered
Fournit des méthodes pour définir la clé métérée.
### Metered {#Metered}

| Nom | Description |
| --- | --- |
| Metered() | Initialise une nouvelle instance de cette classe. |

**Retourne :**
Metered


---


### getConsumptionCredit {#getConsumptionCredit}

| Nom | Description |
| --- | --- |
| getConsumptionCredit () | Obtient le crédit de consommation |

**Retourne :**
double


---


### getConsumptionQuantity {#getConsumptionQuantity}

| Nom | Description |
| --- | --- |
| getConsumptionQuantity () | Obtient la taille du fichier de consommation |

**Retourne :**
double


---


### isMeteredLicensed {#isMeteredLicensed}

| Nom | Description |
| --- | --- |
| isMeteredLicensed () | Vérifie si Metered est licencié |

**Retourne :**
boolean


---


### setMeteredKey {#setMeteredKey}

| Nom | Description |
| --- | --- |
| setMeteredKey (String, String) | Définit la clé publique et privée de Metered. Si vous achetez une licence Metered, au démarrage de l'application, cette API doit être appelée, normalement cela suffit. Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d'évaluation ; pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence, et s'il est en statut d'évaluation, appeler à nouveau cette API. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| publicKey | String | clé publique |
| privateKey | String | clé privée |

**Retourne :**
void


---