---
title: Portion
second_title: 通过 Java API 的 Aspose.Sildes PHP 参考
description: 
type: docs
url: /zh/aspose.slides/portion/
---
## Portion 类

表示文本段落内的一段文本。

### Portion {#Portion}

| 名称 | 描述 |
| --- | --- |
| Portion() | 初始化 Portion 类的新实例。 |

**返回：**
Portion

---

### Portion {#Portion}

| 名称 | 描述 |
| --- | --- |
| Portion(String) | 初始化 Portion 类的新实例。 |

**返回：**
Portion

---

### Portion {#Portion}

| 名称 | 描述 |
| --- | --- |
| Portion([Portion](../portion)) | 初始化 Portion 类的新实例。 |

**返回：**
Portion

---

### addField {#addField}

| 名称 | 描述 |
| --- | --- |
| addField ([FieldType](../fieldtype)) | 将此部分转换为自动更新的字段。 |

**返回：**
void

---

### addField {#addField}

| 名称 | 描述 |
| --- | --- |
| addField (String) | 将此部分转换为自动更新的字段。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| internalString | String | FieldType 的内部名称。 |

**返回：**
void

---

### getCoordinates {#getCoordinates}

| 名称 | 描述 |
| --- | --- |
| getCoordinates () | 获取该部分起始位置的坐标。点的 X 坐标表示从包括左侧间距的第一个字符开始的部分起点，Y 坐标包括顶部间距。 |

**返回：**
Point2D.Float

---

### getField {#getField}

| 名称 | 描述 |
| --- | --- |
| getField () | 返回此部分的字段。只读 IField。 |

**返回：**
[Field](../field)

---

### getPortionFormat {#getPortionFormat}

| 名称 | 描述 |
| --- | --- |
| getPortionFormat () | 返回格式对象，其中包含仅针对该文本部分显式设置的格式属性，不应用继承。只读 IPortionFormat。该格式对象仅包含当前部分的格式参数，不会应用继承数据。如需获取包括继承在内的有效值，请使用 PortionFormat#getEffective 方法。 |

**返回：**
[PortionFormat](../portionformat)

---

### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回文本所属的父级演示文稿。只读 IPresentation。 |

**返回：**
[Presentation](../presentation)

---

### getRect {#getRect}

| 名称 | 描述 |
| --- | --- |
| getRect () | 获取围绕该部分的矩形坐标。该矩形包括部分中的所有文本行，包括空行。 |

**返回：**
Rectangle2D.Float

---

### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () | 返回文本所属的父级幻灯片。只读 BaseSlide。 |

**返回：**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)

---

### getText {#getText}

| 名称 | 描述 |
| --- | --- |
| getText () | 获取或设置该部分的纯文本。可读写 String。值：文本内容。 |

**返回：**
String

---

### removeField {#removeField}

| 名称 | 描述 |
| --- | --- |
| removeField () | 将此字段部分转换为普通部分。 |

**返回：**
void

---

### setText {#setText}

| 名称 | 描述 |
| --- | --- |
| setText (String) | 获取或设置该部分的纯文本。可读写 String。值：文本内容。 |

**返回：**
void

---