---
title: WriteAttributes()
second_title: Aspose.Slides C++ 用 API リファレンス
description: 派生クラスでオーバーライドされた場合、XmlReader の現在位置で見つかったすべての属性を書き出します。
type: docs
weight: 417
url: /ja/system.xml/xmlwriter/writeattributes/
---
## XmlWriter::WriteAttributes(SharedPtr\<XmlReader\>, bool) メソッド


派生クラスでオーバーライドされた場合、[XmlReader](../../xmlreader/)の現在位置で見つかったすべての属性を書き出します。

```cpp
virtual void System::Xml::XmlWriter::WriteAttributes(SharedPtr<XmlReader> reader, bool defattr)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | 属性をコピーする元となる[XmlReader](../../xmlreader/)です。 |
| defattr | **bool** | **true** は [XmlReader](../../xmlreader/) からデフォルト属性をコピーするため、**false** の場合はコピーしません。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlReader](../../xmlreader/)
* クラス [XmlWriter](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)