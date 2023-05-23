---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
weight: 864
url: /java/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Callback interface used to determine how object should be processed during saving.
## Methods

| Method | Description |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Determines where object should be stored. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Returns an URL to an external object. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Saves external object. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Determines where object should be stored. This method is called once for each object id. It is not guaranteed that there won't be two objects with same data, semanticName and contentType but with different id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | Object id. This id is saving operation-wide unique. |
| entityData | byte[] | Object binary data. This parameter can be null, if object binary data is not generated yet. |
| semanticName | java.lang.String | Some short text, describing meaning of object. Controller may use this as a part of external object name, but it is up to dispatcher to ensure that names will be unique and contain only allowed characters. |
| contentType | java.lang.String | MIME type of object. |
| recomendedExtension | java.lang.String | File name extension, recommended for this MIME type. |

**Returns:**
int - Decision
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Returns an URL to an external object. This method always called if \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) returned [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) and may be called if \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) returned [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) but embedding is impossible. Can be called multiple time for same object id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | Object id. This id is saving operation-wide unique. |
| referrer | int | id of referrencing object or 0, if object is referrenced by the root document. May be used to generate relative link. |

**Returns:**
java.lang.String - Url of external object or null if this object should be ignored.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


Saves external object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | Object id. This id is saving operation-wide unique. |
| entityData | byte[] | Object binary data. This parameter cannot be null. |

