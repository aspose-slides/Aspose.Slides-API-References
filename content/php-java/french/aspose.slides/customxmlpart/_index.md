---
title: CustomXmlPart
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/customxmlpart/
---
## CustomXmlPart classe

 Représente une partie xml personnalisée.
 
### getItemId {#getItemId}

| Nom | Description |
| --- | --- |
| getItemId () | Spécifie un identifiant globalement unique (GUID) qui identifie de façon unique une seule partie XML personnalisée dans un document Office Open XML. Lecture seule java.util.UUID. |

 **Renvoie:**  
UUID


---


### getNamespaceSchemas {#getNamespaceSchemas}

| Nom | Description |
| --- | --- |
| getNamespaceSchemas () | Renvoie la collection de schémas XML associés à la partie XML personnalisée. Lecture seule String[]. |

 **Renvoie:**  
String


---


### getXmlAsString {#getXmlAsString}

| Nom | Description |
| --- | --- |
| getXmlAsString () | Renvoie ou définit les données xml sous forme de chaîne UTF-8. Lecture/écriture String. |

 **Renvoie:**  
String

 **Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | la valeur est vide ou les données xml sont invalides. |


---


### getXmlData {#getXmlData}

| Nom | Description |
| --- | --- |
| getXmlData () | Renvoie ou définit les données xml. Lecture/écriture byte[]. |

 **Renvoie:**  
byte

 **Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | la valeur est vide ou les données xml sont invalides. |


---


### remove {#remove}

| Nom | Description |
| --- | --- |
| remove () | Supprime la partie xml personnalisée de la présentation. |

 **Renvoie:**  
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| PptxEditException | Lancée si la partie xml est déjà supprimée. |


---


### setItemId {#setItemId}

| Nom | Description |
| --- | --- |
| setItemId (UUID) | Spécifie un identifiant globalement unique (GUID) qui identifie de façon unique une seule partie XML personnalisée dans un document Office Open XML. Lecture seule java.util.UUID. |

 **Renvoie:**  
void


---


### setXmlAsString {#setXmlAsString}

| Nom | Description |
| --- | --- |
| setXmlAsString (String) | Renvoie ou définit les données xml sous forme de chaîne UTF-8. Lecture/écriture String. |

 **Renvoie:**  
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | la valeur est vide ou les données xml sont invalides. |


---


### setXmlData {#setXmlData}

| Nom | Description |
| --- | --- |
| setXmlData (byte[]) | Renvoie ou définit les données xml. Lecture/écriture byte[]. |

 **Renvoie:**  
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentException | la valeur est vide ou les données xml sont invalides. |


---