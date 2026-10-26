---
title: Audio
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs
url: /fr/aspose.slides/audio/
---
## Audio classe

 Représente un fichier audio intégré.
 
### getBinaryData {#getBinaryData}

| Nom | Description |
| --- | --- |
| getBinaryData () | Renvoie une copie des données d'un audio. En cas de grande quantité de données, envisagez d'utiliser la méthode #getStream pour éviter le chargement inutile des données de l'audio en mémoire ou même une OutOfMemoryException. Lecture seule byte[]. |

 **Renvoie:**  
byte


---


### getContentType {#getContentType}

| Nom | Description |
| --- | --- |
| getContentType () | Renvoie un type MIME d'un audio, encodé dans ( #getBinaryData). Lecture seule String. |

 **Renvoie:**  
String


---


### getStream {#getStream}

| Nom | Description |
| --- | --- |
| getStream () | Renvoie Stream stream pour la lecture. Utilisez 'using' ou fermez le flux après utilisation. |

 **Renvoie:**  
InputStream


---


### setContentType {#setContentType}

| Nom | Description |
| --- | --- |
| setContentType (String) | Renvoie un type MIME d'un audio, encodé dans ( #getBinaryData). Lecture seule String. |

 **Renvoie:**  
void


---