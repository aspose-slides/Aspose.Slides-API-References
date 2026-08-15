---
title: SetLowerLimit()
second_title: Aspose.Slides for C++ API 參考
description: 設定下限
type: docs
weight: 144
url: /zh-hant/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) 方法

設定下限

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 限制 |

### 傳回值

新執行個體類型 [IMathLimit](../../imathlimit/)

## 備註



範例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) 方法

設定下限

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | 限制 |

### 傳回值

新執行個體類型 [IMathLimit](../../imathlimit/)

## 備註



範例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathLimit](../../imathlimit/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathElementBase](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)