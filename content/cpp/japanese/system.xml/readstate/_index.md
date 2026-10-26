---
title: ReadState
second_title: Aspose.Slides for C++ API リファレンス
description: リーダーの状態を指定します。
type: docs
weight: 703
url: /ja/system.xml/readstate/
---
## ReadState 列挙型

リーダーの状態を指定します。

```cpp
enum class ReadState
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Initial | 0 | [XmlReader::Read](../xmlreader/read/) メソッドは呼び出されていません。 |
| Interactive | 1 | [XmlReader::Read](../xmlreader/read/) メソッドが呼び出されました。リーダーで追加のメソッドを呼び出すことができます。 |
| Error | 2 | 読み取り操作の継続を妨げるエラーが発生しました。 |
| EndOfFile | 3 | ファイルの終端に正常に到達しました。 |
| Closed | 4 | [XmlReader::Close](../xmlreader/close/) メソッドが呼び出されました。 |

## 参照

* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)