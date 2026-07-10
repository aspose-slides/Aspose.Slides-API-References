---
title: Images
second_title: Aspose.Slides Android 版 Java API 参考
description: 用于实例化和使用的 .
type: docs
url: /zh/com.aspose.slides/images/
---
**继承:**  
java.lang.Object
```
public class Images
```

用于实例化和使用 [IImage](../../com.aspose.slides/iimage) 的方法。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Images()](#Images--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [fromData(byte[] imageData)](#fromData-byte---) | Create an image from byte array. |
| [fromFile(String filename)](#fromFile-java.lang.String-) | Create an image from the file. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Create an image from the stream. |
### Images() {#Images--}
```
public Images()
```

### fromData(byte[] imageData) {#fromData-byte---}
```
public static IImage fromData(byte[] imageData)
```

从字节数组创建图像。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageData | byte[] |  |

**返回:**
[IImage](../../com.aspose.slides/iimage)
### fromFile(String filename) {#fromFile-java.lang.String-}
```
public static IImage fromFile(String filename)
```

从文件创建图像。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | java.lang.String |  |

**返回:**
[IImage](../../com.aspose.slides/iimage)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static IImage fromStream(InputStream stream)
```

从流创建图像。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream |  |

**返回:**
[IImage](../../com.aspose.slides/iimage)