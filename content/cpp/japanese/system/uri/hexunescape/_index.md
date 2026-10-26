---
title: HexUnescape()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字の16進表現を文字に変換します。
type: docs
weight: 443
url: /ja/system/uri/hexunescape/
---
## Uri::HexUnescape(const String\&, int32_t\&) メソッド

指定された文字の16進表現を文字に変換します。

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | 文字の16進表現を含む文字列 |
| index | **int32_t**\& | **pattern** 内で文字の16進表現が始まる位置 |

### 戻り値

位置 **index** の16進エンコードで表される文字を返します。**index** の位置にある文字が16進エンコードされていない場合、その文字がそのまま返されます。**index** の値は、返された文字の次の文字を指すようにインクリメントされます。

## 参照

* クラス [String](../../string/)
* クラス [Uri](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)