---
title: ILinkEmbedController
second_title: Aspose.Slides for Android 之 Java API 參考
description: 用於決定在儲存過程中如何處理物件的回呼介面。
type: docs
url: /zh-hant/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

用於決定在儲存過程中如何處理物件的回呼介面。
## 方法

| Method | Description |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | 決定物件應儲存的位置。 |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | 傳回外部物件的 URL。 |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | 儲存外部物件。 |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

決定物件應儲存的位置。此方法會在每個物件 id 被呼叫一次。無法保證不會出現兩個具有相同資料、semanticName 與 contentType 但 id 不同的物件。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | 物件 ID。此 ID 在整個儲存操作中唯一。 |
| entityData | byte[] | 物件二進位資料。若尚未產生物件二進位資料，則此參數可以為 null。 |
| semanticName | java.lang.String | 一些簡短文字，用於描述物件的意義。Controller 可能會將此作為外部物件名稱的一部份，但名稱的唯一性與僅包含允許的字元需由 dispatcher 確保。 |
| contentType | java.lang.String | 物件的 MIME 類型。 |
| recomendedExtension | java.lang.String | 建議用於此 MIME 類型的檔案副檔名。 |

**傳回:**
int - 決策
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

傳回外部物件的 URL。若 #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) 回傳 [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link)，則此方法一定會被呼叫；若回傳 [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) 但無法嵌入，則可能會被呼叫。相同物件 ID 可多次呼叫此方法。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | 物件 ID。此 ID 在整個儲存操作中唯一。 |
| referrer | int | 參考物件的 ID，若為 0，表示此物件被根文件參考。可用於產生相對連結。 |

**傳回:**
java.lang.String - 外部物件的 URL，若此物件應被忽略則回傳 null。
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

儲存外部物件。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | 物件 ID。此 ID 在整個儲存操作中唯一。 |
| entityData | byte[] | 物件二進位資料。此參數不能為 null。 |