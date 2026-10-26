---
title: WriteState
second_title: Aspose.Slides for C++ API 參考文件
description: 指定 XmlWriter 的狀態。
type: docs
weight: 755
url: /zh-hant/system.xml/writestate/
---
## WriteState 列舉

指定 [XmlWriter](../xmlwriter/) 的狀態。

```cpp
enum class WriteState
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Start | 0 | 表示尚未呼叫 XmlWriter::Write 方法。 |
| Prolog | 1 | 表示正在寫入 prolog。 |
| Element | 2 | 表示正在寫入元素的起始標籤。 |
| Attribute | 3 | 表示正在寫入屬性值。 |
| Content | 4 | 表示正在寫入元素內容。 |
| Closed | 5 | 表示已呼叫 [XmlWriter::Close](../xmlwriter/close/) 方法。 |
| Error | 6 | 拋出了例外，使得 [XmlWriter](../xmlwriter/) 處於無效狀態。您可以呼叫 [XmlWriter::Close](../xmlwriter/close/) 方法將 [XmlWriter](../xmlwriter/) 置於 [WriteState::Closed](./) 狀態。任何其他 [XmlWriter](../xmlwriter/) 方法的呼叫都會導致 InvalidOperationException。 |

## 另請參閱

* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)