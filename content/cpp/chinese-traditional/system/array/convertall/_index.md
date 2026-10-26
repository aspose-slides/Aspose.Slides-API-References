---
title: ConvertAll()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新的 Array 物件，並使用指定的轉換委託，將指定陣列的元素轉換為 OutputType 類型後填入其中。
type: docs
weight: 625
url: /zh-hant/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) 方法

建立一個新的 [Array](../) 物件，並使用指定的轉換委託，將指定陣列的元素轉換為 **OutputType** 類型後填入其中。

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| InputType | 輸入陣列中元素的類型 |
| OutputType | 結果陣列中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | 一個 [Array](../) 物件 |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | 用於將輸入陣列的每個元素轉換為 **OutputType** 類型等價值的 Converter 物件 |

### 返回值

一個新的陣列，包含與 **input_array** 的值等價的 **OutputType** 類型值

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) 方法

建立一個新的 [Array](../) 物件，並使用指定的轉換函式物件，將指定陣列的元素轉換為 **OutputType** 類型後填入其中。

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| InputType | 輸入陣列中元素的類型 |
| OutputType | 結果陣列中元素的類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | 一個 [Array](../) 物件 |
| converter | std::function\<OutputType(InputType)> | 用於將輸入陣列的每個元素轉換為 **OutputType** 類型等價值的函式物件 |

### 返回值

一個新的陣列，包含與 **input_array** 的值等價的 **OutputType** 類型值

## 另請參閱

* 型別定義 [ArrayPtr](../../arrayptr/)
* 型別定義 [Converter](../../converter/)
* 類別 [Array](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)