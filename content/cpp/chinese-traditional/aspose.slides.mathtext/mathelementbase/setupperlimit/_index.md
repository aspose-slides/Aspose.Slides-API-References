---
title: SetUpperLimit()
second_title: Aspose.Slides for C++ API 參考
description: 取得上限
type: docs
weight: 131
url: /zh-hant/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) 方法


取得上限

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### 返回值

新執行個體型別 [IMathLimit](../../imathlimit/)
## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) 方法


取得上限

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### 返回值

新執行個體型別 [IMathLimit](../../imathlimit/)
## 備註



範例： 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathLimit](../../imathlimit/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathElementBase](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)