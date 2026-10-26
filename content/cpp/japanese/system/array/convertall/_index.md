---
title: ConvertAll()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたコンバータ デリゲートを使用して、指定された配列の要素を OutputType 型に変換した新しい Array オブジェクトを作成し、要素で満たします。
type: docs
weight: 625
url: /ja/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) メソッド

[Array](../) オブジェクトを新しく作成し、指定されたコンバータ デリゲートを使用して、指定された配列の要素を **OutputType** 型に変換したものを格納します。

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| InputType | 入力配列の要素の型 |
| OutputType | 結果配列の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | [Array](../) オブジェクト |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | 入力配列の各要素を **OutputType** 型の同等値に変換するために使用される Converter オブジェクト |

### 戻り値

**input_array** の値に相当する **OutputType** 型の値を含む新しい配列

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) メソッド

[Array](../) オブジェクトを新しく作成し、指定されたコンバータ 関数オブジェクトを使用して、指定された配列の要素を **OutputType** 型に変換したものを格納します。

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| InputType | 入力配列の要素の型 |
| OutputType | 結果配列の要素の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | [Array](../) オブジェクト |
| converter | std::function\<OutputType(InputType)> | 入力配列の各要素を **OutputType** 型の同等値に変換するために使用される関数オブジェクト |

### 戻り値

**input_array** の値に相当する **OutputType** 型の値を含む新しい配列

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)