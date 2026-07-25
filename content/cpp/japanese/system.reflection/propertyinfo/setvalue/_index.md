---
title: SetValue()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたオブジェクトにプロパティ値を設定します。
type: docs
weight: 14
url: /ja/system.reflection/propertyinfo/setvalue/
---
## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) メソッド

指定されたオブジェクトにプロパティ値を設定します。

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) プロパティを書き込む対象。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 設定するプロパティの値。 |

## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) メソッド

指定されたオブジェクトにプロパティ値を設定します。

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) プロパティを書き込む対象。 |
| indexer | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | インデックス付きプロパティ用のオプションのインデックス値です。インデックスなしプロパティの場合、この値は null にしてください。 |
| value | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | 設定するプロパティの値。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [Object](../../../system/object/)
* クラス [PropertyInfo](../)
* 名前空間 [System::Reflection](../../)
* Library [Aspose.Slides](../../../)