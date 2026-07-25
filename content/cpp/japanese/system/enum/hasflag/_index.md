---
title: HasFlag()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された列挙型値のビタリ表現で、指定されたビットが設定されているかどうかを判断します。
type: docs
weight: 14
url: /ja/system/enum/hasflag/
---
## Enum::HasFlag(E, E) メソッド

指定された列挙型値のビタリ表現で、指定されたビットが設定されているかどうかを判断します。

```cpp
static bool System::Enum<E, Guard>::HasFlag(E value, E mask)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | E | テストする列挙型の値 |
| mask | E | value のビットをチェックするためのマスク |

### 戻り値

**mask** に設定されているビットが **value** にも設定されている場合は true、そうでなければ false

## 参照

* 構造体 [Enum](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)