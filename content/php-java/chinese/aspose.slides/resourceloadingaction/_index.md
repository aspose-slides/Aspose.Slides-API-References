---
title: ResourceLoadingAction
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/resourceloadingaction/
---
## ResourceLoadingAction 类

指定外部资源加载的模式。

## 常量

| 名称 | 值 | 描述 |
| --- | --- | --- |
[Default](#Default) | 0 | Aspose.Slides 将像往常一样加载外部资源。 |
[Skip](#Skip) | 1 | Aspose.Slides 将跳过加载外部资源。对于图像，仅存储不含数据的链接。 |
[UserProvided](#UserProvided) | 2 | Aspose.Slides 将使用用户在 IResourceLoadingArgs#setData(byte[]) 中提供的字节数组作为图像数据。 |

---


### Default {#Default}
Aspose.Slides 将像往常一样加载外部资源。

---

### Skip {#Skip}
Aspose.Slides 将跳过加载外部资源。对于图像，仅存储不含数据的链接。

---

### UserProvided {#UserProvided}
Aspose.Slides 将使用用户在 IResourceLoadingArgs#setData(byte[]) 中提供的字节数组作为图像数据。

---