---
title: UnknownToObject()
second_title: Aspose.Slides for C++ API リファレンス
description: 不明な型を Object に変換し、スマートポインタ型と値型の両方の状況を処理します。
type: docs
weight: 118
url: /ja/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) メソッド

不明な型を [Object](../../object/) に変換し、スマート ポインタ型と値型の両方の状況を処理します。

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | [Object](../../object/) に変換する型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) を変換します。 |

### 戻り値

[Object](../../object/) へのスマート ポインタで、変換されたポインタまたはボックス化された値のいずれかです。

## ObjectExt::UnknownToObject(const T\&) メソッド

不明な型を [Object](../../object/) に変換し、スマート ポインタ型と値型の両方の状況を処理します。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | [Object](../../object/) に変換する型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) を変換します。 |

### 戻り値

[Object](../../object/) へのスマート ポインタで、変換されたポインタまたはボックス化された値のいずれかです。

## 参照

* クラス [SmartPtr](../../smartptr/)
* クラス [Object](../../object/)
* クラス [ObjectExt](../)
* 構造体 [IsSmartPtr](../../issmartptr/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)