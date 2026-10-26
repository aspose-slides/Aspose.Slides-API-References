---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: 用於決定在保存期間如何處理物件的回呼介面。
type: docs
url: /zh-hant/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

用於決定在保存期間如何處理物件的回呼介面。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | 決定物件應該儲存的位置。 |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | 傳回外部物件的 URL。 |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | 儲存外部物件。 |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

決定物件應該儲存的位置。此方法對每個物件 id 只會呼叫一次。無法保證不會有兩個物件具有相同的資料、semanticName 和 contentType 但 id 不同。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| id | int | 物件 id。此 id 在整個保存操作中唯一。 |
| entityData | byte[] | 物件二進位資料。若尚未產生物件二進位資料，此參數可以為 null。 |
| semanticName | java.lang.String | 一些簡短文字，描述物件的含義。控制器可能會將其用作外部物件名稱的一部分，但由分派器確保名稱唯一且僅包含允許的字元。 |
| contentType | java.lang.String | 物件的 MIME 類型。 |
| recomendedExtension | java.lang.String | 檔名副檔名，建議用於此 MIME 類型。 |

**傳回：**
int - 決策
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

傳回外部物件的 URL。如果 \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) 回傳 [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link)，此方法總是會被呼叫；如果回傳 [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) 但無法嵌入，可能會被呼叫。可對相同物件 id 多次呼叫。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| id | int | 物件 id。此 id 在整個保存操作中唯一。 |
| referrer | int | 參考物件的 id，若物件被根文件參考則為 0。可用於產生相對連結。 |

**傳回：**
java.lang.String - 外部物件的 URL，若此物件應被忽略則為 null。
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

儲存外部物件。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| id | int | 物件 id。此 id 在整個保存操作中唯一。 |
| entityData | byte[] | 物件二進位資料。此參數不能為 null。 |