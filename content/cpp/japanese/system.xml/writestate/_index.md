---
title: WriteState
second_title: Aspose.Slides for C++ API リファレンス
description: XmlWriter の状態を指定します。
type: docs
weight: 755
url: /ja/system.xml/writestate/
---
## WriteState 列挙体

[XmlWriter](../xmlwriter/) の状態を指定します。

```cpp
enum class WriteState
```

### 列挙値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Start | 0 | XmlWriter::Write メソッドがまだ呼び出されていないことを示します。 |
| Prolog | 1 | プロローグが書き込まれていることを示します。 |
| Element | 2 | 要素の開始タグが書き込まれていることを示します。 |
| Attribute | 3 | 属性値が書き込まれていることを示します。 |
| Content | 4 | 要素のコンテンツが書き込まれていることを示します。 |
| Closed | 5 | [XmlWriter::Close](../xmlwriter/close/) メソッドが呼び出されたことを示します。 |
| Error | 6 | 例外がスローされ、[XmlWriter](../xmlwriter/) が無効な状態になっています。[XmlWriter::Close](../xmlwriter/close/) メソッドを呼び出すことで、[XmlWriter](../xmlwriter/) を [WriteState::Closed](./) 状態に設定できます。他の [XmlWriter](../xmlwriter/) メソッド呼び出しは InvalidOperationException を引き起こします。 |

## 参照

* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)