---
title: get_HideDegree()
second_title: Aspose.Slides C++ API 參考
description: 隱藏指數 當為 true 時，指數不會顯示，如 \\u221A\\uD835\\uDC65
type: docs
weight: 27
url: /zh-hant/aspose.slides.mathtext/mathradical/get_hidedegree/
---
## MathRadical::get_HideDegree() 方法


隱藏指數 當為 true 時，指數不會顯示，如 \\u221A\\uD835\\uDC65

```cpp
bool Aspose::Slides::MathText::MathRadical::get_HideDegree() override
```

## 備註


範例： 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
radical->set_HideDegree(true);
```

## 另請參閱

* 類別 [MathRadical](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)