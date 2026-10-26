---
title: ObjectToUnknown()
second_title: Aspose.Slides for C++ APIリファレンス
description: Object を未知の型に変換し、スマートポインタ型とボックス化された値の両方に対応します。
type: docs
weight: 131
url: /ja/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) メソッド

[Object](../../object/) を未知の型に変換し、スマートポインタ型とボックス化された値の両方に対応します。

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../object/) を変換する型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) を変換する。 |

### 戻り値

アンボックス化された値または変換されたポインタのいずれか。

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) メソッド

[Object](../../object/) を未知の型に変換し、スマートポインタ型とボックス化された値の両方に対応します。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../object/) を変換する型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) を変換する。 |

### 戻り値

アンボックス化された値または変換されたポインタのいずれか。

## 関連項目

* クラス [SmartPtr](../../smartptr/)
* クラス [Object](../../object/)
* クラス [ObjectExt](../)
* 構造体 [IsSmartPtr](../../issmartptr/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)