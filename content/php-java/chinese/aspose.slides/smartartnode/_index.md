---
title: SmartArtNode
second_title: Aspose.Sildes for PHP 的 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/smartartnode/
---
## SmartArtNode 类

 表示 SmartArt 对象的节点

### getBulletFillFormat {#getBulletFillFormat}

| Name | Description |
| --- | --- |
| getBulletFillFormat () | 返回 包含节点项目符号填充属性的 FillFormat 对象。注意：对于某些不提供项目符号的 SmartArt 布局，可能返回 null。只读 IFillFormat. |

 **返回:**
[FillFormat](../fillformat)

---

### getChildNodes {#getChildNodes}

| Name | Description |
| --- | --- |
| getChildNodes () | 返回 当前节点的所有子节点的集合。只读 ISmartArtNodeCollection. |

 **返回:**
[SmartArtNodeCollection](../smartartnodecollection)

---

### getLevel {#getLevel}

| Name | Description |
| --- | --- |
| getLevel () | 返回 节点的嵌套级别。只读 int. |

 **返回:**
int

---

### getOrganizationChartLayout {#getOrganizationChartLayout}

| Name | Description |
| --- | --- |
| getOrganizationChartLayout () | 返回或设置 与当前节点关联的组织结构图布局类型。可读写 OrganizationChartLayoutType. |

 **返回:**
int

---

### getPosition {#getPosition}

| Name | Description |
| --- | --- |
| getPosition () | 返回或设置 节点在同级节点中的零基位置。可读写 int. |

 **返回:**
int

 **异常**

| Error | Condition |
| --- | --- |
| ArgumentOutOfRangeException | 值小于 0，或值大于等于同级节点数量 |

---

### getShapes {#getShapes}

| Name | Description |
| --- | --- |
| getShapes () | 返回 与节点关联的所有形状的集合。只读 ISmartArtShapeCollection. |

 **返回:**
[SmartArtShapeCollection](../smartartshapecollection)

---

### getTextFrame {#getTextFrame}

| Name | Description |
| --- | --- |
| getTextFrame () | 返回 节点的文本框。只读 ITextFrame. |

 **返回:**
[TextFrame](../textframe)

---

### isAssistant {#isAssistant}

| Name | Description |
| --- | --- |
| isAssistant () | 返回或设置 节点为助手。可读写 boolean. |

 **返回:**
boolean

---

### isHidden {#isHidden}

| Name | Description |
| --- | --- |
| isHidden () | 如果此节点在数据模型中是隐藏节点，则返回 true。只读 boolean. |

 **返回:**
boolean

---

### remove {#remove}

| Name | Description |
| --- | --- |
| remove () | 删除当前节点。 |

 **返回:**
boolean

---

### setAssistant {#setAssistant}

| Name | Description |
| --- | --- |
| setAssistant (boolean) | 返回或设置 节点为助手。可读写 boolean. |

 **返回:**
void

---

### setOrganizationChartLayout {#setOrganizationChartLayout}

| Name | Description |
| --- | --- |
| setOrganizationChartLayout (int) | 返回或设置 与当前节点关联的组织结构图布局类型。可读写 OrganizationChartLayoutType. |

 **返回:**
void

---

### setPosition {#setPosition}

| Name | Description |
| --- | --- |
| setPosition (int) | 返回或设置 节点在同级节点中的零基位置。可读写 int. |

 **返回:**
void

 **异常**

| Error | Condition |
| --- | --- |
| ArgumentOutOfRangeException | 值小于 0，或值大于等于同级节点数量 |

---