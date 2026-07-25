---
title: CompareTo()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトと指定されたオブジェクトを比較します。
type: docs
weight: 27
url: /ja/system/timespan/compareto/
---
## TimeSpan::CompareTo(TimeSpan) const メソッド

現在のオブジェクトと指定されたオブジェクトを比較します。

```cpp
constexpr int System::TimeSpan::CompareTo(TimeSpan value) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [TimeSpan](../) | 現在のオブジェクトと比較する [TimeSpan](../) オブジェクト |

### 戻り値

- 1 は、現在のオブジェクトが **value** より短い間隔を表す場合；0 は、現在のオブジェクトが **value** と等しい間隔を表す場合；1 は、現在のオブジェクトが **value** より長い間隔を表す場合

## TimeSpan::CompareTo(const SharedPtr\<Object\>\&) const メソッド

現在のオブジェクトと指定されたオブジェクトを比較します。

```cpp
int System::TimeSpan::CompareTo(const SharedPtr<Object> &obj) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 現在のオブジェクトと比較する [TimeSpan](../) オブジェクト |

### 戻り値

- 1 は、現在のオブジェクトが **value** より短い間隔を表す場合；0 は、現在のオブジェクトが **value** と等しい間隔を表す場合；1 は、現在のオブジェクトが **value** より長い間隔を表す場合

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* クラス [TimeSpan](../)
* クラス [Object](../../object/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)