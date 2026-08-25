---
title: Output
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/output/
---
## Output classe

 Représente une collection d'éléments de sortie pour IWebDocument.
 
### add {#add}

| Nom | Description |
| --- | --- |
| add (String, String, TContextObject) | Ajoute un élément de sortie pour l'objet de contexte. |

 **Paramètres:** 

| Nom | Type | Description |
| --- | --- | --- |
| path | String | Chemin de sortie. |
| templateKey | String | La clé du modèle utilisé pour la transformation de l'objet de contexte avant la sortie. |
| contextObject | TContextObject | Objet de contexte. |

 **Retour:** 
[OutputFile](../outputfile)


---


### add {#add}

| Nom | Description |
| --- | --- |
| add (String, [PPImage](../ppimage)) | Ajoute un élément de sortie pour l'image. |

 **Paramètres:** 

| Nom | Type | Description |
| --- | --- | --- |
| path | String | Chemin de sortie. |
| image | [PPImage](../ppimage) | Image à sortir. |

 **Retour:** 
[OutputFile](../outputfile)


---


### add {#add}

| Nom | Description |
| --- | --- |
| add (String, [IImage](../iimage)) | Ajoute un élément de sortie pour l'image. |

 **Paramètres:** 

| Nom | Type | Description |
| --- | --- | --- |
| path | String | Chemin de sortie. |
| image | [IImage](../iimage) | Image à sortir. |

 **Retour:** 
[OutputFile](../outputfile)


---


### add {#add}

| Nom | Description |
| --- | --- |
| add (String, [Video](../video)) | Ajoute un élément de sortie pour la vidéo. |

 **Paramètres:** 

| Nom | Type | Description |
| --- | --- | --- |
| path | String | Chemin de sortie. |
| video | [Video](../video) | Vidéo à sortir. |

 **Retour:** 
[OutputFile](../outputfile)


---


### add {#add}

| Nom | Description |
| --- | --- |
| add (String, [FontData](../fontdata), int) | Crée et ajoute un élément de fichier de sortie pour la police spécifiée. |

 **Paramètres:** 

| Nom | Type | Description |
| --- | --- | --- |
| path | String | Le chemin du fichier où la police sera sauvegardée. |
| fontData | [FontData](../fontdata) | Les données de la police à écrire dans la sortie. |
| fontStyle | int | Le style de la police (p. ex., Regular, Bold, Italic). |

 **Retour:** 
[OutputFile](../outputfile)


---


### add {#add}

| Nom | Description |
| --- | --- |
| add (String, String) | Ajoute un élément de sortie pour le contenu texte. |

 **Paramètres:** 

| Nom | Type | Description |
| --- | --- | --- |
| path | String | Chemin de sortie. |
| textContent | String | Contenu à sortir. |

 **Retour:** 
[OutputFile](../outputfile)


---


### bindResource {#bindResource}

| Nom | Description |
| --- | --- |
| bindResource ([OutputFile](../outputfile), Object) | Lie la ressource au fichier de sortie. |

 **Paramètres:** 

| Nom | Type | Description |
| --- | --- | --- |
| outputFile | [OutputFile](../outputfile) | Fichier de sortie. |
| obj | Object | Objet ressource. |

 **Retour:** 
void


---


### getResourcePath {#getResourcePath}

| Nom | Description |
| --- | --- |
| getResourcePath (Object) | Renvoie le chemin d'une ressource donnée. |

 **Paramètres:** 

| Nom | Type | Description |
| --- | --- | --- |
| obj | Object | Objet ressource. |

 **Retour:** 
String


---