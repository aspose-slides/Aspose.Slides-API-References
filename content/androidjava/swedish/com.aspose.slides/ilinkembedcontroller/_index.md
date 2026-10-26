---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
description: Återuppringningsgränssnitt som används för att bestämma hur objektet ska bearbetas vid sparning.
type: docs
url: /sv/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Återuppringningsgränssnitt som används för att bestämma hur objektet ska bearbetas vid sparning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Bestämmer var objektet ska lagras. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Returnerar en URL till ett externt objekt. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Sparar externt objekt. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Bestämmer var objektet ska lagras. Denna metod anropas en gång för varje objekt-ID. Det är inte garanterat att det inte finns två objekt med samma data, semanticName och contentType men med olika ID.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | int | Objekt-ID. Detta ID är unikt för hela sparningsoperationen. |
| entityData | byte[] | Objektets binära data. Denna parameter kan vara null, om objektets binära data ännu inte har genererats. |
| semanticName | java.lang.String | Kort text som beskriver objektets innebörd. Kontrollen kan använda detta som en del av det externa objektets namn, men det är upp till dispatcher att säkerställa att namnen är unika och endast innehåller tillåtna tecken. |
| contentType | java.lang.String | MIME-typ för objektet. |
| recomendedExtension | java.lang.String | Filnamnstillägg rekommenderat för denna MIME-typ. |

**Returnerar:**
int - Beslut
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Returnerar en URL till ett externt objekt. Denna metod anropas alltid om #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) returnerade [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) och kan anropas om #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) returnerade [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) men inbäddning är omöjlig. Kan anropas flera gånger för samma objekt-ID.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | int | Objekt-ID. Detta ID är unikt för hela sparningsoperationen. |
| referrer | int | ID för refererande objekt eller 0, om objektet refereras av rot-dokumentet. Kan användas för att generera relativ länk. |

**Returnerar:**
java.lang.String - URL för externt objekt eller null om detta objekt ska ignoreras.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


Sparar externt objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | int | Objekt-ID. Detta ID är unikt för hela sparningsoperationen. |
| entityData | byte[] | Objektets binära data. Denna parameter får inte vara null. |