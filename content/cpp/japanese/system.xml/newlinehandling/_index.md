---
title: NewLineHandling
second_title: Aspose.Slides for C++ API リファレンス
description: 改行の処理方法を指定します。
type: docs
weight: 690
url: /ja/system.xml/newlinehandling/
---
## NewLineHandling 列挙体

改行の処理方法を指定します。

```cpp
enum class NewLineHandling
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Replace | 0 | 改行文字は [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/) の値で指定された文字に置き換えられます。 |
| Entitize | 1 | 改行文字はエンティティ化されます。この設定は、正規化する [XmlReader](../xmlreader/) で出力を読み取る場合にすべての文字を保持します。 |
| None | 2 | 改行文字は変更されません。出力は入力と同じです。 |

## 参照

* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)