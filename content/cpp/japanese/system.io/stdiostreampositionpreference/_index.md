---
title: STDIOStreamPositionPreference
second_title: Aspose.Slides for C++ API リファレンス
description: "ラッパー作成時に std::basic_iostream およびその派生クラスが読み取り位置と書き込み位置が異なる場合に、共通の読み取りおよび書き込み位置として好ましいストリーム内の位置を決定します。"
type: docs
weight: 586
url: /ja/system.io/stdiostreampositionpreference/
---
## STDIOStreamPositionPreference 列挙型

ラッパー作成時に std::basic_iostream およびその派生クラスが読み取り位置と書き込み位置が異なる場合に、一般的な読み取りおよび書き込み位置として好ましいストリーム内の位置を決定します。

```cpp
enum class STDIOStreamPositionPreference
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Zero | 0 | Zero 位置は読み取りおよび書き込み位置として設定されます。 |
| ReadPosition | 1 | gptr 位置は読み取りおよび書き込み位置として設定されます。 |
| WritePosition | 2 | pptr 位置は読み取りおよび書き込み位置として設定されます。 |

## 関連項目

* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)