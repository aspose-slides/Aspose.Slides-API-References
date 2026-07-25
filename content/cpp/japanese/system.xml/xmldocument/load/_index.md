---
title: Load()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された URL から XML ドキュメントをロードします。
type: docs
weight: 508
url: /ja/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) メソッド

指定された URL から XML ドキュメントをロードします。

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [String](../../../system/string/) | ロードする XML ドキュメントを含むファイルの URL。URL はローカルファイルまたは HTTP URL（[Web](../../../system.web/) アドレス）のいずれかです。 |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) メソッド

指定されたストリームから XML ドキュメントをロードします。

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | ロードする XML ドキュメントを含むストリーム。 |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) メソッド

指定された TextReader から XML ドキュメントをロードします。

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | XML データをドキュメントに供給するために使用される TextReader。 |

## XmlDocument::Load(SharedPtr\<XmlReader\>) メソッド

指定された [XmlReader](../../xmlreader/) から XML ドキュメントをロードします。

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | XML データをドキュメントに供給するために使用される [XmlReader](../../xmlreader/)。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [XmlDocument](../)
* クラス [Stream](../../../system.io/stream/)
* クラス [TextReader](../../../system.io/textreader/)
* クラス [XmlReader](../../xmlreader/)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)