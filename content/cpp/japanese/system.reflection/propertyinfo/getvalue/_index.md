---
title: GetValue()
second_title: Aspose.Slides for C++ API リファレンス
description: 特定のオブジェクトからプロパティ値を取得します。
type: docs
weight: 1
url: /ja/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) メソッド

特定のオブジェクトからプロパティ値を取得します。

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) からプロパティを読み取ります。 |

### 戻り値

指定されたオブジェクトの指定されたプロパティの値です。

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) メソッド

特定のオブジェクトからプロパティ値を取得します。

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) からプロパティを読み取ります。 |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | インデックス付きプロパティ用のオプションのインデックス値です。インデックスなしプロパティの場合、この値は null にする必要があります。 |

### 戻り値

指定されたオブジェクトの指定されたプロパティの値です。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [Object](../../../system/object/)
* クラス [PropertyInfo](../)
* 名前空間 [System::Reflection](../../)
* ライブラリ [Aspose.Slides](../../../)