---
title: Save()
second_title: Aspose.Slides for C++ API 参考
description: 将 XML 文档保存到指定的文件。如果指定的文件已存在，此方法会覆盖它。
type: docs
weight: 534
url: /zh/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) 方法

将 XML 文档保存到指定的文件。如果指定的文件已存在，此方法会覆盖它。

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | [String](../../../system/string/) | 您想要保存文档的文件位置。 |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) 方法

将 XML 文档保存到指定的流。

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 您想要保存的目标流。 |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) 方法

将 XML 文档保存到指定的 TextWriter。

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | 您想要保存的目标 TextWriter。 |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) 方法

将 XML 文档保存到指定的 [XmlWriter](../../xmlwriter/)。

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | 您想要保存的目标 [XmlWriter](../../xmlwriter/)。 |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [XmlDocument](../)
* 类 [Stream](../../../system.io/stream/)
* 类 [TextWriter](../../../system.io/textwriter/)
* 类 [XmlWriter](../../xmlwriter/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)