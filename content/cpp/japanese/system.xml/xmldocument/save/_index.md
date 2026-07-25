---
title: Save()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたファイルに XML ドキュメントを保存します。指定されたファイルが存在する場合、このメソッドは上書きします。
type: docs
weight: 534
url: /ja/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) メソッド

指定されたファイルに XML ドキュメントを保存します。指定されたファイルが存在する場合、このメソッドは上書きします。

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | [String](../../../system/string/) | ドキュメントを保存したいファイルの場所。 |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) メソッド

指定されたストリームに XML ドキュメントを保存します。

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 保存したいストリーム。 |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) メソッド

指定された TextWriter に XML ドキュメントを保存します。

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | 保存したい TextWriter。 |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) メソッド

指定された [XmlWriter](../../xmlwriter/) に XML ドキュメントを保存します。

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | 保存したい [XmlWriter](../../xmlwriter/)。 |

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [XmlDocument](../)
* クラス [Stream](../../../system.io/stream/)
* クラス [TextWriter](../../../system.io/textwriter/)
* クラス [XmlWriter](../../xmlwriter/)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)