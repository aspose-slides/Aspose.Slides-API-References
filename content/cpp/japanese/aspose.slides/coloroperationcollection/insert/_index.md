---
title: Insert()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい操作をコレクションに挿入します。
type: docs
weight: 79
url: /ja/aspose.slides/coloroperationcollection/insert/
---
## ColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) メソッド

新しい操作をコレクションに挿入します。

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | **int32_t** | 操作が挿入されるインデックス。 |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 操作の種類。 |
| parameter | **float** | 操作のパラメータ。 |

### 戻り値

挿入された操作。

## ColorOperationCollection::Insert(int32_t, ColorTransformOperation) メソッド

新しい操作をコレクションに挿入します。

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| position | **int32_t** | 操作が挿入されるインデックス。 |
| operation | [ColorTransformOperation](../../colortransformoperation/) | 操作の種類。 |

### 戻り値

挿入された操作。

## 参照

* 列挙型 [ColorTransformOperation](../../colortransformoperation/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IColorOperation](../../icoloroperation/)
* クラス [ColorOperationCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)