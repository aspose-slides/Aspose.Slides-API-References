---
title: ILinkEmbedController
second_title: Aspose.Slides voor Android via Java API-referentie
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

Bepaalt waar het object moet worden opgeslagen. Deze methode wordt één keer per object-id aangeroepen. Het is niet gegarandeerd dat er geen twee objecten met dezelfde gegevens, semanticName en contentType maar met verschillende id’s bestaan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | int | Object-id. Deze id is uniek voor de gehele opslaactie. |
| entityData | byte[] | Binaire gegevens van het object. Deze parameter kan null zijn, als de binaire gegevens van het object nog niet zijn gegenereerd. |
| semanticName | java.lang.String | Korte tekst die de betekenis van het object beschrijft. De controller mag dit gebruiken als deel van de naam van het externe object, maar het is aan de dispatcher om te zorgen dat namen uniek zijn en alleen toegestane tekens bevatten. |
| contentType | java.lang.String | MIME-type van het object. |
| recomendedExtension | java.lang.String | Bestandsextensie, aanbevolen voor dit MIME-type. |

**Retourneert:**
int - Decision
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

Retourneert een URL naar een extern object. Deze methode wordt altijd aangeroepen als \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) retourneerde en kan worden aangeroepen als \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) retourneerde maar insluiten onmogelijk is. Kan meerdere keren worden aangeroepen voor dezelfde object-id.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | int | Object-id. Deze id is uniek voor de gehele opslaactie. |
| referrer | int | Id van het verwijzende object of 0, als het object wordt verwezen door het hoofd-document. Kan worden gebruikt om een relatieve link te genereren. |

**Retourneert:**
java.lang.String - URL van extern object of null als dit object moet worden genegeerd.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

Slaat extern object op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | int | Object-id. Deze id is uniek voor de gehele opslaactie. |
| entityData | byte[] | Binaire gegevens van het object. Deze parameter mag niet null zijn. |