---
title: EmbeddingLevel
second_title: Aspose.Slides for Java API 参考
description: 表示用于嵌入字体的授权权利。
type: docs
url: /zh/com.aspose.slides/embeddinglevel/
---
**继承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

表示用于嵌入字体的授权权利。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Installable](#Installable) | 带有此设置的字体表示它们可以被嵌入并由应用程序永久安装在远程系统上。 |
| [Restricted](#Restricted) | 仅设置此位的字体必须在未经合法所有者许可的情况下，不能以任何方式进行修改、嵌入或交换。 |
| [PreviewPrint](#PreviewPrint) | 当设置此位时，字体可以被嵌入并临时加载到远程系统。 |
| [Editable](#Editable) | 当设置此位时，字体可以被嵌入，但只能在其他系统上临时安装。 |
| [NoSubsetting](#NoSubsetting) | 当设置此位时，字体在嵌入前不得进行子集化。 |
| [BitmapOnly](#BitmapOnly) | 当设置此位时，仅可以嵌入字体中包含的位图。 |
### 可安装的 {#Installable}
```
public static final int Installable
```

带有此设置的字体表示它们可以被嵌入并由应用程序永久安装在远程系统上。远程系统的用户获得与字体原始购买者相同的权利、义务和许可证，并受与原始购买者相同的最终用户许可协议、版权、设计专利和/或商标的约束。

### 受限的 {#Restricted}
```
public static final int Restricted
```

仅设置此位的字体必须在未经合法所有者许可的情况下，不能以任何方式进行修改、嵌入或交换。

### 预览打印 {#PreviewPrint}
```
public static final int PreviewPrint
```

当设置此位时，字体可以被嵌入并临时加载到远程系统。包含预览和打印字体的文档必须以只读方式打开；文档不能进行编辑。

### 可编辑的 {#Editable}
```
public static final int Editable
```

当设置此位时，字体可以被嵌入，但只能在其他系统上临时安装。与预览和打印字体不同，包含可编辑字体的文档可以打开进行阅读，允许编辑，并且可以保存更改。

### 不可子集化 {#NoSubsetting}
```
public static final int NoSubsetting
```

当设置此位时，字体在嵌入前不得进行子集化。位 0-3 和 9 中规定的其他嵌入限制亦适用。

### 仅位图 {#BitmapOnly}
```
public static final int BitmapOnly
```

当设置此位时，仅可以嵌入字体中包含的位图。轮廓数据不能被嵌入。如果字体中没有可用的位图，则该字体被视为不可嵌入，嵌入服务将失败。