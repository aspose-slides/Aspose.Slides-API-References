---
title: GetValueOf()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前を持つ列挙定数のボックス化された値を返します。
type: docs
weight: 53
url: /ja/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const method

指定された名前を持つ列挙定数のボックス化された値を返します。

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 列挙定数の名前 |
| ignoreCase | **bool** | 列挙定数の名前を解釈する際に大文字小文字を無視すべきかどうかを指定します |

### 戻り値

**str** で指定された名前の列挙定数のボックス化された値です。

## EnumValues::GetValueOf(long) const method

指定された値を持つ列挙定数のボックス化された値を返します。

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| val | long | 列挙定数の値 |

### 戻り値

**str** で指定された値の列挙定数のボックス化された値です。

## 参照

* 型定義 [SharedPtr](../../sharedptr/)
* クラス [Object](../../object/)
* クラス [String](../../string/)
* クラス [EnumValues](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)