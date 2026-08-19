---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: Callback-interface die wordt gebruikt om te bepalen hoe een object moet worden verwerkt tijdens het opslaan.
type: docs
url: /nl/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Callback-interface die wordt gebruikt om te bepalen hoe een object moet worden verwerkt tijdens het opslaan.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Bepaalt waar het object moet worden opgeslagen. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Retourneert een URL naar een extern object. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Slaat extern object op. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Bepaalt waar het object moet worden opgeslagen. Deze methode wordt één keer aangeroepen voor elke object-id. Het is niet gegarandeerd dat er geen twee objecten met dezelfde data, semanticName en contentType bestaan, maar met verschillende id-s.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | int | Object-id. Deze id is uniek binnen de gehele opslaan-operatie. |
| entityData | byte[] | Binaire data van het object. Deze parameter kan null zijn, als de binaire data van het object nog niet is gegenereerd. |
| semanticName | java.lang.String | Korte tekst die de betekenis van het object beschrijft. De controller kan dit gebruiken als onderdeel van de naam van het externe object, maar het is aan de dispatcher om ervoor te zorgen dat namen uniek zijn en alleen toegestane tekens bevatten. |
| contentType | java.lang.String | MIME-type van het object. |
| recomendedExtension | java.lang.String | Bestandsextensie die wordt aanbevolen voor dit MIME-type. |

**Retour:**
int - Beslissing
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Retourneert een URL naar een extern object. Deze methode wordt altijd aangeroepen als \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) heeft geretourneerd en kan worden aangeroepen als \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) heeft geretourneerd maar insluiting onmogelijk is. Kan meerdere keren worden aangeroepen voor dezelfde object-id.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | int | Object-id. Deze id is uniek binnen de gehele opslaan-operatie. |
| referrer | int | id van het verwezende object of 0, als het object wordt verwezen door het hoofddocument. Kan worden gebruikt om een relatieve link te genereren. |

**Retour:**
java.lang.String - Url van het externe object of null als dit object moet worden genegeerd.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


Slaat extern object op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | int | Object-id. Deze id is uniek binnen de gehele opslaan-operatie. |
| entityData | byte[] | Binaire data van het object. Deze parameter mag niet null zijn. |