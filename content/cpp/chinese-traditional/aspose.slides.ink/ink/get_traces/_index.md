---
title: get_Traces()
second_title: Aspose.Slides C++ API 參考
description: 取得所有包含於 IInk 元素 IInkTrace 中的痕跡。唯讀。
type: docs
weight: 1
url: /zh-hant/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() 方法


取得所有包含於 [IInk](../../iink/) 元素 [IInkTrace](../../iinktrace/) 中的痕跡。唯讀。

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## 備註


範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IInkTrace](../../iinktrace/)
* 類別 [Ink](../)
* 命名空間 [Aspose::Slides::Ink](../../)
* 函式庫 [Aspose.Slides](../../../)