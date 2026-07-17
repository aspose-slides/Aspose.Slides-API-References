---
title: EmbeddingLevel
second_title: Aspose.Slides for C++ API 参考
description: 表示嵌入字体的许可权利。
type: docs
weight: 5786
url: /zh/aspose.slides/embeddinglevel/
---
## EmbeddingLevel 枚举

表示嵌入字体的许可权利。

```cpp
enum class EmbeddingLevel : uint16_t
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Installable | 0 | [Fonts](../fonts/) 使用此设置表示它们可以被嵌入并永久安装在远程系统上，由应用程序完成。远程系统的用户获得与该字体的原始购买者相同的权利、义务和许可证，并受相同的最终用户许可协议、版权、外观专利和/或商标约束，正如原始购买者一样。 |
| Restricted | 2 | [Fonts](../fonts/) 只设置了此位的必须在未先获得合法所有者许可的情况下，不能以任何方式修改、嵌入或交换。 |
| PreviewPrint | 4 | 当设置此位时，字体可以被嵌入，并临时加载到远程系统。包含预览与打印字体的文档必须以\"只读;\"方式打开；文档不能被编辑。 |
| Editable | 8 | 当设置此位时，字体可以被嵌入，但只能在其他系统上临时安装。与预览与打印字体相对，包含可编辑字体的文档可以打开以供阅读，允许编辑，并且可以保存更改。 |
| NoSubsetting | 256 | 当设置此位时，字体在嵌入前不得进行子集化。位 0-3 和 9 中指定的其他嵌入限制同样适用。 |
| BitmapOnly | 512 | 当设置此位时，仅可嵌入字体中包含的位图。轮廓数据不能被嵌入。如果字体中没有可用的位图，则该字体被视为不可嵌入，嵌入服务将失败。 |

## 另见

* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)