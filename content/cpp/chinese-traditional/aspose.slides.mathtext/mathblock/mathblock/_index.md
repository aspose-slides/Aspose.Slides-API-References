---
title: MathBlock()
second_title: Aspose.Slides for C++ API 參考
description: 初始化 MathBlock 類別的新執行個體。
type: docs
weight: 66
url: /zh-hant/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() 建構式

初始化 [MathBlock](../) 類別的新執行個體。

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## 說明

範例：
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) 建構式

建立新的數學區塊，並將指定的元素放入其中

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要放入區塊的數學元素 |
## 說明

範例：
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) 建構式

建立新的數學區塊，並將指定的元素集合放入其中

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | 要放入區塊的數學元素集合 |
## 說明

範例：
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [MathBlock](../)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)