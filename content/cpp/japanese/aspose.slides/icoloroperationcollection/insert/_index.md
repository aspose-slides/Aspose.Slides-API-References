---
title: Insert()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい操作をコレクションに挿入します。
type: docs
weight: 40
url: /ja/aspose.slides/icoloroperationcollection/insert/
---
## IColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) メソッド


コレクションに新しい操作を挿入します。

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | **int32_t** | 操作が挿入されるインデックスです。 |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 操作の種類です。 |
| parameter | **float** | 操作のパラメータです。 |

### 戻り値

挿入された操作。

## IColorOperationCollection::Insert(int32_t, ColorTransformOperation) メソッド


コレクションに新しい操作を挿入します。

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | **int32_t** | 操作が挿入されるインデックスです。 |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 操作の種類です。 |

### 戻り値

挿入された操作。

## 参照

* 列挙型 [ColorTransformOperation](../../colortransformoperation/)
* タイプ定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IColorOperation](../../icoloroperation/)
* クラス [IColorOperationCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)