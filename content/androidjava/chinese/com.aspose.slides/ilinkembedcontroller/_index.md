---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API 参考
description: 用于确定对象在保存期间应如何处理的回调接口。
type: docs
url: /zh/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

用于确定对象在保存期间应如何处理的回调接口。
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

确定对象应存储的位置。此方法会针对每个对象 id 调用一次。不能保证没有两个对象拥有相同的数据、semanticName 和 contentType，但 id 不同。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | int | 对象 id。此 id 在整个保存操作中唯一。 |
| entityData | byte[] | 对象二进制数据。如果对象二进制数据尚未生成，此参数可以为 null。 |
| semanticName | java.lang.String | 简短文本，描述对象的含义。控制器可以将其用作外部对象名称的一部分，但由调度程序确保名称唯一且仅包含允许的字符。 |
| contentType | java.lang.String | 对象的 MIME 类型。 |
| recomendedExtension | java.lang.String | 文件名扩展名，针对该 MIME 类型的推荐扩展名。 |

**返回值:**
int - 决策
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

返回指向外部对象的 URL。如果 \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) 返回 [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link)，则始终调用此方法；如果返回 [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) 且嵌入不可行，也可能调用此方法。可以对同一对象 id 多次调用。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | int | 对象 id。此 id 在整个保存操作中唯一。 |
| referrer | int | 引用对象的 id，或为 0 表示对象由根文档引用。可用于生成相对链接。 |

**返回值:**
java.lang.String - 外部对象的 URL，或者如果应该忽略此对象则为 null。
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