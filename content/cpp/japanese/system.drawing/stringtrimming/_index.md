---
title: StringTrimming
second_title: Aspose.Slides for C++ API リファレンス
description: レイアウト形状に収まらない文字列から文字をどのようにトリムすべきかを指定します。
type: docs
weight: 495
url: /ja/system.drawing/stringtrimming/
---
## StringTrimming 列挙型


レイアウト形状に収まらない文字列から文字をどのようにトリムするかを指定します。

```cpp
enum class StringTrimming
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | トリムしません。 |
| Character | 1 | 最も近い文字までトリムします。 |
| Word | 2 | 最も近い単語までトリムします。 |
| EllipsisCharacter | 3 | 最も近い文字までトリムし、文字列の末尾に省略記号を挿入します。 |
| EllipsisWord | 4 | 最も近い単語までトリムし、文字列の末尾に省略記号を挿入します。 |
| EllipsisPath | 5 | トリムされた行の中央部分が削除され、省略記号で置き換えられます。可能な限り、行の最後のスラッシュで区切られたセグメントを多く残します。 |

## 参照

* 名前空間 [System::Drawing](../)
* ライブラリ [Aspose.Slides](../../)