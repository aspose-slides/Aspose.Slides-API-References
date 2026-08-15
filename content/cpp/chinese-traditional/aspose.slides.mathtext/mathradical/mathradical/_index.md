---
title: MathRadical()
second_title: Aspose.Slides for C++ API 參考文件
description: 初始化 MathRadical 類別的新執行個體。
type: docs
weight: 53
url: /zh-hant/aspose.slides.mathtext/mathradical/mathradical/
---
## MathRadical::MathRadical(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor


初始化 [MathRadical](../) 類別的新執行個體。

```cpp
Aspose::Slides::MathText::MathRadical::MathRadical(System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> degreeArgument)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 基底 |
| degreeArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 次方 |
## 備註



範例： 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathRadical](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)