---
title: ResourceLoadingAction
second_title: 适用于 Android 的 Aspose.Slides（通过 Java API）参考
description: 指定外部资源加载的模式。
type: docs
url: /zh/com.aspose.slides/resourceloadingaction/
---
**继承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

指定外部资源加载的模式。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Default](#Default) | Aspose.Slides 将按常规加载外部资源。 |
| [Skip](#Skip) | Aspose.Slides 将跳过外部资源的加载。 |
| [UserProvided](#UserProvided) | Aspose.Slides 将使用用户在[IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) 中提供的字节数组作为图像数据。 |
### Default {#Default}
```
public static final int Default
```

Aspose.Slides 将按常规加载外部资源。

### Skip {#Skip}
```
public static final int Skip
```

Aspose.Slides 将跳过外部资源的加载。仅会为图像存储没有数据的链接。

### UserProvided {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides 将使用用户在[IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) 中提供的字节数组作为图像数据。