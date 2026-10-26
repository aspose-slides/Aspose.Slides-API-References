---
title: EmbeddingLevel
second_title: Aspose.Slides for Android via Java API 参考文档
description: 表示用于嵌入字体的许可权利。
type: docs
url: /zh/com.aspose.slides/embeddinglevel/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

表示用于嵌入字体的许可权利。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Installable](#Installable) | 具有此设置的字体表示它们可以被嵌入并永久安装在远程系统上，由应用程序进行。 |
| [Restricted](#Restricted) | 仅设置了此位的字体在未先获得合法所有者的许可之前，禁止以任何方式修改、嵌入或交换。 |
| [PreviewPrint](#PreviewPrint) | 当此位被设置时，字体可以被嵌入，并临时加载到远程系统上。 |
| [Editable](#Editable) | 当此位被设置时，字体可以被嵌入，但只能临时安装在其他系统上。 |
| [NoSubsetting](#NoSubsetting) | 当此位被设置时，嵌入前不得对字体进行子集化。 |
| [BitmapOnly](#BitmapOnly) | 当此位被设置时，仅可以嵌入字体中包含的位图。 |
### Installable {#Installable}
```
public static final int Installable
```

具有此设置的字体表示它们可以被嵌入并永久安装在远程系统上，由应用程序进行。远程系统的用户获得与原始购买者相同的权利、义务和许可证，并受原始购买者相同的最终用户许可协议、版权、外观专利和/或商标约束。

### Restricted {#Restricted}
```
public static final int Restricted
```

仅设置了此位的字体在未先获得合法所有者的许可之前，禁止以任何方式修改、嵌入或交换。

### PreviewPrint {#PreviewPrint}
```
public static final int PreviewPrint
```

当此位被设置时，字体可以被嵌入，并临时加载到远程系统上。包含 Preview & Print 字体的文档必须以“只读”方式打开；不能对文档进行编辑。

### Editable {#Editable}
```
public static final int Editable
```

当此位被设置时，字体可以被嵌入，但只能临时安装在其他系统上。与 Preview & Print 字体相反，包含 Editable 字体的文档可以打开阅读，允许编辑，并且可以保存更改。

### NoSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```

当此位被设置时，嵌入前不得对字体进行子集化。位于第 0-3 位和第 9 位中指定的其他嵌入限制也适用。

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```

当此位被设置时，仅可以嵌入字体中包含的位图。不能嵌入轮廓数据。如果字体中没有可用的位图，则视为不可嵌入，嵌入服务将失败。