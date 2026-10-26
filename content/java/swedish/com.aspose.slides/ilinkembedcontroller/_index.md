---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: Callback-gränssnitt som används för att bestämma hur ett objekt ska behandlas vid sparning.
type: docs
url: /sv/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Callback-gränssnitt som används för att bestämma hur ett objekt ska behandlas vid sparning.
## Methods

| Method | Description |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Bestämmer var objektet ska lagras. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Returnerar en URL till ett externt objekt. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Sparar externt objekt. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

Bestämmer var objektet ska lagras. Denna metod anropas en gång för varje objekt-id. Det är inte garanterat att det inte finns två objekt med samma data, semanticName och contentType men med olika id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | Objekt-id. Detta id är unikt för hela sparningsoperationen. |
| entityData | byte[] | Objektets binära data. Denna parameter kan vara null, om objektets binära data ännu inte har genererats. |
| semanticName | java.lang.String | Kort text som beskriver objektets betydelse. Kontrollen kan använda detta som en del av det externa objektets namn, men det är upp till dispatcher att säkerställa att namn är unika och endast innehåller tillåtna tecken. |
| contentType | java.lang.String | MIME-typ för objektet. |
| recomendedExtension | java.lang.String | Filnamnstillägg som rekommenderas för denna MIME-typ. |

**Returns:**
int - Beslut
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

Returnerar en URL till ett externt objekt. Denna metod anropas alltid om \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) returnerade [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) och kan anropas om \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) returnerade [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) men inbäddning är omöjlig. Kan anropas flera gånger för samma objekt-id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | Objekt-id. Detta id är unikt för hela sparningsoperationen. |
| referrer | int | Id för refererande objekt eller 0, om objektet refereras av huvud-dokumentet. Kan användas för att generera relativ länk. |

**Returns:**
java.lang.String - URL till externt objekt eller null om detta objekt ska ignoreras.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

Sparar externt objekt.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | Objekt-id. Detta id är unikt för hela sparningsoperationen. |
| entityData | byte[] | Objektets binära data. Denna parameter får inte vara null. |