---
title: License
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/license/
---
## classe License
Fournit des méthodes pour licencier le composant.

Dans cet exemple, une tentative sera effectuée pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée puis dans les ressources incorporées de l'assembly appelant.

### License {#License}

| Nom | Description |
| --- | --- |
| License() | Initialise une nouvelle instance de cette classe. Dans cet exemple, une tentative sera effectuée pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée puis dans les ressources incorporées de l'assembly appelant. |

**Renvoie:**  
License

---

### getVersion {#getVersion}

| Nom | Description |
| --- | --- |
| getVersion () | Renvoie la version d'Aspose.Slides pour Java. |

**Renvoie:**  
String

---

### isLicensed {#isLicensed}

| Nom | Description |
| --- | --- |
| isLicensed () |  |

**Renvoie:**  
boolean

---

### resetLicense {#resetLicense}

| Nom | Description |
| --- | --- |
| resetLicense () | Réinitialise la licence. Utilisez cette méthode pour réinitialiser la licence dans le composant. |

**Renvoie:**  
void

---

### setLicense {#setLicense}

| Nom | Description |
| --- | --- |
| setLicense (InputStream) | Licencie le composant. Dans cet exemple, une tentative sera effectuée pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée puis dans les ressources incorporées de l'assembly appelant. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| stream | InputStream | Un flux contenant la licence. Utilisez null pour passer en mode d'évaluation. |

**Renvoie:**  
void

---

### setLicense {#setLicense}

| Nom | Description |
| --- | --- |
| setLicense (String) | Licencie le composant. Dans cet exemple, une tentative sera effectuée pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée puis dans les ressources incorporées de l'assembly appelant. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| namePath | String | Peut être un nom de fichier complet ou court ou le nom d'une ressource incorporée. Utilisez une chaîne vide pour passer en mode d'évaluation. |

**Renvoie:**  
void