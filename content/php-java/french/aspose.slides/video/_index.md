---
title: Video
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/video/
---
## classe Video

 Représente une image intégrée dans une présentation.
 
### getBinaryData {#getBinaryData}

| Name | Description |
| --- | --- |
| getBinaryData () | Retourne une copie des données d'un audio. En cas de grande quantité de données, envisagez d'utiliser la méthode #getStream pour éviter le chargement inutile des données de la vidéo en mémoire ou même une OutOfMemoryException. Lecture seule byte[]. |

 **Renvoie :**
byte


---


### getContentType {#getContentType}

| Name | Description |
| --- | --- |
| getContentType () | Retourne un type MIME d'une vidéo, encodé dans (#getBinaryData). Lecture seule String. |

 **Renvoie :**
String


---


### getStream {#getStream}

| Name | Description |
| --- | --- |
| getStream () | Retourne un flux Stream pour la lecture. Utilisez 'using' ou fermez le flux après utilisation. |

 **Renvoie :**
InputStream


---