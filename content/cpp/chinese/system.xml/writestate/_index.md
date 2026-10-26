---
title: WriteState
second_title: Aspose.Slides C++ API 参考
description: 指定 XmlWriter 的状态。
type: docs
weight: 755
url: /zh/system.xml/writestate/
---
## WriteState 枚举

指定 [XmlWriter](../xmlwriter/) 的状态。

```cpp
enum class WriteState
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Start | 0 | 指示 XmlWriter::Write 方法尚未被调用。 |
| Prolog | 1 | 指示正在写入序言。 |
| Element | 2 | 指示正在写入元素开始标签。 |
| Attribute | 3 | 指示正在写入属性值。 |
| Content | 4 | 指示正在写入元素内容。 |
| Closed | 5 | 指示已调用 [XmlWriter::Close](../xmlwriter/close/) 方法。 |
| Error | 6 | 抛出异常，导致 [XmlWriter](../xmlwriter/) 处于无效状态。您可以调用 [XmlWriter::Close](../xmlwriter/close/) 方法将 [XmlWriter](../xmlwriter/) 设置为 [WriteState::Closed](./) 状态。任何其他 [XmlWriter](../xmlwriter/) 方法调用都会导致 InvalidOperationException。 |

## 另见

* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)