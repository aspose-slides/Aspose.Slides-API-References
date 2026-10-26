---
title: SystemIOStreamWrappingMode
second_title: Aspose.Slides for C++ API リファレンス
description: "ラッパーが System::IO::Stream のようなストリームに対して実行する I/O 操作のモードを指定します。"
type: docs
weight: 599
url: /ja/system.io/systemiostreamwrappingmode/
---
## SystemIOStreamWrappingMode 列挙型

[System::IO::Stream](../stream/) のようなストリームに対してラッパーが実行する I/O 操作のモードを指定します。

```cpp
enum class SystemIOStreamWrappingMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Binary | 0 | 入力操作がストリームバイトを char_type データにエンコードし、出力操作が char_type データをストリームバイトにデコードできるモードです。 |
| Conversion | 1 | 入力操作がストリームバイトを **uint8_t** 型から char_type 型へ、出力操作がその逆に変換できるモードです。 |

## 参照

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)