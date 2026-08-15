---
title: MathArray()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個數學陣列並將指定的元素放入其中
type: docs
weight: 144
url: /zh-hant/aspose.slides.mathtext/matharray/matharray/
---
## MathArray::MathArray(System::SharedPtr\<IMathElement\>) 建構函式


建立一個數學陣列並將指定的元素放入其中

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<IMathElement> element)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要放入陣列的元素 |
## 備註



範例： 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
```

## MathArray::MathArray(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) 建構函式


建立一個數學陣列並將指定的元素放入其中

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> elements)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| elements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | 要放入陣列的元素 |

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathArray](../)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)