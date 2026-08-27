---
title: Background
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/background/
---
## Background 类

表示幻灯片的背景。

### getEffectFormat {#getEffectFormat}

| 名称 | 描述 |
| --- | --- |
| getEffectFormat () | 返回一个用于 BackgroundType.OwnBackground 填充的 EffectFormat。只读 IEffectFormat。 |

**返回:**  
[EffectFormat](../effectformat)

---

### getEffective {#getEffective}

| 名称 | 描述 |
| --- | --- |
| getEffective () | 获取已应用继承的有效背景数据。 |

**返回:**  
BackgroundEffectiveData

---

### getFillFormat {#getFillFormat}

| 名称 | 描述 |
| --- | --- |
| getFillFormat () | 返回一个用于 BackgroundType.OwnBackground 填充的 FillFormat。只读 IFillFormat。 |

**返回:**  
[FillFormat](../fillformat)

---

### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回幻灯片的父级演示文稿。只读 IPresentation。 |

**返回:**  
Presentation

---

### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () | 返回形状的父幻灯片。只读 IBaseSlide。 |

**返回:**  
BaseSlide

---

### getStyleColor {#getStyleColor}

| 名称 | 描述 |
| --- | --- |
| getStyleColor () | 返回一个用于 BackgroundType.Themed 填充的 ColorFormat。只读 IColorFormat。 |

**返回:**  
[ColorFormat](../colorformat)

---

### getStyleIndex {#getStyleIndex}

| 名称 | 描述 |
| --- | --- |
| getStyleIndex () | 返回背景主题集合中 BackgroundType.Themed 填充的索引。0 表示无填充。1..999 为索引。可读写 int。 |

**返回:**  
int

---

### getType {#getType}

| 名称 | 描述 |
| --- | --- |
| getType () | 返回背景填充的类型。可读写 BackgroundType。 |

**返回:**  
byte

---

### getVersion {#getVersion}

| 名称 | 描述 |
| --- | --- |
| getVersion () |  |

**返回:**  
long

---

### setStyleIndex {#setStyleIndex}

| 名称 | 描述 |
| --- | --- |
| setStyleIndex (int) | 返回背景主题集合中 BackgroundType.Themed 填充的索引。0 表示无填充。1..999 为索引。可读写 int。 |

**返回:**  
void

---

### setType {#setType}

| 名称 | 描述 |
| --- | --- |
| setType (byte) | 返回背景填充的类型。可读写 BackgroundType。 |

**返回:**  
void

---