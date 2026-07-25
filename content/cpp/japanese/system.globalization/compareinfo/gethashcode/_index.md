---
title: GetHashCode()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定された比較オプションに基づいて文字列のハッシュコードを取得します。
type: docs
weight: 144
url: /ja/system.globalization/compareinfo/gethashcode/
---
## CompareInfo::GetHashCode(const String\&, CompareOptions) const メソッド

指定された比較オプションに基づいて文字列のハッシュコードを取得します。

```cpp
virtual int System::Globalization::CompareInfo::GetHashCode(const String &value, CompareOptions options) const
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 入力文字列。 |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 比較オプション。 |

### 戻り値

ハッシュコード。

## CompareInfo::GetHashCode() const メソッド

C# [Object.GetHashCode()](../../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。

```cpp
int System::Globalization::CompareInfo::GetHashCode() const override
```

### 戻り値

対応するクラスで計算されたハッシュコード値。

## 参照

* 列挙型 [CompareOptions](../../compareoptions/)
* クラス [String](../../../system/string/)
* クラス [CompareInfo](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)