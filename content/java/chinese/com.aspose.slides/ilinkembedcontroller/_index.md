---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /zh/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

用于确定在保存过程中对象应如何处理的回调接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | 确定对象应存储的位置。 |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | 返回指向外部对象的 URL。 |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | 保存外部对象。 |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


确定对象应存储的位置。此方法对每个对象 id 调用一次。无法保证不会出现具有相同数据、semanticName 和 contentType 但 id 不同的两个对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | int | 对象 id。此 id 在整个保存操作中唯一。 |
| entityData | byte[] | 对象二进制数据。如果对象二进制数据尚未生成，此参数可以为 null。 |
| semanticName | java.lang.String | 一些简短文本，描述对象的含义。控制器可能将其用作外部对象名称的一部分，但由调度程序确保名称唯一且只包含允许的字符。 |
| contentType | java.lang.String | 对象的 MIME 类型。 |
| recomendedExtension | java.lang.String | 针对该 MIME 类型推荐的文件扩展名。 |

**返回:**
int - 决策
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


返回指向外部对象的 URL。如果 \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) 返回 [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link)，则始终调用此方法；如果返回 [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) 但嵌入不可能，则可能调用此方法。可以对同一对象 id 多次调用。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | int | 对象 id。此 id 在整个保存操作中唯一。 |
| referrer | int | 引用对象的 id，或者为 0 表示对象由根文档引用。可用于生成相对链接。 |

**返回:**
java.lang.String - 外部对象的 URL，若该对象应被忽略则为 null。
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


保存外部对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | int | 对象 id。此 id 在整个保存操作中唯一。 |
| entityData | byte[] | 对象二进制数据。此参数不能为空。 |