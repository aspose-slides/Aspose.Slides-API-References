---
title: AudioCollection
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/audiocollection/
---
## AudioCollection classe

 Représente une collection de fichiers audio incorporés.
 
### addAudio {#addAudio}

| Nom | Description |
| --- | --- |
| addAudio ([Audio](../audio)) | Ajoute une copie d'un fichier audio d'une autre présentation. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| audio | [Audio](../audio) | Audio source. |

 **Retour :**
[Audio](../audio)

---


### addAudio {#addAudio}

| Nom | Description |
| --- | --- |
| addAudio (InputStream) | Crée et ajoute un audio à une présentation depuis le flux. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | InputStream | Flux à partir duquel ajouter l'audio. |

 **Retour :**
[Audio](../audio)

---


### addAudio {#addAudio}

| Nom | Description |
| --- | --- |
| addAudio (InputStream, int) | Crée et ajoute un audio à une présentation depuis le flux. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | InputStream | Flux à partir duquel ajouter l'audio vidéo. |
| loadingStreamBehavior | int | Le comportement qui sera appliqué au flux. |

 **Retour :**
[Audio](../audio)

---


### addAudio {#addAudio}

| Nom | Description |
| --- | --- |
| addAudio (byte[]) | Crée et ajoute un audio à une présentation depuis un tableau d'octets. |

 **Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| audioData | byte[] | Octets audio. |

 **Retour :**
[Audio](../audio)

---


### getSyncRoot {#getSyncRoot}

| Nom | Description |
| --- | --- |
| getSyncRoot () | Renvoie une racine de synchronisation. Lecture seule Object. |

 **Retour :**
Object

---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (int) | Obtient l'élément à l'index spécifié. Lecture seule IAudio. |

 **Retour :**
[Audio](../audio)

---


### isSynchronized {#isSynchronized}

| Nom | Description |
| --- | --- |
| isSynchronized () | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean. |

 **Retour :**
boolean

---


### iterator {#iterator}

| Nom | Description |
| --- | --- |
| iterator () | Renvoie un énumérateur qui parcourt la collection. |

 **Retour :**



---


### iteratorJava {#iteratorJava}

| Nom | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur Java pour l'ensemble de la collection. |

 **Retour :**



---


### size {#size}

| Nom | Description |
| --- | --- |
| size () | Renvoie le nombre de fichiers audio dans la collection. Lecture seule int. |

 **Retour :**
int

---